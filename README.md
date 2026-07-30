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
- Videos are intentionally omitted for now so the entry format can stay flexible.

## Identity / Character Consistency

**Homelander_LTX2.3**  
Released: `2026-07-24`  
Author: `ssjenforcer191`  
Source: `Community`  
Links: [HF](https://huggingface.co/ssjenforcer191/Homelander_LTX2.3)  
GitHub stars: `-`  
Notes: Character identity IC LoRA for Homelander-themed subject consistency.

**ltx2.3-ic-lora-ingredients-multishot**  
Released: `2026-07-06`  
Author: `linoyts`  
Source: `Community`  
Links: [HF](https://huggingface.co/linoyts/ltx2.3-ic-lora-ingredients-multishot)  
GitHub stars: `-`  
Notes: Multi-shot ingredients-based reference consistency fine-tune.

**LTX-2.3-22b-IC-LoRA-Ingredients**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official reference-sheet IC LoRA for character, prop, and brand consistency.

**LTX-2.3-Multiple-Subject-Reference**  
Released: `2026-06-01`  
Author: `LiconStudio`  
Source: `Official`  
Links: [HF](https://huggingface.co/LiconStudio/LTX-2.3-Multiple-Subject-Reference) | [GitHub](https://github.com/liconstudio/ComfyUI-Licon-MSR)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/liconstudio/ComfyUI-Licon-MSR?style=flat-square)](https://github.com/liconstudio/ComfyUI-Licon-MSR)  
Notes: Multi-subject reference IC LoRA for keeping several subjects coherent together.

**LTX-2.3-ID-LoRA-CelebVHQ-3K**  
Released: `2026-03-18`  
Author: `AviadDahan`  
Source: `Community`  
Links: [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
Notes: ID-LoRA checkpoint for audio-visual identity transfer trained on CelebVHQ-3K.

**LTX-2.3-ID-LoRA-TalkVid-3K**  
Released: `2026-03-18`  
Author: `AviadDahan`  
Source: `Community`  
Links: [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
Notes: ID-LoRA checkpoint aimed at talking-video identity transfer.

## Lip Sync / Dubbing

**ltx2-greenscreen-avatar-ic-lora-vertical-v1**  
Released: `2026-05-13`  
Author: `OmerHagage`  
Source: `Community`  
Links: [HF](https://huggingface.co/OmerHagage/ltx2-greenscreen-avatar-ic-lora-vertical-v1)  
GitHub stars: `-`  
Notes: Greenscreen avatar IC LoRA for vertical talking-avatar and presenter-style videos.

**LTX-2.3-22b-IC-LoRA-DubIt (LipDub)**  
Released: `2026-05-11`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-DubIt) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official dubbing and lip-sync IC LoRA. The reference README also refers to this family as LipDub.

## Camera / Motion Control

**LTX2.3-22B_IC-LoRA-Cameraman_v2**  
Released: `2026-06-23`  
Author: `Cseti`  
Source: `Community`  
Links: [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2)  
GitHub stars: `-`  
Notes: Community camera-motion IC LoRA for pan, zoom, orbit, and shot movement prompts.

**ltx2.3-chinese-drama-iclora-pose**  
Released: `2026-05-29`  
Author: `SyFeee`  
Source: `Community`  
Links: [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-pose)  
GitHub stars: `-`  
Notes: Pose-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-depth**  
Released: `2026-05-29`  
Author: `SyFeee`  
Source: `Community`  
Links: [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-depth)  
GitHub stars: `-`  
Notes: Depth-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-canny**  
Released: `2026-05-29`  
Author: `SyFeee`  
Source: `Community`  
Links: [HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-canny)  
GitHub stars: `-`  
Notes: Canny-guided Chinese-drama style control IC LoRA.

**LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction**  
Released: `2026-05-18`  
Author: `yuvraj108c`  
Source: `Community`  
Links: [HF](https://huggingface.co/yuvraj108c/LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction) | [GitHub](https://github.com/bytedance/ATI)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ATI?style=flat-square)](https://github.com/bytedance/ATI)  
Notes: Community LTX port of trajectory-instruction control for motion-path prompting.

**LTX2.3-22B_IC-LoRA-Cameraman_v1**  
Released: `2026-04-06`  
Author: `Cseti`  
Source: `Community`  
Links: [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v1)  
GitHub stars: `-`  
Notes: Earlier Cameraman release for camera path and shot movement control.

**LTX-2.3-22b-IC-LoRA-Motion-Track-Control**  
Released: `2026-03-05`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Motion-Track-Control) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official motion and track-guided control LoRA.

**LTX-2.3-22b-IC-LoRA-Union-Control**  
Released: `2026-03-05`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Union-Control) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official multi-control conditioning LoRA built around control-signal guidance.

## Editing / Cleanup

**ltx-2.3-22b-ic-lora-lens_remover**  
Released: `2026-07-27`  
Author: `JanKanta`  
Source: `Community`  
Links: [HF](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover)  
GitHub stars: `-`  
Notes: Community restoration model focused on removing lens flare and lens artifacts.

**LTX-2.3-22b-IC-LoRA-Clean-Plate**  
Released: `2026-07-19`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official clean-plate and object-removal IC LoRA for VFX prep.

**LTX2.3-ICEdit-Insight**  
Released: `2026-04-23`  
Author: `joyfox`  
Source: `Official`  
Links: [HF](https://huggingface.co/joyfox/LTX2.3-ICEdit-Insight) | [GitHub](https://github.com/joyfoxai/LTX2-ICEdit-Insight)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/joyfoxai/LTX2-ICEdit-Insight?style=flat-square)](https://github.com/joyfoxai/LTX2-ICEdit-Insight)  
Notes: Editing and cleanup suite for watermark, subtitle, and structure-aware correction tasks.

## Enhancement / Restoration

**LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler**  
Released: `2026-06-23`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official pixel-space upscaler for video super-resolution.

**LTX-2.3-22b-IC-LoRA-Deblur**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Restores focus and sharpness while preserving the shot layout.

**LTX-2.3-22b-IC-LoRA-Decompression**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Repairs compression artifacts such as macroblocking and ringing.

**LTX-2.3-22b-IC-LoRA-Colorization**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Colorizes grayscale footage while keeping framing and motion intact.

**ltx-2.3-dearchive-lora**  
Released: `2026-05-07`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/ltx-2.3-dearchive-lora)  
GitHub stars: `-`  
Notes: Archive restoration and remastering IC LoRA for old footage modernization.

**LTX-2.3-22b-IC-LoRA-Deinterlace**  
Released: `2026-04-28`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Deinterlace)  
GitHub stars: `-`  
Notes: Deinterlacing-focused restoration IC LoRA.

**LTX-2.3-22b-IC-LoRA-ReFocus**  
Released: `2026-04-20`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-ReFocus)  
GitHub stars: `-`  
Notes: Refocus and lens-blur restoration IC LoRA.

## Relighting / HDR / Tone

**LTX-2.3-22b-IC-LoRA-Relight**  
Released: `2026-07-27`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official relighting LoRA for matching target light direction and intensity.

**LTX-2.3-Black-Magic-LoRA**  
Released: `2026-07-27`  
Author: `FuzzPuppy`  
Source: `Community`  
Links: [HF](https://huggingface.co/FuzzPuppy/LTX-2.3-Black-Magic-LoRA)  
GitHub stars: `-`  
Notes: Community low-light reconstruction and shadow-detail recovery IC LoRA.

**LTX-2.3-22b-IC-LoRA-Golden-Hour**  
Released: `2026-07-22`  
Author: `Hoffm4nz`  
Source: `Community`  
Links: [HF](https://huggingface.co/Hoffm4nz/LTX-2.3-22b-IC-LoRA-Golden-Hour)  
GitHub stars: `-`  
Notes: Community golden-hour relighting and tone-shift LoRA.

**LTX-2.3-22b-IC-LoRA-Day-To-Night**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Time-of-day relighting from daylight to night scenes.

**LTX-2.3-22b-IC-LoRA-HDR**  
Released: `2026-04-20`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-HDR) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official HDR and tone-enhancement IC LoRA.

**LTX-2.3-22b-IC-LoRA-Ungrade**  
Released: `2026-04-06`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Ungrade)  
GitHub stars: `-`  
Notes: Community color ungrading IC LoRA for neutralizing stylized grades.

## Outpaint / Expansion / Viewpoint

**LTX2.3-22B_IC-LoRA-CrossView-Warp**  
Released: `2026-07-20`  
Author: `Cseti`  
Source: `Community`  
Links: [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp)  
GitHub stars: `-`  
Notes: Depth-warp proof-of-concept for viewpoint transfer and novel views.

**LTX2.3-22B_IC-LoRA-CrossView-Prompt**  
Released: `2026-07-11`  
Author: `Cseti`  
Source: `Community`  
Links: [HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt)  
GitHub stars: `-`  
Notes: Prompt-steered novel-view and camera-viewpoint generation.

**LTX-2.3-22b-IC-LoRA-In-Outpainting**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-In-Outpainting) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official inpainting and outpainting IC LoRA.

**VR-360-Outpaint-LTX2.3-IC-LoRA**  
Released: `2026-04-23`  
Author: `TheBurgstall`  
Source: `Community`  
Links: [HF](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA)  
GitHub stars: `-`  
Notes: 360 and equirectangular VR outpainting model.

**LTX-2.3-22b-IC-LoRA-Outpaint**  
Released: `2026-04-09`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Outpaint)  
GitHub stars: `-`  
Notes: Early community outpaint checkpoint for LTX 2.3.

## Style Transfer / Restyle

**ltx-2.3-22b-ic-lora-abercrom-me**  
Released: `2026-07-25`  
Author: `CoachBate`  
Source: `Community`  
Links: [HF](https://huggingface.co/CoachBate/ltx-2.3-22b-ic-lora-abercrom-me)  
GitHub stars: `-`  
Notes: Editorial fashion restyle IC LoRA.

**LTX-2.3-3DREAL-LoRA**  
Released: `2026-06-26`  
Author: `fal`  
Source: `Official`  
Links: [HF](https://huggingface.co/fal/LTX-2.3-3DREAL-LoRA)  
GitHub stars: `-`  
Notes: Official render-to-real IC LoRA for pushing 3D inputs toward photoreal outputs.

**LTX2.3-22B_ReStyle_IC-LoRA**  
Released: `2026-05-05`  
Author: `Cseti`  
Source: `Community`  
Links: [HF](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA)  
GitHub stars: `-`  
Notes: Community restyle model with broad video style-transfer examples.

## Multi-purpose / Experimental

**LTX-2.3-22b-IC-LoRA-Water-Simulation**  
Released: `2026-06-17`  
Author: `Lightricks`  
Source: `Official`  
Links: [HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation) | [GitHub](https://github.com/Lightricks/LTX-2)  
GitHub stars: [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
Notes: Official VFX-oriented IC LoRA for adding water, flood, and stream behavior.

**LTX-2.3-22b-IC-LoRA-Audio-Only-Context**  
Released: `2026-06-01`  
Author: `fbjr`  
Source: `Community`  
Links: [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context)  
GitHub stars: `-`  
Notes: Experimental audio-only IC context and identity conditioning.

**LTX-2.3-22b-IC-LoRA-Helium**  
Released: `2026-05-30`  
Author: `fbjr`  
Source: `Community`  
Links: [HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium)  
GitHub stars: `-`  
Notes: Experimental audio-driven pitch and style effect LoRA.

**SYSTMS-FLW-IC-LORA-LTX-2.3**  
Released: `2026-05-13`  
Author: `systms`  
Source: `Community`  
Links: [HF](https://huggingface.co/systms/SYSTMS-FLW-IC-LORA-LTX-2.3)  
GitHub stars: `-`  
Notes: Seamless transition and shot-bridging IC LoRA.

**fxic-ltx2-iclora**  
Released: `2026-04-18`  
Author: `oumoumad`  
Source: `Community`  
Links: [HF](https://huggingface.co/oumoumad/fxic-ltx2-iclora)  
GitHub stars: `-`  
Notes: Experimental IC LoRA with sparse upstream documentation.

**ltx2.3-staging-ic-lora-512**  
Released: `2026-04-13`  
Author: `Nightfury16`  
Source: `Community`  
Links: [HF](https://huggingface.co/Nightfury16/ltx2.3-staging-ic-lora-512)  
GitHub stars: `-`  
Notes: Staging and composition-oriented IC LoRA with minimal documentation.

**MergeGreen_IC-lora_ltx2.3**  
Released: `2026-04-04`  
Author: `siraxe`  
Source: `Community`  
Links: [HF](https://huggingface.co/siraxe/MergeGreen_IC-lora_ltx2.3)  
GitHub stars: `-`  
Notes: Transition and loop control IC LoRA using green-fill merge frames.

**TTM_IC-lora_ltx2.3**  
Released: `2026-03-18`  
Author: `siraxe`  
Source: `Community`  
Links: [HF](https://huggingface.co/siraxe/TTM_IC-lora_ltx2.3)  
GitHub stars: `-`  
Notes: Experimental inserted-cutout and motion-transfer IC LoRA.

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
