# 其他项目

## 项目列表

### 计算机图形学项目

Computer Graphics Projects

- **Github链接：** https://github.com/wmFrank/intro-graphics-projects
- **说明：** 一系列项目，来自于一门很好的在线课程：[GAMES101: Introduction to Computer Graphics](https://games-cn.org/intro-graphics/)，由[闫令琪](https://sites.cs.ucsb.edu/~lingqi/)教授授课
- **编程语言：** C/C++, HTML, JavaScript
- **证书:**

    <img src="https://user-images.githubusercontent.com/30235642/176627583-6acf8a61-bd66-4959-b76a-80fb2415e709.png" alt="MW(en)" width="500"/>

- **结果：**

    > Z-缓冲和抗锯齿

    | <img src="https://user-images.githubusercontent.com/30235642/176399741-c530cbb3-f06e-450a-a172-2504da357fea.png" alt="base_image" width="300" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/176403303-1ad2c2a8-8872-4d7e-b611-40650fbfca65.png" alt="image_improve" width="300" height="300"/> |
    | ----------- | ----------- |
    | Z-缓冲渲染的三角形 | 使用超级采样抗锯齿进行改进 |

    > Blinn-Phong着色器和纹理着色器

    | <img src="https://user-images.githubusercontent.com/30235642/176619825-7d27712c-50ac-4dc3-887b-7be2753bf3de.png" alt="phong" width="300" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/176619865-d29983b8-360d-4e06-acce-e412411c6a2b.png" alt="texture" width="300" height="300"/> |
    | ----------- | ----------- |
    | Blinn-Phong着色器渲染的奶牛 | 纹理着色器渲染的奶牛 |

    > 光线追踪

    | <img src="https://user-images.githubusercontent.com/30235642/176623977-f15625df-c544-44a6-8b47-10ad51221d00.png" alt="raytracing" width="300" height="300"/> |
    | ----------- |
    | 采用Moller-Trumbore相交算法的光线追踪 |

    > BVH和SAH加速结构

    | <img src="https://user-images.githubusercontent.com/30235642/176625299-f2dca66a-e682-470b-9b59-40eb8d68f8b7.png" alt="binary_naive" width="300" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/176625323-8151715f-9893-4fcd-b05e-4b938ef4d214.png" alt="binary_sah" width="300" height="300"/> |
    | ----------- | ----------- |
    | Bounding Volume Hierarchy(BVH): 7.84s | Surface Area Heuristic(SAH): 6.39s |

    > 路径追踪

    | <img src="https://user-images.githubusercontent.com/30235642/176627091-c3023c0a-f1d3-4e75-8dde-616857c7d88b.png" alt="cornell_box" width="300" height="300"/> |
    | ----------- |
    | 路径追踪渲染的Cornell Box |

---

### 图像处理项目

Image Processing Projects

- **Github链接：** https://github.com/wmFrank/image-processing-projects
- **说明：** 关于直方图均衡化、边缘检测、边缘连接、数字识别的项目
- **编程语言:** Matlab
- **结果:**

    > 直方图均衡化

    | <img src="https://user-images.githubusercontent.com/30235642/177032193-317f2106-9c48-4bd0-bf62-d96e16a76314.jpeg" width="400" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/177032197-c35adb9b-4d75-4fd3-8604-ee21d99adf13.png" width="400" height="300"/> | 
    | ----------- | ----------- |
    | 输入 | 输入的直方图 |
    <img src="https://user-images.githubusercontent.com/30235642/177032402-3d99dec0-33df-48ee-9100-242355d41cc8.jpeg" width="400" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/177032403-24230d84-b1e3-492d-b144-c95c169903ba.png" width="400" height="300"/> | 
    | 输出 | 输出的直方图 |

    > Canny算子边缘检测和边缘链接

    | <img src="https://user-images.githubusercontent.com/30235642/177032527-40f98daf-2075-44b6-a243-dfb72b12dcbb.png" width="350" height="250"/> | <img src="https://user-images.githubusercontent.com/30235642/177032532-5010b2d6-761b-43e5-a402-7012157660ef.png" width="350" height="250"/> | <img src="https://user-images.githubusercontent.com/30235642/177032537-2c28ce8c-54f5-4787-a72c-2f886f1e555c.png" width="350" height="250"/> | 
    | ----------- | ----------- | ----------- |
    | 输入 | 边缘检测后的输出 | 边缘链接后的输出 |

---

### 图像拼接

Image Stitching

- **Github链接：** https://github.com/wmFrank/image-stitching
- **描述：** 图像拼接的一种实现
- **编程语言:** Matlab
- **技术：** VLFeat, Ransac
- **结果:**

    | <img src="https://user-images.githubusercontent.com/30235642/177033247-c350539e-2a70-41f4-9bb5-010123fa8ab0.jpeg" width="500" height="300"/> | <img src="https://user-images.githubusercontent.com/30235642/177033244-a40a0b08-d755-4a72-beda-bbf00b1bedd8.jpeg" width="500" height="300"/> |
    | ----------- | ----------- |
    | 输入1 | 输入2 |

    | <img src="https://user-images.githubusercontent.com/30235642/177033249-91d5aa7a-0176-4402-bc6a-86b72d822ef5.png" width="600" height="360"/> |
    | ----------- |
    | 输出 |

---

### 基于线采样的蒙特卡洛渲染

Monte Carlo Rendering based on Line Sampling

- **Github链接：** https://github.com/wmFrank/line-sampling-rendering
- **说明：** 基于线采样的蒙特卡洛渲染的实现，具有面光源处理、路径追踪、多线程加速、微表面材质等功能支持。
- **编程语言：** C++
- **技术：** CMake

---

### 图像爬取和处理

Images Crawling and Processing

- **Github链接：** https://github.com/wmFrank/image-crawl-and-process
- **说明：** 用requests爬取图像，用OpenCV处理的图像
- **编程语言：** Python, C/C++
- **技术：** requests, OpenCV, Bloom filter

---

### 葫芦兄弟

Calabash Brothers

- **Github链接：** https://github.com/wmFrank/Calabash-Brothers
- **描述：** 基于Java的图形游戏--《葫芦兄弟》
- **编程语言:** Java
- **技术:** JavaFX, Maven
- **结果:**

    > 游戏界面：

    <img src="https://user-images.githubusercontent.com/30235642/177749007-3cf710b7-58be-4f6a-be28-fd523d7524ee.gif" width="800"/>

---

### 基于Qt的画板

Qt Canvas

- **Github链接：** https://github.com/wmFrank/simple-canvas
- **描述:** 一个具有一系列绘画功能的画板的Qt实现
- **编程语言:** C++
- **技术:** Qt, QMake
- **结果:**

    > 画板展示：

    <video width="800" controls><source src="https://user-images.githubusercontent.com/30235642/177096432-15035c6d-f511-4342-9429-b3de3f4ffd68.mp4" type="video/mp4"></video>

---

### 金庸小说中的人物关系挖掘

Relationships Mining in Jin's Novels

- **Github链接：** https://github.com/wmFrank/relationships-mining
- **描述：** 关于挖掘金庸小说中人物关系的大数据处理项目
- **编程语言：** Java, Scala, Python
- **技术:** MapReduce, Hadoop, Spark, Hive, HBase
- **结果：**
    
    > 人物关系图

    | <img src="https://user-images.githubusercontent.com/30235642/177063489-16a6f282-4db0-42a7-8f66-8bb8202a906e.png" width="500" height="350"/> | <img src="https://user-images.githubusercontent.com/30235642/177063493-54e8593d-c7aa-4a4d-90f2-ea19d7c5dfbb.png" width="500" height="350"/> |
    | ----------- | ----------- |
    | 通过Gephi实现可视化 |

---

### 学生信息管理系统

Student Information Management System

- **Github链接：** https://github.com/wmFrank/simple-student-admin-system
- **描述：** 基于MFC框架的简单学生信息管理系统的实现，支持添加、删除、排序、数据I/O、数据高亮
- **编程语言：** C/C++
- **技术:** Microsoft MFC
- **结果:**

    <video width="800" controls><source src="https://user-images.githubusercontent.com/30235642/177220129-a70079e4-b64d-481b-8d78-62643af0129f.mp4" type="video/mp4"></video>

---

### 简单的计算机系统

Simple Computer System

- **Github链接：** https://github.com/wmFrank/simple-computer-system
- **说明：** 基于i386框架的简单计算机系统的实现
- **编程语言:** C
- **技术:** Linux

---

### 操作系统项目

Operating System Projects

- **Github链接:** https://github.com/wmFrank/simple-operating-system
- **说明：** 一系列关于汇编语言编程、ELF加载器和系统调用、进程切换和调度、信号灯和多线程的项目
- **编程语言：** C、Assembly

---

### 图灵机模拟

Turing Machine Simulation

- **Github链接：** https://github.com/wmFrank/simple-turing-machine
- **描述：** 简单的图灵机的实现，用来判断一些字符串是否属于某种特定的语言
- **编程语言:** C++

---

### 计算机网络项目

Computer Networks Projects

- **Github链接：** https://github.com/wmFrank/computer-networks-projects
- **说明：** 一系列关于网络拓扑结构、原始套接字编程、子网和NAT、静态路由、VPN构建的项目
- **编程语言：** C/C++
- **技术：** Linux, Wireshark

---

### 数据库项目

Databases Projects

- **Github链接：** https://github.com/wmFrank/databases-projects
- **说明：** 一系列关于MySql基本操作、约束性数据库、第三方工具操作数据库的项目
- **编程语言：** MySQL, Java
