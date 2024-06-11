# 下载安装 anaconda

https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/

Anaconda3-2021-11-Linux-x86_64.sh

bash Anaconda3-2021.11-Linux-x86_64.sh

并设置环境变量

      export PATH="/home/你的用户名/anaconda3/bin:$PATH"
      
      source ~/.bashrc 

我就是export PATH="/home/Akaxi/anaconda3/bin:$PATH"

设置 anaconda中pip 镜像源

pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple