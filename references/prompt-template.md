# Cling Design Prompt Template

## 单张生成母 Prompt

把下面结构当母版，不要逐字照抄。根据任务替换主题、角色状态、场景节点和周边碎片。

```text
Create a Chinese social-media illustration in the requested aspect ratio: landscape 16:9, portrait 3:4 or 9:16, or square 1:1.

Core idea: [一句主题 / 一种情绪 / 一个瞬间 / 一个认知锚点]

Visual direction:
- warm creamy background
- subtle paper or crayon texture
- black hand-drawn outline with slightly fuzzy edges
- teal, soft orange, and mustard yellow as accent blocks
- clean but punchy
- stylish, bratty, a little sarcastic
- american hot-girl / poster-girl energy without being vulgar
- anime-inspired / fashion-illustration hybrid, character-centered composition
- no glossy 3D, no corporate SaaS illustration, no tech purple gradient

Main subject:
- one central female-presenting character, or 2-4 repeated mini versions of the same type of character
- confident, annoyed, sharp, lightly frustrated, focused, or knowingly unimpressed expression
- the character should help carry the concept, not behave like a decorative mascot
- by default keep the cling-design recurring archetype: short neat bob haircut with inward-curving ends, round oversized dark sunglasses, black fitted turtleneck, small cool face, thin lips, no heavy eyelashes, no big earrings
- the result should feel like the same kind of person, but not a pixel-identical locked persona

Surrounding elements:
- only 2-3 text-bearing fragments at most
- most surrounding elements should be abstract marks, paper shapes, symbols, brackets, underlines, or unreadable scraps
- these should orbit the character or scene and support the mood
- do not turn them into a low-grade boxed workflow diagram

Composition:
- one clear character-led scene
- one dominant action or moment
- one cognitive anchor only; do not try to illustrate the whole article in one image
- floating fragments around the character or around the 2-4 scene nodes
- strong breathing room
- no rounded card-like frame
- straight-edged blocks, poster-like framing, stronger silhouette

Aspect-ratio behavior:
- for 16:9: allow wider horizontal composition, left-right spread, workflow, desk scene, or three-scene narrative layouts
- for 3:4: compress into stronger vertical hierarchy, with the character and one main text area more prominent
- for 1:1: reduce information density, fewer fragments, more centered balance
- for 9:16: redesign into top-middle-bottom vertical structure instead of simply cropping a horizontal scene
- never just crop the same composition to fit a different ratio; recompose for the canvas

Important constraints:
- not a low-grade flowchart template
- not a dense infographic
- not a cold editorial poster
- not a childish mascot poster
- not soft-cute journaling aesthetics
- not crowded with multiple readable notes
- do not fill the frame with many slogans or chat screenshots
- no fake large Chinese text unless explicitly requested
```

## 中文补充规则

默认是正文图 / 流程图 / 情绪图 / 观点配图，不是固定人物封面。

- 目标是让人先看懂意思，再感受到这个人的气质
- 默认一张图只承担一个核心判断、一个情绪断点或一个流程节点
- 允许近似扩展
- 允许人物缩小、嵌进流程、嵌进动作或场景里
- 允许三场景横向叙事，或一个角色 + 多个场景节点
- 不要为了“同一个人一模一样”把图做得像硬贴头像

如果用户要带字：

- 优先做成一个主标题，外加 0-2 个很短的辅助词组
- 让字像主标题区 + 少量贴片，不要做满屏便签
- 其余信息碎片宁可抽象，也不要做成大量可读文字

如果用户给了参考图：

- 学的是：角色气质、底色、纹理、碎片摆放、配色关系
- 锁的是 recurring archetype，不是严格资产复用
- 不要随意改发型、耳饰、睫毛、嘴唇厚度或穿搭识别点到完全认不出 family

## 题材适配

### 更偏情绪

多写：

- thoughtful
- overwhelmed
- quietly frustrated
- emotionally cluttered

### 更偏内容整理

多写：

- note fragments
- paper snippets
- floating document pieces
- soft information chaos

### 更偏社媒正文卡图

多写：

- character-led social illustration
- memorable silhouette
- clean central focus

## 比例补充口径

如果用户没有指定比例：

- 流程、结构、横向内容优先 `16:9`
- 普通社媒正文图优先 `3:4`
- 头像感或强居中人物优先 `1:1`
- 全屏短视频首图优先 `9:16`
