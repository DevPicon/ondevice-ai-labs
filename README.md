# On-Device AI Lab

Repositorio umbrella para agrupar mis pruebas de modelos de IA on-device en Android, iOS y KMP.

## Repos incluidos (submódulos)

- [`miyabi-nano`](./miyabi-nano): Gemini Nano en Android.
- [`iki-nano`](./iki-nano): Gemma 2B (2.6B quantizado) en iOS usando MediaPipe GenAI.
- `gemma2b-android`: (próximamente) Gemma 2B en Android.
- `gemma2b-kmp`: (próximamente) Ejemplo con Kotlin Multiplatform.

## Cómo clonar

```bash
git clone git@github.com:devpicon/ondevice-ai-lab.git
cd ondevice-ai-lab
git submodule update --init --recursive
