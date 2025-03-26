1. Pull Ollama model

ollama pull llama3.2

2. Serve ollama

ollama serve

3. Make a request

curl http://127.0.0.1:11434/api/generate -d '{
  "model": "deepseek-r1:1.5b",
  "prompt":"Why is the sky blue?"
}'