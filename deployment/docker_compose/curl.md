curl https://api.runpod.ai/v2/adjh7oq2z0qd4f/openai/v1/chat/completions \
    -H "Content-Type: application/json" \
    -H "Authorization: YC0JCT5QW8Y2J2KXO5M8RPOQRE6E4IRO3P340IJ8" \
    -d '{
    "model": "google/gemma-7b",
    "messages": [
      {
        "role": "user",
        "content": "Why is RunPod the best platform?"
      }
    ],
    "temperature": 0,
    "max_tokens": 100
    }'


