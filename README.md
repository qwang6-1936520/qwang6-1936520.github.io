# qwang6-1936520.github.io

《凡人修仙传》网页文游入口：`index.html`。

## 发布方式（GitHub Pages）

仓库已添加自动发布工作流：

- 推送到 `main` 或 `work` 分支后会自动触发部署。
- 部署完成后访问：<https://qwang6-1936520.github.io/>

> 如果你在 GitHub 上没看到 `.github/workflows/deploy-pages.yml`，通常是因为改动还在 `work` 分支，尚未合并到 `main`。请先发起 PR 并合并。

## 本地体验

```bash
python3 -m http.server 4173
```

然后打开：<http://127.0.0.1:4173/index.html>
