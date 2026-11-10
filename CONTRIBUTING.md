# 贡献指南

感谢你对 DSHWORK 的关注！本仓库是 DSH Superagent 的演示仓库，用于测试和展示 Agent 自动修复问题的流程。欢迎提交文档修正、示例改进等改动。

## 如何 clone

```bash
git clone https://github.com/Dvd951/DSHWORK.git
cd DSHWORK
```

如果你没有本仓库的写入权限，请先在 GitHub 上 fork 本仓库，再把上面的地址换成你的 fork 地址。

## 如何提交改动

1. 基于 `main` 创建独立分支，分支名简明描述改动内容：

   ```bash
   git switch -c docs/update-contributing main
   ```

2. 完成修改，并在本地检查改动（例如校对文档内容、确认链接可访问）。

3. 提交改动，建议使用 [Conventional Commits](https://www.conventionalcommits.org/) 风格的信息，如 `docs: ...`、`fix: ...`：

   ```bash
   git add CONTRIBUTING.md
   git commit -m "docs: 更新贡献指南"
   ```

4. 推送到远端：

   ```bash
   git push -u origin docs/update-contributing
   ```

## 如何提 PR

1. 在 GitHub 仓库页面点击 “Compare & pull request”，选择你的分支与 `main` 对比。
2. 填写清晰的标题和说明，包括改动内容、原因以及验证方式。
3. 如果有相关 Issue，请在说明中关联，例如 `Closes #123`。
4. 提交后关注评审意见，按反馈继续修改；合并后即可删除临时分支。

## 注意事项

- 保持改动聚焦，一个 PR 尽量只解决一个问题。
- 不要提交密钥、令牌或其他敏感信息。
- 提交前确认工作区干净（`git status`），避免混入无关文件。
