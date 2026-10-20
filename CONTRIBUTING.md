# 一起继续做

欢迎修复问题、调整文案、改善手机操作、增加幽默感，或试做后续章节。先在 Issue 中说明想改的内容，再 fork 仓库、开分支并提交 PR。经济模型的推导应写明条件，别把故事直接当作历史结论。

```sh
npm ci
npm test
npm run build
```

涉及交互时，请说明从哪一步开始、点击什么、期望和实际发生了什么，并附手机或电脑截图。改动图片、字体及原作代码时保留来源与许可。未实际执行的检查请明确说明。

当前入口是 `portable.tsx` → `components/playable-story.tsx`。嵌入舞台的文案和绘制主要在 `lib/`，样式在 `app/trust-stage.css`。尾声作者信息在 `lib/trust-document.ts` 的 `assets.author`。
