# NEURAL-STYLE-TRANSFER

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Mirza Muqaraab Ali Baig

**INTERN ID**: CT06DY2291

**DOMAIN**: Artificial Intelligence

**DURATION**: 6 WEEKS

**MENTOR**: NEELA SANTHOSH

# DESCRIPTION
This task explores the fascinating intersection of art and artificial intelligence through neural style transfer — a deep learning technique that blends the content of one image with the artistic style of another. The result is a beautifully transformed picture that combines the subject of the original image with the colors, textures, and brushstrokes of a chosen artwork. This project showcases how technology can mimic human creativity, turning ordinary photos into artistic masterpieces.

At the core of this project lies a pre-trained model from TensorFlow Hub, developed by Google’s Magenta team:
arbitrary-image-stylization-v1-256/2.
This model has been trained on a vast dataset of artwork and natural images, allowing it to capture both artistic patterns and structural integrity. It uses convolutional neural networks (CNNs) to understand and reproduce stylistic features from paintings such as strokes, textures, and color gradients, while preserving the underlying shapes and layout of the original photo.

The process begins by loading two input images — a content image and a style image. The content image provides the base subject (for example, a portrait, landscape, or building), while the style image defines the artistic mood (such as the brushwork of Van Gogh or the soft hues of Monet). Both images are read using OpenCV (cv2), converted from BGR to RGB format for accurate color representation, and normalized by scaling pixel values between 0 and 1. This preprocessing ensures compatibility with TensorFlow models and maintains image quality.

Each image is then converted into a TensorFlow tensor and expanded into the proper dimensions expected by the model. The Magenta model takes these two inputs and applies the learned transformation to merge them into a single stylized output. Essentially, it transfers the artistic “style” features from the painting onto the “content” structure of the photo, achieving a harmonious fusion of both.

After processing, the stylized image is displayed using Matplotlib, alongside the original and style reference images for visual comparison. The final output often resembles a painting created by an artist who reimagined the photo through a specific aesthetic lens. The model runs efficiently and produces high-quality results even without retraining, thanks to TensorFlow Hub’s pre-optimized architecture.

This project is not only technically impressive but also creatively inspiring. It demonstrates how artificial intelligence can contribute to digital art, design, and media creation. Artists can use it to experiment with new visual expressions, photographers can apply painterly effects to their work, and educators can use it to teach the principles of machine learning and image processing in an engaging way.

In a broader sense, this task emphasizes how AI is becoming a creative collaborator rather than just a computational tool. By blending artistic intuition with algorithmic precision, it reflects humanity’s timeless desire to merge art and science. What once required a painter’s brush and months of effort can now be achieved in seconds — proof that technology, when guided thoughtfully, can amplify creativity rather than replace it.
# OUTPUT
## Context Image
<img width="300" height="800" alt="Image" src="https://github.com/user-attachments/assets/995c2747-f7e5-48ba-8289-18193003c6cd" />

## Style Image
<img width="300" height="800" alt="Image" src="https://github.com/user-attachments/assets/6b9c7c2f-9ff3-42f7-aa4d-67572d170e76" />

## Styled Image
<img width="300" height="800" alt="Image" src="https://github.com/user-attachments/assets/8408c1b8-952b-42c1-ad50-9b0067bd3c13" />
