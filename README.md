# ENP Language (UPM)

**Package ID:** `io.github.enpe5v3ldj1nn.language`  
JSON-based localization utilities for TextMeshPro (TMP) with runtime switching.

## Install (Git URL)

### Stable (recommended)
https://github.com/ENPe5v3ldj1nn/enp-unity-language.git#v0.1.0

### Latest (head of main)
https://github.com/ENPe5v3ldj1nn/enp-unity-language.git


## Quick Start
1. Put JSON files into `Resources/Languages` (or set a custom path).
2. Call `LanguageController.SetLanguage(...)` at startup.
3. Use `LanguageText` on your TMP components and assign keys.

## Sample JSON
```json
{
  "hello": "Привіт!",
  "score_fmt": "Рахунок: {0}"
}
```

## Assemblies
- ENP.Language.Runtime (depends on Unity.TextMeshPro, Newtonsoft.Json)

## License
MIT
