# 可视化物流仿真平台 · 演示 MVP

湖州师范学院电子信息（计算机技术）专业实践演示页：四向穿梭车立体库的 Web 原型。算法和调度在浏览器里实时运行，订单与库存为模拟数据，不对接企业现网。

实践单位：浙江中匠智能装备有限公司  
对应报告：基于 Unity3D 构建可视化物流仿真动画平台

## 在线演示

- 仓库：https://github.com/zhanghui949493354/visual-logistics-sim-mvp
- 网页：https://zhanghui949493354.github.io/visual-logistics-sim-mvp/

## 本地打开

1. 下载或克隆本仓库
2. 用 Chrome / Edge 直接打开 `index.html`
3. 点「开始演示」，再点「演示 12 单」

也可在本目录执行：

```bash
npx serve .
```

然后访问 http://localhost:3000

## 演示里有什么

- 三层立体库等距视图（1F / 2F / 3F 平铺）
- 两台四向穿梭车，A* 寻路（含换向代价）
- 入库 / 出库 / 移库任务调度
- KPI：完成率、平均等待、冲突次数
- 模拟货位 / 车辆 / 任务表

## 说明

这是专业实践的 **HTML 收口演示**，不是 Unity 工程，也不是生产 WMS/WCS。现场设备未接入。
