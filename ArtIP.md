# IP形象创意 - 设计规范 v0.7

---

## 一、创作核心理念

> **轻叙事，重符号，强互动**
> 
> IP形象应让人一眼就能了解其角色魅力，无需过多叙事铺垫。

---

## 二、情感驱动系统

### 核心原则

**情感驱动一切** —— 根据情感自动选择最合适的艺术风格、表情和身材比例。

### 情感定位确定规则

根据用户描述的关键词，匹配对应的情感定位：

| 用户关键词 | 匹配的情感定位 |
|------------|---------------|
| 生气、暴躁、愤怒、发火 | 暴怒大喊 |
| 害怕、恐惧、惊恐 | 惊恐尖叫 |
| 丧、无聊、厌世、躺平、摆烂 | 悠闲躺平 |
| 坏、调皮、狡猾、得意 | 得意坏笑 |
| 焦虑、纠结、困扰、烦恼 | 焦虑困扰 |
| 饿、馋、贪吃、想吃 | 贪吃馋嘴 |
| 哭、伤心、崩溃、绝望 | 大哭崩溃 |
| 紧张、不安、僵硬 | 紧张僵硬 |
| 恨、咬牙、愤恨 | 咬牙切齿 |
| 开心、快乐、兴奋、大笑 | 开心大笑 |
| 惊讶、震惊、意外、吃惊 | 震惊吃惊 |
| 傲娇、高冷、不屑 | 傲娇不屑 |
| 害羞、脸红、内向、社恐 | 害羞脸红 |
| 呆、傻、迷茫、懵 | 困惑迷茫 |
| 邪恶、坏、狂、恶 | 邪恶狂笑 |

**用户未指定情感时**：根据对需求的理解，自主选择最合适的情感定位

### 情感 → 自动推荐组合

根据情感定位，**自动推荐**最合适的艺术风格和身材比例：

| 情感定位 | 推荐艺术风格 | 推荐身材比例 |
|----------|-------------|-------------|
| 暴怒大喊 | Chibi, 蜡笔小新 | Q版（表情最夸张） |
| 惊恐尖叫 | Chibi, Tim Burton | Q版（表情最夸张） |
| 悠闲躺平 | Loopy, Chiikawa | 萌系圆润, Q版 |
| 得意坏笑 | Pokemon, Molly | 标准比例, Q版 |
| 焦虑困扰 | Line Friends, Chiikawa | 标准比例 |
| 贪吃馋嘴 | Loopy, Sanrio | Q版, 标准比例 |
| 大哭崩溃 | Chiikawa, Loopy | Q版（更惹人怜） |
| 紧张僵硬 | Line Friends, Chibi | 标准比例 |
| 咬牙切齿 | Chibi, 蜡笔小新 | Q版（更显奶凶） |
| 开心大笑 | Sanrio, Pokemon, Loopy | 标准比例, Q版 |
| 震惊吃惊 | Chibi, 蜡笔小新 | Q版（表情最夸张） |
| 傲娇不屑 | Kuromi, Nara | 标准比例, 修长比例 |
| 害羞脸红 | Chiikawa, Sanrio, Loopy | Q版, 萌系圆润 |
| 困惑迷茫 | Line Friends, Chiikawa | 标准比例, Q版 |
| 无聊厌世 | Nara, Chiikawa | 标准比例 |
| 邪恶狂笑 | Tim Burton, Kuromi | 标准比例, 修长比例 |

**用户指定风格时**：优先使用用户指定的风格

---

## 三、可识别性与可记忆性

### 核心原则

> **要新颖的、要有辨识度的**

IP形象必须具备**一眼识别**的能力，有两种实现思路：

### 思路一：极简造型（剪影识别）

造型尽可能简单，花纹颜色尽量简洁，**不能复杂**。

| 要求 | 说明 | 提示词关键词 |
|------|------|-------------|
| 剪影识别 | 只看轮廓就能认出 | `iconic silhouette, instantly recognizable shape` |
| 简洁花纹 | 无复杂图案 | `minimal patterns, clean simple design` |
| 颜色简洁 | 1-2个主色 | `limited color palette, single dominant color` |
| 造型简单 | 几何化简化 | `simplified geometric forms, basic shapes` |

**代表案例**：米老鼠（三个圆）、熊本熊（黑熊+红腮红）、Hello Kitty（极简符号）

**提示词模板**：
```
iconic silhouette, instantly recognizable shape, minimal patterns, clean simple design, limited color palette with [主色], simplified geometric forms
```

---

### 思路二：标志性视觉抓手

为IP制造**独特的视觉抓手**，一个标志性元素让人过目不忘。

| 抓手类型 | 说明 | 示例 |
|----------|------|------|
| **标志性配饰** | 独特的帽子/眼镜/围巾等 | 路飞的草帽、皮卡丘的闪电尾巴 |
| **标志性服装** | 独特的服装元素 | 冰墩墩的冰壳外套、超人的披风 |
| **标志性符号** | 身上的图案/标记 | 超人胸口的"S"、蝙蝠侠的蝙蝠标志 |
| **标志性颜色** | 独特的配色组合 | 熊本熊的黑+红腮红 |
| **标志性特征** | 独特的身体特征 | 大眼仔的单眼、毛怪的蓝紫毛 |

**提示词模板**：
```
wearing signature [配饰], iconic [特征] as visual hook, distinctive [元素] for instant recognition
```

---

### 视觉抓手库（可选元素）

| 类别 | 可选元素 | 提示词示例 |
|------|---------|-----------|
| 帽子 | 草帽、贝雷帽、皇冠、兜帽、针织帽 | `wearing signature straw hat` |
| 眼镜 | 圆框眼镜、墨镜、护目镜 | `wearing iconic round glasses` |
| 围巾 | 长围巾、蝴蝶结、领带 | `wearing long flowing scarf` |
| 耳朵装饰 | 蝴蝶结、耳机、耳环 | `with signature bow on ear` |
| 背饰 | 翅膀、背包、披风 | `with small angel wings on back` |
| 手持物 | 魔杖、伞、气球、星星棒 | `holding signature magic wand` |
| 身体标记 | 心形、星星、闪电、花纹 | `with heart-shaped mark on cheek` |
| 尾巴特征 | 闪电形、心形、星星形 | `with lightning bolt shaped tail` |

---

### 设计检查：识别度测试

设计完成后，问自己：

- [ ] **剪影测试**：只看黑色轮廓，能认出这是什么角色吗？
- [ ] **视觉抓手测试**：有没有一个独特元素让人过目不忘？
- [ ] **简洁度测试**：能用3个词描述这个角色的核心特征吗？
- [ ] **区分度测试**：和市面上其他IP放在一起，能一眼认出吗？

---

## 四、表情系统（夸张感染力版）

### 核心原则

表情由 **3个维度** 组合构成，追求**一眼能读懂的夸张表情**，让人产生共鸣：

| 维度 | 控制什么 | 作用 |
|------|---------|------|
| 眉毛 | 情绪基调 | 决定整体情绪倾向 |
| 眼睛 | 情绪强度 | 传递情感深度和细节 |
| 嘴巴 | 情绪表达 | 完成最终的情绪输出 |

### 情感 → 表情映射表

| 情感定位 | 眉毛 | 眼睛 | 嘴巴 | 完整表情关键词 |
|----------|------|------|------|---------------|
| **暴怒大喊** | deeply furrowed angry | bulging wide eyes | wide open mouth screaming | `deeply furrowed angry brows, bulging wide furious eyes, wide open mouth screaming in rage` |
| **惊恐尖叫** | high raised in terror | round bulging shocked eyes | wide open mouth screaming | `high raised terrified brows, round bulging shocked eyes, wide open mouth screaming in fear` |
| **悠闲躺平** | relaxed droopy | half-closed lazy eyes | slightly open relaxed mouth | `relaxed droopy brows, half-closed lazy contented eyes, slightly open relaxed mouth` |
| **得意坏笑** | one raised mischievous | squinting sly eyes | crooked smug smirk | `one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk` |
| **焦虑困扰** | furrowed worried | darting anxious eyes | teeth clenched grimace | `furrowed worried brows, darting anxious uneasy eyes, teeth clenched nervous grimace` |
| **贪吃馋嘴** | raised eager | wide sparkling hungry eyes | tongue sticking out licking lips | `raised eager brows, wide sparkling hungry eyes, tongue sticking out licking lips` |
| **大哭崩溃** | raised in despair | streaming tears overflowing | wide open mouth wailing | `raised despairing brows, eyes streaming with tears overflowing, wide open mouth wailing crying` |
| **紧张僵硬** | slightly raised tense | wide stiff nervous eyes | tight closed tense mouth | `slightly raised tense brows, wide stiff nervous eyes, tight closed tense mouth` |
| **咬牙切齿** | deeply furrowed intense | fierce glaring eyes | teeth bared snarling | `deeply furrowed intense brows, fierce glaring eyes, teeth bared snarling` |
| **开心大笑** | raised joyful | sparkling crescent happy eyes | wide open laughing mouth | `raised joyful brows, sparkling crescent-shaped happy eyes, wide open laughing mouth showing teeth` |
| **震惊吃惊** | high raised shocked | bulging popping out eyes | wide O-shaped gasping mouth | `high raised shocked brows, bulging popping out eyes, wide O-shaped gasping mouth` |
| **傲娇不屑** | one slightly raised | side-eye dismissive glance | small pouty pursed lips | `one slightly raised brow, side-eye dismissive glance, small pouty pursed lips` |
| **害羞脸红** | raised worried | downcast shy eyes with blush | nervous small smile | `raised worried brows, downcast shy eyes with heavy blush, nervous small timid smile` |
| **无聊厌世** | droopy flat | half-lidded dead fish eyes | flat unamused straight line | `droopy flat brows, half-lidded dead fish bored eyes, flat unamused straight line mouth` |
| **困惑迷茫** | one raised confused | squinting puzzled eyes | crooked confused frown | `one brow raised confused, squinting puzzled uncertain eyes, crooked confused slight frown` |
| **邪恶狂笑** | lowered menacing | narrowed evil scheming eyes | wide sinister grin | `lowered menacing brows, narrowed evil scheming eyes, wide sinister evil grin` |

---

## 五、艺术风格库

### 风格核心原则

> **颜色明亮、分割清晰、不要过于花、明确的主色**

所有风格都应遵循：
- ✅ 饱和度高的明亮色彩
- ✅ 颜色区域分明，边界清晰
- ✅ 简洁造型，避免过多细节
- ✅ 1-2个标志性主色

---

### 风格1：Sanrio 三丽鸥风（Hello Kitty、美乐蒂）

**特点**：极简符号化、纯粹可爱、颜色分割清晰

| 维度 | 关键词 |
|------|--------|
| 造型 | `Sanrio style, extremely simple kawaii character, minimal dot eyes, no mouth or tiny mouth, round soft blob shape, clean solid colors, flat color blocks, iconic silhouette` |
| 配色 | 明亮单一主色（粉/白/黄），颜色分割清晰 |
| 适用 | 可爱、少女向、文创、表情包 |

---

### 风格2：Line Friends 风（布朗熊、可妮兔）

**特点**：简洁轮廓、大色块填充、表情简单直接

| 维度 | 关键词 |
|------|--------|
| 造型 | `Line Friends style, simple rounded character, bold clean outline, flat solid color fill, minimal facial features, dot eyes, simple expressions, smooth surface` |
| 配色 | 单一明确主色（棕/白/黄），无渐变 |
| 适用 | 通用、表情包、品牌吉祥物 |

---

### 风格3：Loopy 露比风（粉红小海狸）

**特点**：圆润软萌、粉嫩配色、简单五官

| 维度 | 关键词 |
|------|--------|
| 造型 | `Loopy style, super round soft character, chubby cute proportions, simple dot eyes, small nose, minimal details, smooth matte surface, bright pastel colors` |
| 配色 | 粉嫩柔和主色，颜色纯净 |
| 适用 | 软萌、治愈、儿童向 |

---

### 风格4：Pokemon 宝可梦风（皮卡丘）

**特点**：明亮饱和色、清晰轮廓、标志性造型

| 维度 | 关键词 |
|------|--------|
| 造型 | `Pokemon style, bright saturated colors, clean sharp outlines, iconic simple silhouette, expressive large eyes, cute creature design, solid color blocks` |
| 配色 | 高饱和明亮主色（黄/蓝/红），对比清晰 |
| 适用 | 活泼、儿童向、游戏角色 |

---

### 风格6：Crayon Shin-chan 蜡笔小新风

**特点**：粗线条、扁平色块、夸张简化

| 维度 | 关键词 |
|------|--------|
| 造型 | `Crayon Shin-chan style, thick black outlines, flat bold colors, simplified exaggerated features, 2D cartoon aesthetic, minimal shading, comic style` |
| 配色 | 鲜艳扁平色块，无渐变 |
| 适用 | 搞笑、日常、表情夸张 |

---

### 风格7：Kuromi 库洛米风（暗黑可爱）

**特点**：黑粉配色、小恶魔元素、可爱中带叛逆

| 维度 | 关键词 |
|------|--------|
| 造型 | `Kuromi style, cute devil character, black and pink color scheme, simple kawaii features, small skull or bat accessories, clean color blocks, minimal details` |
| 配色 | 黑+粉/紫为主，对比强烈 |
| 适用 | 暗黑可爱、亚文化、少女向 |

---

### 风格8：Chiikawa 吉伊卡哇风（极简手绘）

**特点**：极简线条、软糯造型、手绘感

| 维度 | 关键词 |
|------|--------|
| 造型 | `Chiikawa style, extremely simple hand-drawn character, wobbly soft outlines, tiny dot eyes, blushing cheeks, minimal blob body, pastel soft colors` |
| 配色 | 柔和淡色，简单纯净 |
| 适用 | 治愈、可爱、表情包 |

---

### 风格9：Molly 泡泡玛特潮玩风

**特点**：光滑乙烯基质感、大眼无表情、潮流艺术

| 维度 | 关键词 |
|------|--------|
| 造型 | `Molly Pop Mart style, vinyl toy aesthetic, smooth glossy surface, large sparkly eyes, blank cute expression, designer toy proportions, collectible figure look` |
| 配色 | 明亮糖果色，光泽质感 |
| 适用 | 潮玩、收藏、艺术向 |

---

### 风格10：Chibi 夸张Q版风

**特点**：超大头、小身体、表情夸张

| 维度 | 关键词 |
|------|--------|
| 造型 | `Chibi style, super deformed 2-head-tall proportions, extremely large head, tiny body, exaggerated expressions, bright solid colors, clean simple design` |
| 配色 | 明亮饱和，颜色分明 |
| 适用 | 暴躁、搞笑、动态表情 |

---

### 风格11：Yoshitomo Nara 奈良美智风

**特点**：叛逆眼神、嘟嘴、朋克可爱

| 维度 | 关键词 |
|------|--------|
| 造型 | `Yoshitomo Nara style, large flat head, big defiant eyes, minimal features, punk-cute aesthetic, muted earth tones, simple clean design` |
| 配色 | 柔和大地色，偶尔亮色点缀 |
| 适用 | 傲娇、厌世、文艺向 |

---

### 风格12：Tim Burton 哥特风

**特点**：大眼睛、苍白、暗黑童话

| 维度 | 关键词 |
|------|--------|
| 造型 | `Tim Burton style, huge round eyes, pale skin, dark whimsical aesthetic, simple gothic design, black and white with color accents, quirky proportions` |
| 配色 | 黑白为主，点缀亮色 |
| 适用 | 诡异、万圣节、暗黑可爱 |

---

### 风格速查表

| 风格 | 关键词前缀 | 配色特点 | 最适合情感 |
|------|-----------|---------|-----------|
| Sanrio | `Sanrio style` | 粉/白/黄，极简 | 开心、害羞 |
| Line Friends | `Line Friends style` | 棕/白，大色块 | 通用 |
| Loopy | `Loopy style` | 粉嫩柔和 | 软萌、治愈 |
| Pokemon | `Pokemon style` | 高饱和明亮 | 活泼、开心 |
| 蜡笔小新 | `Crayon Shin-chan style` | 扁平鲜艳 | 搞笑、夸张 |
| Kuromi | `Kuromi style` | 黑+粉/紫 | 傲娇、叛逆 |
| Chiikawa | `Chiikawa style` | 柔和淡色 | 治愈、害羞 |
| Molly | `Molly Pop Mart style` | 糖果色光泽 | 潮流、艺术 |
| Chibi | `Chibi style` | 明亮饱和 | 暴怒、惊讶 |
| Nara | `Yoshitomo Nara style` | 大地色 | 傲娇、厌世 |
| Tim Burton | `Tim Burton style` | 黑白+亮色 | 诡异、邪恶 |

---

## 六、身材比例库

### 比例选择规则

根据情感和角色定位，选择合适的身材比例：

| 比例类型 | 头身比 | 关键词 | 适用场景 |
|----------|--------|--------|---------|
| **Q版/Chibi** | 2-3头身 | `chibi proportions, big head tiny body` | 可爱、搞笑、夸张表情 |
| **标准比例** | 4-5头身 | `balanced proportions, medium head to body ratio` | 通用、自然、日常 |
| **修长比例** | 6-7头身 | `elegant slim proportions, longer limbs` | 优雅、帅气、时尚 |
| **写实比例** | 7-8头身 | `realistic human proportions` | 成熟、写实、严肃 |
| **萌系圆润** | 1-2头身 | `round blob shape, minimal body` | 极简萌物、表情包 |

### 情感 → 推荐比例

| 情感 | 推荐比例 | 原因 |
|------|---------|------|
| 生气/愤怒 | Q版 | 头大身小更显"奶凶" |
| 惊讶/震惊 | Q版 | 夸张表情更有冲击力 |
| 傲娇/不屑 | 标准/修长 | 显得更有气场 |
| 邪恶/坏笑 | 标准/修长 | 更有威胁感 |
| 害羞/紧张 | Q版/标准 | 显得更可爱无害 |
| 其他情感 | 标准比例 | 通用选择 |

---

## 七、角色类型库

### 角色类型选择

IP 形象**不限于动物**，可以是任何类型：

| 角色类型 | 描述关键词 | 质感关键词 |
|----------|-----------|-----------|
| **人类角色** | `character, person, girl, boy` | `smooth skin texture, realistic fabric texture` |
| **拟人动物** | `anthropomorphic [animal]` | `realistic soft fur texture` |
| **Q版动物** | `cute [animal]` | `realistic soft fur texture` |
| **机器人** | `robot, mecha, android` | `smooth metallic surface, reflective material` |
| **食物精灵** | `[food] character, food spirit` | `smooth glossy surface` 或对应食物质感 |
| **植物精灵** | `plant spirit, flower fairy` | `organic natural texture, soft petal surface` |
| **物品拟人** | `[object] character` | 根据物品材质选择 |
| **幻想生物** | `fantasy creature, mythical being` | 根据设定选择 |
| **抽象形态** | `abstract character, geometric being` | `smooth surface` |

### 质感模块（按角色材质选用）

| 材质类型 | 质感关键词 |
|----------|-----------|
| 毛绒/皮毛 | `realistic soft fur texture` |
| 布料/服装 | `realistic fabric texture with soft folds` |
| 金属/机械 | `smooth metallic surface, reflective material` |
| 果冻/透明 | `translucent jelly texture, soft subsurface scattering` |
| 陶瓷/瓷器 | `smooth porcelain surface, glossy ceramic texture` |
| 皮肤/人类 | `smooth skin texture, soft natural complexion` |
| 木质 | `natural wood grain texture, warm organic surface` |
| 塑料/乙烯基 | `smooth vinyl surface, toy-like plastic texture` |

---

## 八、提示词组装系统

### 设计流程

```
用户需求 → 情感定位 → 自动推荐(风格+比例) → 角色类型 → 表情关键词 → 组装提示词
```

### 提示词组装公式

```
[艺术风格] [身材比例] [角色类型], [表情关键词], [配色], [质感], 3D CGI render, white background, high quality
```

### 模块说明

| 模块 | 说明 | 示例 |
|------|------|------|
| 艺术风格 | 从风格库选择 | `Pokemon style`, `Sanrio style` |
| 身材比例 | 从比例库选择 | `chibi proportions` 或 `balanced proportions` |
| 角色类型 | 从角色库选择 | `fox`, `girl`, `robot`, `cake character` |
| 表情关键词 | 从表情系统获取 | `one raised eyebrow, half-lidded smug eyes, sly confident smirk` |
| 配色 | 描述颜色方案 | `orange and cream colors` |
| 质感 | 从质感库选择 | `realistic soft fur texture` |

### 完整示例

| 类型 | 角色 | 比例 | 完整提示词 |
|------|------|------|-----------|
| 动物 | 狐狸 | Q版 | `Pokemon style, chibi proportions, cute fox, one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk, orange and cream colors, realistic soft fur texture, 3D CGI render, white background, high quality` |
| 人类 | 女孩 | 标准 | `Loopy style, balanced proportions, cute girl character, raised worried brows, downcast shy eyes with heavy blush, nervous small timid smile, soft pink colors, smooth skin texture, 3D CGI render, white background, high quality` |
| 机器人 | 小机器人 | Q版 | `Molly Pop Mart style, chibi proportions, cute robot, one brow raised confused, squinting puzzled uncertain eyes, crooked confused slight frown, silver and blue colors, smooth metallic surface, reflective material, 3D CGI render, white background, high quality` |
| 食物 | 蛋糕精灵 | 萌系圆润 | `Sanrio style, round blob shape, cake character with face, raised joyful brows, sparkling crescent-shaped happy eyes, wide open laughing mouth, pastel pink and cream colors, smooth glossy surface, 3D CGI render, white background, high quality` |
| 人类 | 帅气少年 | 修长 | `Line Friends style, elegant slim proportions, handsome boy character, one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk, cool blue and black colors, smooth skin texture, 3D CGI render, white background, high quality` |

---

## 九、设计避坑指南

### 必须避免的问题

| 问题类型 | 具体表现 | 正确方向 |
|----------|----------|----------|
| ❌ 同质化帅气 | 一眼看不出谁是谁的帅 | 加入反差特征 |
| ❌ 平庸萌感 | 没啥特色的大眼圆脸萌 | 加入性格冲突 |
| ❌ 空洞仙美 | 又仙又美又无趣 | 加入趣味细节 |
| ❌ 单一性格 | 只可爱 / 只酷 / 只凶 | 设计冲突组合 |
| ❌ 风格缺失 | 只写风格名称不展开 | 必须使用4维度完整描述 |
| ❌ 配色缺失 | 没有指定颜色方案 | 必须包含配色方案关键词 |
| ❌ 物品缺失 | 没有标志性元素 | 必须包含物品元素装饰 |

### 创作边界约束

- **禁止**未经用户要求的额外发挥（如随意添加"现代化"、"未来感"等）
- 服装设计应优先尊重角色原有设定
- 只有当用户明确要求特定风格时才加入

---

## 十、交付规范

生成IP形象后，**必须输出以下内容**：

```
【艺术风格】xxx
【身材比例】xxx
【情感定位】xxx
【角色类型】xxx
【完整提示词】
```

### 交付示例

```
【艺术风格】Pokemon
【身材比例】标准比例
【情感定位】得意坏笑
【角色类型】动物角色
【视觉抓手】闪电形尾巴

【完整提示词】
Pokemon style, balanced proportions, cute fox character, one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk, orange and cream colors, with lightning bolt shaped tail, realistic soft fur texture, 3D CGI render, white background, high quality
```

### 更多示例（多样化角色类型）

| 角色类型 | 角色 | 比例 | 情感 | 完整提示词 |
|----------|------|------|------|-----------|
| 人类 | 女孩 | 标准 | 害羞 | `Loopy style, balanced proportions, cute girl character, raised worried brows, downcast shy eyes with heavy blush, nervous small timid smile, soft pink colors, smooth skin texture, 3D CGI render, white background` |
| 人类 | 帅哥 | 修长 | 得意 | `Line Friends style, elegant slim proportions, handsome boy character, one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk, cool blue and black colors, smooth skin texture, 3D CGI render, white background` |
| 动物 | 狐狸 | Q版 | 调皮 | `Pokemon style, chibi proportions, cute fox, one raised mischievous brow, squinting sly cunning eyes, crooked smug smirk, orange and cream colors, realistic soft fur texture, 3D CGI render, white background` |
| 机器人 | 小机器人 | Q版 | 困惑 | `Molly Pop Mart style, chibi proportions, cute robot, one brow raised confused, squinting puzzled uncertain eyes, crooked confused slight frown, silver and blue colors, smooth metallic surface, 3D CGI render, white background` |
| 食物 | 蛋糕 | 萌系 | 开心 | `Sanrio style, round blob shape, cake character with face, raised joyful brows, sparkling crescent-shaped happy eyes, wide open laughing mouth, pastel pink colors, smooth glossy surface, 3D CGI render, white background` |
| 暗黑 | 小恶魔 | 标准 | 傲娇 | `Kuromi style, balanced proportions, cute devil character, one slightly raised brow, side-eye dismissive glance, small pouty pursed lips, black and pink colors, 3D CGI render, white background` |

---

## 十一、评估检查清单

在最终交付前，请对照以下清单进行自检：

**可识别性（重要！）**
- [ ] **剪影测试**：只看黑色轮廓，能认出这是什么角色吗？
- [ ] **视觉抓手**：有没有一个独特元素让人过目不忘？
- [ ] **简洁度**：能用3个词描述核心特征吗？
- [ ] **区分度**：和市面上其他IP放在一起，能一眼认出吗？

**风格与情感**
- [ ] 是否选择了合适的艺术风格？
- [ ] 是否确定了情感定位？
- [ ] 是否使用了完整的3维度表情关键词（眉毛+眼睛+嘴巴）？

**颜色与造型**
- [ ] 颜色是否明亮？
- [ ] 颜色分割是否清晰？
- [ ] 是否有明确的1-2个主色？
- [ ] 造型是否简洁（不过于花）？

**提示词结构**
- [ ] 是否以艺术风格名称开头？
- [ ] 是否包含完整表情关键词？
- [ ] 是否有配色关键词？
- [ ] 是否有标志性视觉抓手？（配饰/符号/特征）
- [ ] 是否有固定渲染模块？（`3D CGI render, white background, high quality`）

**交付内容**
- [ ] 是否输出了艺术风格？
- [ ] 是否输出了情感定位？
- [ ] 是否输出了视觉抓手？
- [ ] 是否输出了完整提示词？
