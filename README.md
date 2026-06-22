# DLSM Shadow Puppetry

# “数影双魂”实时动捕皮影系统

A Unity-based real-time body-driven digital shadow puppetry system using Kinect v2.

“数影双魂”是一套基于 Unity 和 Kinect v2 开发的实时动捕皮影系统。系统将人体骨骼动作实时映射至二维数字皮影角色，用于数字表演、文化展示、交互体验与相关科研活动。

## Overview｜项目简介

The DLSM Shadow Puppetry System translates markerless human body movements captured by Kinect v2 into real-time planar shadow-puppet performances.

The project is being developed through several major versions:

| Version | Main functions                                                              | Status            |
| ------- | --------------------------------------------------------------------------- | ----------------- |
| v1.0    | Basic real-time body-driven shadow-puppet performance                       | Preparing release |
| v2.0    | Planar motion retargeting and physics-mediated contact-preserving rendering | Preparing release |
| v3.0    | Video recording, export, media management, and one-click sharing            | In development    |

系统按照以下路径持续迭代：

> 实时动作映射 → 平面动作重定向 → 物理接触保持 → 视频内容导出与传播

## Main Features｜主要功能

* Kinect v2 markerless body tracking
* Real-time body-driven shadow-puppet control
* Planar skeletal motion retargeting
* Digital character and scene presentation
* Multi-scene shadow-puppet performance
* Physics-mediated contact handling in Version 2.0
* Planned video export and one-click sharing in Version 3.0

## Repository Contents｜仓库内容

This repository currently provides:

* Compiled Windows releases;
* Project documentation;
* Version descriptions and release notes;
* System screenshots and demonstration materials;
* Asset copyright and usage notices.

The complete Unity source project is not currently included in this public repository.

本仓库目前主要提供 Windows 编译程序、项目说明、版本记录、演示材料及素材版权声明，暂不包含完整 Unity 源工程。

## System Requirements｜运行环境

* Windows 10 or Windows 11, 64-bit
* Kinect v2 sensor
* Kinect v2 power adapter
* Kinect for Windows SDK 2.0
* USB 3.0 connection
* Dedicated graphics card recommended

## Installation and Use｜安装与运行

1. Download the required version from the repository Releases page.
2. Extract the complete ZIP archive.
3. Do not delete, rename, or separate any files or folders inside the program package.
4. Connect the Kinect v2 sensor and confirm that its driver is working.
5. Run `数影双魂.exe`.
6. Keep the executable file, the corresponding `_Data` folder, `MonoBleedingEdge`, `UnityPlayer.dll`, and other runtime files in the same directory.

中文使用步骤：

1. 在 Releases 页面下载所需版本；
2. 完整解压 ZIP 压缩包；
3. 不要删除、改名或拆分程序内部文件；
4. 连接 Kinect v2，并确认驱动正常；
5. 双击运行 `数影双魂.exe`；
6. 主程序、`数影双魂_Data`、`MonoBleedingEdge` 和相关 DLL 必须保存在同一目录中。

## Version Roadmap｜版本路线

### Version 1.0

Initial real-time motion-capture version supporting body-driven digital shadow-puppet performance.

基础实时动作映射版本，实现 Kinect v2 人体动作到数字皮影角色的实时控制。

### Version 2.0

Introduces planar retargeting and physics-mediated contact-preserving rendering to improve visible blocking, contact response, and post-contact recovery.

新增平面动作重定向与物理介导的接触保持机制，改善角色与场景道具或其他角色之间的阻挡、接触响应和解除接触后的恢复表现。

### Version 3.0

Planned functions include:

* Performance video recording;
* Video export;
* Output file management;
* Export progress feedback;
* One-click sharing;
* Additional usability improvements.

3.0 版本将在实时表演基础上进一步增加视频录制、导出、文件管理和一键分享功能。

## Asset Copyright｜素材版权

Certain shadow-puppet characters, stage backgrounds, scene settings, props, and related materials were designed, produced, and provided by teachers under the unified organization of:

**陕西省渭南市临渭区站南办朝阳幼儿园**

These assets are used under a separate authorization arrangement and are not automatically covered by any license that may apply to the software or documentation.

相关角色形象、背景布景、道具及美术素材不作为开放素材资源发布。未经书面许可，不得单独提取、复制、再分发、出售或用于其他商业项目。

See [ASSET_NOTICE.md](ASSET_NOTICE.md) for the complete asset copyright and usage terms.

## Important Notice｜重要说明

The downloadable software may contain third-party Unity runtime components and plugins. All third-party components remain subject to their respective licenses and terms.

Unless otherwise expressly stated, publication of the compiled software does not grant permission to extract or redistribute embedded artistic assets or third-party components.

## Acknowledgments｜致谢

We sincerely thank **陕西省渭南市临渭区站南办朝阳幼儿园** for organizing the production and provision of shadow-puppet characters, stage backgrounds, scene settings, props, and related physical materials used in the project.

感谢陕西省渭南市临渭区站南办朝阳幼儿园对本项目的大力支持，并统一组织教师完成相关皮影角色、背景布景、场景道具及实物素材的设计与制作。

## Contact｜联系方式

Project contact: `yunhengchao@stu.xupt.edu.cn`

## Copyright

Copyright © 2026 DLSM Shadow Puppetry Project Team.

All rights are reserved unless otherwise expressly stated. The artistic assets described in `ASSET_NOTICE.md` are governed by separate authorization and usage restrictions.
