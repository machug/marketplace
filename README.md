# machug marketplace

A Claude Code plugin marketplace by Hugh McIntyre. AI-powered writing and research tools.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [fact-checker](https://github.com/machug/fact-checker) | Multi-LLM fact-checking for documents. Extracts claims, cross-checks with independent models, and verifies against authoritative sources. |
| [spec-debate](https://github.com/machug/spec-debate) | Multi-LLM adversarial spec debate. Refines PRDs and tech specs through iterative critique until all models reach consensus. Fork of [adversarial-spec](https://github.com/zscole/adversarial-spec) with updated models and GPT-5/O3/O4 fixes. |
| [gtm-forge](https://github.com/machug/gtm-forge) | Build, validate, and stress-test Go-To-Market strategies for enterprise managed services. Multi-LLM adversarial critique, vendor claim verification, competitive counter-pitches, and funding research. |

## Usage

Add the marketplace once:

```
/plugin marketplace add machug/marketplace
```

Then install any plugin:

```
/plugin install fact-checker@machug
```

## Author

[Hugh McIntyre](https://hughtec.com/) ([X](https://x.com/mmhughmm))

## License

MIT
