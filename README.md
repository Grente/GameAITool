# GameAITool

游戏开发 AI 工具精选，面向**策划 / 技术 / 美术 / 音效 / 文案**。只收录官方站点可访问、团队能直接用上的工具；优先免费、开源或免费增值，同类产品不重复堆砌。

> 更新于 2026-10。模型、套餐和商用条款变化很快，上线前请自行核对授权。欢迎按 [CONTRIBUTING.md](CONTRIBUTING.md) 补充条目。

**标签说明：** `开源` · `免费` · `免费增值` · `付费` · `需 API Key`

## 目录

- [策划](#策划)
- [技术](#技术)
- [美术](#美术)
- [音效](#音效)
- [文案](#文案)
- [选用与合规](#选用与合规)

---

## 策划

立项、GDD、系统数值和关卡构想。通用长文写作也可直接用这里的大模型，文案栏目不再重复罗列。

- [Ludo.ai](https://ludo.ai/) — 面向游戏的构思与 GDD 工作区，可从题材生成玩法、角色和关卡骨架，并顺手出占位素材。适合从 0 到 1 把想法写成可评审文档。`免费增值`
- [Claude](https://claude.ai/) — 长上下文强，适合通读整份 GDD、拆系统循环、写经济案和关卡说明。付费档更稳，也可走 API。`免费增值` `需 API Key`
- [DeepSeek](https://www.deepseek.com/) — 推理与性价比好，适合推战斗公式、经济循环和「这个系统会不会坏掉」。国内访问方便。`免费增值`
- [Kimi](https://www.kimi.com/) — 长文档、多文件理解强，适合丢一叠竞品分析、版本文案或设计日志，再要结构化摘要与待办。`免费增值`
- [NotebookLM](https://notebooklm.google.com/) — 把 GDD、设定集、会议记录喂进去做问答和摘要，适合维护会膨胀的世界观资料，而不是从空白生成故事。`免费`

---

## 技术

### 代码助手

- [Cursor](https://cursor.com/) — AI 原生编辑器，适合跨文件改玩法、补引擎样板代码和对照报错改工程。免费档可起步，Agent 与高级模型需订阅。`免费增值`
- [GitHub Copilot](https://github.com/features/copilot) — 主流 IDE 补全与 Agent，和 GitHub 仓库、PR 审查绑得紧。适合已有 GitHub 工作流的团队。`付费`
- [通义灵码](https://lingma.aliyun.com/) — 阿里云出品的 IDE 插件 / Lingma IDE，中文问答和国内网络更稳，适合客户端、服务端和配置表一类重复代码。`免费增值`
- [Claude Code](https://claude.com/product/claude-code) — 终端里的编程 Agent，适合在已有 Unity / 服务器仓库里做大范围重构和排障。需 Anthropic 账号。`付费` `需 API Key`
- [Aider](https://aider.chat/) — 开源命令行结对编程，对接自备模型或本地 Ollama。适合不想换编辑器、只要 Git 友好改动的人。`开源` `需 API Key`

### 引擎与运行时

- [Unity 编辑器 AI 工具](https://unity.com/features/ai) — Unity 6 起的编辑器助手、AI Gateway 和 MCP，能带着工程上下文写脚本、改场景和出占位资源。需要 Unity 6+；助手本身消耗积分。`免费增值`
- [Unity Sentis（Inference Engine）](https://docs.unity3d.com/Packages/com.unity.ai.inference@latest) — 在玩家设备上跑 ONNX 模型，做识别、本地 NPC 决策或轻量语音，不必把推理送到云端。随 Unity 包管理器安装。`免费`
- [NVIDIA ACE](https://developer.nvidia.com/ace-for-games) — 面向游戏角色的语音、口型和在线推理套件，Unreal 文档和支持更完整。适合已有 NVIDIA 生态、要做会说话角色的项目。`免费增值` `需 API Key`
- [Ollama](https://ollama.com/) — 本机拉起开源大模型，给编辑器插件、Godot `HTTPRequest` 或离线工具当后端。Godot 目前缺少成体系的官方 AI 插件，本地模型 + 自己接请求是更稳的路。`开源` `免费`

### 对话 NPC

- [Convai](https://www.convai.com/) — 会说话的 NPC 平台，官方 Unity / Unreal / Web SDK。免费档只够原型（交互次数和月活用户很少），上线要付费。`免费增值` `需 API Key`
- [Inworld](https://inworld.ai/) — 带人设、记忆和语音的角色运行时，按用量计费。适合要动态对白、而不是写死对话树的项目；别把密钥打进客户端。`免费增值` `需 API Key`

---

## 美术

### 2D、概念与像素

- [Midjourney](https://www.midjourney.com/) — 概念图、氛围和角色方向快。中文提示一般，商用看订阅档；年营收超门槛通常要更高套餐。`付费`
- [Leonardo.Ai](https://leonardo.ai/) — 2D 出图 + 可平铺纹理，有偏游戏的模型和训练自定义风格。适合一个人同时要概念图和 PBR 贴图草稿。`免费增值`
- [Scenario](https://www.scenario.com/) — 用自己的美术规范训练风格，再批量出道具、UI、背景。风格要锁死、资产要成套时比通用生图稳。`免费增值`
- [PixelLab](https://www.pixellab.ai/) — 像素角色、四/八方向、动作帧和 tileset。做像素游戏、要和 Aseprite 工作流对齐时用。`免费增值`
- [Recraft](https://www.recraft.ai/) — 矢量图标、Logo 和 UI 元件，能保持一套自定义风格。适合商店页、HUD 和图标，而不是角色原画。`免费增值`
- [即梦 AI](https://jimeng.jianying.com/) — 字节出品，中文提示和国风概念图好上手，适合立项阶段快速铺角色 / 场景方向。商用以会员条款为准。`免费增值`
- [通义万相](https://tongyi.aliyun.com/wan/) — 阿里文生图，API 清楚，适合接到自己的出图管线做批量概念或贴图参考。`免费增值` `需 API Key`
- [LiblibAI](https://www.liblib.art/) — 国内托管的 Stable Diffusion / Comfy 社区，模型多、可在线跑。用之前核底模和 LoRA 各自的授权。`免费增值`
- [ComfyUI](https://www.comfy.org/) — 开源节点式出图，可本地或自建服务器跑 SD / FLUX 等。适合要可复现、能批量的贴图和概念管线。`开源` `免费`

### 3D 资产

- [Meshy](https://www.meshy.ai/) — 文生 / 图生 3D，带减面、PBR、绑骨和引擎导出。道具、摆件和中低模初稿最快；拓扑仍要人工收。`免费增值`
- [Tripo](https://www.tripo3d.ai/) — 另一条成熟的文生 / 图生 3D，迭代快，导出格式看套餐。和 Meshy 二选一试即可，不必两家都订。`免费增值`
- [混元生 3D](https://3d.hunyuan.tencent.com/) — 腾讯混元文生 / 图生 3D，网页试用；开源权重见 [Hunyuan3D](https://github.com/Tencent-Hunyuan/Hunyuan3D-2)。适合能自建推理、或想走国内服务的团队。`开源` `免费增值`

### 放大

- [Upscayl](https://upscayl.org/) — 开源本地放大，把小稿、像素图或旧贴图拉到能进引擎的分辨率。不经过云、也没有按张扣费。`开源` `免费`

---

## 音效

原清单里的第三方「TikTok AI Voice」站带推广参数，不是官方产品，已换成下面这些可核验的工具。

### 配乐

- [Suno](https://suno.com/) — 带人声的完整曲子来得快，适合预告片、主题曲小样。商用下载和授权以付费档为准，下载次数有上限。`免费增值`
- [Beatoven](https://www.beatoven.ai/) — 按情绪和时长出免版税器乐，面向视频和游戏背景乐。免费试听，下载商用看套餐。`免费增值`
- [AIVA](https://www.aiva.ai/) — 偏电影和管弦的配乐生成，适合过场、主菜单和需要主题动机的项目。`免费增值`
- [Stable Audio](https://www.stableaudio.com/) — Stability 的音乐 / 音效生成，有网页和开放权重路线。社区许可对营收有门槛，上线前读当前条款。`免费增值` `开源`

### 音效 SFX

- [ElevenLabs](https://elevenlabs.io/) — 同一套产品里做角色 TTS、短音效和氛围 loop（约 0.5–30 秒）。原型可用免费积分，上线走 API。`免费增值` `需 API Key`

（Stable Audio、Beatoven 也能出部分音效；短交互音优先试 ElevenLabs。）

### 语音 / TTS

- [Fish Audio](https://fish.audio/) — 中文表现力和情绪控制较好，适合角色台词、旁白和要克隆音色的原型。有免费额度，量产走 API。`免费增值` `需 API Key`
- [MiniMax Audio](https://www.minimax.io/audio) — 海螺 / MiniMax 语音，中文配音和音色多，国内也可用 [minimax.cn/audio](https://www.minimax.cn/audio)。适合对白批量和多语试音。`免费增值` `需 API Key`
- [Piper](https://github.com/rhasspy/piper) — 本地、轻量的开源 TTS，Godot / 自建工具用 HTTP 就能接。音质不如云端旗舰，但无按字计费、可离线。`开源` `免费`
- [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) — 开源少样本音色克隆，中文社区常用。适合固定角色配音；商用要单独看训练数据和模型许可，不要直接克隆真人未授权声音。`开源` `免费`
- [CosyVoice](https://github.com/QwenAudio/CosyVoice) — 通义系开源 TTS，中文自然度高，可自建推理给对白管线用。`开源` `免费`

---

## 文案

对白、设定、任务文本和本地化。系统案、数值和经济请看 [策划](#策划)。

- [Novelcrafter](https://www.novelcrafter.com/) — 给长篇和设定集用的写作台，带人物 / 地点 Codex。适合维护会互相引用的世界观，再按需接自己的模型。`免费增值` `需 API Key`
- [Sudowrite](https://www.sudowrite.com/) — 偏散文和故事节拍的写作辅助，适合过场、日志和长对白润色，不是表格填空工具。`付费`
- [ChatGPT](https://chatgpt.com/) — 通用写作和头脑风暴，任务描述、物品说明、命名和多方案对比都快。深度设定建议配合资料库或其它长上下文模型。`免费增值`
- [通义千问](https://tongyi.aliyun.com/) — 中文文案、命名和任务文本好用，并能接到阿里云 API 做批量生成。`免费增值` `需 API Key`
- [豆包](https://www.doubao.com/) — 中文口语和短文案顺，适合商店卖点、活动页、引导和偏轻松的 NPC 对白草稿。`免费`
- [DeepL](https://www.deepl.com/zh) — 翻译质量和术语表适合游戏本地化初稿（UI、任务、物品）。上线仍要母语者过一遍。`免费增值`
- [Crowdin](https://crowdin.com/) — 本地化平台，可接机器翻译 / AI 预译和术语表。字符串一多、要和 Unity / Unreal 导出对接时用。`免费增值`

---

## 选用与合规

- **先看授权再进包体。** 免费档、开源权重、会员「可商用」往往带营收门槛、署名或禁止再训练等条款。
- **密钥不要进客户端。** NPC 对话、TTS、生图 API 都应放在你控制的服务端；Steam 对实时生成内容也有披露要求。
- **AI 稿当初稿。** 3D 要收拓扑和贴图，对白要过人设和本地化，音效要听循环接缝。
- **不要克隆未授权的真人声音或画风去商用。**

许可：本清单以 [CC0 1.0](LICENSE) 发布。所列工具的商标和版权归各权利人。
