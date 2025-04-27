# Image Processing Flow

## Introduction
This project implements an automated flow to:
1. Generate "image prompts."
2. Create images based on the prompts.
3. Use the Facebook API to upload images to a Facebook page.

## Processing Flow

### 1. Generating Image Prompts
- Image prompts are created based on user inputs or automatically generated using algorithms.
- Elements such as themes, colors, and art styles can be customized.

### 2. Image Generation
- Leverages AI tools or models (e.g., Stable Diffusion) to create images from the prompts.
- Ensures images meet requirements for resolution, quality, and style.

### 3. Uploading to Facebook
- Utilizes Facebook Graph API to upload the generated images.
- Requires API access through an OAuth token.
- Steps involved:
  - Authenticate and obtain permissions.
  - Upload the image to Facebook via the `/PAGE_ID/photos` endpoint.
  - In this case, the page ID is: `61575683403452`.

### Facebook Page Link
- The associated Facebook page: [Facebook Page](https://www.facebook.com/profile.php?id=61575683403452).

