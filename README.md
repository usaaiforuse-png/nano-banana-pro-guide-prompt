# 🎨 Nano Banana Pro: AI Image Generation Guide / 生图实战指南

Welcome! This repository documents my exploration of AI image generation using **Nano Banana Pro**. I have summarized my personal workflow, common settings, and some curated prompts, hoping to provide inspiration for fellow enthusiasts.

欢迎！这里记录了我使用 **Nano Banana Pro** 进行 AI 图像生成的探索过程。我汇总了个人的工作流、常用设置以及一些满意的提示词（Prompts），希望能给同样爱好的你一些灵感。

---

## ✨ Gallery / 精选作品展示

*(Place your best 2-3 images here. Upload them to the repo first, then reference them.)*
*(建议：在这里放 2-3 张你觉得最满意的代表作。你需要先把图片上传到仓库里，然后用 markdown 语法引用它。)*

![Sample Image 1](images/sample1.jpg)
*Caption: A brief description of the style. / 图注：简短描述这张图的风格*

---

## 🛠️ Workflow & Settings / 核心工作流与设置

Here are the basic settings I use with Nano Banana Pro. I find these parameters deliver the most stable results.
这里分享我通常使用 Nano Banana Pro 的基础设置，这些设置是我认为出图比较稳定的。

### Basic Parameters / 基础参数建议

* **Model (Checkpoint) / 模型:** `[e.g., ChilloutMix_Ni, or your favorite model]`
* **Sampler / 采样方法:** `[e.g., DPM++ 2M Karras]`
* **Steps / 迭代步数:** `[e.g., 20 - 30]`
* **CFG Scale / 提示词相关性:** `[e.g., 7.0]`
* **Resolution / 分辨率:** `[e.g., 512x768 (Portrait/竖图)]`
* **VAE:** `[e.g., vae-ft-mse-840000]`

### Tips & Tricks / 经验之谈

1.  **About Features / 关于功能:**
    * *EN:* I found that the `[Feature Name]` is very useful for...
    * *CN:* 我发现 `[某功能]` 特别好用，可以用来...
2.  **Fixing Hands / 手部修复:**
    * *EN:* To avoid bad anatomy on hands, I usually use specific negative prompts like...
    * *CN:* 为了避免手指崩坏，我通常会使用特定的负面提示词...
3.  **Hires. Fix / 高清修复:**
    * *EN:* I recommend enabling Hires. Fix with a denoising strength of `0.4`.
    * *CN:* 建议开启高清修复，重绘幅度设置在 `0.4` 左右效果比较自然。

---

## 📝 Prompts Collection / 提示词分享

Here is a collection of prompts for the styles I frequently use.
这里是我整理的一些常用风格的提示词。

### Style 1: [e.g., Anime Pastel] / 风格一：[例如：二次元清新风格]

**Preview / 效果图:**
![Style Preview](images/style1_preview.jpg)

**Positive Prompt / 正面提示词:**

```text
(masterpiece:1.2), best quality, highres,
[Subject Description, e.g., 1girl, solo, white dress, smiling],
[Background, e.g., standing in a field of flowers, sunny day, blue sky],
[Art Style, e.g., anime style, soft lighting, gentle breeze],
<lora:Your_Lora_Name:0.8>
