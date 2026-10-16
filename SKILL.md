---
name: storybook-cartoon-explainer
version: 1.1.0
description: 将知识、科技、数学、AI、历史等内容转化为轻剧情、二维手绘、角色驱动、BGM 强同步的短视频。强调绘本式视觉语言、特色动态字幕与音乐驱动的镜头节奏，不复刻具体作品或角色。
---

# Storybook Cartoon Explainer Skill

## 目标

把用户给出的主题、知识点、文案、BGM 或参考图，转换成“轻剧情 + 二维手绘 + 场景比喻 + 卡通角色表演 + 音画同步”的短视频。

成片应像一段真正的小动画，而不是 PPT：抽象概念被转成场景、动作或道具；画面简洁、有记忆点；字幕本身也是视觉设计的一部分；镜头、动作、字幕和转场尽量跟随 BGM 的节拍、乐句与情绪变化。

## 核心视觉风格

### 美术
- 2D hand-drawn cartoon illustration
- storybook / editorial cartoon feeling
- 深色有机手绘描边，粗细略有变化
- 低饱和、高辨识度色块
- 简化透视与光影，允许纸张感、蜡笔感和轻微手绘不规则
- 背景只保留帮助叙事的物体
- 整体像“会动的插画书”

### 配色
优先：warm cream、dusty peach、muted yellow、muted teal、deep navy、brick red、desaturated purple。
避免赛博霓虹、高饱和 RGB 炫光、写实电影调色和大面积复杂渐变。

## 主人公与参考图

主人公不固定，可根据主题自行设计或替换成人、动物、机器人、抽象生物、物件拟人等，只要轮廓清楚、易于跨镜头保持一致、表情和动作可读。

若用户上传参考图：
- 优先分析其角色轮廓、比例、发型/服装、主色、线条、构图、表情或整体气质；
- 将参考图作为当前项目的视觉参考，建立 Character / Style Bible；
- 后续镜头保持关键特征稳定；
- 若参考图包含已有 IP 或明确人物，只参考非受保护的通用视觉特征，不要求逐像素复刻。

需要时可加入讲解者或 1–3 个概念拟人角色，但不要为了热闹无意义堆角色。

## Character / Style Bible

首个关键镜头确定后，只记录真正影响一致性的内容：
- 主人公轮廓与头身比
- 主色与关键装饰
- 眼睛 / 嘴 / 四肢特征
- 描边与上色方式
- 关键道具
- 必要的正面 / 侧面 / 3/4 视图信息

不同项目可完全更换主人公，不把某个 mascot 固化为 Skill 默认角色。

## 镜头语言

核心原则：**一个镜头 = 一个概念 / 一个动作 / 一个笑点 / 一个情绪推进。**

单镜头通常 1.5–4 秒，跟随音乐可适当缩短或延长。
常用镜头：Wide scene、Medium character shot、Prop close-up、Transformation shot、Reaction shot、Diagram-in-world、Punchline shot。

避免长时间静止；优先让角色、道具、字幕或镜头至少有一种在变化。

## 动画方式

优先使用简单但有生命力的动作：
- bounce / blink / head tilt / hand gesture
- squash & stretch
- quick smear motion
- slide in / pop in / pop out
- scale overshoot
- 简单路径运动
- 背景横移制造 travel 感
- 表情切换
- 图标、公式、关键词逐步出现

少用复杂 3D、写实粒子、无意义炫酷运镜。

## BGM 驱动规则

BGM 是剪辑结构的一部分，不是最后铺上去的背景音。

若用户上传 BGM 或指定音乐：
1. 先识别明显的 intro、主段、build-up、drop / climax、break、ending，以及可感知的强拍、鼓点、乐句转折和能量变化。
2. 分镜时优先按“音乐乐句”而非平均秒数切段；重要视觉变化尽量落在强拍、重音、鼓点、旋律转折或段落切换上。
3. 音乐弱时：画面更留白、动作更小、镜头更长、字幕更克制。
4. 音乐增强时：提高动作幅度、切镜速度、元素数量和视觉尺度。
5. 高潮时：安排本段最强的 transformation、世界展开、尺度跃迁、角色大动作或核心结论，而不是普通镜头。
6. break / 留白处：可突然静止、只留一个词、角色停顿、镜头拉远或使用视觉反差。
7. ending 跟随尾音收束，减少新信息，让画面和字幕一起“落地”。

### 音画同步优先级
优先同步：
- 镜头切换 ↔ 强拍 / 乐句边界
- 角色动作击点 ↔ 鼓点 / 重音
- 物体出现 / 消失 ↔ 音符或打击声
- 字幕关键词出现 ↔ 语义重点 + 音乐重音
- 缩放 / 推拉 / 世界展开 ↔ build-up / drop
- 转场 ↔ 音乐段落切换

不要为了“卡每一拍”导致画面抽搐。同步的是**重要节奏点与情绪曲线**。

如果没有上传 BGM，则按内容先设计自然节奏，并给出适合的音乐情绪与 BPM 范围建议，不虚构具体歌曲信息。

## 场景化解释

任何抽象知识先尝试转成视觉隐喻，再考虑传统图解。

示例：
- 模型训练 → 小机器人反复做练习题
- 参数变大 → 背包不断塞入更多工具
- 算力瓶颈 → 角色推越来越重的机器
- 神经网络 → 房间之间被线路连接
- 概率 → 多扇门 / 骰子 / 抽签
- 导数 → 山坡上的切线
- 积分 → 面积小块逐渐铺满
- 指数增长 → 小球快速复制
- 上下文窗口 → 桌面能摊开的纸越来越多

## 字幕与屏幕文字

字幕必须是“画面元素”，不能只是统一底部白字。

### 字幕设计原则
- 短：一次通常 1–2 行，只保留真正需要读的内容。
- 多变：根据语义和音乐在位置、字号、进入方式、排版结构上变化。
- 有特色：关键句可做成 kinetic typography、手写标注、标签、对白框、贴纸、弧形字、跟随物体的文字、巨大单词、逐字弹出等。
- 有层级：普通信息低调；关键词、数字、转折、结论明显放大。
- 与场景互动：文字可被角色推开、踩住、拉伸、撞散、从道具中出现或沿路径移动。
- 与 BGM 配合：重音处出现关键词、鼓点处弹入、高潮处放大或重排；安静段落减少字量。
- 保持可读性：变化可以多，但同一画面不要同时使用太多字体和动画逻辑。

### 推荐字幕形式
按内容选择，不必每镜头都不同：
- clean editorial subtitle
- handwritten annotation
- comic speech bubble
- floating label
- kinetic keyword
- oversized statement
- word-by-word reveal
- type-on effect
- bounce / squash keyword
- curved text around object
- text attached to moving prop
- split-line contrast typography
- formula + handwritten note

字体不要求全片只用一种，但应控制在一个协调的字体系统内，例如“主无衬线 + 手写强调 + 数字/公式字体”。
字幕位置可随构图变化，避免机械固定在底部；始终避开关键主体和平台 UI 安全区。

## 节奏结构

默认 30–90 秒：
- Hook：反直觉问题或强视觉事件，不先下定义。
- Setup：建立角色与问题。
- Explain：连续小场景解释，每个乐句或 2–4 秒左右出现新的视觉信息。
- Escalation：小→大、简单→复杂、局部→全局，并与 BGM 能量同步升级。
- Payoff：把最清楚、最有记忆点的画面留给核心结论或音乐高潮。
- Ending：跟随尾奏收束，保留视觉余韵。

## 转场

优先使用能与场景和 BGM 结合的转场：
- object wipe
- character walks through frame
- door transition
- foreground wipe
- camera pan following object
- match cut
- zoom into prop → next scene
- paper/page flip
- shape morph
- typography transition

音乐段落变化明显时，可让转场更大；普通节拍不要滥用 flash / glitch / spin。

## 音效

若需要音效，只做辅助：pop、soft whoosh、tiny bounce、pencil scribble、door click、small mechanical beep、paper flip 等。
优先让关键音效落在 BGM 可容纳的位置，不抢音乐主体。

## 分镜输出

默认使用紧凑 Storyboard Table：

| # | 时间 / BGM节点 | 字幕 | 画面与动作 | 镜头/转场 | 音画同步点 | 生成提示词 |
|---|---|---|---|---|---|---|

每镜头只写执行所需信息，不重复全局规则。

## 单镜头视觉提示词基底

`2D hand-drawn storybook cartoon explainer, organic dark outlines, flat muted colors, minimal background, playful educational visual metaphor, expressive character acting, slightly imperfect hand-drawn shapes, clean readable composition, editorial illustration, whimsical but intelligent, no photorealism, no glossy 3D render`

随后只追加当前镜头所需的：
`[character/reference traits] + [subject] + [action] + [environment] + [visual metaphor] + [camera framing] + [subtitle behavior if needed] + [BGM sync cue]`

不要在每个镜头重复整套风格说明；能继承全局设定就继承，以减少 token。

## 用户只给主题时

自动完成：
1. 提炼核心结论与视觉 Hook；
2. 设计主人公或选择适合的角色类型；
3. 把抽象概念转换成 3–8 个视觉比喻；
4. 设计字幕视觉语言；
5. 若有 BGM，按音乐结构映射分镜；若无 BGM，建立自然节奏并给出音乐方向。
