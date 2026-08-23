<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 009 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 009

### 把照片压缩成极小锚点、巨大留白与由密到疏的网点空间诗

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种网点空间逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 极小主体 · 巨大留白 · 单一空间关系 · 专色体系 · Halftone 丝网印刷

XXD Panel 009 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它从照片里锁定主体、轮廓、姿态与叙事关系，把复杂信息压缩为一个极小却可一眼辨认的视觉锚点，再只选择一个方向和一个空间关系，让大面积纸张底色成为距离、空气、停顿与时间。

画面只使用纸张底色、主墨色和可选雾层色；所有雾气、远近、阴影、消散与过渡都由网点从密到疏完成，不使用数字模糊或普通渐变。纸纹、丝网油墨、轻微套印偏差与不均匀着墨保留真实版画感；文字沿地平线、轮廓、轴线、网点边界或负形进入构图。

## 为什么需要 009

普通“高级复古海报”很容易退化成模板：把主体缩小，套一层旧纸，再贴几个英文编号和普通渐变，就以为产生了诗意。

009 的顺序完全相反：

```text
锁定源图事实 → 压缩为一个唯一锚点 → 只选一个方向与一个空间关系 → 让纸张留白承担距离与时间 → 建立纸底／主墨／雾层专色 → 让所有过渡由网点密度完成 → 把文字嵌入空间结构
```

如果换成一张无关照片，锚点、方向、空间关系、网点路径、综合色温和文字仍然成立，这张图就不属于 009。

## 009 的视觉契约

- **一个极小锚点：** 至少三个源图专属线索保住身份、轮廓、姿态、动作与关系；极少信息仍可辨认。
- **一个方向：** 水平延展、纵向延伸、孤立悬置、向外消散或由浅入深只选其一。
- **一个空间关系：** 一条地平线、边界、阴影或网点带即可，绝不叠加多种构图技巧。
- **留白是主体：** 纸张底色占最大面积，承担距离、空气、停顿、时间或孤独。
- **2–3 种专色：** 纸底、一个安静有重量的主墨、可选的浅灰同系雾层；点色极小且必须有叙事理由。
- **网点承担过渡：** 雾、远近、阴影与消散全部由 halftone 从密到疏完成。
- **真实物理印刷：** 保留纸纹、油墨、轻微套印偏差与不均匀着墨，拒绝廉价脏污滤镜。
- **聪明的文字介入：** 极短标题与少量微字进入地平线、轮廓、轴线、网点边界或负形。

## 样张 · 即将补充

项目已预留 [`assets/examples/`](assets/examples/) 样张目录。只有经项目作者确认、确实使用 009 完成的作品才会加入；在此之前不借用其他风格的推文或图片作为占位。

未来样张只用于展示 009 对不同题材的适应力，不会把样张主体、隐喻、配色、文案或画幅变成生成参考或默认值。

## 四种输出共享同一种网点空间逻辑

四种模式支持单选或多选。可回复 `1`、`1+3`、`1、2、4` 或 `全部`；Skill 去重后按 1→4 执行。每种模式独立输出并进入独立子文件夹，不制作总图；`全部` 每张原图得到 7 个 PNG（前三种各 1 张＋壁纸 4 张）。尺寸可在同一回复中按模式标注，未标注普通模式按源图适配；文案默认跨所选模式共用，也可按模式单独指定。

| 模式 | 尺寸逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 | 上方完整原图，下方 009 极简网点空间版画；两块都保持原图完整尺寸，严格 50/50 |
| `left-right` | 源图自适应 | 左侧完整原图，右侧 009 极简网点空间版画；两块都保持原图完整尺寸，严格 50/50 |
| `design-only` | 源图自适应 | 只显示变化设计，不显示原照片；沿用原图比例和尺寸 |
| `wallpaper-pack` | 四种设备尺寸 | 分别输出手机、iPad、电脑、儿童手表四张 PNG |

用户精确尺寸 > 指定比例或用途 > 普通模式源图自适应。原始 `009.md` 里的 3:4 只是一开始的创作画幅，不会被写成当前 Skill 的静默默认值。

双联模式的摄影区域保持真实，只允许克制调色和必要的环境扩展。纯设计版与壁纸仍以照片为事实依据，但不显示原片。

### 四端壁纸：连贯或独立

壁纸没有静默尺寸默认。可选择常用预设——手机 `1440×3200`、iPad `2048×2732`、电脑 `3840×2160`、儿童手表 `1024×1024`——也可逐设备自定义。

- **连贯套装（推荐）：** 先生成并验收 iPad 定调图，另外三张都直接参考原照片＋同一张定调图，分别为设备重新构图。
- **四张独立：** 每张只参考原照片，可以分别探索不同的小锚点位置、单一方向、空间关系、专色组合、网点路径与文字介入。

连贯不等于裁切。四张壁纸始终分别生成、分别构图、分别验收，也不会按 iPad→手机→电脑→手表顺序垫图造成漂移。

## 文字必须成为空间与版画结构的一部分

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从照片可见或有依据的主题、情绪、时间、动作、材质、距离或隐喻中提炼一个极短标题。它可以抽象、文学、策展而含蓄，但必须与当前画面高度绑定。

按需增加零至三组微型副文、短句、章节号、编号、年份、坐标式数字或档案标记；但日期、坐标、地点、年份、编号与出处必须由用户提供或可靠确认，绝不会为了显得高级而伪造。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体会在当地文字系统中寻找克制无衬线、温和衬线或极简窄体的高级编辑等价物，不会把拉丁字距、纵排或小型大写规则生硬套过去。

## 精确拼版交给代码，作品交给图像生成

图像模型负责源图绑定的小锚点、单一方向与空间关系、巨大纸色留白、有限专色、网点密度过渡、物理丝网质感以及空间内文字。`scripts/compose_panel.py` 只负责画布规划、精确 50/50 位图拼合、最终尺寸和审计，不会用程序绘图伪造成品。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

精确上下画布的总高度必须为偶数，精确左右画布的总宽度必须为偶数。Skill 不会静默修改用户指定的像素。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-009.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-009" ~/.codex/skills/xxd-panel-009
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-009`。安装后重新启动 Agent 会话。

```text
$xxd-panel-009
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-009-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-009-prompt.en.md)
- [原始风格提示词](references/009-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-009/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-009-prompt.zh-CN.md
    ├── xxd-panel-009-prompt.en.md
    └── 009-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**把复杂留给照片，把距离、停顿与回声交给一个小锚点和整张纸。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
