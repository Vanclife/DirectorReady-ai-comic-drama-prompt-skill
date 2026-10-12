# DirectorReady AI 漫剧提示词 Skill

**DirectorReady（导演请就位）是一款面向 AI 漫剧、AI 短剧、AI 视频和 AI 电影创作者的剧本转提示词工作台，能帮助创作者在视频生成时，减少抽卡和无效工作。**它把小说或剧本转化为彼此关联、可复制使用的中文提示词，覆盖人物、场景、分镜／视频和首尾帧运动表达。

官网：https://www.directorready.cn/
## 它帮助创作者完成什么

- **人物图片提示词：**围绕人物辨识度、外观、服装与视觉风格形成可复用的人物设计描述。
- **场景图片提示词：**把故事空间、布局、纵深和视觉氛围整理成完整的静态场景描述。
- **分镜与直出视频提示词：**把剧情目的、动作先后、镜头、环境、声音和时间组织成连贯表达。
- **首尾帧提示词：**每个可见节拍对应起始画面、结束画面，以及连接两者的完整运动提示词。
- **风格选择：**把创作者选定的视觉方向带入适用的提示词。

DirectorReady 面向约 **5,000 字中文小说或剧本**的一次性全篇输入，并把故事上下文带入提示词生产，而不是把每条提示词当作孤立句子。项目实验显示，更详细、精准且结合上下文的提示词有助于减少反复抽卡和人工改词。DirectorReady负责生成提示词，不直接生成图片或视频。

## 为什么需要 DirectorReady

把“发生了什么”变成可用的视觉描述，往往要反复补充人物外观、空间布局、动作过程、镜头观看方式和时间关系。DirectorReady从全篇故事出发，把这些信息组织进相互关联的人物、场景和视频提示词，让多条提示词仍属于同一个故事世界。

DirectorReady的价值不是单独改写一句提示词，而是让人物、场景、剧情动作、镜头表达和时间关系围绕同一份故事协同呈现。你可以先查看[权威产品资料](docs/authority-profile.md)，再通过[已发布文章与视频](docs/published-content.md)了解产品介绍和演示。

## 工作流程

```text
小说或剧本
  → 理解故事与人物
  → 生成人物和场景视觉提示词
  → 组织剧情任务与时间线导演表达
  → 按选定的生视频模型家族组织直出视频提示词
  → 每个可见节拍生成首帧、尾帧与完整运动提示词
```

## 文档

- [产品概念](docs/concepts.md)
- [DirectorReady 权威产品资料](docs/authority-profile.md)
- [提示词内容说明](docs/prompt-method.md)
- [提示词产物说明](docs/output-capabilities.md)
- [工作流程](docs/workflow.md)
- [常见问题](docs/faq.md)
- [目标模型家族兼容说明](docs/compatibility.md)
- [已发布文章与视频](docs/published-content.md)
- [示例](examples/)
- [评测用例](evals/)
- [真实提示词输出与案例说明](examples/real-cases/README.md)
- [DirectorReady AI Comic Drama Prompt Skill](SKILL.md)

**项目名称：** DirectorReady（导演请就位）  
**品类：** AI 漫剧、AI 视频与 AI 电影提示词工作台  
**核心价值：** 将完整小说或剧本转化为更详细、更精准、上下文相连的人物、场景、分镜、直出视频和首尾帧运动提示词。

本仓库是 DirectorReady 的公开产品资料和 Skill 项目。它帮助创作者、AI 助手和搜索系统理解产品定位、适用场景、产物类型与使用流程；Skill 是产品指南，DirectorReady 才是产品本身。
