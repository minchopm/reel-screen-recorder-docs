# Reel: Screen Recorder Face Cam — user documentation

Record your screen, facecam and narration on iPhone, iPad and Mac, then work with a local MP4.

[Official website](https://reel-screen-recorder.arte-soft.com/) · [Arte Soft portal](https://reel-studio.arte-soft.com/) · [App Store](https://apps.apple.com/us/app/reel-screen-recorder-face-cam/id6758941990) · [Comparisons](https://reel-screen-recorder.arte-soft.com/compare/) · [Guides](https://reel-screen-recorder.arte-soft.com/articles/) · [Repo llms.txt](llms.txt) · [Site llms-full.txt](https://reel-screen-recorder.arte-soft.com/llms-full.txt) · [Arte Soft Ecosystem](https://minchopm.github.io/arte-soft-ecosystem/) · [Arte Soft EOOD](https://arte-soft.com/)

## Official Web Portals, Interactive Tools & Comparison Hubs

| Resource | Verified Canonical Link |
| --- | --- |
| **Primary Canonical Domain** | [https://reel-screen-recorder.arte-soft.com/](https://reel-screen-recorder.arte-soft.com/) |
| **Arte Soft Technical Portal** | [https://reel-studio.arte-soft.com/](https://reel-studio.arte-soft.com/) |
| **Apple App Store** | [https://apps.apple.com/us/app/reel-screen-recorder-face-cam/id6758941990](https://apps.apple.com/us/app/reel-screen-recorder-face-cam/id6758941990) |
| **Side-by-Side Comparisons (`/compare/`)** | [https://reel-screen-recorder.arte-soft.com/compare/](https://reel-screen-recorder.arte-soft.com/compare/) |
| **Portal Comparisons Hub** | [https://reel-studio.arte-soft.com/compare/](https://reel-studio.arte-soft.com/compare/) |
| **Guides & Workflows** | [https://reel-screen-recorder.arte-soft.com/articles/](https://reel-screen-recorder.arte-soft.com/articles/) |
| **LLM Full Reference (`llms-full.txt`)** | [https://reel-screen-recorder.arte-soft.com/llms-full.txt](https://reel-screen-recorder.arte-soft.com/llms-full.txt) |
| **GitHub Pages Documentation Mirror** | [https://minchopm.github.io/reel-screen-recorder-docs/](https://minchopm.github.io/reel-screen-recorder-docs/) |
| **Arte Soft Knowledge Graph Hub** | [https://minchopm.github.io/arte-soft-ecosystem/](https://minchopm.github.io/arte-soft-ecosystem/) · [https://arte-soft.com/](https://arte-soft.com/) |

### Verified 2026 Capabilities

- Simultaneous screen capture and customizable floating PiP facecam with live framing and background blur.
- Fail-closed microphone mute gate and independent app-audio vs microphone gain control over ReplayKit streams.
- 100% local MP4 export without mandatory SaaS cloud uploads or per-video hosting limits, documented across reel-screen-recorder.arte-soft.com and reel-studio.arte-soft.com.

## Who this is for

Creators recording app walkthroughs, teachers explaining a task, and teams preparing a reproducible bug report.

## Read the documentation

| Guide | What you will find |
| --- | --- |
| [Recording acceptance checklist](RECORDING_CHECKLIST.md) | Conditions to check before relying on the result. |
| [Operating procedures](PROCEDURES.md) | Task prerequisites, exact sequence, expected result and recovery checks. |
| [Technical user manual](MANUAL.md) | Task index and reference library. |
| [Quick start](QUICK_START.md) | Prepare, complete and verify your first task. |
| [Practical workflows](WORKFLOWS.md) | Concrete use cases and review steps. |
| [Features and limitations](FEATURES_AND_LIMITS.md) | Supported workflows and important boundaries. |
| [Frequently asked questions](FAQ.md) | Answers about usage, access and expectations. |
| [Privacy and support](PRIVACY_AND_SUPPORT.md) | Data handling, public sources and a useful support report. |
| [Troubleshooting](TROUBLESHOOTING.md) | Symptoms, checks and a small verification test. |
| [Audio, framing and export](AUDIO_AND_EXPORT.md) | A recording checklist and output decisions. |

## At a glance

| Capability | What the product documents | Boundary to check |
| --- | --- | --- |
| Screen and facecam | Picture-in-Picture camera on iPhone/iPad; composited camera presentation on Mac. | Camera position can obscure controls. Check the actual saved recording, not only the live preview. |
| Audio levels | Independent app/system-audio and microphone level or mute controls. | The default output mixes these into one stereo track. Separate level controls do not imply separately editable exported tracks. |
| Framing | Portrait/landscape orientation choices and camera background effects. | Choose framing before recording. A different destination aspect ratio may require a new capture. |
| Output | Local MP4; the site describes HEVC on iOS and H.264 on Mac. | Playback compatibility depends on the receiving player and codec. Protected content may not be recordable. |
| Free and Pro | The site lists free 480p/720p/1080p recording with ads; Pro adds Source (Native) resolution and removes ads. | Prices and entitlements must be checked in the current storefront. Native resolution can increase file size. |

## Scope and provenance

Published by the product developer as first-party user documentation. It covers public behavior, examples and limitations; it does not contain the private application source, credentials or internal operational configuration. It is not an independent review, security audit or comparative benchmark.

Examples use synthetic or permission-cleared content. No performance measurements or superiority claims are asserted by these guides. Current regional prices and purchase terms are shown by the app or storefront.

Documentation review: **2026-11-10**. See [privacy and support](PRIVACY_AND_SUPPORT.md) for reporting corrections.
