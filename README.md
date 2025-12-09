# On-Device AI Lab

Repositorio umbrella para agrupar mis pruebas de modelos de IA on-device en Android, iOS y KMP.

## Repos incluidos (submódulos)

- [`miyabi-nano`](./miyabi-nano): Gemini Nano en Android.
- [`iki-nano`](./iki-nano): Gemma 2B (2.6B quantizado) en iOS usando MediaPipe GenAI.
- `gemma2b-android`: (próximamente) Gemma 2B en Android.
- `gemma2b-kmp`: (próximamente) Ejemplo con Kotlin Multiplatform.

## Talks & Videos

### AI models on-device (mDevConf 2024)
En esta charla exploro las posibilidades de ejecutar modelos de IA directamente en dispositivos móviles, incluyendo Gemini Nano (Android) y Gemma 2B (iOS con MediaPipe). También comento las limitaciones actuales, casos de uso, y hacia dónde se mueve esta tendencia.

▶️ **Video:** https://www.youtube.com/watch?v=kEf7pvGdKC0&t=25210s  

**Temas cubiertos**
- Gemini Nano (AICore)
- MediaPipe Task GenAI
- Gemma 2B on-device
- Limitaciones actuales
- Perspectiva mobile developer

## Cómo clonar

```bash
git clone git@github.com:devpicon/ondevice-ai-lab.git
cd ondevice-ai-lab
git submodule update --init --recursive
