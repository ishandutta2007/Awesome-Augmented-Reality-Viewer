# Awesome Augmented Reality Viewer 👓✨

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Augmented Reality Viewer Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
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

- **[A-Frame](https://github.com/aframevr/aframe)** [![GitHub_Stars](https://img.shields.io/github/stars/aframevr/aframe?style=social&color=white)](https://github.com/aframevr/aframe/stargazers)  
  🥽 **Web framework for building 3D, AR, and VR experiences.** An open-source, declarative entity-component HTML framework for Three.js. Supports WebXR AR sessions, mobile hit-testing, surface anchoring, and cross-browser spatial immersion with standard HTML tags. Open-source under MIT.

- **[model-viewer](https://github.com/google/model-viewer)** [![GitHub_Stars](https://img.shields.io/github/stars/google/model-viewer?style=social&color=white)](https://github.com/google/model-viewer/stargazers)  
  📦 **Google's web component for interactive 3D and AR viewing.** A `<model-viewer>` custom element that renders interactive 3D models on the web and seamlessly transitions to AR on supported mobile devices. **Key features**: `ar` attribute triggers an AR button on ARCore Android devices; falls back to Scene Viewer if WebXR is unavailable; `ar-modes` controls whether WebXR or Scene Viewer is used. **Model compatibility**: glTF and GLB formats (with USDZ for iOS Quick Look fallback). Works on all modern browsers with zero app install. Open-source under Apache 2.0.

- **[AR.js](https://github.com/AR-js-org/AR.js)** [![GitHub_Stars](https://img.shields.io/github/stars/AR-js-org/AR.js?style=social&color=white)](https://github.com/AR-js-org/AR.js/stargazers)  
  ⚡ **Efficient Augmented Reality for the Web.** Marker-based, Image Tracking, and Location-based AR running at 60fps on mobile web browsers. Built on top of three.js and A-Frame, AR.js delivers ultra-fast, cross-browser web AR without app downloads or proprietary software dependencies. Open-source under MIT.

- **[ARCore Android SDK](https://github.com/google-ar/arcore-android-sdk)** [![GitHub_Stars](https://img.shields.io/github/stars/google-ar/arcore-android-sdk?style=social&color=white)](https://github.com/google-ar/arcore-android-sdk/stargazers)  
  🤖 **Google's Augmented Reality SDK for Android.** The underlying native platform for surface tracking, hit testing, environmental lighting estimation, depth sensing, and motion tracking that powers native Android AR viewers and Google Scene Viewer. Open-source under Apache 2.0.

- **[antimatter15/splat](https://github.com/antimatter15/splat)** [![GitHub_Stars](https://img.shields.io/github/stars/antimatter15/splat?style=social&color=white)](https://github.com/antimatter15/splat/stargazers)  
  ✨ **JavaScript 3D Gaussian Splat Viewer.** Real-time in-browser Gaussian Splatting renderer using WebGL and Web Workers. Allows instant viewing and real-world scale inspection of `.splat` and `.ply` point cloud reconstructions directly on the web with zero plugins. Open-source under MIT.

- **[Jeeliz FaceFilter](https://github.com/jeeliz/jeelizFaceFilter)** [![GitHub_Stars](https://img.shields.io/github/stars/jeeliz/jeelizFaceFilter?style=social&color=white)](https://github.com/jeeliz/jeelizFaceFilter/stargazers)  
  🎭 **Lightweight WebGL & JavaScript library for real-time face tracking.** High-performance multi-face detection, facial rotation tracking, and AR face mask viewing in mobile web browsers. Integrates directly with Three.js, Babylon.js, and Canvas2D. Open-source under Apache 2.0.

- **[GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D)** [![GitHub_Stars](https://img.shields.io/github/stars/mkkellogg/GaussianSplats3D?style=social&color=white)](https://github.com/mkkellogg/GaussianSplats3D/stargazers)  
  🌌 **Three.js-based 3D Gaussian Splat viewer.** Highly optimized renderer with WebXR AR support, progressive loading, dynamic LOD scene streaming, and full interaction controls for spatial 3D scenes on mobile devices and VR headsets. Open-source under MIT.

- **[MindAR](https://github.com/hiukim/mind-ar-js)** [![GitHub_Stars](https://img.shields.io/github/stars/hiukim/mind-ar-js?style=social&color=white)](https://github.com/hiukim/mind-ar-js/stargazers)  
  🎯 **Pure JavaScript AR tracking library for Image and Face Tracking.** Written end-to-end in JavaScript from the computer vision engine to the frontend using WebGL and Web Workers. Integrates with Three.js and A-Frame to build markerless image tracking or facial filter web applications in less than 10 lines of code. Open-source under MIT.

- **[react-xr](https://github.com/pmndrs/xr)** [![GitHub_Stars](https://img.shields.io/github/stars/pmndrs/xr?style=social&color=white)](https://github.com/pmndrs/xr/stargazers)  
  ⚛️ **VR/AR WebXR components for React Three Fiber.** The premier library for building interactive AR and VR viewing experiences in React. Provides hands tracking, hit-testing for real-world surface placement, spatial controller inputs, and WebXR session management. Open-source under MIT.

- **[ViroReact](https://github.com/ReactVision/viro)** [![GitHub_Stars](https://img.shields.io/github/stars/ReactVision/viro?style=social&color=white)](https://github.com/ReactVision/viro/stargazers)  
  📱 **Cross-platform AR/VR framework for React Native.** Builds immersive native AR experiences on iOS (ARKit) and Android (ARCore) using React Native and Expo. Supports plane detection, 3D object rendering, lighting estimation, and spatial audio with a declarative React component architecture. Open-source under MIT.

- **[Sceneview](https://github.com/sceneview/sceneview)** [![GitHub_Stars](https://img.shields.io/github/stars/sceneview/sceneview?style=social&color=white)](https://github.com/sceneview/sceneview/stargazers)  
  🪄 **3D & AR SDK for Android (Jetpack Compose + Filament) and Apple (SwiftUI + RealityKit).** Opens glTF/GLB, 3MF, STL, OBJ, and PLY on Android and USDZ on iOS at real physical scale in augmented reality. Features instant surface hit testing and environment reflections. Open-source under Apache 2.0.

- **[Sceneform SDK](https://github.com/google-ar/sceneform-android-sdk)** [![GitHub_Stars](https://img.shields.io/github/stars/google-ar/sceneform-android-sdk?style=social&color=white)](https://github.com/google-ar/sceneform-android-sdk/stargazers)  
  🏛️ **Google's 3D and AR viewing SDK for Android.** High-level scene graph library on top of Filament and ARCore that simplifies building AR viewer applications, plane visualizations, node manipulation, and shadow rendering. Open-source under Apache 2.0.

- **[WebXR Samples](https://github.com/immersive-web/webxr-samples)** [![GitHub_Stars](https://img.shields.io/github/stars/immersive-web/webxr-samples?style=social&color=white)](https://github.com/immersive-web/webxr-samples/stargazers)  
  🌐 **Official W3C Immersive Web Working Group WebXR Samples.** Demonstrates standards-compliant WebXR Device API implementations for immersive AR and VR sessions in browsers. Includes hit-test surface placement, anchors, lighting estimation, DOM overlay, and depth sensing for cross-platform WebAR viewing. Open-source under W3C / BSD-3-Clause.

- **[Jeeliz Weboji](https://github.com/jeeliz/jeelizWeboji)** [![GitHub_Stars](https://img.shields.io/github/stars/jeeliz/jeelizWeboji?style=social&color=white)](https://github.com/jeeliz/jeelizWeboji/stargazers)  
  😀 **JavaScript and WebGL library for face tracking and animated avatars in browsers.** Renders real-time expressions, eye gazing, and head tracking to drive 3D AR avatars and animated emojis in real-time web sessions. Open-source under Apache 2.0.

- **[PlayCanvas Model Viewer](https://github.com/playcanvas/model-viewer)** [![GitHub_Stars](https://img.shields.io/github/stars/playcanvas/model-viewer?style=social&color=white)](https://github.com/playcanvas/model-viewer/stargazers)  
  🎨 **Lightweight 3D model viewer with WebXR AR support.** Built on the high-performance PlayCanvas WebGL engine. Supports drag-and-drop glTF, GLB, and Splat loading, real-time environment lighting, morph targets, animations, and zero-latency WebXR hit testing. Open-source under MIT.

- **[artoolkitX](https://github.com/artoolkitx/artoolkitx)** [![GitHub_Stars](https://img.shields.io/github/stars/artoolkitx/artoolkitx?style=social&color=white)](https://github.com/artoolkitx/artoolkitx/stargazers)  
  📐 **Cross-platform marker tracking SDK for AR.** Evolution of the classic ARToolKit providing natural feature tracking (NFT), planar marker tracking, and multi-marker viewing pipelines across iOS, Android, macOS, Windows, Linux, and experimental WebAssembly compilation. Open-source under LGPLv3.

- **[AlvaAR](https://github.com/alanross/AlvaAR)** [![GitHub_Stars](https://img.shields.io/github/stars/alanross/AlvaAR?style=social&color=white)](https://github.com/alanross/AlvaAR/stargazers)  
  🧭 **Pure JavaScript Visual SLAM engine for WebAR.** In-browser markerless 6DoF camera tracking and point cloud reconstruction using computer vision algorithms without native OS plugins or app installation requirements. Open-source under MIT.

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

- 📌 This is a **community-curated** list — not exhaustive and not an official commercial endorsement.
- 🔄 **8th Wall's hosted platform change**: The hosted SaaS viewing service was retired on February 28, 2026. The open-source framework covers Image Targets, Face Effects, and Sky Effects, but SLAM (world tracking) remains distributed as a binary.
- 📱 **Hardware & browser compatibility**: AR capabilities depend on device sensors and OS runtimes (ARCore on Android, ARKit / Quick Look on iOS, and WebXR browser flags on desktop/headsets).
