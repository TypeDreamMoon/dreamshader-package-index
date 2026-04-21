# DreamShader Package Index

This repository is the default package index template for DreamShaderLang.

The published URL expected by the VSCode extension is:

```text
https://raw.githubusercontent.com/TypeDreamMoon/dreamshader-package-index/main/packages.json
```

## Entry Format

```json
{
  "name": "@typedreammoon/dream-noise",
  "displayName": "Dream Noise",
  "description": "Noise, FBM and Voronoi helpers for DreamShaderLang.",
  "repository": "https://github.com/TypeDreamMoon/dream-noise",
  "tags": ["noise", "procedural"]
}
```

Each repository should contain a `dreamshader.package.json` file at its root.

## Default Packages

- `@typedreammoon/dreamshader-math`
- `@typedreammoon/dreamshader-color`
- `@typedreammoon/dreamshader-uv`
- `@typedreammoon/dreamshader-noise`
- `@typedreammoon/dreamshader-sdf`
- `@typedreammoon/dreamshader-normal`
- `@typedreammoon/dreamshader-pbr`
- `@typedreammoon/dreamshader-postprocess`
