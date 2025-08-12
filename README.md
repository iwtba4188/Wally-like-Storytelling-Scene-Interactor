# Wally-like-Storytelling-Scene-Interactor

This repository contains a Wally-like Storytelling Scene Interactor, which is a tool designed to facilitate interactive storytelling experiences. The interactor allows users to engage with scenes in a dynamic way. Generating the scene through user textual imagination, then enhancing the narrative through user input and interaction with story elements through audio effects.

## Features

- Dynamic scene generation based on user imagination
- Interactive storytelling with user-generated scenes
- Audio effects to enhance the narrative

## Architecture

### Text-to-Prompt

![Text-to-Prompt](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/blob/main/assets/imgs/1_text-to-prompt.png)

This initial stage allows users to provide a high-level narrative or scene description. An intelligent model then processes this input to generate precise, detailed prompts optimized for Text-to-Image (T2I) models, ensuring that the generated image accurately reflects the user's vision.

### Text-to-Image

![Text-to-Image](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/blob/main/assets/imgs/2_text-to-image.png)

Leveraging the refined prompts, a state-of-the-art T2I model generates the core visual scenes. This step transforms textual descriptions into rich, vivid images, forming the foundation of the user's interactive storybook world.

### Image Mask to Text Description

Once the image is generated, users can interact with it by selecting specific regions or objects using an intuitive masking tool. A sophisticated model then analyzes these masked areas and provides detailed textual descriptions of the visual content within them.

![Image Mask to Text Description](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/blob/main/assets/imgs/3_image-mask-to-text-description.png)

### Text Description to Sound Effect

The textual descriptions obtained from the masked image regions are further processed. Another AI model converts these visual descriptions into corresponding sound effect prompts. These prompts are then fed into a Text-to-Audio model, which generates realistic sound effects for the selected objects or areas, enhancing the immersion.

![Text Description to Sound Effect](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/blob/main/assets/imgs/4_text-description-to-sound-effect.png)

## More Information

For more details on the design process, implementation and usage of the Wally-like Storytelling Scene Interactor, please refer to the:

1. [Proposal](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/tree/main/assets/docs/1_Final_Project_Proposal_110020007.pdf)
2. [Progress Report](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/tree/main/assets/docs/2_Progress_Report_110020007.pdf)
3. [Final Report](https://github.com/iwtba4188/Wally-like-Storytelling-Scene-Interactor/tree/main/assets/docs/3_Final_Report_110020007.pdf)
