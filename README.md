# Awesome Augmented Reality Viewer 👓✨

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Augmented Reality Viewer Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Augmented-Reality-Viewer/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Augmented-Reality-Viewer?style=flat-square&logo=github&color=gold" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Augmented-Reality-Viewer/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Augmented-Reality-Viewer?style=flat-square&logo=github&color=blue" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Augmented-Reality-Viewer/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Augmented-Reality-Viewer?style=flat-square&color=green" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌐 Top Augmented Reality Viewer Ecosystem 🚀

> **Curated List of SaaS Platforms, WebAR Engines & Open-Source 3D Spatial Viewers**  
> *Focused on Web-Based AR Viewing, 3D Model Placement, Gaussian Splats & Self-Hosted WebXR Frameworks*  
> **Last updated: October 2026** 📅

Welcome to the **Awesome Augmented Reality Viewer** directory! 🌟 This repository tracks notable **SaaS platforms** and **open-source projects** designed for **Augmented Reality (AR) Viewers**. These developer tools and viewing runtimes enable users to visualize and interact with 3D models in augmented reality—placing digital objects into the physical world directly through mobile web browsers or native apps without proprietary barriers.

Whether you are looking for zero-install **WebAR / WebXR** components, native OS viewers (Apple Quick Look, Google Scene Viewer), or self-hosted computer vision tracking engines (MindAR, AR.js), this guide indexes the entire landscape.

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [📈 Star History](#-star-history)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support](#-support)
- [⚠️ Disclaimer](#-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global augmented reality (AR) and web-based AR market is estimated between **$170B and $210B** in 2026, projected to surpass several hundred billion dollars by 2030 (30%+ CAGR) driven by browser-based try-ons, spatial computing, and e-commerce model placement. The sector demonstrates a **concentrated, bifurcated market dynamic**: underlying native mobile runtimes are heavily concentrated in an OS-level duopoly (Apple Quick Look / ARKit and Google Scene Viewer / ARCore), while web-level tooling, authoring suites, and 3D viewer services remain competitive across specialized platforms, open web standards, and emerging Gaussian splat pipelines.

---

## 🏢 SaaS / Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Apple Quick Look](https://developer.apple.com/augmented-reality/quick-look/)** | ~$5.1T Market Cap | Native iOS AR viewer for USDZ files, triggered via AR Quick Look links or Safari. | Free (bundled with iOS / macOS) | Unlimited viewing on compatible iOS/iPadOS devices (requires USDZ model assets, 0 developer fee) |
| **[Google Scene Viewer](https://developers.google.com/ar/develop/scene-viewer)** | ~$4.1T Market Cap | Android native AR viewer for 3D models, triggered from web links or apps. | Free (bundled with Google Play Services for AR) | Unlimited viewing on supported ARCore Android devices (no session/view charges) |
| **[Adobe Aero Player](https://www.adobe.com/products/aero.html)** | ~$100B Market Cap | Viewer for AR experiences created in Adobe Aero, shareable via link or QR code. | Free standalone viewer; authoring free or via Creative Cloud ($69.99/mo Pro) | Free plan includes 2 GB cloud document storage and unlimited scene viewing links |
| **[Sketchfab AR](https://sketchfab.com/)** | ~$8.4M ARR (Sold to KitBash) | Web-based 3D model viewer with integrated WebXR and AR Quick Look mode. | Free basic viewer; Pro plan starts at $15/month ($180/year) | Free plan permits 10 public uploads/month (max 100 MB/file) and 5 annotations/model; private models require Pro |
| **[ZapWorks Viewer](https://zap.works/)** | $45M Valuation / ~$5.1M ARR (Zappar) | Viewer for AR experiences built with ZapWorks Designer, Studio, or Mattercraft. | Starts at $12.99/month (Developer) or $3,060/year (Pro for commercial projects) | 14-day free trial (evaluation only; projects automatically unpublished when trial ends) |
| **[8th Wall (Legacy Hosted Viewer)](https://8thwall.org)** | Acquired by Niantic (~$9B peak valuation) | Formerly a hosted commercial WebAR platform; retired hosted SaaS viewing on February 28, 2026. | Retired as SaaS (engine framework now open-source MIT; SLAM binary licensed separately) | Discontinued as a hosted SaaS product; replaced by self-hosted open-source framework |

---

## 💻 Open-Source GitHub Projects

Sorted by GitHub_Stars (descending) 🌟:

- **[model-viewer](https://github.com/google/model-viewer)** [![GitHub_Stars](https://img.shields.io/github/stars/google/model-viewer?style=social&color=white)](https://github.com/google/model-viewer/stargazers)  
  📦 **Google's web component for interactive 3D and AR viewing.** A `<model-viewer>` custom element that renders interactive 3D models on the web and seamlessly transitions to AR on supported mobile devices. **Key features**: `ar` attribute triggers an AR button on ARCore Android devices; falls back to Scene Viewer if WebXR is unavailable; `ar-modes` controls whether WebXR or Scene Viewer is used. **Model compatibility**: glTF and GLB formats (with USDZ for iOS Quick Look fallback). Works on all modern browsers with zero app install. Open-source under Apache 2.0.

- **[AR.js](https://github.com/AR-js-org/AR.js)** [![GitHub_Stars](https://img.shields.io/github/stars/AR-js-org/AR.js?style=social&color=white)](https://github.com/AR-js-org/AR.js/stargazers)  
  ⚡ **Efficient Augmented Reality for the Web.** Marker-based, Image Tracking, and Location-based AR running at 60fps on mobile web browsers. Built on top of three.js and A-Frame, AR.js delivers ultra-fast, cross-browser web AR without app downloads or proprietary software dependencies. Open-source under MIT.

- **[MindAR](https://github.com/hiukim/mind-ar-js)** [![GitHub_Stars](https://img.shields.io/github/stars/hiukim/mind-ar-js?style=social&color=white)](https://github.com/hiukim/mind-ar-js/stargazers)  
  🎯 **Pure JavaScript AR tracking library for Image and Face Tracking.** Written end-to-end in JavaScript from the computer vision engine to the frontend using WebGL and Web Workers. Integrates with Three.js and A-Frame to build markerless image tracking or facial filter web applications in less than 10 lines of code. Open-source under MIT.

- **[react-xr](https://github.com/pmndrs/react-xr)** [![GitHub_Stars](https://img.shields.io/github/stars/pmndrs/react-xr?style=social&color=white)](https://github.com/pmndrs/react-xr/stargazers)  
  ⚛️ **VR/AR WebXR components for React Three Fiber.** The premier library for building interactive AR and VR viewing experiences in React. Provides hands tracking, hit-testing for real-world surface placement, spatial controller inputs, and WebXR session management. Open-source under MIT.

- **[ViroReact](https://github.com/ReactVision/viro)** [![GitHub_Stars](https://img.shields.io/github/stars/ReactVision/viro?style=social&color=white)](https://github.com/ReactVision/viro/stargazers)  
  📱 **Cross-platform AR/VR framework for React Native.** Builds immersive native AR experiences on iOS (ARKit) and Android (ARCore) using React Native and Expo. Supports plane detection, 3D object rendering, lighting estimation, and spatial audio with a declarative React component architecture. Open-source under MIT.

- **[WebXR Samples](https://github.com/immersive-web/webxr-samples)** [![GitHub_Stars](https://img.shields.io/github/stars/immersive-web/webxr-samples?style=social&color=white)](https://github.com/immersive-web/webxr-samples/stargazers)  
  🌐 **Official W3C Immersive Web Working Group WebXR Samples.** Demonstrates standards-compliant WebXR Device API implementations for immersive AR and VR sessions in browsers. Includes hit-test surface placement, anchors, lighting estimation, DOM overlay, and depth sensing for cross-platform WebAR viewing. Open-source under W3C / BSD-3-Clause.

- **[artoolkitX](https://github.com/artoolkitx/artoolkitx)** [![GitHub_Stars](https://img.shields.io/github/stars/artoolkitx/artoolkitx?style=social&color=white)](https://github.com/artoolkitx/artoolkitx/stargazers)  
  📐 **Cross-platform marker tracking SDK for AR.** Evolution of the classic ARToolKit providing natural feature tracking (NFT), planar marker tracking, and multi-marker viewing pipelines across iOS, Android, macOS, Windows, Linux, and experimental WebAssembly compilation. Open-source under LGPLv3.

- **[8th Wall (Open-Source Framework)](https://github.com/8thwall/8thwall)** [![GitHub_Stars](https://img.shields.io/github/stars/8thwall/8thwall?style=social&color=white)](https://github.com/8thwall/8thwall/stargazers)  
  🛠️ **Open-source WebAR framework engine.** Released by Niantic under MIT license after retiring its legacy hosted platform in February 2026. Powers Face Effects, Image Targets, and Sky Effects across A-Frame, Three.js, Babylon.js, and PlayCanvas (*Note: SLAM world tracking remains distributed as a binary under a commercial license*).

- **[spARcl](https://github.com/OpenARCloud/sparcl)** [![GitHub_Stars](https://img.shields.io/github/stars/OpenARCloud/sparcl?style=social&color=white)](https://github.com/OpenARCloud/sparcl/stargazers)  
  🌍 **Open AR Cloud spatial computing client.** Reference spatial client implementation connecting to the Open Spatial Computing Platform (OSCP). Supports GeoPose positioning, decentralized spatial discovery, and multi-user persistent AR viewing across city-scale digital twins. Open-source under Apache 2.0.

- **[Splatviewer](https://github.com/5p4m3r/Splatviewer)** [![GitHub_Stars](https://img.shields.io/github/stars/5p4m3r/Splatviewer?style=social&color=white)](https://github.com/5p4m3r/Splatviewer/stargazers)  
  🔮 **WebXR viewer for 3D Gaussian Splats.** A custom web component with an attribute-based API similar to `<model-viewer>`, enabling immersive real-time AR placement of Gaussian Splat files (`.ply`, `.splat`, `.sog`) on mobile devices with `splat-transform` optimization CLI. Open-source under MIT.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Augmented-Reality-Viewer&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Augmented-Reality-Viewer&type=date&legend=top-left)

---

## 🤝 How to Contribute

Contributions are warmly welcomed! 💡 To add or update an augmented reality viewer or WebAR library:

1. 🍴 Fork the repository.
2. 📝 Add or edit entries in `README.md` keeping descriptions factual, concise, and linked to official repositories or homepages.
3. 🏷️ Include pricing and free limits for SaaS tools, or stargazers badge for open-source repos.
4. 🚀 Submit a Pull Request with a clear explanation of your addition.

---

## 💖 Support

If you find **Awesome Augmented Reality Viewer** helpful for your spatial computing, 3D development, or WebAR projects, please consider supporting the project:

- ⭐ **Star this repository** on GitHub to help others discover it!
- 🍴 **Fork and share** it with your developer community and XR colleagues.
- ☕ **Buy me a coffee**: Sponsor ongoing open-source curation via the [GitHub Sponsors Dashboard](http://github.com/sponsors/ishandutta2007).

Your support keeps this ecosystem up to date! Thank you! 🙌

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an official commercial endorsement.
- **8th Wall's hosted platform change**: The hosted SaaS viewing service was retired on February 28, 2026. The open-source framework covers Image Targets, Face Effects, and Sky Effects, but SLAM (world tracking) remains distributed as a binary.
- **Hardware & browser compatibility**: AR capabilities depend on device sensors and OS runtimes (ARCore on Android, ARKit / Quick Look on iOS, and WebXR browser flags on desktop/headsets).
# Awesome-Augmented-Reality-Viewer

# Top Augmented Reality Viewer Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on WebAR Viewing, 3D Model Placement & Self-Hosted AR Frameworks*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Augmented Reality (AR) Viewers**. These tools enable users to view and interact with 3D content in augmented reality—placing virtual objects in the real world through a browser or native app—ranging from platform-locked viewers to open-source web components that work across devices without proprietary dependencies.

**Examples** include Apple Quick Look, Google Scene Viewer, 8th Wall, ZapWorks, Sketchfab AR, and model-viewer (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, avoiding platform lock-in, and controlling the AR viewing pipeline. The open-source landscape shifted significantly in **February 2026** when **8th Wall** retired its hosted platform and released its framework under MIT (with SLAM remaining binary-only) . The current landscape is anchored by **model-viewer** (Google's web component for 3D/AR viewing with Scene Viewer fallback) , **MindAR** (pure-JavaScript image and face tracking) , and **Splatviewer** (WebXR-based 3D Gaussian Splat viewing) .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Apple Quick Look](https://developer.apple.com/quick-look-gallery/)** | Native iOS AR viewer for USDZ files, triggered via AR Quick Look links in Safari, Messages, and other built-in apps . | **Free** (built into iOS). | **Fully free** for iOS users. No developer fees for basic usage. |
| **[Google Scene Viewer](https://developers.google.com/ar/develop/scene-viewer)** | Android's native AR viewer for glTF/GLB models, triggered from web links or apps . | **Free** (built into Google Play Services for AR). | **Fully free** for Android users. Requires ARCore-supported device. |
| **[Adobe Aero Player](https://helpx.adobe.com/aero/using/android-faqs.html)** | Viewer for AR experiences created in Adobe Aero. **Discontinued**: Aero will be discontinued on iOS, Android, and Creative Cloud Desktop effective **November 6, 2025** . | **Free** (was free during operation). | **Fully free** until discontinuation. Content download available until December 3, 2025 . |
| **[8th Wall (Legacy Hosted Platform)](https://8thwall.org)** | Formerly a paid WebAR platform. **Hosted platform retired February 28, 2026**—now fully open source . | **No longer offered as SaaS**. | N/A (discontinued as SaaS). See Open-Source section. |
| **[ZapWorks Viewer](https://docs.zap.works/workspaces/workspace-plans/)** | Viewer for AR experiences built with ZapWorks Designer or Studio. | **Developer**: Free (non-commercial, unlimited views). **Pro**: 12k views/year; additional views $30/thousand . | **Developer plan**: Unlimited views for **non-commercial use only** . |
| **[Sketchfab AR](https://help.sketchfab.com/en/articles/16152686-ar-on-sketchfab)** | Web-based 3D viewer with AR mode for supported devices. Premium/Enterprise customers can enable "app-free" AR mode . | **Free** for viewing public models. **Premium** subscription for uploading private models and app-free AR . | **Free** to view models in AR. App-free AR mode requires Premium/Enterprise . |

## Open-Source GitHub Projects

- **[model-viewer](https://github.com/google/model-viewer)**  
  **Google's web component for 3D and AR viewing.** A `<model-viewer>` custom element that renders interactive 3D models on the web and seamlessly transitions to AR on supported devices . **Key features**: `ar` attribute triggers an AR button on ARCore Android devices; falls back to Scene Viewer if WebXR is unavailable; `ar-modes` controls whether WebXR or Scene Viewer is used . **Model compatibility**: glTF and GLB formats (with USDZ for iOS Quick Look fallback). **Strengths**: works on all evergreen browsers for 3D viewing; no app installation required; free and open-source. Best for developers wanting a simple, standards-based way to embed 3D models with optional AR viewing on any website.

- **[MindAR](https://github.com/hiukim/mind-ar-js)**  
  **The pure-JavaScript AR tracking library.** Image tracking and face tracking written end-to-end in JavaScript—from the computer vision engine to the frontend—using WebGL and Web Workers for performance . **Key advantage**: no native dependencies, no binary components—runs entirely in the browser. **A-Frame integration**: create an image-tracking app in ~10 lines of code . **Companion tools**: MindAR Studio (drag-and-drop face tracking, free to self-host) and Pictarize (hosted image-tracking platform) . **Status**: actively maintained by an individual developer seeking community contributions . Best for developers wanting a fully open, dependency-light AR viewing library for image and face tracking on the web.

- **[8th Wall (Open Source Framework)](https://github.com/8thwall/8thwall)**  
  **The open-source WebAR framework (without SLAM).** After retiring its hosted platform on February 28, 2026, 8th Wall released its engine framework under **MIT license**—including **Face Effects, Image Targets, and Sky Effects** . **Critical caveat**: **SLAM (world tracking) is not open source**—it remains available only through the Distributed Engine Binary under a limited-use license . The framework supports A-Frame, Three.js, Babylon.js, and PlayCanvas integrations. Best for developers wanting a proven WebAR engine for marker-based and face-tracking experiences without vendor lock-in—but requiring the binary for world tracking.

- **[Splatviewer](https://github.com/5p4m3r/Splatviewer)**  
  **The WebXR viewer for 3D Gaussian Splats.** A custom web component with an attribute-based API similar to `<model-viewer>`, enabling immersive AR experiences for Gaussian Splat files on mobile devices and interactive desktop viewing . **Features**: supports `.ply`, `.splat`, `.sog`, and `.compressed.ply` formats; includes `splat-transform` CLI for format conversion and optimization; CSP-hardened for sandboxed deployment . MIT licensed. Best for developers wanting to view and share 3D Gaussian Splat reconstructions in AR—a newer format increasingly used for photorealistic captures.

### Additional Strong Open-Source Options

- **AR.js** — Marker-based and location-based AR for the web, often paired with A-Frame. ~5,664 stars, MIT licensed . Best for simple marker-tracking experiences on a wide range of devices.
- **WebARKit** — Markerless AR libraries including `@webarkit/ar-nft` (image tracking) and `jsartoolkit-nft`. Best for developers wanting a lighter-weight markerless tracking alternative .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- **8th Wall's hosted platform is gone**: the paid SaaS viewer was retired February 28, 2026. The open-source framework covers Image Targets, Face Effects, and Sky Effects—but **SLAM (world tracking) remains a binary-only dependency** . Verify your tracking requirements before adopting.
- **Adobe Aero is discontinued**: effective November 6, 2025, with content download available until December 3, 2025 . Do not select for new projects.
- **model-viewer's AR support depends on device**: AR viewing requires ARCore on Android (with Scene Viewer fallback) or Quick Look on iOS. 3D viewing works in all evergreen browsers, but AR is device-constrained .
- **Open-source AR viewers vary in scope**: MindAR is fully open but maintained by an individual ; 8th Wall's framework is MIT but incomplete without the SLAM binary ; Splatviewer targets a specific format (Gaussian Splats) . Match the tool to your content type and tracking needs.

---

**Made for AR developers, 3D content creators, and organizations building immersive viewing experiences.**  
Let's make augmented reality viewing more open, accessible, and self-hostable.
