---
permalink: /
title: "README!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello. I am now living in Guangdong, ShenZhen, pursuing my Master's degree in Control Science and Engineering in **Harbin Institute of Technology(ShenZhen)**. Also,I received my bachelor's degree from HITSZ. Now I am a member of [nROS-lab](https://www.nrs-lab.com/), who is doing research and projects on Vision-Language-Action Model and Open-vocabulary Mobile Manipulation.

Education & Internship
======
- Internship: [**LimX Dynamics**](https://www.limxdynamics.com/en), Embodied AI and Manipulation Group. 2024/11--2025/04
- Master degree: Harbin Institute of Technology (Shenzhnen), Control Science and Engineering [@nROS-lab](https://www.nrs-lab.com/) 2024/09--now
- Bachelor degree: Harbin Institute of Technology (Shenzhnen), Automation [@nROS-lab](https://www.nrs-lab.com/) 2020/09--2024/06


Skills 
======
- Python ⭐⭐⭐⭐
- C++ ⭐⭐⭐
- Pytorch ⭐⭐⭐
- ROS(Robot Operating System) ⭐⭐⭐⭐
- CMake/xmake ⭐⭐⭐
- OpenGL ⭐⭐
- Some Web languages(JS/HTML/CSS) ⭐⭐

Projects
======


<table>
<td  width="45%" style="vertical-align:middle;">
     <iframe width="354px" height="225px" src="https://player.bilibili.com/player.html?isOutside=true&aid=113062933695302&bvid=BV173Hqe2EW3&cid=25694374217&p=1" scrolling="no" border="0" frameborder="0" framespacing="0"> </iframe><br/>
</td>
<td width="55%" style="vertical-align:top;">
    <big><big><strong>Apple Vision Pro Teleoperation </strong></big></big><br/>
       We implemented the Demo of <a href="https://github.com/unitreerobotics/avp_teleoperate">TeleVison</a>.
       We use the realman RM65 arm and the Inspire dexterous hand to build the experiment platform.The teleoperation system can be used to collect dual arm mobile platform joints and sensors data for imitation learning and embodied AI. Hand retargeting is solved using <a href="https://github.com/dexsuite/dex-retargeting">dexipilot</a>.The message communication is implemented by <a href="https://grpc.io">gRPC.</a> The camera streaming relys on the <a href="https://webrtc.org/?hl=zh-cn"> webrtc</a>.
</td>
</table> 

<table>
<td  width="45%" style="vertical-align:middle;">
     <iframe width="354px" height="225px" src="https://player.bilibili.com/player.html?isOutside=true&aid=114001769930414&bvid=BV1GHKKeyE1N&cid=28388295236&p=1" scrolling="no" border="0" frameborder="0" framespacing="0"> </iframe><br/></td>
<td width="55%" style="vertical-align:top;">
    <big><big><strong>LimX VGM </strong></big></big><br/>
    The embodied operation algorithm LimX VGM based on a video generation large model: By post-training the existing video generation large model with human operation video data, it requires only scene images and operation task instructions as prompts to achieve the full process of task understanding and decomposition, object manipulation trajectory generation, and robot operation execution. The entire process uses zero real-machine sample data and achieves generalization across multiple platforms. This is the first time in China that human operation data has been directly applied to robot operations.
    </td>
</table> 


<table>
<td  width="45%" style="vertical-align:middle;">
     <iframe width="354px" height="225px" src="https://player.bilibili.com/player.html?isOutside=true&aid=706447463&bvid=BV1eQ4y1t7cz&cid=1345809450&p=1" scrolling="no" border="0" frameborder="0" framespacing="0"> </iframe><br/></td>
<td width="55%" style="vertical-align:top;">
    <big><big><strong>VR Immersive Viuslization </strong></big></big><br/>
       For complex and dangerous post-disaster scenarios, sometimes the autonomous intelligence of existing robots cannot be fully relied on and manual intervention is required.We use <a href="https://github.com/hku-mars/r3live">R3LIVE</a> as the odometry and provide RGB colorful pointcloud for VR user to visualize the scene where the robot is in real time.I programm the application with OpenXR for VR development to realize high performance rendering.
    </td>
</table> 

<table>
<td  width="50%" style="vertical-align:middle;">
     <img width="100%" height="100%" src="../pics/sparklink.png"/><br/></td>
<td width="50%" style="vertical-align:top;">
    <big><big><strong>Camera Surround Stitching </strong></big></big><br/>
       首届“星闪杯”高校应用挑战赛是面向高校开发者的命题应用挑战赛，由国际星闪联盟联合多所高校联合举办。赛题为摄像头环视拼接系统的开发，在指定平台上完成无人车鸟瞰图的融合拼接，要求拼接处无明显痕迹，图像全局亮度均衡，图像无明显畸变，无明显延时，运行流畅稳定。我们使用C++进行程序开发，并且进行了多线程优化与CUDA加速，最终实现了每帧28ms的处理速度。来自哈尔滨工业大学（深圳）的1504Ders队获得了首届“星闪杯”高校应用挑战赛的全国第二名。    </td>
</table>

<table>
<td  width="45%" style="vertical-align:middle;">
     <iframe width="354px" height="225px" src="https://player.bilibili.com/player.html?isOutside=true&aid=613376126&bvid=BV1Uh4y1J7hN&cid=1124218431&p=1" scrolling="no" border="0" frameborder="0" framespacing="0"> </iframe><br/></td>
<td width="55%" style="vertical-align:top;">
    <big><big><strong>Tetris Robot </strong></big></big><br/>
    We created a robot that plays Tetris.Using a robotic arm and an RGB camera with eyes outside the hand, it picks up the Tetris blocks and places them on the plate according to the specified rules.
    </td>
</table> 



Publications
======
**Real-Time LiDAR Point Cloud Compression and Transmission for
Resource-constrained Robots.** *Yuhao Cao, Yu Wang and Haoyao Chen (ICRA2025 accepted)* [arxiv](https://github.com/ZorAttC/RCPCC) [bilibili](https://www.bilibili.com/video/BV1XrZHYqEBE/?vd_source=5afc90db9c8787a059e3d9c402d20d33) [github](https://github.com/HITSZ-NRSL/RCPCC)

------