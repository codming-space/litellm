# LiteLLM Custom Docker Image

## Run
```shell
docker run \
-e LITELLM_MASTER_KEY=sk-1234 \
-e OPENAI_API_KEY=sk-your-key \
-p 4000:4000 \
ghcr.io/codming-space/litellm:latest
```
