## Awesome RoboMaster

> 有关 机甲大师 RoboMaster，DJI大疆创新以及机器人领域的资源和开源项目整理合集

- [官方资源](#%E5%AE%98%E6%96%B9%E8%B5%84%E6%BA%90)
  - [机甲大师产品](#%E6%9C%BA%E7%94%B2%E5%A4%A7%E5%B8%88%E4%BA%A7%E5%93%81)
    - [裁判系统](#%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F)
      - [裁判系统软件](#%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%BD%AF%E4%BB%B6)
      - [裁判系统用户手册](#%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C)
      - [裁判系统结构图纸](#%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E7%BB%93%E6%9E%84%E5%9B%BE%E7%BA%B8)
  - [大疆创新产品](#%E5%A4%A7%E7%96%86%E5%88%9B%E6%96%B0%E4%BA%A7%E5%93%81)
    - [妙算Manifold](#%E5%A6%99%E7%AE%97manifold)
    - [遥控器](#%E9%81%A5%E6%8E%A7%E5%99%A8)
- [开源项目](#%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE)
  - [能量机关](#%E8%83%BD%E9%87%8F%E6%9C%BA%E5%85%B3)

# 官方资源

## 机甲大师产品

### 裁判系统

#### 裁判系统软件
- [服务器和客户端程序](https://www.robomaster.com/zh-CN/products/components/referee)
- [RoboMaster Assistant](https://www.robomaster.com/zh-CN/products/components/assistant) - 裁判系统固件升级程序
- [RoboMaster Tools](https://cdn-hz.robomaster.com/tem/b0dc2704127871521423958643262343.zip) - 图传接收机手动调频工具

#### 裁判系统用户手册
- [主控模块MC01](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E4%B8%BB%E6%8E%A7%E6%A8%A1%E5%9D%97MC01%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf) - 车载型裁判系统主控
- [主控模块（轻型）MC11](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E4%B8%BB%E6%8E%A7%E6%A8%A1%E5%9D%97(%E8%BD%BB%E5%9E%8B)MC11%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf) - 机载型裁判系统主控
- [装甲模块AM01及AM11](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%A3%85%E7%94%B2%E6%A8%A1%E5%9D%97AM01%E5%8F%8AAM11%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [相机图传模块](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E7%9B%B8%E6%9C%BA%E5%9B%BE%E4%BC%A0%E6%A8%A1%E5%9D%97%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [测速模块SM01及SM11](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E6%B5%8B%E9%80%9F%E6%A8%A1%E5%9D%97SM01%E5%8F%8ASM11%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [场地交互模块FI01](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E5%9C%BA%E5%9C%B0%E4%BA%A4%E4%BA%92%E6%A8%A1%E5%9D%97FI01%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [主控开发板](https://cdn-hz.robomaster.com/tem/RM%E5%BC%80%E5%8F%91%E6%9D%BF-%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C.pdf) - 俗称信仰板，已停产
- [开发板](https://cdn-hz.robomaster.com/tem/RoboMaster%E5%BC%80%E5%8F%91%E7%89%88%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C.pdf) - 2018新款，此手册包含 A 、 B 、 OLED 三个模块的所有使用手册内容
- [开发板原理图&位号图](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E5%BC%80%E5%8F%91%E6%9D%BF%E5%8E%9F%E7%90%86%E5%9B%BE&%E4%BD%8D%E5%8F%B7%E5%9B%BE.zip)
- [开发板线材包物品清单](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E5%BC%80%E5%8F%91%E6%9D%BF%E7%BA%BF%E6%9D%90%E5%8C%85%E7%89%A9%E5%93%81%E6%B8%85%E5%8D%95.pdf)

#### 裁判系统结构图纸
- [主控模块MC01](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E4%B8%BB%E6%8E%A7%E6%A8%A1%E5%9D%97MC01-STEP.STEP) - 车载型裁判系统主控
- [主控模块（轻型）MC11](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E4%B8%BB%E6%8E%A7%E6%A8%A1%E5%9D%97%EF%BC%88%E8%BD%BB%E5%9E%8B%EF%BC%89MC11-STEP.STEP) - 机载型裁判系统主控
- [装甲模块AM01](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%A3%85%E7%94%B2%E6%A8%A1%E5%9D%97AM01-STEP.STEP) - 俗称小装甲
- [装甲模块AM11](https://cdn-hz.robomaster.com/tem/RoboMaster%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%A3%85%E7%94%B2%E6%A8%A1%E5%9D%97AM11-STEP.STEP) - 俗称大装甲
- [相机图传模块（发送端）VT01](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E7%9B%B8%E6%9C%BA%E5%9B%BE%E4%BC%A0%E6%A8%A1%E5%9D%97%EF%BC%88%E5%8F%91%E9%80%81%E7%AB%AF%EF%BC%89VT01-STEP.STEP) - 车 / 机载图传系统发射端
- [测速模块SM01](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E6%B5%8B%E9%80%9F%E6%A8%A1%E5%9D%97SM01-STEP.STEP) - 17mm 测速模块
- [测速模块SM11](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E6%B5%8B%E9%80%9F%E6%A8%A1%E5%9D%97SM11-STEP..STEP) - 42mm 测速模块
- [场地交互模块FI01](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E5%9C%BA%E5%9C%B0%E4%BA%A4%E4%BA%92%E6%A8%A1%E5%9D%97%20FI01-STEP.STEP)
- [装甲支撑架（A型）](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%A3%85%E7%94%B2%E6%94%AF%E6%92%91%E6%9E%B6%EF%BC%88A%EF%BC%89-STEP.STEP) - 随裁判系统主控提供的支撑架
- [装甲支撑架（B型）](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E8%A3%85%E7%94%B2%E6%94%AF%E6%92%91%E6%9E%B6%EF%BC%88B%EF%BC%89-STEP.STEP) - 独立安装的支撑架
- [定位模块](https://cdn-hz.robomaster.com/tem/RoboMaster%20%E8%A3%81%E5%88%A4%E7%B3%BB%E7%BB%9F%E5%AE%9A%E4%BD%8D%E6%A8%A1%E5%9D%97%EF%BC%88%E6%A0%87%E7%AD%BE%EF%BC%89-STEP.STEP)

## 大疆创新产品

### 妙算Manifold
- [wqf233333/DJI-SDK-SKILL](https://github.com/wqf233333/DJI-SDK-SKILL) - FAQ for Onboard SDK , Guidance SDK, Manifold

### 遥控器
- [DJI DT7 Remote Controller Driver for Windows](https://cdn-hz.robomaster.com/tem/3e8726fd06d4a1517404291621742928.7z)


# 开源项目

## 能量机关
 - [gezp/RoboMasterMarkSim](https://github.com/gezp/RoboMasterMarkSim) - 电科成开源的能量机关模拟器(麦克风判定，无 LED 数码管和侧边进度指示灯模拟)