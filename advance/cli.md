# 命令行参数

## 显示帮助信息

> `-h` `--help` 用于显示帮助信息。

输入 `python mooc.py -h` 或 `python mooc.py --help`。

## 指定下载目录

> `-d <path>` 用于指定下载目录为 `<path>`。

课程文件夹将在创建在 `<path>` 中。默认创建在当前目录，即 `-d ""`。

示例

```cmd
python mooc.py https://www.icourse163.org/course/TONGJI-53004 -d "G:\MOOCs"
```

!> `<path>` 不能以 `\` 结尾；当 `<path>` 存在空格的时候，必须使用 `"` 将路径包裹起来。

## 不下载文档

> `--no-doc` 用于阻止下载 PDF、Word、PowerPoint 等文档。

默认会下载所有文档。


当指定了这个选项之后，不会下载任何文档（包括 PPT 和书籍等）。

示例

```cmd
python mooc.py https://www.icourse163.org/course/TONGJI-53004 --no-doc
```


## 修正视频/文档名

> `--inter` 用于修改文件名。

会调出文件编辑器，编辑好视频的名字之后保存。默认没有启用。

!> 请严格按照原来文本长度进行设置，否则可能会发生没有标题的情况。

## 不下载字幕

> `--no-sub` 用于阻止下载字幕。

## 不下载富文本

> `--no-text` 用于阻止下载富文本。

## 不下载附件

> `--no-file` 用于阻止下载附件。

