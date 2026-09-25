# hpsks416

当用户的输入里出现成对的 `hpsks416` 界定符时，对被圈定范围内的文本，用下面这套「逻辑习惯」来审视；范围之外的内容不做这种审视，也不扩权外推。

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 使用 hpsks416 界定符做个人化逻辑审视的人（个人透镜）

## 目录结构

    hpsks416/
    ├── SKILL.md    技能入口与工作流
    ├── agents\openai.yaml
    ├── references\background.md

## 安装

    # GitHub
    git clone https://github.com/hpsks416/hpsks416.git "$env:USERPROFILE\.dsh\skills\hpsks416"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/hpsks416.git "$env:USERPROFILE\.dsh\skills\hpsks416"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
