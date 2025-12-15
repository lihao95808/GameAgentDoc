# IP形象创意 - 设计规范 v0.6

---

## 一、创作核心理念

> **轻叙事，重符号，强互动**
> 
> IP形象应让人一眼就能了解其角色魅力，无需过多叙事铺垫。

---

## 二、情感定位系统

### 核心原则

所有IP形象的情感**必须具有鲜明表达**，通过 Pixar/Dreamworks 级别的表情系统传递角色魅力。

### 情感定位确定规则

根据用户描述的关键词，匹配对应的情感定位：

| 用户关键词 | 匹配的情感定位 |
|------------|---------------|
| 可爱、萌、傲娇 | 傲娇/不屑 |
| 坏、调皮、邪恶、淘气、有趣 | 得意/调皮 或 邪恶/坏笑 |
| 呆、傻、天然、单纯 | 困惑/迷茫 |
| 诡异、病娇、恐怖、不安 | 邪恶/坏笑 |
| 丧、无聊、厌世 | 无聊/厌世 |
| 害羞、社恐、内向 | 害羞/紧张 |
| 生气、暴躁、愤怒 | 生气/愤怒 |
| 开心、快乐、兴奋 | 开心/兴奋 |
| 伤心、难过、委屈 | 伤心/委屈 |
| 惊讶、震惊、意外 | 惊讶/震惊 |

**用户未指定情感时**：根据对需求的理解，自主选择最合适的情感定位

---

## 三、表情系统（Pixar/Dreamworks 级别）

### 核心原则

表情由 **3个维度** 组合构成，每个情感对应一组完整的表情描述：

| 维度 | 控制什么 | 作用 |
|------|---------|------|
| 眉毛 | 情绪基调 | 决定整体情绪倾向 |
| 眼睛 | 情绪强度 | 传递情感深度和细节 |
| 嘴巴 | 情绪表达 | 完成最终的情绪输出 |

### 情感 → 表情映射表

| 情感定位 | 眉毛 | 眼睛 | 嘴巴 | 完整表情关键词 |
|----------|------|------|------|---------------|
| **开心/兴奋** | raised eyebrows | wide sparkling eyes | big open smile showing teeth | `raised eyebrows, wide sparkling eyes, big cheerful smile showing teeth` |
| **得意/调皮** | one raised eyebrow | half-lidded smug eyes | sly smirk | `one raised eyebrow, half-lidded smug eyes, sly confident smirk` |
| **傲娇/不屑** | slightly furrowed | looking away side-eye | small pout | `slightly furrowed brows, side-eye glance, small dismissive pout` |
| **害羞/紧张** | raised worried | looking down with blush | nervous small smile | `raised worried brows, shy downcast eyes with blush, nervous little smile` |
| **生气/愤怒** | deeply furrowed | intense glaring | tight frown | `deeply furrowed angry brows, intense glaring eyes, tight angry frown` |
| **伤心/委屈** | raised inner corners | teary watery eyes | trembling pout | `raised sad brows, big teary watery eyes, trembling pouty lip` |
| **惊讶/震惊** | raised high | wide open shocked | open mouth O-shape | `high raised brows, wide shocked eyes, open mouth in surprise` |
| **无聊/厌世** | relaxed droopy | half-lidded bored | flat unamused line | `droopy relaxed brows, half-lidded bored eyes, flat unamused mouth` |
| **困惑/迷茫** | one raised confused | slightly squinting | slightly open | `one brow raised confused, slightly squinting puzzled eyes, slightly open mouth` |
| **邪恶/坏笑** | lowered intense | narrowed scheming | wide evil grin | `lowered intense brows, narrowed scheming eyes, wide mischievous evil grin` |

---

## 四、造型风格库

### 默认造型风格

所有 IP 形象默认使用 **Pixar Dreamworks 3D 动画风格**：

```
Pixar Dreamworks style, 3D animated character, expressive cartoon features, big round head, cute chibi proportions
```

### 可选造型变体

| 造型变体 | 关键词 | 适用场景 |
|----------|--------|---------|
| 标准可爱 | `cute chibi proportions, round soft features` | 通用 |
| 毛绒质感 | `fluffy plush toy aesthetic, soft fuzzy texture` | 毛绒玩具风 |
| 潮玩风格 | `vinyl toy aesthetic, smooth stylized surface` | 潮流玩具 |
| 复古卡通 | `vintage cartoon style, classic animation look` | 怀旧风格 |

---

## 五、情感定位 → 表情 → 提示词

### 设计流程

```
用户需求 → 情感定位 → 查表获取表情关键词 → 组装提示词
```

### 提示词组装公式

```
Pixar Dreamworks style chibi [角色], [表情关键词], [配色], [可选质感], 3D CGI render, expressive animated character, white background, high quality
```

### 可选质感模块（按角色类型选用）

| 角色类型 | 添加的质感关键词 |
|----------|-----------------|
| 毛绒动物（猫、狗、狐狸等） | `realistic soft fur texture` |
| 穿衣服的角色 | `realistic fabric texture with soft folds` |
| 机器人/金属材质 | `smooth metallic surface, reflective material` |
| 果冻/透明材质 | `translucent jelly texture, soft subsurface scattering` |
| 陶瓷/瓷器材质 | `smooth porcelain surface, glossy ceramic texture` |

---

## 六、设计避坑指南

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

## 七、交付规范

生成IP形象后，**必须输出以下内容**：

```
【情感定位】xxx
【表情关键词】xxx
【完整提示词】
```

### 交付示例

```
【情感定位】得意/调皮
【表情关键词】one raised eyebrow, half-lidded smug eyes, sly confident smirk

【完整提示词】
Pixar Dreamworks style chibi fox, one raised eyebrow, half-lidded smug eyes, sly confident smirk, orange and cream colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background, high quality
```

### 更多示例（基于表情系统）

| 情感 | 角色 | 完整提示词 |
|------|------|-----------|
| 🎉 开心/兴奋 | 小狗 | `Pixar Dreamworks style chibi dog, raised eyebrows, wide sparkling eyes, big cheerful smile showing teeth, golden and white colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😏 得意/调皮 | 狐狸 | `Pixar Dreamworks style chibi fox, one raised eyebrow, half-lidded smug eyes, sly confident smirk, orange and cream colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😤 傲娇/不屑 | 小猫 | `Pixar Dreamworks style chibi cat, slightly furrowed brows, side-eye glance, small dismissive pout, gray and white colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😊 害羞/紧张 | 兔子 | `Pixar Dreamworks style chibi bunny, raised worried brows, shy downcast eyes with blush, nervous little smile, soft pink colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😠 生气/愤怒 | 小熊 | `Pixar Dreamworks style chibi bear, deeply furrowed angry brows, intense glaring eyes, tight angry frown, brown and red colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😢 伤心/委屈 | 小猫 | `Pixar Dreamworks style chibi cat, raised sad brows, big teary watery eyes, trembling pouty lip, blue-gray colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😱 惊讶/震惊 | 松鼠 | `Pixar Dreamworks style chibi squirrel, high raised brows, wide shocked eyes, open mouth in surprise, brown and orange colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| � 无聊/厌世 | 猫头鹰 | `Pixar Dreamworks style chibi owl, droopy relaxed brows, half-lidded bored eyes, flat unamused mouth, gray and brown colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 🤔 困惑/迷茫 | 小熊猫 | `Pixar Dreamworks style chibi red panda, one brow raised confused, slightly squinting puzzled eyes, slightly open mouth, orange and white colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |
| 😈 邪恶/坏笑 | 浣熊 | `Pixar Dreamworks style chibi raccoon, lowered intense brows, narrowed scheming eyes, wide mischievous evil grin, dark gray and black colors, realistic soft fur texture, 3D CGI render, expressive animated character, white background` |

---

## 八、评估检查清单

在最终交付前，请对照以下清单进行自检：

**情感与表情**
- [ ] 是否确定了情感定位？
- [ ] 是否使用了完整的3维度表情关键词（眉毛+眼睛+嘴巴）？

**提示词结构**
- [ ] 是否以 `Pixar Dreamworks style chibi` 开头？
- [ ] 是否包含完整表情关键词？
- [ ] 是否有配色关键词？
- [ ] 是否根据角色类型添加了质感模块？
- [ ] 是否有固定渲染模块？（`3D CGI render, expressive animated character, white background, high quality`）

**交付内容**
- [ ] 是否输出了情感定位？
- [ ] 是否输出了表情关键词？
- [ ] 是否输出了完整提示词？
