# Monthly Meeting


### 2020.10.10
在热烈而又友好的氛围下，上海SIGGPU小组在2020.10.10顺利成立，本小组的宗旨是：分享交流GPU相关知识，促进各小组成员发论文，发专利，评职称。

现小组成员如下：(排名不分先后)
- GPU-Compiler : Echo Liu , Declan Huang , Xuedi Wang , Zhiqian Xia
- GPU-Driver-DirectX : Zhongjian Cao , Sybil Yi ,  Skye Wang
- GPU-Driver-OpenGL : Wenke Zhao , Cookie Xu


### 2020.11.10
本次会议共有1篇报告，小组成员一起讨论了图形学学术科研工具 Mitsuba ，这是一款基于PBR的离线渲染器，它拥有许多图形学基本插件(轮子)，学术论文常使用它快速构建算法模型，验证最终的实现，
    
|  报告编号   |  报告人  |    报告题目  |
|  ----  | ----  |  ----  |
| 1  | Zhiqian Xia | 浅谈 Mitsuba-2:A Retargetable Forward and Inverse Renderer|
   

### 2020.12.10
- 本次会议共有2篇报告，

在本次会议Zhongjian Cao 带领大家复习并讨论了光线追踪理论 Part 1：光线与场景中物体求交的基本算法，
内容包括 Whitted-Style Ray Tracing 和 Acceleration structure. 核心知识点有以下几点：
1. 光线与常见几何物体求交方法
2. Axis-Aligned Box Bounding
3. Spatial Partitions (Kd-tree) and Object Partitions (BVH)

- Zhiqian Xia 为大家整理了一些加速光线与物体求交算法的思路，如 BVH 压缩，SIMD加速，MBVH ,Ray排序。 

|  报告编号   |  报告人  |    报告题目  |
|  ----  | ----  |  ----  |
| 1  | Zhongjian Cao | GAMES101_Lecture_13 && GAMES101_Lecture_14 |
| 2  | Zhiqian Xia | Faster，Higher，Stronger |



### 2021.1.10
本次会议主要内容如下：

1.《光线追踪原理2：渲染方程》 ZhiqianXia  Xuedi Wang  Declan Huang. 核心知识点有以下几点：
- 渲染方程建立
- BRDF项意义
- 蒙特卡洛求渲染方程

2.《光线追踪 DirectX API》: Skpe Wang 核心知识点有以下几点：
- raytracing 流程
- 5类新shader : 3 个必选 ： ray generation shader , closest-hit shader , miss shader ， 2个可选 : any-hit (透明物体) ， intersection shader (自定义Primitive)

3.《光线追踪 Vulkan API》: Wenke Zhao
- 流程基本与DirextX 一致 ， 但是有些setting up 工作，可以放到Host-CPU 处理。 

4.讨论接下来3个月的文献任务，大家从自己感兴趣的子主题里面，继续深入研究。
- Intersections and Efficiency    ： Zhongjian Cao && Declan Huang 
- Reflections, Refractions, and Shadows  ： Echo Liu && Cookie Xu
- Sampling  :  Zhiqian Xia && Wenke Zhao
- Denoising and Filtering  : Xuedi Wang && Skye Wang

### 2021.2.10
春节临近，事务繁忙，本次聚会取消.


### 2021.3.10