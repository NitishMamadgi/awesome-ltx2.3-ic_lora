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
- The list prefers canonical or original model pages over mirrors and reuploads.
- `Source` marks whether an entry is `Official` or `Community`.
- `GitHub` is only filled when a clear canonical project repo exists for that model family.
- `GitHub stars` uses live Shields badges when a GitHub repo exists.
- Each entry uses three compact lines: metadata, links, then notes.

## Identity / Character Consistency

**Homelander_LTX2.3**  
`2026-07-24 | ssjenforcer191 | Community`  
[HF](https://huggingface.co/ssjenforcer191/Homelander_LTX2.3) | - | -  
Character identity IC LoRA for Homelander-themed subject consistency.

**ltx2.3-ic-lora-ingredients-multishot**  
`2026-07-06 | linoyts | Community`  
[HF](https://huggingface.co/linoyts/ltx2.3-ic-lora-ingredients-multishot) | - | -  
Multi-shot ingredients-based reference consistency fine-tune.

**LTX-2.3-22b-IC-LoRA-Ingredients**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official reference-sheet IC LoRA for character, prop, and brand consistency.

**LTX-2.3-Multiple-Subject-Reference**  
`2026-06-01 | LiconStudio | Official`  
[HF](https://huggingface.co/LiconStudio/LTX-2.3-Multiple-Subject-Reference) | [GitHub](https://github.com/liconstudio/ComfyUI-Licon-MSR) | [![GitHub Repo stars](https://img.shields.io/github/stars/liconstudio/ComfyUI-Licon-MSR?style=flat-square)](https://github.com/liconstudio/ComfyUI-Licon-MSR)  
Multi-subject reference IC LoRA for keeping several subjects coherent together.

**LTX-2.3-ID-LoRA-CelebVHQ-3K**  
`2026-03-18 | AviadDahan | Community`  
[HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
ID-LoRA checkpoint for audio-visual identity transfer trained on CelebVHQ-3K.

**LTX-2.3-ID-LoRA-TalkVid-3K**  
`2026-03-18 | AviadDahan | Community`  
[HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
ID-LoRA checkpoint aimed at talking-video identity transfer.

## Lip Sync / Dubbing

**ltx2-greenscreen-avatar-ic-lora-vertical-v1**  
`2026-05-13 | OmerHagage | Community`  
[HF](https://huggingface.co/OmerHagage/ltx2-greenscreen-avatar-ic-lora-vertical-v1) | - | -  
Greenscreen avatar IC LoRA for vertical talking-avatar and presenter-style videos.

**LTX-2.3-22b-IC-LoRA-DubIt (LipDub)**  
`2026-05-11 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-DubIt) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official dubbing and lip-sync IC LoRA. The reference README also refers to this family as LipDub.

## Camera / Motion Control

**LTX2.3-22B_IC-LoRA-Cameraman_v2**  
`2026-06-23 | Cseti | Community`  
[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2) | - | -  
Community camera-motion IC LoRA for pan, zoom, orbit, and shot movement prompts.

**ltx2.3-chinese-drama-iclora-pose**  
`2026-05-29 | SyFeee | Community`  
[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-pose) | - | -  
Pose-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-depth**  
`2026-05-29 | SyFeee | Community`  
[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-depth) | - | -  
Depth-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-canny**  
`2026-05-29 | SyFeee | Community`  
[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-canny) | - | -  
Canny-guided Chinese-drama style control IC LoRA.

**LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction**  
`2026-05-18 | yuvraj108c | Community`  
[HF](https://huggingface.co/yuvraj108c/LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction) | [GitHub](https://github.com/bytedance/ATI) | [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ATI?style=flat-square)](https://github.com/bytedance/ATI)  
Community LTX port of trajectory-instruction control for motion-path prompting.

**LTX2.3-22B_IC-LoRA-Cameraman_v1**  
`2026-04-06 | Cseti | Community`  
[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v1) | - | -  
Earlier Cameraman release for camera path and shot movement control.

**LTX-2.3-22b-IC-LoRA-Motion-Track-Control**  
`2026-03-05 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Motion-Track-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official motion and track-guided control LoRA.

**LTX-2.3-22b-IC-LoRA-Union-Control**  
`2026-03-05 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Union-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official multi-control conditioning LoRA built around control-signal guidance.

## Editing / Cleanup

**ltx-2.3-22b-ic-lora-lens_remover**  
`2026-07-27 | JanKanta | Community`  
[HF](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover) | - | -  
Community restoration model focused on removing lens flare and lens artifacts.

**LTX-2.3-22b-IC-LoRA-Clean-Plate**  
`2026-07-19 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official clean-plate and object-removal IC LoRA for VFX prep.

**LTX2.3-ICEdit-Insight**  
`2026-04-23 | joyfox | Official`  
[HF](https://huggingface.co/joyfox/LTX2.3-ICEdit-Insight) | [GitHub](https://github.com/joyfoxai/LTX2-ICEdit-Insight) | [![GitHub Repo stars](https://img.shields.io/github/stars/joyfoxai/LTX2-ICEdit-Insight?style=flat-square)](https://github.com/joyfoxai/LTX2-ICEdit-Insight)  
Editing and cleanup suite for watermark, subtitle, and structure-aware correction tasks.

## Enhancement / Restoration

**LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler**  
`2026-06-23 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official pixel-space upscaler for video super-resolution.

**LTX-2.3-22b-IC-LoRA-Deblur**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Restores focus and sharpness while preserving the shot layout.

**LTX-2.3-22b-IC-LoRA-Decompression**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Repairs compression artifacts such as macroblocking and ringing.

**LTX-2.3-22b-IC-LoRA-Colorization**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Colorizes grayscale footage while keeping framing and motion intact.

**ltx-2.3-dearchive-lora**  
`2026-05-07 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/ltx-2.3-dearchive-lora) | - | -  
Archive restoration and remastering IC LoRA for old footage modernization.

**LTX-2.3-22b-IC-LoRA-Deinterlace**  
`2026-04-28 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Deinterlace) | - | -  
Deinterlacing-focused restoration IC LoRA.

**LTX-2.3-22b-IC-LoRA-ReFocus**  
`2026-04-20 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-ReFocus) | - | -  
Refocus and lens-blur restoration IC LoRA.

## Relighting / HDR / Tone

**LTX-2.3-22b-IC-LoRA-Relight**  
`2026-07-27 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official relighting LoRA for matching target light direction and intensity.

**LTX-2.3-Black-Magic-LoRA**  
`2026-07-27 | FuzzPuppy | Community`  
[HF](https://huggingface.co/FuzzPuppy/LTX-2.3-Black-Magic-LoRA) | - | -  
Community low-light reconstruction and shadow-detail recovery IC LoRA.

**LTX-2.3-22b-IC-LoRA-Golden-Hour**  
`2026-07-22 | Hoffm4nz | Community`  
[HF](https://huggingface.co/Hoffm4nz/LTX-2.3-22b-IC-LoRA-Golden-Hour) | - | -  
Community golden-hour relighting and tone-shift LoRA.

**LTX-2.3-22b-IC-LoRA-Day-To-Night**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Time-of-day relighting from daylight to night scenes.

**LTX-2.3-22b-IC-LoRA-HDR**  
`2026-04-20 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-HDR) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official HDR and tone-enhancement IC LoRA.

**LTX-2.3-22b-IC-LoRA-Ungrade**  
`2026-04-06 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Ungrade) | - | -  
Community color ungrading IC LoRA for neutralizing stylized grades.

## Outpaint / Expansion / Viewpoint

**LTX2.3-22B_IC-LoRA-CrossView-Warp**  
`2026-07-20 | Cseti | Community`  
[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp) | - | -  
Depth-warp proof-of-concept for viewpoint transfer and novel views.

**LTX2.3-22B_IC-LoRA-CrossView-Prompt**  
`2026-07-11 | Cseti | Community`  
[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | - | -  
Prompt-steered novel-view and camera-viewpoint generation.

**LTX-2.3-22b-IC-LoRA-In-Outpainting**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-In-Outpainting) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official inpainting and outpainting IC LoRA.

**VR-360-Outpaint-LTX2.3-IC-LoRA**  
`2026-04-23 | TheBurgstall | Community`  
[HF](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA) | - | -  
360 and equirectangular VR outpainting model.

**LTX-2.3-22b-IC-LoRA-Outpaint**  
`2026-04-09 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Outpaint) | - | -  
Early community outpaint checkpoint for LTX 2.3.

## Style Transfer / Restyle

**ltx-2.3-22b-ic-lora-abercrom-me**  
`2026-07-25 | CoachBate | Community`  
[HF](https://huggingface.co/CoachBate/ltx-2.3-22b-ic-lora-abercrom-me) | - | -  
Editorial fashion restyle IC LoRA.

**LTX-2.3-3DREAL-LoRA**  
`2026-06-26 | fal | Official`  
[HF](https://huggingface.co/fal/LTX-2.3-3DREAL-LoRA) | - | -  
Official render-to-real IC LoRA for pushing 3D inputs toward photoreal outputs.

**LTX2.3-22B_ReStyle_IC-LoRA**  
`2026-05-05 | Cseti | Community`  
[HF](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA) | - | -  
Community restyle model with broad video style-transfer examples.

## Multi-purpose / Experimental

**LTX-2.3-22b-IC-LoRA-Water-Simulation**  
`2026-06-17 | Lightricks | Official`  
[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Official VFX-oriented IC LoRA for adding water, flood, and stream behavior.

**LTX-2.3-22b-IC-LoRA-Audio-Only-Context**  
`2026-06-01 | fbjr | Community`  
[HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context) | - | -  
Experimental audio-only IC context and identity conditioning.

**LTX-2.3-22b-IC-LoRA-Helium**  
`2026-05-30 | fbjr | Community`  
[HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium) | - | -  
Experimental audio-driven pitch and style effect LoRA.

**SYSTMS-FLW-IC-LORA-LTX-2.3**  
`2026-05-13 | systms | Community`  
[HF](https://huggingface.co/systms/SYSTMS-FLW-IC-LORA-LTX-2.3) | - | -  
Seamless transition and shot-bridging IC LoRA.

**fxic-ltx2-iclora**  
`2026-04-18 | oumoumad | Community`  
[HF](https://huggingface.co/oumoumad/fxic-ltx2-iclora) | - | -  
Experimental IC LoRA with sparse upstream documentation.

**ltx2.3-staging-ic-lora-512**  
`2026-04-13 | Nightfury16 | Community`  
[HF](https://huggingface.co/Nightfury16/ltx2.3-staging-ic-lora-512) | - | -  
Staging and composition-oriented IC LoRA with minimal documentation.

**MergeGreen_IC-lora_ltx2.3**  
`2026-04-04 | siraxe | Community`  
[HF](https://huggingface.co/siraxe/MergeGreen_IC-lora_ltx2.3) | - | -  
Transition and loop control IC LoRA using green-fill merge frames.

**TTM_IC-lora_ltx2.3**  
`2026-03-18 | siraxe | Community`  
[HF](https://huggingface.co/siraxe/TTM_IC-lora_ltx2.3) | - | -  
Experimental inserted-cutout and motion-transfer IC LoRA.

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
