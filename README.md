# PHiLIP: Personalized Human in Loop Image Production

### Authors

Engineers:
Michael Chen,
Freddy Song,
Peter Lu

Advisors:
Xianghao Kong,
Ratnodeep Bandyopadhyay


Investing significant time into producing a single high-quality image using text-to-image generative AI risks not effectively meeting user requirements, leading to multiple generations and wasted computing resources.

An interface that uses an iterative methodology to generate various low-resolution images from text. Images that correspond with the user's vision are selected and iterated upon to create a single high-resolution image.

The current state-of-the-art focuses on improving single image generation performance. Our proposed idea would improve precision by intermittently receiving user feedback, utilizing compute resources more efficiently to better align with user expectations.

The proposed system allows users to input a text prompt, which an AI model uses to generate a collection of low-resolution images. Users can then interactively select images they prefer or dislike. Based on this feedback, the AI model identifies and enhances desired features in the images while deemphasizing less preferred elements. The process involves multiple rounds, with the number of iterations determined by the user's level of satisfaction with the images. In each successive round, the image quality improves, gradually converging towards a single, high-resolution image that closely aligns with the user's preferences. This approach offers a tailored and iterative experience, enabling users to refine their visual ideas through direct engagement with the AI's creative process.

The AMD Instinct MI210 or AMD Radeon Pro W7900 will be used for AI image generation through PyTorch 2.0 and Stable Diffusion (open to change).

### Hardware:
- AMD Instinct MI210 or AMD Radeon Pro W7900

### Software:
- PyTorch 2.0: Stable Diffusion
- AMD ROCm Software

### Framework:
- Next.js

### Deployment:
- Vercel

### Front-end:
- React

### Back-end:
- Flask
