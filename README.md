# 烘焙变量查询 / Baking Variable Search

中文：收录 60 种经典烘焙品，支持按六个变量（品类、面团、发酵、油脂、口感、场合）多选组合搜索。选中的条件实时联动计数，零匹配的选项自动禁用，帮你快速找到符合要求的烘焙品，每种附实拍图与做法要点。

English: A search tool for 60 classic baked goods. Filter by six variables — category, dough, fermentation, fat level, texture, and occasion — with multi-select combination search. Counts update live as you select, and options with zero matches are disabled automatically. Each item includes a photo and key notes.

![烘焙变量查询截图](./assets/screenshot.png)

## 在线体验 / Live Demo

- [GitHub Pages 在线体验](https://holynova.github.io/baking-variable-search/)
- [GitHub Repo](https://github.com/holynova/baking-variable-search)

<img src="./assets/qr.png" width="180" alt="扫码访问在线体验">

## 本地运行 / Run locally

```bash
python3 -m http.server
```

然后打开 http://localhost:8000/，或直接用浏览器打开 `index.html`。

## 发布 / Deploy

```bash
~/workspace/custom-connectors/custom.legacy-github/bin/gh-push-dir holynova/baking-variable-search <本地目录> main "Publish baking variable search"
```

GitHub Pages · 主分支 `main` 根目录
