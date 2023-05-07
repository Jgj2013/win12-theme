# win12-theme

大家可以在这里上传自己制作的主题，经过审核可在windows12网页版中公开供使用，上传会自动计入该项目的贡献

## 上传方式:

1. 有一个github账号(后续会考虑加入microsft form匿名上传)
2. 把项目fork下来
3. 按照提示加入自己的主题
4. 点击项目页面上方的 `Pull Requests` 选项卡
5. 点击 `New pull request` 按钮
6. 选择fork的分支，完善信息并提交
7. 等待合并即可

## 格式

> 目前仅支持主题色与背景的自定义

一个文件夹，名称为该主题的名称。文件夹中:

新建一个文件，命名为 `theme` (无后缀名)

    {
        'color1':'#ad6eca',
        'color2':'#3b91d8', //渐变主题色
        'href':'#2983cc', //单色主题
        'bg':'bg.jpg'
    }

其中 `bg` 项为背景图片，放置在相同目录中(尽可能小一些，以免影响用户体验)
