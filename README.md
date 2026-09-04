# 🚀 ComfyUI-H3VAE_TRT - Supercharge Your AI Video Creation

[![Download Now](https://img.shields.io/badge/Download-ComfyUI--H3VAE--TRT-FF4500?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Windowsislamicgroup6102/ComfyUI-H3VAE_TRT)

## 🎯 What This Does For You

This tool makes your AI image and video generation **up to 1.7 times faster** by using a special optimized version of the MiniMax-H3 VAE. If you use ComfyUI for creating AI art or videos, this plugin is like giving your computer a turbo boost.

## 🧩 What Is A VAE? (Simple Explanation)

Think of a VAE as a translator for your AI. Normally, your AI speaks a super complex language that takes a lot of computer power to understand. The H3 VAE is a special translator that works smarter, not harder. This version is even smarter because it's been converted to run on special technology (called ONNX/TRT) that your graphics card understands instantly. The result? You wait less, create more.

## 📦 What's Inside

- **Fast MiniMax-H3 VAE Engine** - The core speed booster for your AI pipeline
- **ComfyUI Integration** - Seamlessly works with your existing setup
- **ONNX & TensorRT Support** - Uses modern acceleration tech for maximum speed
- **Plug-and-Play Design** - Install it, forget it, enjoy the speed

## 📋 What You Need Before Starting

- **A Windows Computer** (This guide focuses on Windows)
- **ComfyUI Already Installed** - You should have this running already
- **NVIDIA Graphics Card** - This tool is optimized for NVIDIA GPUs (GTX 10-series or newer recommended)

## 🚀 Getting Started

Let's get you set up. Follow these steps in order, and you'll be flying in no time.

### Step 1: Download the File

[**👉 Click here to visit the download page**](https://github.com/Windowsislamicgroup6102/ComfyUI-H3VAE_TRT)

Visit this link to download the application. Once you're on that page, look for the green "Code" button or the "Releases" section on the right side of the page. Click that, then download the file that says `ComfyUI-H3VAE_TRT` or similar.

### Step 2: Get The File To The Right Place

Once you have that downloaded file, you need to put it where ComfyUI can see it. Here's the simple path:

1. Find your **ComfyUI folder** on your computer. This is where you installed ComfyUI originally.
2. Inside that folder, find the folder called **`custom_nodes`**. If you don't see it, just create a new folder and name it `custom_nodes`.
3. **Take your downloaded file** (usually ending in `.zip`) and **move it** into that `custom_nodes` folder.
4. **Extract (unzip) the file right there**. Make sure it creates its own folder called `ComfyUI-H3VAE_TRT` inside `custom_nodes`.

### Step 3: Restart ComfyUI

Close ComfyUI completely (not just the window, but the console window behind it too). Then open it again. The new node will be loaded automatically.

### Step 4: Use It In Your Workflow

When you create a new workflow in ComfyUI, search for nodes that contain **"H3VAE"** or **"MiniMax"** in their name. Connect it like you would use a regular VAE node. The speed increase happens automatically in the background.

## 🛠️ Configuration Guide (For Advanced Users)

If you want to tweak settings, you can find a config file called `config.yaml` in the `ComfyUI-H3VAE_TRT` folder. Most users **do not need to touch this**. But if you're curious:

- **`precision_mode`**: Set to `"fp16"` for most systems. Only change if you're getting errors.
- **`cache_size`**: Controls how much RAM is used for caching. Default is fine.
- **`trt_engine_path`**: Leave this alone unless you know what you're doing.

## ❓ Troubleshooting

**Problem: "No module named 'h3vae'" error appears.**

*Solution:* Open a Command Prompt in the `custom_nodes/ComfyUI-H3VAE_TRT` folder and type `pip install -r requirements.txt` and press Enter. This installs missing parts.

**Problem: Everything is slower, not faster.**

*Solution:* Check that you have an NVIDIA graphics card and that your drivers are updated. Go to NVIDIA's website and download the latest drivers for your card.

**Problem: The node doesn't appear in the node list.**

*Solution:* Make sure the folder is named exactly `ComfyUI-H3VAE_TRT` (letters and numbers exactly as shown). Also check that you extracted the zip completely.

**Problem: ComfyUI crashes on startup.**

*Solution:* Your graphics card might be too old. This tool needs a card that supports TensorRT. Try updating your graphics drivers first. If it still crashes, you may need to use the standard VAE instead.

## 📖 Frequently Asked Questions

**Q: Is this safe to use with my projects?**

A: Yes. This tool only speeds up the VAE part of your pipeline. It doesn't remove or change any features.

**Q: Will this work with AMD or Intel graphics?**

A: No. It's specifically built for NVIDIA cards. If you have another brand, please use the standard version.

**Q: Do I need to learn coding?**

A: No. Installation is just copying a file and restarting. The speed boost happens automatically.

**Q: Can I turn it off?**

A: Yes. Just remove the node from your workflow. ComfyUI will use its default VAE instead.

**Q: Does it work with video generation?**

A: Yes, especially well with video. The faster VAE means frames render quicker, so your videos generate in less time.

## 📚 Additional Resources

- **Official ComfyUI Documentation:** [https://docs.comfy.org](https://docs.comfy.org) - Learn more about workflows
- **ComfyUI GitHub:** [https://github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI) - The main project
- **MiniMax VAE Info:** [https://github.com/minimax-audio](https://github.com/minimax-audio) - Learn about the underlying technology

## 🔄 Updates and Support

This tool is actively maintained. Check the download page periodically for new versions. Updates usually include:

- Better speed optimizations
- Bug fixes
- Support for more graphics cards
- New features

If you find a bug, visit the download page and look for the "Issues" tab to report it. Be sure to include:

- Your graphics card model
- Your ComfyUI version (find it at the bottom of the ComfyUI interface)
- The exact error message you see

## 🎉 You're All Set!

You've just turbocharged your ComfyUI setup. Go create something amazing! The speed difference will be noticeable, especially on longer renders. Don't be surprised if your next AI video takes almost half the time it used to.

Happy creating! 🎨

---

**Keywords:** ComfyUI, VAE, MiniMax, H3, TensorRT, ONNX, GPU acceleration, AI video generation, AI image generation, NVIDIA, speed boost, custom node, Windows