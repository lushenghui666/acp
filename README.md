---
AIGC:
  ContentProducer: '001191110102MAD55U9H0F10002'
  ContentPropagator: '001191110102MAD55U9H0F10002'
  Label: '1'
  ProduceID: 'add4e244-8e48-4968-a3d8-08cde09c7d9e'
  PropagateID: 'add4e244-8e48-4968-a3d8-08cde09c7d9e'
  ReservedCode1: '363436ff-b7a9-4140-9c45-d40a0f027879'
  ReservedCode2: '363436ff-b7a9-4140-9c45-d40a0f027879'
---

# 智算认证刷题练习（ACP 大模型应用方向）

纯原生 HTML/CSS/JS 单文件练习小程序，零外部依赖，数据保存在浏览器本地（localStorage）。

- 题库：10 套 200 题（143 单选 / 57 多选，12 题含代码块）
- 练习模式：练习集筛选、题型筛选、顺序/随机、逐题判分/答完再看
- 模拟考试：全真 75 题（120 分钟）/ 快测 30 题（45 分钟）/ 短测 20 题（30 分钟）；单选 1 分、多选 2 分（多选全对才得分），折算百分制，80 分及格；刷新可续考，超时自动交卷
- 错题本：自动收录练习与考试错题，可单独重练
- 统计：各练习集正确率、最近练习记录、考试成绩归档

## 使用

打开页面即可使用。练习记录、错题本、成绩均保存在**当前浏览器**的本地存储中，换设备/浏览器不会同步。

## 部署说明

GitHub Pages 部署，步骤：

1. 新建公开仓库（如 `acp-quiz`）
2. 上传 `index.html` 与 `README.md`
3. Settings → Pages → Source 选择 `main` 分支 `/ (root)` → Save
4. 约 1 分钟后访问 `https://<用户名>.github.io/acp-quiz/`

> AI生成