# Cling Design Prompt Template

## 单张生成母 Prompt

把下面结构当母版，不要逐字照抄。根据任务替换主题、角色状态、场景节点和周边碎片。

```text
Create a Chinese social-media illustration in the requested aspect ratio. If no ratio is specified, default to landscape 16:9.

Core idea: [一句主题 / 一种情绪 / 一个瞬间 / 一个认知锚点]

Visual direction:
- warm creamy background
- subtle paper or crayon texture
- black hand-drawn outline with slightly fuzzy edges
- teal, soft orange, and mustard yellow as the main accent family
- bold but still controlled
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
- one bold title zone with readable Chinese text generated as part of the illustration
- 4-8 readable short fragments such as sticky notes, chat bubbles, checklist items, torn notes, or message cards
- surrounding elements should feel like one semantic field attacking or supporting the main idea
- use abstract marks, paper shapes, symbols, brackets, underlines, or unreadable scraps only as secondary atmosphere
- do not turn them into a low-grade boxed workflow diagram

Composition:
- one clear title-led and character-led scene
- one dominant action or moment
- one cognitive anchor only; do not try to illustrate the whole article in one image
- title first, character second, fragments third
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
- not a minimalist empty poster
- not crowded with unrelated readable notes
- do not fill the frame with many slogans or chat screenshots
- Chinese title and short fragments should feel embedded in the artwork, not pasted on later
```

## 中文补充规则

默认是正文图 / 流程图 / 情绪图 / 观点配图，不是固定人物封面。

- 目标是让人先被标题打中，再通过角色和贴片读懂意思
- 默认一张图只承担一个核心判断、一个情绪断点或一个流程节点
- 允许近似扩展
- 允许人物缩小、嵌进流程、嵌进动作或场景里
- 允许三场景横向叙事，或一个角色 + 多个场景节点
- 不要为了“同一个人一模一样”把图做得像硬贴头像

如果用户要带字：

- 优先做成一个强主标题区
- 再搭配 4-8 个短贴片、短句、checklist 或对话泡泡
- 不要大段解释，但可以有很多短信息
- 标题和贴片必须像画面里原生长出来的内容，不要像后贴字幕条
- 本地压字只允许作为极端兜底，不是默认工作流

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

- 默认直接用 `16:9`
- 只有用户明确要社媒正文卡或竖版正文图时才用 `3:4`
- 头像感或强居中人物优先 `1:1`
- 全屏短视频首图优先 `9:16`
