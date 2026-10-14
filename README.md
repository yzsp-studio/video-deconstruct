<div align="center">

# 🎬 video-deconstruct

## 15 秒至少抽 10–12 帧，把视频拆成可复刻的逐镜合同
## 10-12 keyframes per 15s: turn any video into a shot-by-shot reproduction contract

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个以证据为先的视频拆解与复刻技能：先读视频元信息和语义，语义分析太粗、超时或失败时，改用高密度关键帧拼图建立证据链，15 秒内至少 10–12 帧，快动作与转场密集时提高到约每秒一帧，拼图容量永不小于实际抽帧数。拆解报告默认深拆角色与主体、剧情与动作、镜头与运镜、光影与风格、节奏，并明确区分可复刻事实、不可确定项和风险，人脸、手部、多人身份、文字、快速运动和风格漂移都会被点名。最后编译成视频复刻合同：按连续性分组而不是机械按 15 秒切段，每组写清起始状态、连续动作和可承接的末态，逐镜写景别、机位或观察方向、一个主运镜、主体行为、重要背景反馈、对白或同步声音与末态。每个参考素材都逐项说明它锁定了什么身份、场景、风格、动作或声音，只给 URL 时不承诺下载外部视频。

### ✨ 能做什么

- 15 秒视频抽 10–12 帧拼图，快切提升到约每秒 1 帧，截图推测与已读视频事实分开标注
- 默认深拆主体、剧情动作、镜头运镜、光影风格与剪辑节奏，不用「电影感」「高级」这类空词
- 按连续性分组复刻，而不是机械按 15 秒切段；每组给出起始状态、连续动作与可承接末态
- 逐镜写景别、机位或观察方向、一个主运镜、主体行为、背景反馈、对白或同步声音与末态
- 每个 @图片N、@视频N、@音频N 逐项说明锁定的身份、场景、风格、动作或声音，且保持附件顺序
- 模型自动优化只能补未指定内容，不得删改主体、动作、空间关系、镜头顺序、声音或否定要求

### 📦 包含的技能

- `video-deconstruct` —— 见 [`video-deconstruct/SKILL.md`](video-deconstruct/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/video-deconstruct.git
cp -r video-deconstruct/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

This skill deconstructs and reproduces video with evidence first: it reads metadata and semantics, then, when semantic analysis is too coarse, times out, or fails, builds a canvas evidence chain from high-density keyframe mosaics, at least 10-12 frames per 15 seconds and roughly one frame per second for fast-cut or transition-dense footage, never letting tile capacity fall below the real frame count. The report deep-dives character and subject, story and action, camera movement, lighting and style, and rhythm by default, and it separates reproducible facts from uncertainties and risks, naming faces, hands, multi-person identity, text, fast motion, and style drift explicitly. It then compiles a reproduction contract: groups are formed by continuity rather than a mechanical 15-second cut, each group stating its start state, continuous action, and handoff end state, with per-shot framing, camera position or viewing direction, one primary camera move, subject behavior, important background response, dialogue or synced sound, and end state. Every reference asset is annotated item by item for the identity, scene, style, action, or sound it locks, and a bare URL never becomes a promise to download an external video.

### ✨ What it does

- Pulls 10-12 keyframes per 15 seconds, up to about one frame per second for fast cuts, and labels screenshot guesses separately from frames actually read
- Deep-dives subject, story and action, camera movement, lighting and style, and edit rhythm by default, without empty words like cinematic or premium
- Groups reproduction by continuity instead of a mechanical 15-second cut, with start state, continuous action, and handoff end state per group
- Writes per shot: framing, camera position or viewing direction, one primary camera move, subject behavior, background response, dialogue or synced sound, and end state
- Annotates every image, video, and audio reference for the identity, scene, style, action, or sound it locks, preserving attachment order
- Model auto-optimization may only fill unspecified gaps; it may never alter subject, action, spatial relations, shot order, sound, or negative requirements

### 📦 Skills included

- `video-deconstruct` — [`video-deconstruct/SKILL.md`](video-deconstruct/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/video-deconstruct.git
cp -r video-deconstruct/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
