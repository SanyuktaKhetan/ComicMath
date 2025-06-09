# ComicMath – AI-Powered Comic Generation for Teaching Mathematics

ComicMath is an innovative AI-powered educational tool designed to teach Grade 9 Mathematics using engaging, Marvel-themed comic narratives. By combining natural language processing, generative AI, computer vision, and speech synthesis, ComicMath transforms abstract mathematical concepts into interactive, visual, and auditory learning experiences.

## 📌 Project Highlights

- Converts math topics into comic scripts using the **Mistral Large Language Model API**
- Generates stylized comic panels from text using **Stable Diffusion**
- Maps dialogues to characters in each panel using **face detection** techniques
- Stores and handles dialogues in structured **JSON** format
- Enables interactive **Text-to-Speech (TTS)** playback for each comic panel
- Offers a multimodal AI experience using **NLP**, **CV**, and **generative modeling**

## 🧠 Technologies Used

- **Python**
- **Mistral LLM API** – for narrative/script generation
- **Stable Diffusion** – for generating comic visuals
- **OpenCV** – for face detection and image mapping
- **JSON** – for dialogue storage and manipulation
- **Text-to-Speech (TTS)** – for interactive audio playback
- **NLP & Computer Vision (CV)** techniques

## 📂 Repository Structure
├── ComicMath_–_AI_Powered_Comic_Generation_for_Teaching_Mathematics.ipynb
├── images/
│ └── generated_comic_panels/
├── data/
│ └── math_topics.json
│ └── dialogues.json
├── models/
│ └── stable_diffusion_model/
├── README.md
└── requirements.txt



## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python ≥ 3.8
- Jupyter Notebook
- Git
- CUDA-compatible GPU (for image generation)
- Mistral API access
- Stable Diffusion environment

