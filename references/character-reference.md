# 角色参考图提示词模板

Phase 4.5 需要生成角色参考图提示词时读取本文件。

## 模板结构

角色参考图使用 **多视图角色表（Multi-View Character Sheet）**——在一张图中包含角色的正面、侧面、背面、3/4 视角等多个角度，一次性锁定角色形象。

### 标准结构

```
TECHNICAL REFERENCE PACK: [角色描述摘要], hyperrealistic full character sheet of [角色详细描述], multiple views including front view, side view, 3/4 view, back view, [按需添加更多视角], wearing [服装全套描述：款式+颜色+材质], fabric texture close-up references: [各材质纹理描述], color swatch list, material list, height scale, clean plain white background, character consistency sheet, soft studio lighting[按需调整灯光], photorealistic, 8k, ultra detailed, sharp focus, realistic skin texture, individual hair strands, no distortion --ar 16:9
```

### 构成要素

| 要素 | 说明 | 示例 |
|------|------|------|
| 角色描述摘要 | 开篇概括，用于整体定位 | CURATED SEXY OUTFIT / TEENAGE ATHLETIC BOY / ELDERLY WIZARD |
| 详细描述 | 年龄、体型、面部特征、表情 | a Chinese male teenager aged 16-18, lean athletic build, clean clear skin, neutral determined expression |
| 多视角列表 | 最少 4 个视角，推荐 7+ | front view, side view, 3/4 view, back view, walking profile view, top-down full body view, half-body 45° view |
| 服装描述 | 全套服装 + 材质细节 | wearing a Japanese-style white button-up school shirt with collar unbuttoned, dark straight-leg school pants, white sneakers |
| 材质特写 | 各材质的纹理参考 | fabric texture close-up references: soft cotton weave texture, dark polyester pants fabric, sneaker mesh and rubber texture |
| 色板与材料 | 颜色和材料列表 | color swatch list including skin tone, shirt white, pant dark gray, sneaker white with blue accent, material list |
| 比例尺 | 身高参考 | height scale indicated |
| 一致性说明 | 角色一致性保证 | character consistency sheet |
| 灯光 | 工作室灯光设定 | soft studio lighting with slight golden accent |
| 画质锚定 | 收尾画质/画风 | photorealistic, 8k, ultra detailed, sharp focus, realistic skin texture, individual hair strands, no distortion |

### 完整示例

```
TECHNICAL REFERENCE PACK: TEENAGE ATHLETIC BOY, hyperrealistic full character sheet of a Chinese male teenager aged 16-18, lean athletic build, clean clear skin, neutral determined expression, multiple views including front view, side view, 3/4 view, back view, running profile view, top-down full body view, half-body 45° view, wearing a Japanese-style white button-up school shirt with collar unbuttoned, dark straight-leg school pants, white sneakers, wet messy black hair pushed back by sweat, fabric texture close-up references: white cotton shirt weave texture with sweat patches, dark polyester pants fabric, sneaker mesh and rubber texture, wet hair strand details, skin pore texture suitable for subsurface transparency effect, color swatch list including skin tone, shirt white, pant dark gray, sneaker white with blue accent, material list, height scale indicated, clean plain white studio background, character consistency sheet, soft studio lighting with slight golden accent, photorealistic, 8k, ultra detailed, sharp focus, realistic skin texture, individual hair strands, no distortion --ar 16:9
```

## 使用规则

1. **每个角色单独一套提示词**——不要在一套提示词中包含多个角色
2. **服装描述要精确到款式和颜色**——如"黑色紧身九分跑裤"而非"跑裤"，跨格一致性依赖此描述
3. **视角选择需覆盖角色在分镜中出现的所有角度**——如果角色只有背面出镜，至少也要保证 front view + back view + 3/4 view
4. **白底 + 影棚光**——保持干净，不添加场景/环境，确保角色本身是唯一的视觉焦点
5. **英语书写**——角色参考图提示词统一用英语
6. **固定 `--ar 16:9`**——与分镜提示词保持一致
