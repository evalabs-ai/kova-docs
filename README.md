# kova-docs

Public developer documentation for the Kova TTS API, published at https://docs.kova.ai.

Built with [Mintlify](https://mintlify.com/). Push to `main` → Mintlify rebuilds and deploys.

## Local development

```sh
npm install -g mintlify
mintlify dev
```

Then open http://localhost:3000.

## OpenAPI sync

The canonical OpenAPI spec at `api-reference/openapi.json` is maintained by CI in
[evalabs-ai/kova-tts-server](https://github.com/evalabs-ai/kova-tts-server).
That repo's `sync-openapi-docs` workflow opens PRs here whenever the API surface changes.

Do not hand-edit `api-reference/openapi.json` — your changes will be overwritten.
