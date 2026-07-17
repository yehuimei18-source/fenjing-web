---
name: prompt-optimization-system
description: 提示词优化体系 v2.0 完整逻辑——摄影写实框架：角色六步流程/场景六层结构/非人角色/风格知识库/万能模板
metadata:
  type: project
---

# 提示词优化体系 · 完整逻辑文档 v2.0

适用：优化角色/场景/道具提示词（Nanobanana/Midjourney/SD/Flux/即梦生图）。在 Seedance 视频分镜中应用时保留时间戳分镜框架，仅借用其视觉增强方法。

## 第一部分：核心哲学

### 最高原则：这是一张照片，不是一张CG

| 禁止 | 必须 |
|------|------|
| 抽象形容词（美丽、震撼、梦幻）| 具象五官/骨相/材质描述 |
| "不要CG感"等负面指令 | 正向物理参数（毛孔、SSS、菲涅尔反射）|
| 笼统的光影描述 | 指定光源类型、方向、光质、光比 |
| 无拍摄方案的画面 | 指定相机/镜头/胶片型号、光圈、ISO |
| 完美无瑕的表面 | 可见毛孔、绒毛、油脂、灰尘、磨损、氧化 |

### 摄影质感模块（必选其一叠加）

- **数字电影机**：ARRI Alexa 65, Panavision anamorphic lenses, Kodak Vision3 250D, organic film grain, subtle halation
- **复古胶片**：Hasselblad 500C/M, Kodak Portra 800 pushed, medium format film, shadow color shift
- **纪实摄影**：Leica M6, Kodak Tri-X 400, 35mm documentary grain, high contrast
- **大画幅**：4x5 large format, Kodak Ektar 100, front rise correction, hyper-detailed
- **监控/取证**：Sony A7S III, 12800 ISO, surveillance footage, sensor noise
- **科研记录**：Schlieren imaging rig, cooled monochrome CCD, laboratory diagnostic aesthetic

### 一句话质感锚定

`16:9. A single unretouched photograph. [相机+镜头+胶片型号]. This is not CGI. This is a photograph of a real place.`

### 三层不可违背规则

1. **绝不用抽象形容词**："美得惊心动魄"→"鹅蛋脸，琼鼻，含珠唇，冰蓝虹膜带深色轮缘"
2. **绝不用负面定义正面**："不要CG感"→"表皮镜面高光，真皮SSS，可见毛孔，胶片颗粒"
3. **绝不脱离背景堆细节**：每个细节有叙事逻辑——伤疤来自什么经历，尘土来自什么环境

## 第二部分：角色优化六步流程

`角色档案 → 辨识度锚点 → 中式审美具象翻译 → VPEP材质匹配 → 使用痕迹与废土编码 → 拍摄方案`

### 步骤1 角色档案：她/他是谁？经历了什么？第一眼特征是什么？

### 步骤2 辨识度锚点（打破AI模板脸）

| 锚点类型 | 原则 | 示例 |
|---------|------|------|
| 面部不对称 | 3-5%以内 | 左嘴角比右嘴角高约0.3mm；左单右双眼皮 |
| 独特标记 | 有叙事逻辑 | 眉尾上方小痣；颧骨雀斑 |
| 比例偏差 | 正常范围内个性化 | 眼距略宽(1.2倍眼长)；左唇峰略高 |
| 骨骼特征 | 正常结构内 | 鼻骨中段细微不对称隆起（旧伤）|
| 身体印记 | 职业/经历 | 指节薄茧；指甲极短（实验室规范）|

### 步骤3 中式审美具象翻译

| 气质 | 眉形 | 眼型 | 鼻型 | 唇型 | 脸型 |
|------|------|------|------|------|------|
| 冷傲审视 | 远山眉/剑眉 | 瑞凤眼/丹凤眼 | 琼鼻/悬胆鼻 | 薄情唇/含珠唇 | 鹅蛋/瓜子脸 |
| 温柔坚韧 | 柳叶眉 | 杏眼 | 玉葱鼻 | 含珠唇 | 鹅蛋脸 |
| 英气果决 | 剑眉 | 丹凤眼 | 悬胆鼻 | 刀削唇 | 方下颌带浅沟 |
| 妩媚狡黠 | 柳叶眉 | 狐狸眼/桃花眼 | 琼鼻 | 花瓣唇 | 心形脸 |
| 清纯无辜 | 新月眉 | 杏眼圆 | 蒜头鼻 | 樱桃唇 | 圆脸 |
| 儒雅温和 | 修长剑眉 | 凤眼柔和 | 鼻梁秀挺 | 仰月唇 | 鹅蛋脸 |
| 阴鸷精明 | 一字眉细直 | 狼眼 | 鹰钩鼻 | 刀削唇下垂 | 下颌锋利 |

眼型英文具象：瑞凤眼 parallel double eyelids, pupils slightly covered by upper lids / 丹凤眼 long narrow, inner corners down-turned, outer upward-tilted / 狐狸眼 pronounced upward slant, pointed corners / 杏眼 rounded, large dark pupils / 桃花眼 upturned outer corners, watery sheen lower lash line

### 步骤4 VPEP材质物理参数

| 部位 | 光学特性 |
|------|---------|
| 皮肤 | visible fine pores, epidermal specular on T-zone, dermal SSS with cool/warm bleed at thin edges, vellus hair rim light |
| 虹膜 | subtle radial striations, dark limbal ring, wet specular highlight, no magical glow |
| 光面皮革 | semi-gloss, soft specular roll-off, localized roughness where dust-coated |
| 丝绸缎面 | specular highlight with sharp liquid-like edges, deep black folds |
| 棉麻 | diffuse reflection, no specular, absorbent, rounded fold shadows |
| 玉石 | subsurface scattering at thin edges, natural veining, soft sheen |
| 氧化金属 | patchy metallic base under diffuse patina, Fresnel edge brightening |

### 步骤5 使用痕迹与废土编码

尘土覆盖→局部粗糙度升高高光削弱 / 皮肤晒红汗珠旧疤指缝污垢 / 发尾毛躁发根新生 / 肘部哑光磨损撕掉徽章残留线孔 / 金属锈迹铜绿——每项对应叙事原因

### 步骤6 统一拍摄方案（角色资产卡）

16:9，左40%面部特写+右60%三视图，纯白影棚背景，哈苏H6D-100c，100mm f/4面部+50mm f/8全身，三点式布光，无文字水印，皮肤保留真实纹理

## 第三部分：场景优化六层（八段）结构

```
镜头锚点 → 前景锚点 → 中景主体 → 细节层 → 环境大气 → 光影色彩 → 远景延伸 → 质感总结
```

1. **镜头锚点**：16:9 + 实拍电影画面 + 相机镜头胶片 + This is not CGI
2. **前景锚点**：前景物+人物背对镜头+动作（让观众代入）
3. **中景主体**：形态→材质→表面纹样→排列方式
4. **细节层**：材质+工艺+图案+时间痕迹（苔藓锈迹风化磨损）
5. **环境大气**：云雾烟尘粒子，动词：翻涌/环绕/飘浮/弥漫 + Mie散射/大气透视
6. **光影色彩**：光源类型+传播方式（穿透/体积/漫射）+阴影特征+主色调+点缀色
7. **远景延伸**：尽头隐约可见终极目的地，隐入烟岚雾霭
8. **质感总结**：This is not CGI. This is a photograph. Subtle film grain, anamorphic softness.

## 第四部分：非人角色

- **动物**：不表情化，写真实肌肉运动（竖耳/瞳孔收缩），巩膜不露，个体标记（斑纹不对称/旧伤/缺齿）
- **怪兽**：每个夸张结构有功能解释，肌肉符合力学，甲壳有真实材质光学，环境交互证据（脚印抓痕蜕皮）
- **灵体**：核心悖论——无实体却被"拍摄"。引力体→纹影摄影（白背景光线扭曲折射显形）；热信号→红外热成像；电磁→底片过曝光斑；光子→长曝光光迹无影。不解释原理，直接描述画面。

## 第五部分：新兴视觉风格知识库

- **东方科幻**：赛博江湖 neon-lit ancient architecture / 丝绸朋克 bamboo flying machines, porcelain armor / 青铜朋克 taotie-pattern mecha, oracle bone code / 墨家机关术 wooden ox automaton / 新中式废土 sand-buried temples, faded cinnabar red
- **数字美学**：中式梦核 1990s green wall-skirt classroom / 阈限空间 endless hotel corridor / 数字考古 Windows XP low-poly / 故障考古 VHS tape jam, CRT burn-in
- **材质美学**：地质朋克 obsidian facades geode spaces / 菌丝体 mushroom-cap roofs bioluminescent / 金缮朋克 cracked ceramic liquid metal seams
- **氛围美学**：暖核 warm yellow kitchen light / 冷核 dawn street post-human calm / 暮色叙事 golden hour frozen / 冻核 ice-encased fruit still ripe
- **跨媒介**：胶片考古 unearthed lost film faded Technicolor / 湿版火棉胶 19th-century process / 木版画叙事 carved line texture
- **生物改造**：植物克苏鲁 vines from eye sockets / 水晶寄生 half-crystallized fingers / 深海进化 translucent skin bioluminescent
- **建筑空间**：垂直城市 eras stacked / 减法建筑 carved from cliff / 超尺度 doors for giants / 瞬移空间 four walls different landscapes

**风格应用三步**：选风格 → 提取视觉特征关键词 → 用真实摄影语言重述+叠加相机胶片参数

## 第六部分：统一输出标准

- 画幅 16:9（竖屏短剧9:16）/ 2.35:1 电影
- 禁止：文字/水印/标签
- 必须：皮肤毛孔绒毛油脂 + 表面磨损氧化积灰 + 指定胶片型号

**通用负面词**：illustration, anime, cartoon, 3d render, CGI, digital art, plastic texture, smooth surfaces, perfect symmetry, text, watermark, logo
**人物负面**：plastic skin, glass skin, airbrushed, K-pop idol look
**场景负面**：matte painting, concept art, clean pristine surfaces, modern elements in historical scenes
**特效负面**：fantasy glow, magical particles, missing physical interaction

## 第七部分：光影与视角速查

**视角**：广角定场/鸟瞰/低角度仰视/过肩/微距/荷兰角
**光影**：黄金时刻侧光/蓝调漫射/阴天柔光/逆光剪影/体积光束/单灯硬光film noir/月光冷调/火光暖调

## 万能模板

**角色资产卡**：16:9→[摄影质感模块]→纯白影棚→左40%特写右60%三视图→[五官具象+辨识度锚点+VPEP]→[服装分层内到外+材质光学+使用痕迹]→[三点布光]→[胶片颗粒]→This is not CGI→[负面词]

**场景定场**：16:9→实拍[类型]电影→[相机胶片]→[前景+背对人物]→[中景主体形态材质纹样]→[细节+时间痕迹]→[大气动态]→[远景隐入]→[光源+色调]→[质感总结]→[负面词]

**非人生物**：16:9→[摄影质感]→白背景标本记录→正侧背三视→[物种档案]→[解剖+VPEP]→[个体标记]→中性漫射布光→临床感→[负面词]
