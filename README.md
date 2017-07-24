# ImageRepository
图片仓库，用于存放Markdown笔记图片

# 上传图片步骤

## 1、新建仓库

![新建仓库](https://github.com/jhj24/ImageRepository/raw/master/github/step_001.png)

## 2、添加指定文件到仓库

### 2.1 将仓库clone到本地
![将仓库clone到本地](https://github.com/jhj24/ImageRepository/blob/master/github/step_003.png)
### 2.2 文件上传
![上传](https://github.com/jhj24/ImageRepository/blob/master/github/step_004.png)
## 3、github常用命令
![上传](https://github.com/jhj24/ImageRepository/blob/master/github/step_002.png)

## 4、上传错误
### 4.1 README.md文件不在本地代码目录中
![上传](https://github.com/jhj24/ImageRepository/blob/master/github/error_001.png)
 - 解决方案
 
 可以通过如下命令进行代码合并：git pull --rebase origin master，合并完成后再执行 git push -u origin master即可完成代码上传到github
 
