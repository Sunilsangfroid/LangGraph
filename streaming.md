# What is Streaming?

In LLM, streaming means the model starts sending tokens(words) as soon as they're generated, instead of waiting for the entire response to be ready before returning it.

## Why Streaming?

1. **Faster response time**: low drop-off rates.
2. **Mimics human like conversation**: Builds trust, feels alive and keeps the user engaged.
3. **Important for multi-modal UIs**.
4. **Better UX for long output such as code generation, essays, etc**.
5. You can cancel midway saving tokens.
6. You can interleave UI updates, e.g., show "thinking...", show tool results.
