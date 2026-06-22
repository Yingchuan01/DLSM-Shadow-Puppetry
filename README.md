# DLSM Shadow Puppetry

# “数影双魂”实时动捕皮影系统

## Current Release

The current stable version is [DLSM Shadow Puppetry v2.0.0](https://github.com/Yingchuan01/DLSM-Shadow-Puppetry/releases/tag/v2.0.0).

Version 2.0 retains the planar CCD-IK motion-retargeting framework established in Version 1.0, introduces physics-mediated contact-preserving rendering, and improves the recording and video-export workflow.

当前稳定版本为 [DLSM Shadow Puppetry v2.0.0](https://github.com/Yingchuan01/DLSM-Shadow-Puppetry/releases/tag/v2.0.0)。

v2.0 保留了 v1.0 已建立的平面 CCD-IK 动作重定向框架，并在此基础上新增物理介导的接触保持机制，同时完善录屏与视频导出流程。

## Overview｜项目简介

The DLSM Shadow Puppetry System translates markerless human body movements captured by Kinect v2 into real-time planar shadow-puppet performances.

The project is being developed through several major versions:

| Version                                                                         | Main functions                                                                          | Status                 |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- | ---------------------- |
| [v1.0](https://github.com/Yingchuan01/DLSM-Shadow-Puppetry/releases/tag/v1.0.0) | Kinect-based real-time motion capture and planar CCD-IK shadow-puppet control           | Released               |
| [v2.0](https://github.com/Yingchuan01/DLSM-Shadow-Puppetry/releases/tag/v2.0.0) | Physics-mediated contact-preserving rendering and improved performance recording/export | Current stable release |
| v3.0                                                                            | Cloud upload, QR-code generation, and cross-device sharing                              | In development         |


系统按照以下技术路径持续迭代：

> Kinect 实时动作捕捉
> → 平面 CCD-IK 动作重定向
> → 初步录屏与内容保存
> → 物理介导的接触保持与录制功能完善
> → 云端上传、二维码生成与跨设备分享

The system is being developed along the following progression:

> Real-time Kinect motion capture
> → Planar CCD-IK motion retargeting
> → Initial performance recording
> → Physics-mediated contact preservation and improved recording/export
> → Cloud upload, QR-code generation, and cross-device sharing

## Main Features｜主要功能

* Kinect v2 markerless body tracking
* Real-time body-driven shadow-puppet control
* Planar CCD-IK skeletal motion retargeting
* Multi-character and multi-scene shadow-puppet performance
* Basic performance recording introduced during the transition from Version 1.0 to Version 2.0
* Physics-mediated character–object and character–character contact handling in Version 2.0
* Visible blocking, constrained displacement, and post-contact recovery
* Improved recording, video export, and media management in Version 2.0
* Planned cloud upload, QR-code generation, and cross-device sharing in Version 3.0

主要功能包括：

* 基于 Kinect v2 的无标记人体动作捕捉；
* 人体动作到数字皮影角色的实时控制；
* 基于平面 CCD-IK 的二维骨骼动作重定向；
* 多角色、多场景数字皮影表演；
* 在 v1.0 向 v2.0 过渡阶段初步实现表演录制；
* v2.0 新增物理介导的角色—道具与角色—角色接触处理；
* 支持可见阻挡、接触约束位移和接触解除后的姿态恢复；
* v2.0 对录屏、视频导出和媒体管理功能进行完善；
* v3.0 计划增加云端上传、二维码生成和跨设备分享。


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

### Version 1.0 — Planar CCD-IK Motion Retargeting

Version 1.0 established the core real-time body-driven digital shadow-puppetry workflow. Kinect v2 skeletal data were mapped to planar digital shadow-puppet characters through a CCD-IK-based motion-retargeting process.

Core functions include:

* Kinect v2 markerless skeletal tracking;
* Real-time body-driven digital shadow-puppet control;
* Planar CCD-IK pose solving;
* Multi-character and multi-scene performance;
* Basic Windows-based interactive operation.

v1.0 建立了系统最基础的实时动捕皮影工作流程。系统通过 Kinect v2 获取人体骨骼数据，并利用平面 CCD-IK 将人体动作实时重定向至二维数字皮影角色。

其主要功能包括：

* Kinect v2 无标记人体骨骼追踪；
* 人体动作驱动数字皮影角色；
* 平面 CCD-IK 姿态求解；
* 多角色与多场景表演；
* Windows 平台实时交互运行。

### Transitional Development — Initial Performance Recording

During the transition from Version 1.0 to Version 2.0, the system began to support basic performance recording. This early implementation provided the foundation for the more complete recording, export, and media-management functions included in Version 2.0.

在 v1.0 向 v2.0 的过渡开发阶段，系统初步实现了表演录屏功能。该阶段的录制能力为 v2.0 中更加完整的视频录制、导出和媒体管理功能奠定了基础。

### Version 2.0 — Physics-Mediated Contact-Preserving Rendering

Version 2.0 extends the planar CCD-IK system by introducing a physics-mediated rendering layer. The visible shadow-puppet character follows the planar target pose while also responding to contact constraints from props, scene objects, and other characters.

Major improvements include:

* Physics-mediated character–object contact;
* Physics-mediated character–character contact;
* Visible blocking instead of direct pass-through;
* Constrained displacement during contact;
* Post-contact pose recovery;
* Collision masking;
* Contact-related audio feedback;
* Improved performance recording;
* More complete video export and media management.

v2.0 在平面 CCD-IK 动作重定向基础上，进一步加入物理介导的渲染层，使最终可见的数字皮影角色在跟随目标姿态的同时，能够受到道具、场景物体和其他角色的接触约束。

主要改进包括：

* 角色与场景道具之间的物理接触；
* 两个角色之间的物理接触；
* 以可见阻挡替代直接穿透；
* 接触过程中的受约束位移；
* 接触解除后的姿态恢复；
* 碰撞遮罩机制；
* 接触音频反馈；
* 录屏功能完善；
* 更完整的视频导出和媒体管理。

### Version 3.0 — Cloud Upload and QR-Code Sharing

Version 3.0 will extend the system from local performance production to cloud-based dissemination.

Planned functions include:

* Uploading exported performance videos to cloud storage;
* Automatic generation of shareable QR codes;
* QR-code-based access on mobile devices;
* Cross-device viewing and sharing;
* Upload progress and status feedback;
* Cloud media management;
* Improved sharing workflow.

v3.0 将在本地录制与导出基础上，进一步增加面向传播的云端功能。

计划功能包括：

* 将导出的皮影表演视频上传至云端；
* 自动生成可分享的二维码；
* 支持手机等移动设备扫码访问；
* 支持跨设备观看与分享；
* 显示上传进度与状态；
* 云端媒体内容管理；
* 优化整体分享流程。


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
