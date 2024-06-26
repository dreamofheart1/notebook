# jna

## 数组

jna中没有二维数组，二维数组用一维数组代替；  在类中定义二维数组时，new 不出来，会报空指针异常；



## jna类和结构体

### 对应关系

参考地址

https://github.com/java-native-access/jna/blob/master/www/FrequentlyAskedQuestions.md

```
typedef struct _simplestruct {
  int myfield;
} simplestruct;

typedef struct _outerstruct {
  simplestruct nested; // use Structure
} outerstruct;

typedef struct _outerstruct2 {
  simplestruct *byref; // use Structure.ByReference
} outerstruct2;

typedef struct _outerstruct3 {
  simplestruct array[4]; // use Structure[]
} outerstruct3;

typedef struct _outerstruct4 {
  simplestruct* ptr_array[4]; // use Structure.ByReference[]
} outerstruct4;

// Field is a pointer to an array of struct
typedef struct _outerstruct5 {
  simplestruct* ptr_to_array; // use Structure.ByReference, and use
                              // Structure.toArray() to allocate the array, 
                              // then assign the first array element to the field
} outerstruct5;

// struct pointers as return value or argument
simplestruct *myfunc(); // use Structure
void myfunc(simplestruct* data); // use Structure
void myfunc(simplestruct* data_array, int count); // use Structure[], and use Structure.toArray() to generate the array
void myfunc(simplestruct** data_array, int count); // use Structure.ByReference[]

// struct (by value) as return value or argument
// use Structure.ByValue
simplestruct myfunc();
void myfunc(simplestruct);
```



```
public static native int g_parse_segment(RtcmT rtcm, String data);

GNSSDLL_API int g_parse_segment(rtcm_t* rtcm, char* data) 
```



## 对象初始化

jna 对象中的对象没有初始化， 在C 中会自动为结构体中的对象初始化， 但是引用和指针不行；



## 问题

两边数组长度不一样时，会出现两边数据好像是隔离的感觉，C中的数据无法正确的传递到Java中



