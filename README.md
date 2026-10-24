# Awesome-Augmented-Reality-Viewer

## Top Augmented Reality Viewer Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Web-Based AR Viewing, 3D Model Placement & Self-Hosted AR Frameworks*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality (AR) Viewers**. These tools enable users to view and interact with 3D content in augmented reality—placing virtual objects in the real world through a browser or native app—ranging from platform-locked viewers to open-source web components that work across devices without proprietary dependencies.



**Examples** include Apple Quick Look, Google Scene Viewer, Adobe Aero Player, 8th Wall WebAR, ZapWorks Viewer, Sketchfab AR, and model-viewer (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding platform lock-in, and controlling the AR viewing pipeline. The open-source landscape shifted significantly in **February 2026** when **8th Wall** retired its hosted platform and released its framework under MIT (with SLAM remaining binary-only) . The current landscape is anchored by **model-viewer** (Google's web component for 3D/AR viewing with Scene Viewer fallback), **MindAR** (pure-JavaScript image and face tracking), and **ViroReact** (React Native AR/VR), with **Splatviewer** serving 3D Gaussian Splat viewing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global augmented reality (AR) and web-based AR market is estimated between **$170B and $210B** in 2026, projected to surpass several hundred billion dollars by 2030 (30%+ CAGR) driven by browser-based try-ons, spatial computing, and e-commerce model placement. The sector demonstrates a **concentrated, bifurcated market dynamic**: underlying native mobile runtimes are heavily concentrated in an OS-level duopoly (Apple Quick Look / ARKit and Google Scene Viewer / ARCore), while web-level tooling, authoring suites, and 3D viewer services remain competitive across specialized platforms, open web standards, and emerging Gaussian splat pipelines.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple Quick Look](https://developer.apple.com/augmented-reality/quick-look/)** | ~$5.1T Market Cap | Native iOS AR viewer for USDZ files, triggered via AR Quick Look links or Safari. | Free (bundled with iOS / macOS) | Unlimited viewing on compatible iOS/iPadOS devices (requires USDZ model assets, 0 developer fee) |
| **[Google Scene Viewer](https://developers.google.com/ar/develop/scene-viewer)** | ~$4.1T Market Cap | Android native AR viewer for 3D models, triggered from web links or apps. | Free (bundled with Google Play Services for AR) | Unlimited viewing on supported ARCore Android devices (no session/view charges) |
| **[Adobe Aero Player](https://www.adobe.com/products/aero.html)** | ~$100B Market Cap | Viewer for AR experiences created in Adobe Aero, shareable via link or QR code. | Free standalone viewer; authoring free or via Creative Cloud ($69.99/mo Pro) | Free plan includes 2 GB cloud document storage and unlimited scene viewing links |
| **[Sketchfab AR](https://sketchfab.com/)** | ~$8.4M ARR (Sold to KitBash) | Web-based 3D model viewer with integrated WebXR and AR Quick Look mode. | Free basic viewer; Pro plan starts at $15/month ($180/year) | Free plan permits 10 public uploads/month (max 100 MB/file) and 5 annotations/model; private models require Pro |
| **[ZapWorks Viewer](https://zap.works/)** | $45M Valuation / ~$5.1M ARR (Zappar) | Viewer for AR experiences built with ZapWorks Designer, Studio, or Mattercraft. | Starts at $12.99/month (Developer) or $3,060/year (Pro for commercial projects) | 14-day free trial (evaluation only; projects automatically unpublished when trial ends) |
| **[8th Wall (Legacy Hosted Viewer)](https://8thwall.org)** | Acquired by Niantic (~$9B peak valuation) | Formerly a hosted commercial WebAR platform; retired hosted SaaS viewing on February 28, 2026. | Retired as SaaS (engine framework now open-source MIT; SLAM binary licensed separately) | Discontinued as a hosted SaaS product; replaced by self-hosted open-source framework |

## Open-Source GitHub Projects



- **[model-viewer](https://github.com/google/model-viewer)** [![GitHub Stars](https://img.shields.io/github/stars/google/model-viewer?style=social&color=white)](https://github.com/google/model-viewer/stargazers)  

  **Google's web component for 3D and AR viewing.** A `<model-viewer>` custom element that renders interactive 3D models on the web and seamlessly transitions to AR on supported devices . **Key features**: `ar` attribute triggers an AR button on ARCore Android devices; falls back to Scene Viewer if WebXR is unavailable; `ar-modes` controls whether WebXR or Scene Viewer is used . **Model compatibility**: glTF and GLB formats (with USDZ for iOS Quick Look fallback) . **Strengths**: works on all evergreen browsers for 3D viewing; no app installation required; free and open-source (Apache 2.0). Best for developers wanting a simple, standards-based way to embed 3D models with optional AR viewing on any website.



- **[MindAR](https://github.com/hiukim/mind-ar-js)** [![GitHub Stars](https://img.shields.io/github/stars/hiukim/mind-ar-js?style=social&color=white)](https://github.com/hiukim/mind-ar-js/stargazers)  

  **The pure-JavaScript AR tracking library.** Image tracking and face tracking written end-to-end in JavaScript—from the computer vision engine to the frontend—using WebGL and Web Workers for performance . **Key advantage**: no native dependencies, no binary components—runs entirely in the browser. **A-Frame integration**: create an image-tracking app in ~10 lines of code . **Companion tools**: MindAR Studio (drag-and-drop face tracking, free to self-host) and Pictarize (hosted image-tracking platform) . **Status**: actively maintained by an individual developer seeking community contributions . Best for developers wanting a fully open, dependency-light AR viewing library for image and face tracking on the web.



- **[8th Wall (Open Source Framework)](https://github.com/8thwall/8thwall)** [![GitHub Stars](https://img.shields.io/github/stars/8thwall/8thwall?style=social&color=white)](https://github.com/8thwall/8thwall/stargazers)  

  **The open-source WebAR framework (without SLAM).** After retiring its hosted platform on February 28, 2026, 8th Wall released its engine framework under **MIT license**—including **Face Effects, Image Targets, and Sky Effects** . **Critical caveat**: **SLAM (world tracking) is not open source**—it remains available only through the Distributed Engine Binary under a limited-use license . The framework supports A-Frame, Three.js, Babylon.js, and PlayCanvas integrations. Best for developers wanting a proven WebAR engine for marker-based and face-tracking experiences without vendor lock-in—but requiring the binary for world tracking.



- **[ViroReact](https://github.com/ReactVision/viro)** [![GitHub Stars](https://img.shields.io/github/stars/ReactVision/viro?style=social&color=white)](https://github.com/ReactVision/viro/stargazers)  

  **The React Native AR/VR library.** MIT-licensed, ~2,309 stars . Builds AR and VR experiences using React Native and Expo across iOS and Android. Best for mobile developers already in the React Native ecosystem wanting native AR capabilities without writing platform-specific code.



- **[Splatviewer](https://github.com/5p4m3r/Splatviewer)** [![GitHub Stars](https://img.shields.io/github/stars/5p4m3r/Splatviewer?style=social&color=white)](https://github.com/5p4m3r/Splatviewer/stargazers)  

  **The WebXR viewer for 3D Gaussian Splats.** A custom web component with an attribute-based API similar to `<model-viewer>`, enabling immersive AR experiences for Gaussian Splat files on mobile devices and interactive desktop viewing . **Features**: supports `.ply`, `.splat`, `.sog`, and `.compressed.ply` formats; includes `splat-transform` CLI for format conversion and optimization; CSP-hardened for sandboxed deployment . MIT licensed. Best for developers wanting to view and share 3D Gaussian Splat reconstructions in AR—a newer format increasingly used for photorealistic captures.



### Additional Strong Open-Source Options



- **AR.js** — Marker-based and location-based AR for the web, often paired with A-Frame. Best for simple marker-tracking experiences on a wide range of devices.

- **spARcl (Open AR Cloud)** — Peer-to-peer multi-user AR with GeoPose-based content sharing. Best for collaborative location-based AR experiments.

- **artoolkitX** — Cross-platform marker-tracking SDK with experimental web support. Best for native AR requiring robust marker tracking.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **8th Wall's hosted platform is gone**: the paid SaaS viewer was retired February 28, 2026. The open-source framework covers Image Targets, Face Effects, and Sky Effects—but **SLAM (world tracking) remains a binary-only dependency** . Verify your tracking requirements before adopting.

- **model-viewer's AR support depends on device**: AR viewing requires ARCore on Android (with Scene Viewer fallback) or Quick Look on iOS. 3D viewing works in all evergreen browsers, but AR is device-constrained .

- **Open-source AR viewers vary in scope**: MindAR is fully open but maintained by an individual ; 8th Wall's framework is MIT but incomplete without the SLAM binary ; Splatviewer targets a specific format (Gaussian Splats) . Match the tool to your content type and tracking needs.



---



**Made for AR developers, 3D content creators, and organizations building immersive viewing experiences.**  

Let's make augmented reality viewing more open, accessible, and self-hostable.
