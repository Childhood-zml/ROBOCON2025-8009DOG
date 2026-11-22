# ROBOCON2025\-8009DOG

[![English README](https://img.shields.io/badge/English-d9d9d9)](./README_EN.md)
[![简体中文 README](https://img.shields.io/badge/简体中文-d9d9d9)](./README.md)

> Open\-source sorting for the 2025 Robocon quadruped robot \(Team 2\) project of Suzhou University of Technology
> 
> 

## Introduction

This repository archives and organizes the software, control schemes and supporting materials for **Team 2, Suzhou University of Technology, Robocon 2025 quadruped robot**\. The 2025 season marked our university’s debut at the Robocon competition, which carries great commemorative significance\.

> Note: I am a member of the electronic control team for the 2026 season and did not participate in the development work of the 2025 season\. No functional modifications have been made to the original code in this repository\. I only perform archiving, sorting and reorganization, aiming to provide ideas and references for other competing teams\.
> 
> 

2025 Season Results: **National Second Prize for all three events**

Core Technical Directions:

- Quadruped robot motion control

- Body position control

- Mini gyro mode, IKUN mode \(for entertainment only\)

## Demonstration

Bilibili:

- [RC Equestrian Competition \(Equestrian Group Evaluation Video\) \- Work No\.22](https://www.bilibili.com/video/BV1bob8zoEhs/?spm_id_from=333.337.search-card.all.click&vd_source=4f07d0682bac8028161eae946482de58)

- [Top 10 RC Equestrian Robots 25 \- No\.10](https://www.bilibili.com/video/BV171ekzHEKm/?buvid=XU7BB1878C6E81B10B2D7EEE992B78A7A5B3A&from_spmid=search.search-result.0.0&is_story_h5=false&mid=fZWlB3a2%2BVuaZQOcvtVIO38FTQ%2FSZMtL1rElX6M3iMo%3D&plat_id=114&share_from=ugc&share_medium=harmony&share_plat=harmony&share_session_id=926ee987-9284-49f2-bf1d-f34ad3fde5d3&share_source=COPY&share_tag=s_i&timestamp=1785136631&unique_k=CK9V9rV&up_id=447311406&vd_source=4f07d0682bac8028161eae946482de58)

- [Team R\&A Takes on Robocon and Wins National Second Prize](https://www.bilibili.com/video/BV1jAtZzyECV/?spm_id_from=333.1387.upload.video_card.click&vd_source=4f07d0682bac8028161eae946482de58)

- [Team R\&A Takes on Robocon and Wins National Second Prize](https://www.bilibili.com/video/BV1c9tozDEPm/?spm_id_from=333.1387.upload.video_card.click)

Live Photo Album:

- [https://m\.alltuu\.com/album/2123300604/?from=qrCode\&menu=live](https://m\.alltuu\.com/album/2123300604/?from=qrCode\&menu=live)

## Repository Directory Structure
| Directory | Description |
| --- | --- |
| `1.Software/` | Full lower computer (STM32F427, Keil uVision project: [`robohorse2022.uvprojx`](./1.Software/DM8009DOG/project_8009/robohorse2022/MDK-ARM/robohorse2022.uvprojx)，The test_project folder has relevant libraries you can refer to.)|
| `2.Document/` | Documents and manuals (PDF) |
| `3.Video/` | Videos |
| `3.Images/` | Competition photos |
| `assets/` | README image assets |


## Quick Start

### Lower Computer Keil Project

Open [`1.Software/DM8009DOG/project_8009/robohorse2022/MDK-ARM/robohorse2022.uvprojx`](https://github.com/Childhood-zml/ROBOCON2025-8009DOG/blob/main/1.Software/DM8009DOG/project_8009/robohorse2022/MDK-ARM/robohorse2022.uvprojx)

> Recommended Environment: Keil uVision5, compatible with STM32F427, matched with DM 8009 motor driver
> 
> 

## Important Statement

Since the organizer of this repository is not an original developer of the 2025 season, some original design documents, debugging logs and internal notes are missing, and the arrangement of materials may not be well\-organized\. We appreciate your understanding\.

If you have any questions, feel free to discuss via Issues\.

## Acknowledgements \& Open\-source References

Special thanks to Ningbo University of Engineering for their open\-source projects referenced in our scheme:

- [https://gitee\.com/Ha\-WthorN/robocon\-nbut](https://gitee.com/Ha-WthorN/robocon-nbut)

- [https://gitlab\.com/nbutroboticslab/Competition\_Projects/robocon/robocon2022](https://gitlab.com/nbutroboticslab/Competition_Projects/robocon/robocon2022)

Repository document framework references:

- [https://blog\.csdn\.net/weixin\_52612260/article/details/134124028](https://blog.csdn.net/weixin_52612260/article/details/134124028)

- [https://blog\.csdn\.net/Hbutneymar/article/details/147161479](https://blog.csdn.net/Hbutneymar/article/details/147161479)

Reference Materials:

- [【必读】LocoWiki介绍](https://lain-database.feishu.cn/wiki/HwyJwB70niKbW7khmwlcbCH2nXb)

## License Statement

There is no `LICENSE` file attached to this repository for the time being\. Please contact the author to confirm the scope of authorization before using the content in papers or commercial projects\.

