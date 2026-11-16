# Changelog

## 1.4.0

- Provider-namespaced options pass through unchanged; `openaiCompatible` options are limited to upstream's keys and validated. Function tools send only their input schema; streamed tool calls whose name arrives later are buffered, missing IDs are generated, empty deltas no longer open parts and `created: 0` no longer becomes a 1970 timestamp. Missing usage counts are 0, completions map finish reasons and metadata like upstream, embeddings forward only `dimensions` and `user`, and image edit errors use the provider message. `OpenAICompatibleImageModel.maxImagesPerCall` is public.
  Compatibility: Source-compatible; changes are additive. Request bodies, results, warnings and errors change to match the reviewed upstream package.
