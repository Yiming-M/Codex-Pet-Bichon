
# Bichon / 熊熊 Codex Pet

[English](README.md)

Bichon 是一个自定义 Codex pet，中文显示名保持为「熊熊」。它基于熊熊本狗的照片制作：一只白色小比熊，有圆圆蓬松的脑袋、黑亮的眼睛、黑色小鼻子、垂耳和好奇温柔的表情。

这个仓库包含可直接安装的 Codex pet 包，以及用于预览和检查动画效果的素材。

## 效果预览

原始参考图：

![熊熊参考图](assets/references/xiongxiong-reference.png)

生成后的 Codex pet contact sheet：

![Bichon contact sheet](assets/contact-sheet.png)

动画预览：

| Idle | Running Right | Waving | Jumping |
| --- | --- | --- | --- |
| ![Idle preview](assets/previews/idle.gif) | ![Running right preview](assets/previews/running-right.gif) | ![Waving preview](assets/previews/waving.gif) | ![Jumping preview](assets/previews/jumping.gif) |

## 安装方式

把 `bichon` 文件夹复制到 Codex 的 pets 目录：

```bash
mkdir -p ~/.codex/pets
cp -R bichon ~/.codex/pets/
```

然后重启 Codex，在宠物列表里选择显示名为「熊熊」的 pet。

## 包内容

```text
bichon/
  pet.json
  spritesheet.webp
```

内部 pet id 是 `bichon`，Codex 中显示名是「熊熊」。

## 验证信息

生成的 spritesheet 已通过验证：

- 格式：带 alpha 的 WebP
- 尺寸：`1536x1872`
- 单格尺寸：`192x208`
- 行数：9 个 Codex pet 动画状态
- 透明像素 RGB 残留：`0`
- 帧检查：无 errors / warnings

## 来源

基于熊熊的个人照片，使用 Codex hatch-pet 工作流生成。
