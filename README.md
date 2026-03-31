# bistro-gltf

A version of the Bistro scene using AVIF textures.

> **Work in progress:** The resulting scene is not loadable in most glTF viewers.

## Notes

- The original source textures were not available, so the AVIF textures were generated from decompressed BC7 files.
- Materials have been updated to use the standard `metallicRoughness` workflow and the `KHR_materials_specular` extension instead of `KHR_materials_pbrSpecularGlossiness`.

## Results

|                    | Texture Disk Size | Video Memory                                 |
| ------------------ | ----------------- | -------------------------------------------- |
| **Original** (BC7) | 1.9 GB            | 1.9 GB                                       |
| **New** (AVIF)     | 189.7 MB          | 1.9 GB (high quality) / 1.3 GB (low quality) |
