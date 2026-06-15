# OSPF v2 Interactive Demo

这是 `ospf-v2` 项目的公开前端展示仓库。

- Demo 地址：<https://1205240810.github.io/ospf-v2-demo/>
- 进度说明：<https://1205240810.github.io/ospf-v2-demo/progress.html>
- 真实项目源码仓库保持私有；本仓库只发布静态展示文件。

## Demo 边界

- 页面保留拓扑编辑、平台/RF、运行验收等前端交互。
- 保存、自动规划、应用拓扑、下发配置、Ping、导出 YAML 都走浏览器本地模拟数据。
- Demo 不连接真实 FastAPI、host-agent、OVS、Docker、QEMU 或物理网卡。
- 真实部署仍需要 Linux 宿主机上的 controller Docker + host-agent + OVS/Docker/QEMU。

## 当前重点

- x86 混合拓扑已经完成基础验证。
- 下一步需要采购/准备 ARM64 Linux 主机，验证 Docker-only profile、OVS、host-agent、FRR/PC 容器和现场部署流程。
