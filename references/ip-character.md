# 默认 IP 角色

## 参考资产

每次生成原创图片都使用 `assets/default-ip-reference.png` 作为角色参考，除非用户提供了新的 IP 图并明确要求替换本次角色。

## 必须锁定的识别点

- 大头、小身体的玩偶比例
- 半垂、近乎全黑的眼睛
- 黑色、有层次的中长发，轮廓略蓬松
- 灰色针织上衣
- 冷淡、疲惫、无明显笑容的表情
- 简洁柔和的 3D 软质玩偶感

角色不依赖性别化装饰。默认不增加帽子、耳饰、眼镜或复杂配件。

## 可变化部分

- 姿势、手势与视线方向
- 场景和道具
- 镜头远近
- 文章层的光线与配色
- 为解释观点而出现的轻微情绪变化

## 一致性写法

在每张提示词中明确：

```text
Use the supplied IP reference as the identity anchor. Preserve the same oversized head-to-body ratio, half-lidded near-black eyes, layered medium-length black hair, gray knitted sweater, pale soft 3D doll material, and deadpan tired expression. Change only pose, scene, props, lighting, and composition required by this article concept.
```

## 判断标准

- 遮住场景后，角色仍应被认作同一个 IP。
- 遮住角色后，画面仍应表达文章观点；IP 是行动者，不是唯一信息。
- 若发型、眼型、灰色针织衫或头身比有两项以上漂移，重生成或定向编辑。
