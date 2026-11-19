# 刘晓艳行动 · Godot 网页版（v51）

在四级、六级、考研和高中 3500 词书中选择学习计划，通过拼写或四选一完成战斗，积累经验和哈弗币。

## 在线游玩

部署在 GitHub Pages：**https://zwy66312.github.io/liuxiaoyan-action/**

- 手机建议横屏，首次加载约 87MB 资源
- 进度保存在各自浏览器的本地存储里，换设备或清缓存会丢，顶栏「导出进度」可备份 JSON
- 词书：大学英语四级 3837 词 / 六级 5396 词 / 考研 4801 词 / 高中英语词汇 3674 词

## 说明

`docs/` 是已导出的网页版（Godot 4.5.1，单线程，GL Compatibility）。推送后由 `.github/workflows/pages.yml` 自动发布。

词典数据来自 [ECDICT](https://github.com/skywind3000/ECDICT)（MIT），按 cet4 / cet6 / ky / gk 标签筛选。
