# llm_agents_lab

A Dev Container+ Docker Compose setup to easily run a [crewai](https://docs.crewai.com/en/introduction) using [llama.cpp](https://github.com/ggml-org/llama.cpp) server, all of this locally.

## Prerequisites: 
- Docker + Docker Compose
- [VS Code remote containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension
- A LLM model in `.gguf` format (can be found on [Hugging Face](https://huggingface.co/models?library=gguf&sort=trending))

## Quickstart

1. Clone the repo

2. Create a copy of `.env.example` and rename it `.env`, then add the values :
    - `LOCAL_MODELS_DIRECTORY_PATH`: path of the folder where LLM models are stored
    - `LLM_MODEL_GGUF_FILE_NAME`: name of the `.gguf` model file