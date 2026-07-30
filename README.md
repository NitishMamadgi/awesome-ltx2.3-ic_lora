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

## Identity / Character Consistency

**Homelander_LTX2.3**  
&nbsp;&nbsp;`2026-07-24 | ssjenforcer191 | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/ssjenforcer191/Homelander_LTX2.3) | - | -  
&nbsp;&nbsp;Character identity IC LoRA for Homelander-themed subject consistency.

**ltx2.3-ic-lora-ingredients-multishot**  
&nbsp;&nbsp;`2026-07-06 | linoyts | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/linoyts/ltx2.3-ic-lora-ingredients-multishot) | - | -  
&nbsp;&nbsp;Multi-shot ingredients-based reference consistency fine-tune.

**LTX-2.3-22b-IC-LoRA-Ingredients**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Ingredients) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official reference-sheet IC LoRA for character, prop, and brand consistency.  
&nbsp;&nbsp;[Benji's AI Playground](https://www.youtube.com/watch?v=P-nRo5muRCM) | [MaxonShire](https://www.youtube.com/watch?v=7nMTLCfohqs) | [AntIMatter](https://www.youtube.com/watch?v=guxp6uFqwn8)

**LTX-2.3-Multiple-Subject-Reference**  
&nbsp;&nbsp;`2026-06-01 | LiconStudio | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/LiconStudio/LTX-2.3-Multiple-Subject-Reference) | [GitHub](https://github.com/liconstudio/ComfyUI-Licon-MSR) | [![GitHub Repo stars](https://img.shields.io/github/stars/liconstudio/ComfyUI-Licon-MSR?style=flat-square)](https://github.com/liconstudio/ComfyUI-Licon-MSR)  
&nbsp;&nbsp;Multi-subject reference IC LoRA for keeping several subjects coherent together.

**LTX-2.3-ID-LoRA-CelebVHQ-3K**  
&nbsp;&nbsp;`2026-03-18 | AviadDahan | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
&nbsp;&nbsp;ID-LoRA checkpoint for audio-visual identity transfer trained on CelebVHQ-3K.

**LTX-2.3-ID-LoRA-TalkVid-3K**  
&nbsp;&nbsp;`2026-03-18 | AviadDahan | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K) | [GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA)  
&nbsp;&nbsp;ID-LoRA checkpoint aimed at talking-video identity transfer.

## Lip Sync / Dubbing

**ltx2-greenscreen-avatar-ic-lora-vertical-v1**  
&nbsp;&nbsp;`2026-05-13 | OmerHagage | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/OmerHagage/ltx2-greenscreen-avatar-ic-lora-vertical-v1) | - | -  
&nbsp;&nbsp;Greenscreen avatar IC LoRA for vertical talking-avatar and presenter-style videos.

**LTX-2.3-22b-IC-LoRA-DubIt (LipDub)**  
&nbsp;&nbsp;`2026-05-11 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-DubIt) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official dubbing and lip-sync IC LoRA. The reference README also refers to this family as LipDub.  
&nbsp;&nbsp;[Benji's AI Playground](https://www.youtube.com/watch?v=pF9wv-yqnhI) | [ComfyUI](https://www.youtube.com/watch?v=2PEKKU4a924)

## Camera / Motion Control

**LTX2.3-22B_IC-LoRA-Cameraman_v2**  
&nbsp;&nbsp;`2026-06-23 | Cseti | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v2) | - | -  
&nbsp;&nbsp;Community camera-motion IC LoRA for pan, zoom, orbit, and shot movement prompts.

**ltx2.3-chinese-drama-iclora-pose**  
&nbsp;&nbsp;`2026-05-29 | SyFeee | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-pose) | - | -  
&nbsp;&nbsp;Pose-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-depth**  
&nbsp;&nbsp;`2026-05-29 | SyFeee | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-depth) | - | -  
&nbsp;&nbsp;Depth-guided Chinese-drama style control IC LoRA.

**ltx2.3-chinese-drama-iclora-canny**  
&nbsp;&nbsp;`2026-05-29 | SyFeee | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/SyFeee/ltx2.3-chinese-drama-iclora-canny) | - | -  
&nbsp;&nbsp;Canny-guided Chinese-drama style control IC LoRA.

**LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction**  
&nbsp;&nbsp;`2026-05-18 | yuvraj108c | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/yuvraj108c/LTX-2.3-22b-IC-LoRA-Any-Trajectory-Instruction) | [GitHub](https://github.com/bytedance/ATI) | [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ATI?style=flat-square)](https://github.com/bytedance/ATI)  
&nbsp;&nbsp;Community LTX port of trajectory-instruction control for motion-path prompting.

**LTX2.3-22B_IC-LoRA-Cameraman_v1**  
&nbsp;&nbsp;`2026-04-06 | Cseti | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-Cameraman_v1) | - | -  
&nbsp;&nbsp;Earlier Cameraman release for camera path and shot movement control.

**LTX-2.3-22b-IC-LoRA-Motion-Track-Control**  
&nbsp;&nbsp;`2026-03-05 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Motion-Track-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official motion and track-guided control LoRA.  
&nbsp;&nbsp;[Benji's AI Playground](https://www.youtube.com/watch?v=Jf1QzQKTH1w) | [AxiomGraph](https://www.youtube.com/watch?v=8z3aAz4poyQ)

**LTX-2.3-22b-IC-LoRA-Union-Control**  
&nbsp;&nbsp;`2026-03-05 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Union-Control) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official multi-control conditioning LoRA built around control-signal guidance.  
&nbsp;&nbsp;[Prompt Mastery](https://www.youtube.com/watch?v=u1eA8WJeO4s) | [Benji's AI Playground](https://www.youtube.com/watch?v=Jf1QzQKTH1w)

## Editing / Cleanup

**ltx-2.3-22b-ic-lora-lens_remover**  
&nbsp;&nbsp;`2026-07-27 | JanKanta | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/JanKanta/ltx-2.3-22b-ic-lora-lens_remover) | - | -  
&nbsp;&nbsp;Community restoration model focused on removing lens flare and lens artifacts.

**LTX-2.3-22b-IC-LoRA-Clean-Plate**  
&nbsp;&nbsp;`2026-07-19 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Clean-Plate) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official clean-plate and object-removal IC LoRA for VFX prep.

**LTX2.3-ICEdit-Insight**  
&nbsp;&nbsp;`2026-04-23 | joyfox | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/joyfox/LTX2.3-ICEdit-Insight) | [GitHub](https://github.com/joyfoxai/LTX2-ICEdit-Insight) | [![GitHub Repo stars](https://img.shields.io/github/stars/joyfoxai/LTX2-ICEdit-Insight?style=flat-square)](https://github.com/joyfoxai/LTX2-ICEdit-Insight)  
&nbsp;&nbsp;Editing and cleanup suite for watermark, subtitle, and structure-aware correction tasks.

## Enhancement / Restoration

**LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler**  
&nbsp;&nbsp;`2026-06-23 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Pixel-Spatial-Upscaler) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official pixel-space upscaler for video super-resolution.

**LTX-2.3-22b-IC-LoRA-Deblur**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Deblur) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Restores focus and sharpness while preserving the shot layout.

**LTX-2.3-22b-IC-LoRA-Decompression**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Decompression) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Repairs compression artifacts such as macroblocking and ringing.

**LTX-2.3-22b-IC-LoRA-Colorization**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Colorization) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Colorizes grayscale footage while keeping framing and motion intact.

**ltx-2.3-dearchive-lora**  
&nbsp;&nbsp;`2026-05-07 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/ltx-2.3-dearchive-lora) | - | -  
&nbsp;&nbsp;Archive restoration and remastering IC LoRA for old footage modernization.

**LTX-2.3-22b-IC-LoRA-Deinterlace**  
&nbsp;&nbsp;`2026-04-28 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Deinterlace) | - | -  
&nbsp;&nbsp;Deinterlacing-focused restoration IC LoRA.

**LTX-2.3-22b-IC-LoRA-ReFocus**  
&nbsp;&nbsp;`2026-04-20 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-ReFocus) | - | -  
&nbsp;&nbsp;Refocus and lens-blur restoration IC LoRA.

## Relighting / HDR / Tone

**LTX-2.3-22b-IC-LoRA-Relight**  
&nbsp;&nbsp;`2026-07-27 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Relight) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official relighting LoRA for matching target light direction and intensity.

**LTX-2.3-Black-Magic-LoRA**  
&nbsp;&nbsp;`2026-07-27 | FuzzPuppy | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/FuzzPuppy/LTX-2.3-Black-Magic-LoRA) | - | -  
&nbsp;&nbsp;Community low-light reconstruction and shadow-detail recovery IC LoRA.

**LTX-2.3-22b-IC-LoRA-Golden-Hour**  
&nbsp;&nbsp;`2026-07-22 | Hoffm4nz | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Hoffm4nz/LTX-2.3-22b-IC-LoRA-Golden-Hour) | - | -  
&nbsp;&nbsp;Community golden-hour relighting and tone-shift LoRA.

**LTX-2.3-22b-IC-LoRA-Day-To-Night**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Day-To-Night) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Time-of-day relighting from daylight to night scenes.

**LTX-2.3-22b-IC-LoRA-HDR**  
&nbsp;&nbsp;`2026-04-20 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-HDR) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official HDR and tone-enhancement IC LoRA.

**LTX-2.3-22b-IC-LoRA-Ungrade**  
&nbsp;&nbsp;`2026-04-06 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Ungrade) | - | -  
&nbsp;&nbsp;Community color ungrading IC LoRA for neutralizing stylized grades.

## Outpaint / Expansion / Viewpoint

**LTX2.3-22B_IC-LoRA-CrossView-Warp**  
&nbsp;&nbsp;`2026-07-20 | Cseti | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Warp) | - | -  
&nbsp;&nbsp;Depth-warp proof-of-concept for viewpoint transfer and novel views.

**LTX2.3-22B_IC-LoRA-CrossView-Prompt**  
&nbsp;&nbsp;`2026-07-11 | Cseti | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | - | -  
&nbsp;&nbsp;Prompt-steered novel-view and camera-viewpoint generation.

**LTX-2.3-22b-IC-LoRA-In-Outpainting**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-In-Outpainting) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official inpainting and outpainting IC LoRA.

**VR-360-Outpaint-LTX2.3-IC-LoRA**  
&nbsp;&nbsp;`2026-04-23 | TheBurgstall | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/TheBurgstall/VR-360-Outpaint-LTX2.3-IC-LoRA) | - | -  
&nbsp;&nbsp;360 and equirectangular VR outpainting model.

**LTX-2.3-22b-IC-LoRA-Outpaint**  
&nbsp;&nbsp;`2026-04-09 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/LTX-2.3-22b-IC-LoRA-Outpaint) | - | -  
&nbsp;&nbsp;Early community outpaint checkpoint for LTX 2.3.

## Style Transfer / Restyle

**ltx-2.3-22b-ic-lora-abercrom-me**  
&nbsp;&nbsp;`2026-07-25 | CoachBate | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/CoachBate/ltx-2.3-22b-ic-lora-abercrom-me) | - | -  
&nbsp;&nbsp;Editorial fashion restyle IC LoRA.

**LTX-2.3-3DREAL-LoRA**  
&nbsp;&nbsp;`2026-06-26 | fal | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/fal/LTX-2.3-3DREAL-LoRA) | - | -  
&nbsp;&nbsp;Official render-to-real IC LoRA for pushing 3D inputs toward photoreal outputs.

**LTX2.3-22B_ReStyle_IC-LoRA**  
&nbsp;&nbsp;`2026-05-05 | Cseti | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Cseti/LTX2.3-22B_ReStyle_IC-LoRA) | - | -  
&nbsp;&nbsp;Community restyle model with broad video style-transfer examples.

## Multi-purpose / Experimental

**LTX-2.3-22b-IC-LoRA-Water-Simulation**  
&nbsp;&nbsp;`2026-06-17 | Lightricks | Official`  
&nbsp;&nbsp;[HF](https://huggingface.co/Lightricks/LTX-2.3-22b-IC-LoRA-Water-Simulation) | [GitHub](https://github.com/Lightricks/LTX-2) | [![GitHub Repo stars](https://img.shields.io/github/stars/Lightricks/LTX-2?style=flat-square)](https://github.com/Lightricks/LTX-2)  
&nbsp;&nbsp;Official VFX-oriented IC LoRA for adding water, flood, and stream behavior.

**LTX-2.3-22b-IC-LoRA-Audio-Only-Context**  
&nbsp;&nbsp;`2026-06-01 | fbjr | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Audio-Only-Context) | - | -  
&nbsp;&nbsp;Experimental audio-only IC context and identity conditioning.

**LTX-2.3-22b-IC-LoRA-Helium**  
&nbsp;&nbsp;`2026-05-30 | fbjr | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/fbjr/LTX-2.3-22b-IC-LoRA-Helium) | - | -  
&nbsp;&nbsp;Experimental audio-driven pitch and style effect LoRA.

**SYSTMS-FLW-IC-LORA-LTX-2.3**  
&nbsp;&nbsp;`2026-05-13 | systms | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/systms/SYSTMS-FLW-IC-LORA-LTX-2.3) | - | -  
&nbsp;&nbsp;Seamless transition and shot-bridging IC LoRA.

**fxic-ltx2-iclora**  
&nbsp;&nbsp;`2026-04-18 | oumoumad | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/oumoumad/fxic-ltx2-iclora) | - | -  
&nbsp;&nbsp;Experimental IC LoRA with sparse upstream documentation.

**ltx2.3-staging-ic-lora-512**  
&nbsp;&nbsp;`2026-04-13 | Nightfury16 | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/Nightfury16/ltx2.3-staging-ic-lora-512) | - | -  
&nbsp;&nbsp;Staging and composition-oriented IC LoRA with minimal documentation.

**MergeGreen_IC-lora_ltx2.3**  
&nbsp;&nbsp;`2026-04-04 | siraxe | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/siraxe/MergeGreen_IC-lora_ltx2.3) | - | -  
&nbsp;&nbsp;Transition and loop control IC LoRA using green-fill merge frames.

**TTM_IC-lora_ltx2.3**  
&nbsp;&nbsp;`2026-03-18 | siraxe | Community`  
&nbsp;&nbsp;[HF](https://huggingface.co/siraxe/TTM_IC-lora_ltx2.3) | - | -  
&nbsp;&nbsp;Experimental inserted-cutout and motion-transfer IC LoRA.

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
