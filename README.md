# hpsks416

当输入中出现成对的 hpsks416 界定符时，对其圈定范围内的内容，用一套个人化的分析透镜（控制论与反馈、递归与自指、可证伪性、语言的边界）进行审视；仅作用于界定符之内的内容，不触及范围之外。

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/hpsks416.git "$env:USERPROFILE\.dsh\skills\hpsks416"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/hpsks416.git "$env:USERPROFILE\.dsh\skills\hpsks416"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\hpsks416" pull

## 目录结构

    hpsks416/
    ├── SKILL.md    技能入口与工作流
    ├── agents\openai.yaml
    ├── references\background.md

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
