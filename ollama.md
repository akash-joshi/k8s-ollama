1. Pull Ollama model

ollama pull llama3.2

2. Serve ollama

ollama serve

3. Make a request

curl http://localhost:11434/api/generate -d '{
  "model": "llama3.2",
  "prompt":"Why is the sky blue?"
}'

