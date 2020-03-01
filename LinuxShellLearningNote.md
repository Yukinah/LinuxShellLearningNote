# Preserved






# 经常用到的命令
   * 文本命令
   
   * 文件及文件夹命令
      + 定位文件位置的方法
         1. 查找位置
            - ```bash
                  jennywang@JennyWangs-MacBook-Pro DownloadKnackLearningNote % whereis java               
                  /usr/bin/java
              ```
         2. 列出详细信息
            - ```bash
                  jennywang@JennyWangs-MacBook-Pro DownloadKnackLearningNote % ls -l /usr/bin/ |grep java
                  lrwxr-xr-x   1 root   wheel        74  8  2  2019 java -> /System/Library/Frameworks/JavaVM.framework/Versions/Current/Commands/java
            ```
         3. 列出文件原始位置
            - ```bash
                  ls /System/Library/Frameworks/JavaVM.framework/Versions/Current/Commands
              ```
