# Prompt-Driven Image Analysis: Integrating Gen-AI for Segmentation, Object Transformation, and Cognitive Interpretation (FinalYearProject - Batch 2020 to 2024)

This project integrates generative AI models to enable complex image analysis tasks such as segmentation, object transformation, and cognitive image interpretation. By combining various AI models with NLP capabilities, it provides an intuitive, prompt-driven interface for users to analyze and transform images based on natural language instructions.

## Key Features

- **Natural Language Processing Interface**: Enables users to input commands in everyday language, making complex image processing tasks accessible.
- **Advanced Image Segmentation and Transformation**: The system can segment images into distinct components and apply transformations, such as style alteration and object replacement.
- **Cognitive Image Analysis**: Goes beyond editing by understanding image context, content, and semantics to provide in-depth visual analysis.

## Technology Stack

- **Gradio**: For user interface and demonstration.
- **GANs, PyTorch, and Transformers**: Backend frameworks for model implementations.
- **GroundingDINO**: Utilized for accurate visual grounding to identify and locate image elements based on textual descriptions.
- **Segment Anything (SAM)**: For precise segmentation tasks.
- **Stable Diffusion**: For image inpainting and artistic transformations.
- **LLaVA (Large Language-and-Vision Assistant)**: Provides cognitive interpretation of images based on prompts.

## Model Integrations

1. **GroundingDINO by IDEA-Research** - Enables text-based object detection and annotation.
2. **SAM (Segment Anything Model) by Meta** - For advanced segmentation.
3. **Stable Diffusion by StabilityAI** - Used for inpainting and creative modifications.
4. **LLaVA** - Enhances the interplay between language and visual content for detailed analysis.

## Usage - Demo

- **Upload Image**: Load an image to the platform.
- **Segment Objects**: Specify objects to be segmented based on textual descriptions.
- **Object Masking and Transformation**: Apply transformations or masks to selected objects.
- **LLaVA Integration**: Input prompts to receive a detailed, cognitive interpretation of the image.

## Project Structure

- `gradio_demo.ipynb`: Interactive Gradio interface for demonstration purposes.
- `main_code.ipynb`: Core code with model initialization, segmentation, and transformation functionalities.

## References

- [GroundingDINO Paper](https://arxiv.org/abs/2303.05499)
- [Segment Anything by META](https://arxiv.org/abs/2304.02643)
- [Stable Diffusion by StabilityAI](https://arxiv.org/abs/2112.10752)
- [LLaVA](https://arxiv.org/abs/2304.08485)

## License

This project is licensed under the MIT License.
