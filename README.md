# LLMTwins
LLMTwins is an innovative framework designed to streamline the development and deployment of digital twins powered by Large Language Models (LLMs). This cutting-edge tool provides developers with a comprehensive environment to create, train, and deploy AI-driven digital twins that can simulate and predict real-world behaviors and interactions. By leveraging the advanced capabilities of LLMs, LLMTwins enables highly accurate modeling of complex systems, offering insights and foresight into various scenarios across industries such as manufacturing, healthcare, urban planning, and beyond.

## Key Features
- **Seamless Integration with LLMs**: LLMTwins is built to work effortlessly with state-of-the-art language models, including GPT-3, BERT, and other transformers, enabling rich, contextual understanding and generation of human-like text.
- **Customizable Digital Twin Creation**: Users can tailor their digital twins to specific needs, integrating real-time data feeds and custom AI logic to accurately reflect the dynamics of the system being modeled.
- **Scalable Deployment**: Designed for scalability, LLMTwins supports deployment across various platforms, ensuring that your digital twins can grow with your project's needs.
- **Intuitive Development Environment**: With its user-friendly interface, LLMTwins simplifies the process of developing and managing digital twins, making it accessible to both technical and non-technical users.

Whether you're looking to enhance operational efficiency, optimize product development, or create immersive simulation experiences, LLMTwins provides the tools and flexibility needed to harness the power of LLMs for digital twin technology. Start building smarter, more responsive digital twins with LLMTwins today.

## Environment

#### Environment Variables:
- CREDENTIALS_FILE: Google service account private key JSON
- GDRIVE_LLM_ROOT_PATH: LLM root path on Google Drive
- GSHEET_FOR_TEMPLATE_OF_LLM_PROFILE: Template ID for Google sheet
- OPENAI_API_KEY (Optional): OpenAI API Key

#### How to resister environment content:
- [Hown to resister environment content](https://towningtek.github.io/LLMTwins/)

## Installation
```bash=
pip3 install -r requirements.txt
```

## Run
```bash=
source env/bin/activate
uvicorn server:app --host 0.0.0.0 --port 8000 --reload
```

## Procedure

#### Google Sheet:
- TODO

#### LLM Profile:
- TODO

#### Callback APIs:
- Path
  - callbacks/
- Prototype
```python=
Object foo(Object)
```

## Demo

#### API test:
- [Demo APIs on Youtube (Teacher yillkid)](https://youtu.be/VLM60VusPl4)
- [Demo LLMTwins & e2live on Youtube](https://youtu.be/83tZ6raLsSw)

#### LLM Profile:
- [Profile on GoogleSheet (Template)](https://docs.google.com/spreadsheets/d/1sIHUNWrziA82znQW9X6zuI9F163pS_XmqzejPyY-gg8/edit?usp=sharing)
- [Profile on GoogleSheet](https://docs.google.com/spreadsheets/d/10QVQ7MH9GKMDQv6dEr_6qGA3LHYLyXOgWTvM6GKzuK4/edit?usp=sharing)

#### 2025/06/29 Readme Update
* Project Overview  
  This project is developed based on the LLMTwins architecture. It enables controlling IoT devices through fuzzy semantic commands directed at ChatGPT-4o (the original project used GPT-3 as the model). By incorporating RAG and AI Agents, the system allows for more convenient and modular content management.
* [Docker HUB](https://hub.docker.com/r/mason45ok/llmtwins/tags)
* [LLMTwins](https://hub.docker.com/r/mason45ok/llmtwins)
* [Line Webhook](https://hub.docker.com/r/mason45ok/llmtwins-line)

## ICASI
* The project was also submitted to the 2025 ICASI and was presented on April 23, 2025, at the Tokyo Conference Center.
* [ICASI Video](https://youtu.be/vRFYBvC7cpA)
