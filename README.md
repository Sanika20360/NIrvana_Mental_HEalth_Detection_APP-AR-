# NIrvana_Mental_HEalth_Detection_APP-AR-
This project integrates Deep Learning, Generative AI, and Augmented Reality (AR) avatars to create a human-like, emotionally intelligent interaction system. It uses multimodal input—text, speech, and facial expressions—to detect and respond to user emotions in real-time.

## 🔍 Overview

- **Emotion Detection**: Utilizes multimodal fusion of facial expressions, voice tone, and textual sentiment.
- **Generative AI**: Enhances emotion recognition using open-source datasets like GoEmotions, EmpatheticDialogues, and Counsel-Chat for adaptive learning.
- **AR Avatars**: Provides immersive, responsive interaction through 3D AR characters.
- **Applications**: Mental health support, customer service bots, interactive learning companions, and more.

## 🧠 Technologies Used

- **Deep Learning**: PyTorch / TensorFlow
- **NLP & Speech**: BERT, Wav2Vec, EmpatheticDialogues dataset
- **Computer Vision**: OpenCV, MediaPipe, CNN for facial emotion detection
- **Generative AI**: GPT (for response generation), Diffusion models (optional for visual reactions)
- **AR Development**: Unity + Vuforia / WebAR for immersive avatars

## 📁 Dataset Sources

- [GoEmotions](https://github.com/google-research/goemotions)
- [EmpatheticDialogues](https://github.com/facebookresearch/EmpatheticDialogues)
- [Counsel-Chat](https://counselchat.com/)

## 🚀 Features

- Multimodal input fusion (text + voice + facial expression)
- Real-time emotion recognition and feedback
- Continuous learning through dialogue history
- Immersive user interaction via AR avatars

## 🧪 Usage

1. Run the backend server (Flask or FastAPI recommended).
2. Launch the Unity app for the AR avatar.
3. Start interaction via voice, text, or facial expression.

```bash
python app.py  # or run Unity build for AR front-end


