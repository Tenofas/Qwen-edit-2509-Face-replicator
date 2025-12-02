This is a quick workflow I was already working on last summer. I decided to complete it as it was almost ready. And to make it cleaner, I used subgraphs (although I am not a big fan of them).
The workflow is self-explaining. You will have all the links to the model files in the workflow.

Just load the portrait you want to replicate, and modify (if you want, and the way you like) the 6 positive prompts. Do not use negative prompts, they are useless in the workflow.

Try to use the best quality photograph you can for the loaded portrait, and try to load an image with a resolution larger than 1024x1024. The workflow will resize it.

You may use the output images for training a LoRA, just generate as many different poses and expressions as you may need for training.

You can also use the workflow to create consistent images, the only limit is your imagination (as KelevraQuakenstein pointed out in the comments, thanks mate!).

This workflow was tested on a Rtx 5090 GPU, if you have a smaller GPU and have out-of-memory issues, you can try to use the FP8 model for Qwen Edit 2509 model and the text encoder:

Qwen Edit models: https://huggingface.co/Comfy-Org/Qwen-Image-Edit_ComfyUI/tree/main/split_files/diffusion_models

Qwen text encoders: https://huggingface.co/Comfy-Org/Qwen-Image_ComfyUI/tree/main/split_files/text_encoders

If these are still too big, you may need to try the quantized GGUF models.
