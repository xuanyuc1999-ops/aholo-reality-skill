# Aholo Reality Skill — test3

用于照片、普通视频和 INSV/OSV 的 Aholo Reality 重建技能。

## 安装

下载 [aholo reality skill test3.zip](./aholo%20reality%20skill%20test3.zip)，将包内 `aholo-reality-skill` 文件夹解压到 `.claude/skills/`。已安装时先保留自己的修改，再更新对应文件。

## test3 内容

- 重建前展示帧率、分辨率、训练量和高斯上限等适用选项；未选择的参数使用默认值。
- 支持室内、室外、物体选择；原始 INSV/OSV 仅支持场景。
- 优先引导读取线上后台预计时间；无可读取估时则给出注明不确定性的提示。
- 以线上项目页观看和验收，不生成本地 Orbit HTML。
- 首轮之后逐项调优，由用户比较并选择最终交付版本。

连接方式和完整操作流程见安装包内的 `SKILL.md`。后台估时读取与交互选择属于技能引导，不是新的网页面板或自动估时接口。

## 文件校验

`aholo reality skill test3.zip` 的 SHA-256：

```text
ce61116dea8920719b0e4d672afeab97bed5b1e918e6736f9c046c9432661148
```
