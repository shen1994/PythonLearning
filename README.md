# PythonLearning
markdown在线编辑:<https://www.zybuluo.com/mdeditor>

## 0. 下载slides文件
### 0.1 更改config.ini文件内容
> * heading下为PPT首页显示
> * md文件的路径为slides/md
### 0.2 更改页面名称
> * templates/header.content文件下第7行

## 1. 生成网页并发布
> * 在电脑端执行命令
`python autoreveal.py config.ini`
> * 将生成的builds文件夹重新命名为docs,上传到github项目下
> * 点击项目设置Settings,在GitHub Pages/Source中选择master branch/docs folder,保存
> * 运行网页
<https://shen1994.github.io/(ProjectName)>
