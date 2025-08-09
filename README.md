<div align="center">
  <img src="Doc/Figures/NCUST-HORIZON-LiDAR.png" alt="HORIZON 雷达组" width="300"/>
</div>


<h2 align="center">ROBOMASTER-2025 · 华北理工大学 HORIZON 战队 · 能量机关超清视频</h2>

---

## 📖 概述

<div align="left">

**数据来源：** [华北理工大学 HORIZON 战队 — 雷达组](https://github.com/BreCaspian/RoboMaster-Lidar-Lab)  
**依托平台：** [华北理工 RM 创新实验室](https://space.bilibili.com/481866846?spm_id_from=333.337.0.0)  
**录制时间地点：** ROBOMASTER 2025 超级对抗赛 · 北京理工大学（珠海）南部赛区 · 备赛区雷达站调试阶段  
**数据用途：** 适用于能量机关目标检测、旋转速度估计、视频裁剪训练等 ROBOMASTER 相关视觉任务  

</div>

> ⚠️ 说明：视频拍摄于赛前调试区，**视角与正式比赛雷达站录像不同**。数据未附带标注，请按需自行标注与裁剪。

---

## 📷 拍摄设备

| 设备类型   | 型号                            |
| ---------- | ------------------------------- |
| 相机       | 海康威视 MV-CS200-10UC 工业相机 |
| 镜头       | MVL-KF3528M-12MP                |
| 原始分辨率 | **5472 × 3648**（接近 6K）      |
| 视角       | 固定机位，雷达站视角            |

---

## 🗂️ 数据概览（4 段）

> 容器格式：**AVI**；分辨率：**5472 × 3648**（四段一致）

|            文件名             |   时长   |  大小   |   帧率   |   码率    |       备注       |
| :---------------------------: | :------: | :-----: | :------: | :-------: | :--------------: |
| `video_20250511183835100.avi` | 00:01:06 | 64.3 MB | 6.37 fps | 8145 kbps | 2025/05/11 18:38 |
| `video_20250511184035695.avi` | 00:00:29 | 28.5 MB | 6.41 fps | 8130 kbps | 2025/05/11 18:40 |
| `video_20250511184210527.avi` | 00:00:33 | 32.6 MB | 6.38 fps | 8147 kbps | 2025/05/11 18:42 |
| `video_20250511184336815.avi` | 00:00:15 | 14.7 MB | 6.41 fps | 8081 kbps | 2025/05/11 18:43 |


<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="Doc/Figures/light2GIF.gif" width="480"/>
      </td>
    </tr>
  </table>
</div>

​	🎥 能量机关展示视频：[Bilibili 视频链接](https://www.bilibili.com/video/BV1Z7t3zmEKV/?spm_id_from=333.337.search-card.all.click&vd_source=3c76eab145811dc6a99e9691ce7f2384)

---

## ⚙ 使用建议

* **按需裁剪/缩放**：原始分辨率接近 6K，建议根据任务 **先裁剪或缩放** 再训练，降低显存与 IO 压力。
* **低帧率场景**：约 6.4 fps，适合静态检测、少量插帧的跟踪或旋转速度估计。
* **背景与光照**：调试区光照与赛场不同，若用于泛化训练，建议结合额外数据或进行数据增强。

---

## 📥 数据下载

📁 **百度网盘（Baidu Netdisk）** — 🔗 [点击下载](https://pan.baidu.com/s/1Vcy1zLFrLkFdGNz09hikzA?pwd=RMer) — 提取码：`RMer`

🤗 **Hugging Face**--🔗 [ROBOMASTER-2025-Energy-Mechanism-Video](https://huggingface.co/datasets/BreCaspian/ROBOMASTER-2025-Energy-Mechanism-Video)

> 说明：该数据集为赛前调试时录制，与正式比赛雷达站机位不同；欢迎用于相关测试。

---

## 📜 许可协议

本数据集遵循 **MIT License**。使用、修改与再发布请保留来源与许可文件。

---

## 📮 联系方式

如需合作、交流或问题反馈：

📧 `yaoyuzhuo6@gmail.com`

---

<p align="right">
  —— 2025 年 8 月 9 日
</p>
