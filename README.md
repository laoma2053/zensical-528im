# 528.im

这是 [528.im](https://528.im/) 的 Zensical 文档站源代码。

## 本地预览

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\zensical.exe serve
```

## 发布

将内容提交并推送到 `main` 分支。GitHub Actions 会自动构建静态文件，并通过 SSH 增量同步到生产服务器。
