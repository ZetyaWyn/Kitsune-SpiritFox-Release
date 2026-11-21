<p align="center">
  <img src="./header.svg" alt="Kitsune-SpiritFox GKI" width="100%">
</p>

<p align="center">
  <img src="https://i.postimg.cc/DfjzdVXd/IMG-20261121-200118-275.jpg" alt="Kitsune-SpiritFox GKI Kernel" width="100%">
</p>

<p align="center">
  <em>Official Release Repository for Kitsune-SpiritFox GKI Kernels</em>
</p>

<p align="center">
  <img alt="Android" src="https://img.shields.io/badge/Android-12-3DDC84?style=for-the-badge&logo=android&logoColor=white">
  <img alt="Kernel" src="https://img.shields.io/badge/Kernel-5.10.x-7C4DFF?style=for-the-badge&logo=linux&logoColor=white">
  <a href="../../releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/ZetyaWyn/Kitsune-SpiritFox-Release?style=for-the-badge&label=Latest&color=FF6D00"></a>
  <a href="../../releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/ZetyaWyn/Kitsune-SpiritFox-Release/total?style=for-the-badge&label=Downloads&color=00BFA5"></a>
</p>

<p align="center">
  <a href="../../releases/latest">
    <img src="https://img.shields.io/badge/⬇_GET_LATEST_RELEASE-FF5252?style=for-the-badge&logo=github&logoColor=white" height="36" alt="Download Latest Release">
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=24,25,26&height=3" width="100%" alt="Divider" />

## 📥 Download

Get the newest build from the **[Releases page](../../releases/latest)**. Every release includes one AnyKernel3 zip per root manager, plus a plain **Vanilla** zip with no root.

<table width="100%">
  <tr>
    <th width="90" align="center">Icon</th>
    <th align="left" width="45%">Root Manager</th>
    <th align="left" width="210">Kernel Package</th>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://commons.wikimedia.org/wiki/Special:FilePath/Vanilla_planifolia_(6998639597).jpg?width=120" height="56" alt=""></td>
    <td><strong>None (Vanilla)</strong><br><sub>Clean GKI kernel without root</sub></td>
    <td><code>…-Vanilla.zip</code></td>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://github.com/KernelSU-Next/KernelSU-Next/raw/dev/assets/kernelsu_next.png" height="56" alt=""></td>
    <td><strong>KernelSU-Next + SUSFS</strong><br><sub>Next-gen root with SUSFS hiding</sub></td>
    <td><code>…-KSUN_SUSFS.zip</code></td>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://kernelsu.org/logo.png" height="56" alt=""></td>
    <td><strong>KernelSU + SUSFS</strong><br><sub>Standard KSU with SUSFS</sub></td>
    <td><code>…-KSU_SUSFS.zip</code></td>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://github.com/Baka-SU/BakaSU/raw/main/docs/BakaSU_Full.svg" height="56" alt=""></td>
    <td><strong>BakaSU + SUSFS</strong><br><sub>BakaSU fork with SUSFS</sub></td>
    <td><code>…-BAKASU_SUSFS.zip</code></td>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://github.com/SukiSU-Nova/SukiSU-Nova/raw/main/docs/SukiSU-mini.svg" height="56" alt=""></td>
    <td><strong>SukiSU-Nova + SUSFS</strong><br><sub>SukiSU-Nova with SUSFS</sub></td>
    <td><code>…-SUKISU_SUSFS.zip</code></td>
  </tr>
  <tr>
    <td width="90" align="center"><img src="https://github.com/LyraVoid/FinaSU/raw/master/logo.png" height="56" alt=""></td>
    <td><strong>FinaSU + SUSFS</strong><br><sub>FinaSU with SUSFS</sub></td>
    <td><code>…-FINASU_SUSFS.zip</code></td>
  </tr>
</table>

> [!TIP]
> Pick **one** zip. The manager app you install must match the root you flashed. Check the release page for the exact version and commit of each root.

> [!CAUTION]
> Always back up your current `boot` image before flashing, and report any bugs or breakages.

---

## ✨ Key Features

<p>
  <img src="https://img.shields.io/badge/SUSFS-Root_Hiding-6200EA?style=for-the-badge" alt="SUSFS">
  <img src="https://img.shields.io/badge/NoMount-Overlay_Support-0091EA?style=for-the-badge" alt="NoMount">
  <img src="https://img.shields.io/badge/NTSync-Wine%2FProton_Sync-00C853?style=for-the-badge" alt="NTSync">
  <img src="https://img.shields.io/badge/Multi--Root-5_Managers_%2B_Vanilla-FF6D00?style=for-the-badge" alt="Multi-Root">
</p>

- **SUSFS:** Kernel-level root and mount hiding support.
- **NoMount:** Clean mountless module handling.
- **NTSync:** Fast synchronization primitive support for gaming/compatibility layers.
- **Flexible Root Choice:** Pre-built variants for five root managers, or stock unrooted Vanilla.

---

## 🧬 Source Repositories

<table width="100%">
  <tr>
    <th align="left" width="45%">Component</th>
    <th align="left">Repository</th>
  </tr>
  <tr>
    <td><strong>Kernel Source</strong> (<code>android12-5.10</code>)</td>
    <td><a href="https://github.com/ZetyaWyn/android_kernel_common-5.10"><img src="https://img.shields.io/badge/GitHub-Kitsune--SpiritFox-181717?style=flat-square&logo=github" alt="Kitsune-SpiritFox"></a></td>
  </tr>
  <tr>
    <td><strong>Build Scripts</strong></td>
    <td><a href="https://github.com/ZetyaWyn/FleurX-GKI-Builder"><img src="https://img.shields.io/badge/GitHub-GKI_Builder-181717?style=flat-square&logo=github" alt="GKI Builder"></a></td>
  </tr>
</table>

---

## 💎 Acknowledgments

*Dedicated to the developers whose work makes this project possible:*

<table width="100%">
  <tr>
    <th align="left" width="45%">Developer / Project</th>
    <th align="left">Contribution</th>
  </tr>
  <tr>
    <td><a href="https://github.com/ramabondanp/android_kernel_common-5.10"><strong>ramabondanp</strong></a></td>
    <td>Kernel source base</td>
  </tr>
  <tr>
    <td><a href="https://github.com/zylhdrXP"><strong>zylhdrXP</strong></a></td>
    <td>Technical advisor · Builder script</td>
  </tr>
  <tr>
    <td><a href="https://github.com/tiann/KernelSU"><strong>tiann/KernelSU</strong></a></td>
    <td>Root implementation</td>
  </tr>
  <tr>
    <td><a href="https://github.com/KernelSU-Next/KernelSU-Next"><strong>KernelSU-Next</strong></a></td>
    <td>Root implementation</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Baka-SU/BakaSU"><strong>BakaSU</strong></a></td>
    <td>Root implementation</td>
  </tr>
  <tr>
    <td><a href="https://github.com/SukiSU-Nova/SukiSU-Nova"><strong>SukiSU-Nova</strong></a></td>
    <td>Root implementation</td>
  </tr>
  <tr>
    <td><a href="https://github.com/LyraVoid/FinaSU"><strong>FinaSU</strong></a></td>
    <td>Root implementation</td>
  </tr>
  <tr>
    <td><a href="https://gitlab.com/simonpunk/susfs4ksu"><strong>simonpunk (susfs4ksu)</strong></a></td>
    <td>SUSFS</td>
  </tr>
  <tr>
    <td><a href="https://github.com/maxsteeel/nomount"><strong>maxsteeel (NoMount)</strong></a></td>
    <td>NoMount</td>
  </tr>
  <tr>
    <td><a href="https://github.com/WildKernels"><strong>WildKernels</strong></a></td>
    <td>Build workflow ideas and kernel patches</td>
  </tr>
</table>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=24,25,26&height=70&section=footer&text=Built%20with%20precision.%20Driven%20by%20performance.&fontSize=16&fontColor=ffffff&fontAlignY=50" width="100%" alt="Footer" />
</p>
