# awesome-ltx2.3-ic_lora

A curated index of publicly available LTX 2.3 IC LoRAs from official and community sources.

This list is organized by task. Within each category, the newest verified release goes at the top.

## Contents

- [How This Repo Is Organized](#how-this-repo-is-organized)
- [Identity / Character Consistency](#identity--character-consistency)
- [Lip Sync / Dubbing](#lip-sync--dubbing)
- [Camera / Motion Control](#camera--motion-control)
- [Editing / Cleanup](#editing--cleanup)
- [Enhancement / Restoration](#enhancement--restoration)
- [Relighting / HDR / Tone](#relighting--hdr--tone)
- [Outpaint / Expansion / Viewpoint](#outpaint--expansion--viewpoint)
- [Style Transfer / Restyle](#style-transfer--restyle)
- [Multi-purpose / Experimental](#multi-purpose--experimental)
- [Contribution Format](#contribution-format)

## How This Repo Is Organized

- Entries are grouped by task rather than by a single global latest list.
- Within each category, entries should be sorted by release date in descending order.
- When an upstream release date is not explicitly published, the Hugging Face model `createdAt` date is used.
- The list prefers canonical/original model pages over mirrors and reuploads.
- `Source` marks whether an entry is `Official` or `Community`.
- `GitHub` is only filled when a clear canonical project repo exists for that model family.
- `GitHub Stars` uses live Shields badges when a GitHub repo exists.

## Identity / Character Consistency

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Ingredients | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official reference-sheet IC LoRA for character, prop, and brand consistency. |
| 2026-03-18 | LTX-2.3-ID-LoRA-CelebVHQ-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | ID-LoRA checkpoint for audio-visual identity transfer trained on CelebVHQ-3K. |
| 2026-03-18 | LTX-2.3-ID-LoRA-TalkVid-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | ID-LoRA checkpoint aimed at talking-video identity transfer. |

## Lip Sync / Dubbing

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-05-11 | LTX-2.3-22b-IC-LoRA-DubIt | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-DubIt) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official dubbing and lip-sync IC LoRA for speech replacement workflows. |

## Camera / Motion Control

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-23 | LTX2.3-22B_IC-LoRA-Cameraman_v2 | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2) | - | - | Community camera-motion IC LoRA for pan, zoom, orbit, and shot movement prompts. |
| 2026-03-05 | LTX-2.3-22b-IC-LoRA-Motion-Track-Control | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Motion-Track-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official motion and track-guided control LoRA. |
| 2026-03-05 | LTX-2.3-22b-IC-LoRA-Union-Control | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Union-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official multi-control conditioning LoRA built around control-signal guidance. |

## Editing / Cleanup

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-27 | ltx-2.3-22b-ic-lora-lens_remover | JanKanta | Community | [HF](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover) | - | - | Community restoration model focused on removing lens flare and lens artifacts. |
| 2026-07-19 | LTX-2.3-22b-IC-LoRA-Clean-Plate | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official clean-plate and object-removal IC LoRA for VFX prep. |

## Enhancement / Restoration

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-23 | LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official pixel-space upscaler for video super-resolution. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Deblur | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Restores focus and sharpness while preserving the shot layout. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Decompression | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Repairs compression artifacts such as macroblocking and ringing. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Colorization | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Colorizes grayscale footage while keeping framing and motion intact. |

## Relighting / HDR / Tone

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-27 | LTX-2.3-22b-IC-LoRA-Relight | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official relighting LoRA for matching target light direction and intensity. |
| 2026-07-22 | LTX-2.3-22b-IC-LoRA-Golden-Hour | Hoffm4nz | Community | [HF](https://huggingface.co/Hoffm4nz/LTX-2.3-22b-IC-LoRA-Golden-Hour) | - | - | Community golden-hour relighting and tone-shift LoRA. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Day-To-Night | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Time-of-day relighting from daylight to night scenes. |
| 2026-04-20 | LTX-2.3-22b-IC-LoRA-HDR | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-HDR) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official HDR and tone-enhancement IC LoRA. |

## Outpaint / Expansion / Viewpoint

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-20 | LTX2.3-22B_IC-LoRA-CrossView-Warp | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp) | - | - | Depth-warp proof-of-concept for viewpoint transfer and novel views. |
| 2026-07-11 | LTX2.3-22B_IC-LoRA-CrossView-Prompt | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | - | - | Prompt-steered novel-view and camera-viewpoint generation. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-In-Outpainting | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-In-Outpainting) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official inpainting and outpainting IC LoRA. |
| 2026-04-23 | VR-360-Outpaint-LTX2.3-IC-LoRA | TheBurgstall | Community | [HF](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA) | - | - | 360 and equirectangular VR outpainting model. |
| 2026-04-09 | LTX-2.3-22b-IC-LoRA-Outpaint | oumoumad | Community | [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Outpaint) | - | - | Early community outpaint checkpoint for LTX 2.3. |

## Style Transfer / Restyle

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-05-05 | LTX2.3-22B_ReStyle_IC-LoRA | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA) | - | - | Community restyle model with broad video style-transfer examples. |

## Multi-purpose / Experimental

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Water-Simulation | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | Official VFX-oriented IC LoRA for adding water, flood, and stream behavior. |
| 2026-06-01 | LTX-2.3-22b-IC-LoRA-Audio-Only-Context | fbjr | Community | [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context) | - | - | Experimental audio-only IC context and identity conditioning. |
| 2026-05-30 | LTX-2.3-22b-IC-LoRA-Helium | fbjr | Community | [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium) | - | - | Experimental audio-driven pitch and style effect LoRA. |

## Contribution Format

When adding a new entry:

1. Put it in the closest task category.
2. Keep the newest release at the top of that category.
3. Use the original release date when possible, or the Hugging Face publish date when it is not stated.
4. Include the author or organization.
5. Mark the source as `Official` or `Community`.
6. Add the canonical Hugging Face model page.
7. Add the canonical GitHub repo only when there is a clear direct project repo.
8. Use a live GitHub stars badge when a GitHub repo exists.
9. Add one short note describing what the IC LoRA is for.
