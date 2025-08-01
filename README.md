# Text-to-Image Generation with Stable Diffusion and Diffusers

This project demonstrates how to generate images from text prompts using advanced AI models from Hugging Face, focusing on Stable Diffusion. The notebook guides you through setup, model loading, prompt engineering, and parameter tuning for creative image generation.

### https://chat.qwen.ai/s/deploy/dac3cc01-ddd2-4314-ab9a-997e077af25f
### https://mk-knight23.github.io/HuggingFace-Google-Collab
## Features
- Generate images from custom text prompts
- Experiment with different Stable Diffusion models
- Adjust parameters like inference steps, image size, and negative prompts
- Visualize results directly in the notebook

## Technologies Used
- [Hugging Face Diffusers](https://github.com/huggingface/diffusers)
- [Transformers](https://github.com/huggingface/transformers)
- [Accelerate](https://github.com/huggingface/accelerate)
- [PyTorch](https://pytorch.org/)
- [Matplotlib](https://matplotlib.org/)

## Getting Started
1. **Install dependencies** (in the notebook):
   ```python
   !pip install diffusers transformers accelerate
   ```
2. **Run the notebook cells** step by step to:
   - Import libraries
   - Load a Stable Diffusion model
   - Enter your own creative prompts
   - Visualize generated images
   - Experiment with parameters for different results

## Example Prompts
- "A grungy woman with rainbow hair, travelling between dimensions, dynamic pose, happy, soft eyes and narrow chin."
- "A girl is sitting on a chair & she is accompanied by her tiger. Make sure to keep it cinematic and color to be golden iris."

## Customization
- Change the model by editing the `model_id` variable.
- Adjust parameters like `num_inference_steps`, `height`, `width`, `num_images_per_prompt`, and `negative_prompt` for more control.

## Why Use This Notebook?
- **Easy to use**: No deep ML knowledge required.
- **Highly customizable**: Tweak prompts and parameters for unique results.
- **Immediate feedback**: See your generated images instantly.

## License
This project is for educational and research purposes. Please check the licenses of the models you use from Hugging Face.

---

*For a detailed step-by-step explanation, see `text_to_image_notebook_summary.md`.*
