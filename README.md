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
- `Videos` is for official demos, showcase videos, or high-signal tutorials for that exact LoRA.

## Identity / Character Consistency

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-24 | Homelander_LTX2.3 | ssjenforcer191 | Community | [HF](https://huggingface.co/ssjenforcer191/Homelander_LTX2.3) | - | - | - | Character identity IC LoRA for Homelander-themed subject consistency. |
| 2026-07-06 | ltx2.3-ic-lora-ingredients-multishot | linoyts | Community | [HF](https://huggingface.co/linoyts/ltx2.3-ic-lora-ingredients-multishot) | - | - | - | Multi-shot ingredients-based reference consistency fine-tune. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Ingredients | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients/resolve/main/examples/ingredients_lora_1.mp4) | Official reference-sheet IC LoRA for character, prop, and brand consistency. |
| 2026-06-01 | LTX-2.3-Multiple-Subject-Reference | LiconStudio | Official | [HF](https://huggingface.co/LiconStudio/LTX-2.3-Multiple-Subject-Reference) | [GitHub](https://github.com/liconstudio/ComfyUI-Licon-MSR) | [![GitHub Repo stars](https://img.shields.io/github/stars/liconstudio/ComfyUI-Licon-MSR?style=flat-square)](https://github.com/liconstudio/ComfyUI-Licon-MSR) | [Demo](https://huggingface.co/LiconStudio/LTX-2.3-Multiple-Subject-Reference/resolve/main/Validition_V2/01/V2.mp4) | Multi-subject reference IC LoRA for keeping several subjects coherent together. |
| 2026-03-18 | LTX-2.3-ID-LoRA-CelebVHQ-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | [Demo](https://id-lora.github.io/videos/comparisons/speaker_154_pair2/ours.mp4) | ID-LoRA checkpoint for audio-visual identity transfer trained on CelebVHQ-3K. |
| 2026-03-18 | LTX-2.3-ID-LoRA-TalkVid-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | [Demo](https://id-lora.github.io/videos/gallery/4198/knock.mp4) | ID-LoRA checkpoint aimed at talking-video identity transfer. |

## Lip Sync / Dubbing

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-05-13 | ltx2-greenscreen-avatar-ic-lora-vertical-v1 | OmerHagage | Community | [HF](https://huggingface.co/OmerHagage/ltx2-greenscreen-avatar-ic-lora-vertical-v1) | - | - | [Demo](https://huggingface.co/OmerHagage/ltx2-greenscreen-avatar-ic-lora-vertical-v1/resolve/main/samples/hq/sample.mp4) | Greenscreen avatar IC LoRA for vertical talking-avatar and presenter-style videos. |
| 2026-05-11 | LTX-2.3-22b-IC-LoRA-DubIt (LipDub) | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-DubIt) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://justdubit.github.io/assets/videos/teaser_french_ours.mp4) | Official dubbing and lip-sync IC LoRA. The reference README also refers to this family as LipDub. |

## Camera / Motion Control

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-23 | LTX2.3-22B_IC-LoRA-Cameraman_v2 | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2) | - | - | [Demo](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2/resolve/main/assets/test-compa_00007.mp4) | Community camera-motion IC LoRA for pan, zoom, orbit, and shot movement prompts. |
| 2026-05-29 | ltx2.3-chinese-drama-iclora-pose | SyFeee | Community | [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-pose) | - | - | - | Pose-guided Chinese-drama style control IC LoRA. |
| 2026-05-29 | ltx2.3-chinese-drama-iclora-depth | SyFeee | Community | [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-depth) | - | - | - | Depth-guided Chinese-drama style control IC LoRA. |
| 2026-05-29 | ltx2.3-chinese-drama-iclora-canny | SyFeee | Community | [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-canny) | - | - | - | Canny-guided Chinese-drama style control IC LoRA. |
| 2026-05-18 | LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction | yuvraj108c | Community | [HF](https://huggingface.co/yuvraj108c/LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction) | [GitHub](https://github.com/bytedance/ATI) | [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ATI?style=flat-square)](https://github.com/bytedance/ATI) | - | Community LTX port of trajectory-instruction control for motion-path prompting. |
| 2026-04-06 | LTX2.3-22B_IC-LoRA-Cameraman_v1 | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v1) | - | - | [Demo](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v1/resolve/main/assets/test_compa_00049.mp4) | Earlier Cameraman release for camera path and shot movement control. |
| 2026-03-05 | LTX-2.3-22b-IC-LoRA-Motion-Track-Control | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Motion-Track-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [YouTube](https://www.youtube.com/watch?v=f8D2CwF6BIY) | Official motion and track-guided control LoRA. |
| 2026-03-05 | LTX-2.3-22b-IC-LoRA-Union-Control | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Union-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [YouTube](https://www.youtube.com/watch?v=f8D2CwF6BIY) | Official multi-control conditioning LoRA built around control-signal guidance. |

## Editing / Cleanup

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-27 | ltx-2.3-22b-ic-lora-lens_remover | JanKanta | Community | [HF](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover) | - | - | [Demo](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover/resolve/main/Showcase.mp4) | Community restoration model focused on removing lens flare and lens artifacts. |
| 2026-07-19 | LTX-2.3-22b-IC-LoRA-Clean-Plate | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate/resolve/main/examples/clean_plate_001_output_sbs.mp4) | Official clean-plate and object-removal IC LoRA for VFX prep. |
| 2026-04-23 | LTX2.3-ICEdit-Insight | joyfox | Official | [HF](https://huggingface.co/joyfox/LTX2.3-ICEdit-Insight) | [GitHub](https://github.com/joyfoxai/LTX2-ICEdit-Insight) | [![GitHub Repo stars](https://img.shields.io/github/stars/joyfoxai/LTX2-ICEdit-Insight?style=flat-square)](https://github.com/joyfoxai/LTX2-ICEdit-Insight) | - | Editing and cleanup suite for watermark, subtitle, and structure-aware correction tasks. |

## Enhancement / Restoration

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-23 | LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler/resolve/main/examples/spatial_upscale_4x_sbs.mp4) | Official pixel-space upscaler for video super-resolution. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Deblur | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur/resolve/main/examples/Examples_4__00_15485932_sbs.mp4) | Restores focus and sharpness while preserving the shot layout. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Decompression | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression/resolve/main/examples/Examples_2__27_sunflower_field_sbs.mp4) | Repairs compression artifacts such as macroblocking and ringing. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Colorization | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization/resolve/main/examples/Examples_5__00_rabbit_rocks_sbs.mp4) | Colorizes grayscale footage while keeping framing and motion intact. |
| 2026-05-07 | ltx-2.3-dearchive-lora | oumoumad | Community | [HF](https://huggingface.co/oumoumad/ltx-2.3-dearchive-lora) | - | - | - | Archive restoration and remastering IC LoRA for old footage modernization. |
| 2026-04-28 | LTX-2.3-22b-IC-LoRA-Deinterlace | oumoumad | Community | [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Deinterlace) | - | - | - | Deinterlacing-focused restoration IC LoRA. |
| 2026-04-20 | LTX-2.3-22b-IC-LoRA-ReFocus | oumoumad | Community | [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-ReFocus) | - | - | - | Refocus and lens-blur restoration IC LoRA. |

## Relighting / HDR / Tone

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-27 | LTX-2.3-22b-IC-LoRA-Relight | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight/resolve/main/examples/01_ocean_output_lora_sbs.mp4) | Official relighting LoRA for matching target light direction and intensity. |
| 2026-07-27 | LTX-2.3-Black-Magic-LoRA | FuzzPuppy | Community | [HF](https://huggingface.co/FuzzPuppy/LTX-2.3-Black-Magic-LoRA) | - | - | [Demo](https://huggingface.co/FuzzPuppy/LTX-2.3-Black-Magic-LoRA/resolve/main/examples/back-poi.mp4) | Community low-light reconstruction and shadow-detail recovery IC LoRA. |
| 2026-07-22 | LTX-2.3-22b-IC-LoRA-Golden-Hour | Hoffm4nz | Community | [HF](https://huggingface.co/Hoffm4nz/LTX-2.3-22b-IC-LoRA-Golden-Hour) | - | - | - | Community golden-hour relighting and tone-shift LoRA. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Day-To-Night | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night/resolve/main/examples/p_ind_35318605_night.mp4) | Time-of-day relighting from daylight to night scenes. |
| 2026-04-20 | LTX-2.3-22b-IC-LoRA-HDR | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-HDR) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://hdr-lumivid.github.io/videos/carousel_night_glow_sdr_vs_hdr.mp4) | Official HDR and tone-enhancement IC LoRA. |
| 2026-04-06 | LTX-2.3-22b-IC-LoRA-Ungrade | oumoumad | Community | [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Ungrade) | - | - | - | Community color ungrading IC LoRA for neutralizing stylized grades. |

## Outpaint / Expansion / Viewpoint

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-20 | LTX2.3-22B_IC-LoRA-CrossView-Warp | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp) | - | - | [Demo](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp/resolve/main/assets/example_keyframe_01.mp4) | Depth-warp proof-of-concept for viewpoint transfer and novel views. |
| 2026-07-11 | LTX2.3-22B_IC-LoRA-CrossView-Prompt | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | - | - | [Demo](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt/resolve/main/assets/example_warrior_right-lower-closer.mp4) | Prompt-steered novel-view and camera-viewpoint generation. |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-In-Outpainting | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-In-Outpainting) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [YouTube](https://www.youtube.com/watch?v=f8D2CwF6BIY) | Official inpainting and outpainting IC LoRA. |
| 2026-04-23 | VR-360-Outpaint-LTX2.3-IC-LoRA | TheBurgstall | Community | [HF](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA) | - | - | [Demo](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA/resolve/main/junglePAN.mp4) | 360 and equirectangular VR outpainting model. |
| 2026-04-09 | LTX-2.3-22b-IC-LoRA-Outpaint | oumoumad | Community | [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Outpaint) | - | - | - | Early community outpaint checkpoint for LTX 2.3. |

## Style Transfer / Restyle

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-07-25 | ltx-2.3-22b-ic-lora-abercrom-me | CoachBate | Community | [HF](https://huggingface.co/CoachBate/ltx-2.3-22b-ic-lora-abercrom-me) | - | - | [Demo](https://huggingface.co/CoachBate/ltx-2.3-22b-ic-lora-abercrom-me/resolve/main/ABERCROM-ME%20Demo.mp4) | Editorial fashion restyle IC LoRA. |
| 2026-06-26 | LTX-2.3-3DREAL-LoRA | fal | Official | [HF](https://huggingface.co/fal/LTX-2.3-3DREAL-LoRA) | - | - | [Demo](https://v3b.fal.media/files/b/0aa214f8/Ujp4qt6Lk3MfjyAh35gQv_blog_stack_gorge.mp4) | Official render-to-real IC LoRA for pushing 3D inputs toward photoreal outputs. |
| 2026-05-05 | LTX2.3-22B_ReStyle_IC-LoRA | Cseti | Community | [HF](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA) | - | - | [Demo](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA/resolve/main/assets/test-triplet_00125.mp4) | Community restyle model with broad video style-transfer examples. |

## Multi-purpose / Experimental

| Release Date | LoRA / Repo | Author | Source | Hugging Face | GitHub | GitHub Stars | Videos | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-06-17 | LTX-2.3-22b-IC-LoRA-Water-Simulation | Lightricks | Official | [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2) | [Demo](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation/resolve/main/examples/rabbit_forest_sbs.mp4) | Official VFX-oriented IC LoRA for adding water, flood, and stream behavior. |
| 2026-06-01 | LTX-2.3-22b-IC-LoRA-Audio-Only-Context | fbjr | Community | [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context) | - | - | [Demo](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context/resolve/main/assets/example_dialogue_cross_modal.mp4) | Experimental audio-only IC context and identity conditioning. |
| 2026-05-30 | LTX-2.3-22b-IC-LoRA-Helium | fbjr | Community | [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium) | - | - | [Demo](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium/resolve/main/assets/example_1960s_era.mp4) | Experimental audio-driven pitch and style effect LoRA. |
| 2026-05-13 | SYSTMS-FLW-IC-LORA-LTX-2.3 | systms | Community | [HF](https://huggingface.co/systms/SYSTMS-FLW-IC-LORA-LTX-2.3) | - | - | - | Seamless transition and shot-bridging IC LoRA. |
| 2026-04-18 | fxic-ltx2-iclora | oumoumad | Community | [HF](https://huggingface.co/oumoumad/fxic-ltx2-iclora) | - | - | - | Experimental IC LoRA with sparse upstream documentation. |
| 2026-04-13 | ltx2.3-staging-ic-lora-512 | Nightfury16 | Community | [HF](https://huggingface.co/Nightfury16/ltx2.3-staging-ic-lora-512) | - | - | - | Staging and composition-oriented IC LoRA with minimal documentation. |
| 2026-04-04 | MergeGreen_IC-lora_ltx2.3 | siraxe | Community | [HF](https://huggingface.co/siraxe/MergeGreen_IC-lora_ltx2.3) | - | - | [Demo](https://huggingface.co/siraxe/MergeGreen_IC-lora_ltx2.3/resolve/main/vid/w1.mp4) | Transition and loop control IC LoRA using green-fill merge frames. |
| 2026-03-18 | TTM_IC-lora_ltx2.3 | siraxe | Community | [HF](https://huggingface.co/siraxe/TTM_IC-lora_ltx2.3) | - | - | [Demo](https://huggingface.co/siraxe/TTM_IC-lora_ltx2.3/resolve/main/vid/w1.mp4) | Experimental inserted-cutout and motion-transfer IC LoRA. |

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
9. Add an official demo, showcase video, or strong tutorial link in `Videos` when available.
10. Add one short note describing what the IC LoRA is for.
