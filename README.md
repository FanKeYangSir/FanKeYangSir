# VX API — Affordable AI Model Endpoints

**OpenAI-compatible API for DeepSeek, Qwen, GLM, Kimi and more.**

- 🌍 Global access from Los Angeles
- 💰 40–70% cheaper than going direct
- 🔑 One API key, many models
- ⚡ Simple sign-up, no enterprise contract

## Quick start

```bash
curl https://la-api.vxvxvx.top/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "model": "deepseek-chat",
    "messages": [{"role": "user", "content": "Hello"}]
  }'
