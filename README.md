# awesome-ltx2.3-ic_lora

A curated index of LTX 2.3 IC LoRAs from official and community sources.

This list is organized by task. Within each category, the newest release goes at the top.

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
- Where an upstream release date is not explicitly published, the earliest visible model publish date is used.
- `Source` marks whether an entry is `Official` or `Community`.
- `Links` should include Hugging Face and GitHub when available.
- `GitHub Stars` uses live Shields badges when a GitHub repo exists.
- The initial seed entries below were taken from the IC LoRA references listed in `wildminder/awesome-ltx2` and can be expanded over time.

## Identity / Character Consistency

| Release Date | LoRA / Repo | Author | Source | Links | GitHub Stars | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| 2026-03-18 | ID-LoRA-TalkVid-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-TalkVid-3K)<br>[GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | LTX 2.3 ID-LoRA for identity-preserving talking-head style audio-video generation. |
| 2026-03-18 | ID-LoRA-CelebVHQ-3K | AviadDahan | Community | [HF](https://huggingface.co/AviadDahan/LTX-2.3-ID-LoRA-CelebVHQ-3K)<br>[GitHub](https://github.com/ID-LoRA/ID-LoRA) | [![GitHub Repo stars](https://img.shields.io/github/stars/ID-LoRA/ID-LoRA?style=flat-square)](https://github.com/ID-LoRA/ID-LoRA) | LTX 2.3 ID-LoRA for identity transfer and consistency on the CelebVHQ-3K training set. |

## Lip Sync / Dubbing

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Camera / Motion Control

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Editing / Cleanup

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Enhancement / Restoration

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Relighting / HDR / Tone

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Outpaint / Expansion / Viewpoint

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Style Transfer / Restyle

No direct standalone LTX 2.3 IC LoRA model pages seeded here yet.

## Multi-purpose / Experimental

The reference repo mentions several IC-related workflow dependencies, but they are not listed there with a direct standalone model page yet. These can be added once their canonical Hugging Face or GitHub sources are confirmed.

## Contribution Format

When adding a new entry:

1. Put it in the closest task category.
2. Keep the newest release at the top of that category.
3. Use the original release date when possible.
4. Include the author or organization.
5. Mark the source as `Official` or `Community`.
6. Add Hugging Face and GitHub links when available.
7. Use a live GitHub stars badge when a GitHub repo exists.
8. Add one short note describing what the IC LoRA is for.
