# 快速开始

## 安装

请安装最新的 Python 3，并且使用 `pip` 安装 3 个库：`requests` `BeautifulSoup4` `lxml`

```cmd
pip install requests BeautifulSoup4 lxml
```

## 准备

然后 [下载最新程序](https://github.com/Foair/course-crawler/archive/master.zip) 并解压。（也可以使用 `git clone https://github.com/Foair/course-crawler.git`。）

## 输入

在当前路径打开「命令提示符」，并输入 `python mooc.py <url>` 即可下载课程到当前文件夹。

这里的 `<url>` 是课程的地址，可以是受本程序支持的平台的课程地址，程序会自动识别。

比如同济大学的《高等数学（一）》

```cmd
python mooc.py https://www.icourse163.org/course/TONGJI-53004
```

!> 学堂在线·和·网易云课堂·需要经过认证，不能够直接下载，请移步 [视频速览](video-tutorial.md) 或 具体操作。

## 获取

运行完成之后就获得了完整的课程内容，可以在当前目录下查看。

## 下载

打开 `Videos/Vidoes.txt` 即可查看视频下载地址，复制下载地址后，使用自己喜欢的下载工具下载即可。

?> 课程文件中有 `Videos` 文件夹，建议将视频下载到 `Videos/` 中。

## 后续

将课程下载到 `Videos` 文件夹之后，双击 `Rename.bat` 即可修正所有视频文件名的「乱码」。

比如 `1009306529_e6648cb45d1848f290d514faa4b69b0c_shd.mp4` 会变成 `1.1.1 会计是什么.mp4`。

## 最后

付出努力，学完这些课程。
