# LiteLLM Custom Docker Image

## Run
```shell
docker run \
-e LITELLM_MASTER_KEY=sk-1234 \
-e OPENAI_API_KEY=sk-your-key \
-p 4000:4000 \
codming/litellm-arm64:latest
```

[https://github.com/BerriAI/litellm/commit/60c89a3e8a45d19c2e868d25f58dd3c7bb487ac8](https://github.com/BerriAI/litellm/commit/60c89a3e8a45d19c2e868d25f58dd3c7bb487ac8)
