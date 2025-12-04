# Qwen Edit 2509 Face Replicator WF - ComfyUI Workflow

![Preview](assets/preview.png)

## 📖 Description

This is a quick workflow I was already working on last summer. I decided to complete it as it was almost ready. And to make it cleaner, I used subgraphs (although I am not a big fan of them).
The workflow is self-explaining. You will have all the links to the model files in the workflow.
Just load the portrait you want to replicate, and modify (if you want, and the way you like) the 6 positive prompts. Do not use negative prompts, they are useless in the workflow.
Try to use the best quality photograph you can for the loaded portrait, and try to load an image with a resolution larger than 1024x1024. The workflow will resize it.
You may use the output images for training a LoRA, just generate as many different poses and expressions as you may need for training.
You can also use the workflow to create consistent images, the only limit is your imagination.

## ✨ Features

- [Feature 1]
- [Feature 2]
- [Feature 3]
- [Feature 4]
- Modular and customizable structure
- Production-ready outputs

## 🖼️ Examples

| Input/Prompt | Output |
|--------------|--------|
| ![Example 1](assets/example1.png) | ![Result 1](assets/result1.png) |
| ![Example 2](assets/example2.png) | ![Result 2](assets/result2.png) |

## 📋 Requirements

### Models Required
- **Main Model**: [Nome modello] - [Link download Civitai/Hugging Face]
- **VAE**: [Nome VAE] - [Link]
- **Upscaler**: [Nome upscaler] - [Link]
- *Optional*: [Altri modelli opzionali]

### Custom Nodes
- [Custom Node 1] - [Link al repo GitHub]
- [Custom Node 2] - [Link]
- [Custom Node 3] - [Link]

### System Requirements
- **VRAM**: Minimum [X]GB recommended
- **ComfyUI**: Latest version recommended
- **Python**: 3.10+

## 🚀 Installation

1. **Download the workflow**
```bash
   git clone https://github.com/Tenofas/[REPO-NAME].git
```
   Or download the `.json` file directly from [Releases](../../releases)

2. **Install required custom nodes**
   - Open ComfyUI Manager
   - Search and install the custom nodes listed above
   - Restart ComfyUI

3. **Download required models**
   - Download models from links in Requirements section
   - Place in appropriate ComfyUI folders:
     - Main models: `ComfyUI/models/checkpoints/`
     - VAE: `ComfyUI/models/vae/`
     - Upscalers: `ComfyUI/models/upscale_models/`

4. **Load the workflow**
   - Open ComfyUI
   - Drag and drop the `.json` file into the interface
   - Or use "Load" button and select the workflow file

## 💡 Usage

1. **[Step 1]** - [Descrizione]
2. **[Step 2]** - [Descrizione]
3. **[Step 3]** - [Descrizione]
4. Click "Queue Prompt" to generate

### Recommended Settings
- **Steps**: [X]
- **CFG Scale**: [X]
- **Sampler**: [Nome sampler]
- **Scheduler**: [Nome scheduler]

## 🎨 Workflow Structure
```
[Breve descrizione della pipeline]

Input → Base Generation → Upscaling → Face Enhancement → Post-Processing → Output
```

![Workflow Screenshot](assets/workflow_screenshot.png)

## 🔧 Customization

### Adjustable Parameters
- **[Parametro 1]**: [Cosa fa e come modificarlo]
- **[Parametro 2]**: [Cosa fa e come modificarlo]
- **[Parametro 3]**: [Cosa fa e come modificarlo]

### Tips for Best Results
- [Tip 1]
- [Tip 2]
- [Tip 3]

## 🐛 Troubleshooting

**Problem: [Problema comune]**
- Solution: [Soluzione]

**Problem: [Altro problema]**
- Solution: [Soluzione]

**Problem: Out of memory errors**
- Solution: Reduce batch size or image resolution

## 📝 Changelog

### Version [X.X] - [Date]
- [Change 1]
- [Change 2]

### Version [X.X] - [Date]
- Initial release

## 📄 License

This workflow is released under the [MIT License](LICENSE).

Free to use, modify, and distribute. Attribution appreciated but not required.

## 🤝 Support

- **Issues**: Open an issue on this repository
- **X (Twitter)**: [@tenofaz](https://x.com/tenofaz)
- **Website**: [tenofas.ai](https://tenofas.ai)

## ⭐ Credits

Workflow developed by **Tenofas**

If you find this workflow useful, consider:
- ⭐ Starring this repository
- 🔄 Sharing with the community
- 🐦 Following on [X](https://x.com/tenofaz)

---

*Part of the [Tenofas ComfyUI Workflows](https://github.com/Tenofas) collection*
