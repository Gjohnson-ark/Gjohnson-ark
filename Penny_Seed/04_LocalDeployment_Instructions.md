# Local Deployment

## Recommended Setup
- **Hardware:** MSI WS65 / WS66 or similar with RTX GPU
- **Models:** Mistral 8x7B, Mixtral 8x22B, or LLaMA 3 70B
- **Environment:** LM Studio, Ollama, or Text-Gen WebUI

## Steps
1. Install local LLM runtime.
2. Place all Penny MD files in a reference directory.
3. Load `01_Persona_Core.md` as the **primary system prompt**.
4. Load `03_Operational_Memory_Map.md` as **persistent memory context**.
5. Start session with **context ritual** from `02_Context_Engineering_Guide.md`.

> Optional: Add Python voice wrapper for conversational mode.
