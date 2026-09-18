# Starryear-EyeEye｜背后原图·中间荒诞世界

把一张照片做成“原图在背后、生成图在中间”的竖版 EyeEye 画中画。背景保留真实摄影证据，中央矩形把同源主体转译为带极简双眼的水彩生命，并用递归、尺度坍缩或不可能容纳制造可爱又诡异的观看感。

## 核心结构

- 原照片只经等比缩放与裁切，铺满背景，不重绘、不滤镜、不加眼睛。
- 中央生成区约占画布宽度 66%—76%、高度 68%—80%，四周都露出原照片。
- 中央区无白边、描边、阴影或装饰框。
- 默认输出一张竖版 2:3 成品；用户指定其他比例时遵从用户。

## 视觉命题

每次只选择一个主导机制：递归隧道、不可能内部空间、向中心连续缩小、自我包含的群落，或“既是容器又是被容纳者”的深度折叠。诡异来自空间逻辑和集体凝视，不来自血腥或怪物。

严格执行“一块身体＝一只生命＝一对眼睛”。每只生命都来自原图中的真实形体、纹理与色彩；保留原型特征，不把所有主体磨成统一圆球。

## 使用

将整个 `starryear-eyeeye-surreal` 文件夹放入 Codex skills 目录，上传一张原始照片，然后提出：

> 使用 `starryear-eyeeye-surreal`，原图铺满背后，中间打开一个同源的荒诞诡异眼睛世界。

完整提示词：

- [中文](references/starryear-eyeeye-surreal-prompt.zh-CN.md)
- [English](references/starryear-eyeeye-surreal-prompt.en.md)

## 文件结构

```text
starryear-eyeeye-surreal/
├── SKILL.md
├── README.md
├── LICENSE.md
├── agents/openai.yaml
├── references/
│   ├── starryear-eyeeye-surreal-prompt.zh-CN.md
│   └── starryear-eyeeye-surreal-prompt.en.md
└── assets/examples/
```

`assets/examples/` 在测试阶段保持为空。仅加入 Starryear年明确认可的最终成品；示例不得被当作其他照片的内容、构图或配色来源。

使用条款见 [LICENSE.md](LICENSE.md)。
