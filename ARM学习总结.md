## ARM概述
1. ARM V7与V8A
2. 

## ARM架构综述
1. ARM处理器状态  
> PSR
* 
* 
* 
*   
> PSTATE
* 
* 
* 
* 

2. ARM处理器模式
3. 
4. 

#### 测试工具(qemu)
1. 
2. 
3. 
4. 

#### 特权模式
1. 身在何处：处理器状态(PSR和PSTATE)
* 
* 
* 
2. 不同级别的差异：System control register
3. 异常切换 
4. 异常切换一用
5. 

#### 异常切换
1. 分成L0，L1，L2，L3四层，分别对应
2. 中断是一种异常
3. SYNC异常
* 
* 
* 
* 
4. IRQ 异常
5. FIQ 异常
6. System Error 异常

#### 寄存器
1. 

#### 指令集
1. 

#### 架构综述
1. 特权模式
2. 

#### 条件指令优缺点
1. Pros
* 较小代码大小
* 改善性能(尤其是无分支预测时)
2. Cons
* 增加指令依赖难以乱序执行
* 有分支预测的处理器上性能改善很小
3. 

#### system register(站在这里理解不同特权级别)
1. 
2. 
3. 
4. 

#### ARMv8 PSTATE
1. 
2. 
3. 
4. 

#### 特权级别高不一定能做更多事情
1. EL1是能做事情最多的特权级别
2. EL2，EL3更少
3. 

#### 异常进入与退出
1. 现场保护和恢复
2. 哪些硬件做哪些软件做

## ARM内存管理
1. MMU
> MMU起什么作用  
* 虚拟地址到物理地址的转换
> 页表  
* 平映射
* 1：1映射
* 一级页表
* 二级页表
* 
* 
> stage and level
> 32,64内存划分
> memory atttribute
2. Cache
* 
* 
* 
* 
3. TLB
* 
* 
* 

4. memory区域划分
* 
* 
* 

## 分支预测
1. 
2. 
3. 

## 参考资料
1. 《ARM体系结构与编程》
2. 《ARM视频课程》 张健
3. 官方文档路径
4. 

## CLIDR
1. 
2. 
3. 
4. 

## SIMD & NEON 模块
1. 
2. 
3. 

## ARM 安全方面
1. 
2. 
3. 

## TrustZone架构
1. 
2. 
3. 

## SMC
1. 
2. 
3. 

## 中断与时钟
1. 
2. 
3. 中断类型
> SGI  
* 
* 
* 
* 
> PPI
> SPI
> LPI
4. GIC编成模型
> 状态机
* 
* 
> GICC，GICR，GICD
* 
* 

## Timer
> 时钟源和Timer的关系
* 
* 
* 
> system level和pre-cpu timer
* 
* 
* 
> programming model
* 
* 

## SMP

## 内存进阶
