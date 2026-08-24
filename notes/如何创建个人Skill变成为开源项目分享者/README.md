# 如何创建个人 Skill 变成为开源项目分享者

> 一句话路线：把重复做的事情总结成流程 → 写成 Skill → 测试改进 → 上传 GitHub → 分享并持续维护。

## 1. 把经验变成 Skill

1. 选择一件自己经常做、步骤比较固定的事情。
2. 把完整过程交给 AI，请它总结目标、步骤、规则、常见问题和示例。
3. 多轮检查和修改，确保步骤清楚、结果可以重复。
4. 整理成 `SKILL.md`，再用真实任务测试。
5. 测试不满意就继续修改，直到结果稳定。

## 2. 推荐文件结构

```text
skill-name/
├── SKILL.md          # 必需：Skill 的说明和执行规则
├── README.md         # 项目介绍、安装和使用方法
├── LICENSE           # 开源许可证，例如 MIT
├── scripts/          # 可选：自动化脚本
├── references/       # 可选：参考资料
└── assets/           # 可选：图片、模板等素材
```

> 视频中使用了 `skills/skill-name.md`。现在更推荐“一个 Skill 一个文件夹”，并把入口文件固定命名为 `SKILL.md`。

## 3. `SKILL.md` 最小模板

```markdown
---
name: skill-name
description: 说明这个 Skill 能解决什么问题，以及何时使用。
---

# Skill 名称

## 工作步骤

1. 第一步
2. 第二步
3. 检查输出

## 注意事项

- 规则或限制
- 常见错误
```

## 4. 发布到 GitHub

1. 在 GitHub 点击 **New repository**。
2. 填写仓库名称和简介，选择 **Public**。
3. 添加 `README.md` 和 `LICENSE`（常用 MIT）。
4. 上传 Skill 文件并提交修改。
5. 在 README 中写清楚用途、安装方法、使用示例和效果展示。

常用命令：

```bash
git add .
git commit -m "Add my first skill"
git push
```

## 5. 让别人愿意使用

- 提供一个可以直接照做的示例。
- 在 README 放效果截图或约 30 秒演示视频。
- 分享仓库链接到技术社区或学习群。
- 及时回复 Issues 和 Pull Requests。
- 根据反馈持续更新版本。

## 发布前检查

- [ ] Skill 解决的问题明确
- [ ] `SKILL.md` 步骤清楚
- [ ] 已用真实任务测试
- [ ] README 有安装和使用示例
- [ ] 已选择开源许可证
- [ ] 仓库不含密码、Token 或隐私信息
- [ ] GitHub 仓库已设为 Public

## 学习来源

- 小红书：奇迹新新（求关注），[《如何创建个人 Skill 并成为开源项目分享者》](https://www.xiaohongshu.com/discovery/item/6a529a8d000000001101e9e9)
- 补充参考：[OpenAI Skills 文档](https://learn.chatgpt.com/docs/build-skills)

> 本笔记是对视频图片内容的简化总结，并结合当前 Codex Skill 结构做了修正，不是原文转载。
