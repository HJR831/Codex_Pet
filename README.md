# Codex Pet

这里收录三个适用于 Codex 桌面宠物的自定义动态宠物：邦布小光、奶龙之神和五条悟。每个宠物目录都提供 `pet.json` 与透明背景的 `spritesheet.webp`，可单独安装。

## 宠物列表

| 宠物 | 简介 | 目录 |
| --- | --- | --- |
| [邦布小光](bangbu-xiaoguang/README.md) | 黄身黑发的可爱邦布，可变身为白发持剑形态 | `bangbu-xiaoguang/` |
| [奶龙之神](nailong-god/README.md) | 戴着金色光环、圆滚滚的奶龙 | `nailong-god/` |
| [五条悟](gojo/README.md) | 白发、黑色眼罩与深色制服的咒术师 | `gojo/` |

## 下载与安装

1. 在本仓库页面选择 **Code → Download ZIP**，下载并解压。
2. 将要使用的宠物文件夹（例如 `bangbu-xiaoguang`）复制到个人宠物目录：

   - Windows：`%USERPROFILE%\.codex\pets\<宠物目录名>`
   - macOS / Linux：`~/.codex/pets/<宠物目录名>`

   如果设置了 `CODEX_HOME`，请改用该目录下的 `pets/<宠物目录名>`。
3. 确认 `pet.json` 和 `spritesheet.webp` 位于该宠物文件夹的同一层。
4. 打开 Codex 桌面应用的 **Settings → Pets**，点 **Refresh**，然后选择刚安装的宠物。可输入 `/pet` 或使用 **Show pet** 显示宠物。

可按同样步骤安装多个宠物，每个宠物保留独立文件夹。桌宠动画会遵循操作系统的“减少动态效果”设置；开启后会显示静帧。不同界面可用的宠物功能有所不同，详情见 [OpenAI Pets 使用说明](https://learn.chatgpt.com/docs/pets)。

## 格式

每个宠物使用 Codex v2 动态图集：`pet.json` 声明 `spriteVersionNumber: 2`，透明 WebP 图集为 8 列 × 11 行，每格 192 × 208 像素。图集包含标准动作和视线方向帧。

## 版权、许可与来源

本仓库没有为整套宠物素材授予 MIT、Creative Commons 等通用开源或商业许可。公开仓库用于个人体验与展示，不代表本仓库拥有或转让任何第三方角色、作品、商标及用户提供参考图的权利；商业使用、改作发布或再次分发前，请先取得相应权利人的许可。请勿将这些宠物表述为官方作品或官方授权内容。

邦布小光的视觉依据来自用户提供的六张参考图与文字设定；奶龙之神依据用户提供的角色参考和设计方向制作；五条悟为基于《咒术回战》角色形象制作的非官方桌宠。角色名称、原作及相关素材的权利归各自权利人所有。宠物目录中的介绍分别列出角色外观与动作设定。
