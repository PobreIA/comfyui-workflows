# 🚀 ComfyUI Workflows — PobreIA

Bienvenido al repositorio oficial de workflows de **ComfyUI** del canal **[PobreIA](https://www.youtube.com/@PobreIA)**. 

Actualmente te comparto Flujos de Trabajo para ComfyUI altamente optimizados para GPUs de 4GB, 6GB y 8GB de VRAM, especializados en:
- Generación y Edición: Flux 2 Klein 4B y Z-Image Turbo (GGUF).
- Control y Guiado: ControlNet Union 2.1 y LoRAs de reemplazo facial (BFS).
- IA Local y Prompts: Integración directa con Ollama y Qwen 3.

---

## 📂 Lista de Workflows Disponibles

| Workflow | Descripción | Requisitos VRAM | Tutorial / Guía |
| :--- | :--- | :--- | :--- |
| **Flux 2 Klein 4B GGUF Headswap** | Head Swap/Rostros usando LoRA Best-Face-Swap | 4GB - 8GB | [📖 Video YT](https://www.youtube.com/watch?v=OXcE3ABgSzo) |
| **Flux 2 Klein 4B GGUF T2i** | Edición de imagen mediante Text to image (Solo texto) | 4GB - 8GB | [📖 Video YT](https://www.youtube.com/watch?v=n3Tjr18E00w) |
| **Z Image Turbo GGUF Ollama** | Generar imágenes con prompts optimizadas (Ollama) | 4GB - 8GB | [📖 Video YT](https://www.youtube.com/watch?v=4AaEvtyNDhI) |
| **Z Image Turbo GGUF Controlnet** | Uso de ZiT Controlnet Turbo Fun Union 2.1 (Canny/OpenPose) | 4GB - 8GB | [📖 Video YT](https://www.youtube.com/watch?v=ULvhNbhS6TY) |

---

## 🤖 Modelos y Recursos Utilizados

A continuación encuentras los enlaces de descarga directos para los modelos y herramientas de los workflows (filtrados sin duplicados):

### 🧠 Modelos Principales & Diffusion
* **Flux 2 Klein 4B (GGUF):** [HuggingFace - unsloth/FLUX.2-klein-4B-GGUF](https://huggingface.co/unsloth/FLUX.2-klein-4B-GGUF)
* **Z-Image Turbo (GGUF):** [HuggingFace - jayn7/Z-Image-Turbo-GGUF](https://huggingface.co/jayn7/Z-Image-Turbo-GGUF)

### 📝 Text Encoders & LLMs
* **Qwen 3 4B (GGUF):** [HuggingFace - Qwen/Qwen3-4B-GGUF](https://huggingface.co/Qwen/Qwen3-4B-GGUF)
* **Ollama (Prompts locales):** [Ollama Official Download](https://ollama.com/download/windows)

### 🎨 VAE, LoRA & ControlNet
* **VAE Flux (ae.safetensors):** [HuggingFace - Comfy-Org/flux2-dev](https://huggingface.co/Comfy-Org/flux2-dev)
* **LoRA Best Face Swap (BFS):** [HuggingFace - Alissonerdx/BFS-Best-Face-Swap](https://huggingface.co/Alissonerdx/BFS-Best-Face-Swap)
* **ControlNet Z-Image-Turbo Fun Union 2.1:** [HuggingFace - alibaba-pai/Z-Image-Turbo-Fun-Controlnet-Union-2.1](https://huggingface.co/alibaba-pai/Z-Image-Turbo-Fun-Controlnet-Union-2.1)

### 🚀 Upscale, Audio & LipSync
* **SeedVR2 (Super Resolución / Upscale GGUF):** [HuggingFace - cmeka/SeedVR2-GGUF](https://huggingface.co/cmeka/SeedVR2-GGUF)
* **Qwen3 TTS 1.7B (Voz y Clonación):** [HuggingFace Collection - Qwen/qwen3-tts](https://huggingface.co/collections/Qwen/qwen3-tts)
* **ComfyUI-FLOAT (LipSync / Sincronización Labial):** [GitHub - yuvraj108c/ComfyUI-FLOAT](https://github.com/yuvraj108c/ComfyUI-FLOAT)

---

## 🛠️ Requisitos Generales
* [ComfyUI](https://github.com/comfyanonymous/ComfyUI) actualizado.
* [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager) instalado para descargar nodos faltantes de forma automática.

📺 **Canal de YouTube:** ¡Suscríbete a [PobreIA](https://www.youtube.com/@PobreIA) para ver las explicaciones en video!
