清华：https://pypi.tuna.tsinghua.edu.cn/simple

阿里云：http://mirrors.aliyun.com/pypi/simple/

中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/

华中理工大学：http://pypi.hustunique.com/

山东理工大学：http://pypi.sdutlinux.org/ 

豆瓣：http://pypi.douban.com/simple/

pip升级

```
python -m pip install --upgrade pip
```

annconda

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/

conda config --set show_channel_urls yes

ssl_verify: true
channels:

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/msys2/

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/r

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/pro

  - https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2

  - defaults
  show_channel_urls: true

  
