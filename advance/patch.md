# 修改默认值

## 修改默认获取目录

如果不想每次都指定获取目录的话，可以修改 `mooc.py`，找到如下行：

```python
    parser.add_argument('-d', default=r'G:\MOOCs', help='下载目录')
```

将 `G:\MOOCs` 替换为想要的文件夹即可。

## 默认启用某个选项

修改 `mooc.py`，将选项所在 `store_false` 或 `store_true` 切换一下就行了。

示例

如果我想默认不下载 PDF，那么将 `--no-pdf` 所在的那一行的 `store_false` 改了就行了，改成这样

```python
    parser.add_argument('--no-pdf', action='store_true', help='不下载 PDF 文档')
```

这样默认就不会下载 PDF，而如果在命令中使用了 `--no-pdf` 就会下载 PDF 了。
