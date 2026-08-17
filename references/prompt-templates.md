# 提示词模板

每张图单独生成。用用户确认的标题和文章原句替换变量，不要把整套资产拼在一张图里。每次同时提供角色身份锚点与 1–2 张风格样例，并明确两类参考的职责不同。

## 通用风格锚点

```text
Reference roles:
- The IP reference controls character identity only.
- The selected example image(s) are the only style source. They control the visual medium and editorial grammar only: polished soft 3D doll illustration, warm gray-white studio space, diffused light, realistic tactile materials, dark Chinese headline typography, restrained brick-red warning accents, and either a staged physical scene or a translucent 3D information panel.
- Do not copy any example's topic, title, garment, scale, pedestal, interface content, object arrangement, or composition.
```

## 横版封面

```text
Use case: ads-marketing
Asset type: WeChat article wide cover, approximately 2.35:1
Input image: supplied IP reference is the identity anchor
Article thesis: {一句话核心观点}
Primary visual conflict: {冲突}
Subject action: {IP 正在做什么}
Scene and metaphor: {场景与主隐喻}
Style and material: polished soft 3D editorial illustration, warm gray-white studio, diffused light, tactile miniature props, generous negative space; {本篇视觉母题}
Color palette: {背景色 / 主色 / 强调色}
Text (verbatim): "{标题}"
Composition: strong thumbnail readability, generous safe margins, one dominant conflict, title and face unobstructed
Identity invariants: preserve the same oversized head-to-body ratio, half-lidded near-black eyes, layered medium-length black hair, gray knitted sweater, pale soft 3D doll material, and deadpan tired expression
Avoid: hand-drawn line art, flat vector art, realistic photography, PPT layout, extra title variants, tiny text, decorative clutter, unrelated props, logo, watermark, character drift, copying example content
```

## 1:1 缩略图

```text
Create a new square 1:1 composition based on the same article concept and visual system as the wide cover. Do not crop or merely reframe the wide cover. Keep the IP identity unchanged. Reduce the scene to one conflict, enlarge the face and title, and keep both within the central 70% safe area.
Text (verbatim): "{短标题或完整标题}"
Preserve: polished 3D editorial medium, {本篇配色、材质、主隐喻}
Avoid: narrow side-by-side layout, small labels, character redesign, extra text, simple crop of the wide cover
```

## 正文论证配图

```text
Use case: infographic-diagram
Asset type: standalone 16:9 Chinese article body illustration
Input image: supplied IP reference is the identity anchor
Anchor sentence: "{原文完整句子}"
Core idea: {一句话解释}
Structure type: {构图模式}
IP action: {角色承担的关键动作}
Main objects: {1–2 个物件}
Visual system: polished soft 3D editorial illustration, gray-white studio, diffused light, realistic tactile materials, dark headline typography, restrained brick-red warning accents; use either a staged physical scene or a translucent 3D information panel according to {构图模式}; {本篇配色、材质、重复识别元素}
Chinese labels: "{短词1}" / "{短词2}" / "{短词3}"
Composition: one main relationship, readable in one second, no dense nodes, enough negative space
Identity invariants: preserve the same oversized head-to-body ratio, half-lidded near-black eyes, layered medium-length black hair, gray knitted sweater, pale soft 3D doll material, and deadpan tired expression
Avoid: hand-drawn line art, flat vector art, generic PPT slide, flat formal flowchart, dense futuristic UI, long paragraph, decorative-only IP, title in the corner, logo, watermark, copying the selected example's objects or arrangement
```

## 定向改图

```text
Edit the supplied image. Change only: {单一修改目标}.
Preserve exactly: IP identity, facial features, hair, gray knitted sweater, pose unless specified, composition, article visual system, all correct text, aspect ratio, and image quality.
Do not add new text, props, characters, logos, or decorations.
```

若中文错误较多，减少图中文字并重新生成；不要用更多提示词试图强塞长句。
