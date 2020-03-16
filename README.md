# Awesome Service Mesh

Service Mesh 又译“服务网格”，本站创建并维护这份Awesome Service Mesh资料清单供大家交流学习。

资料内容来自国内外公开媒体，转载时我们会指明出处，标注原作者和原译者，如果是原创或者原创翻译也会标明作者或者译者身份。

- [Service Mesh](#servicemesh)
- [Istio](#istio)
- [Conduit](#conduit)
- [Consul](#consul)
- [Envoy](#envoy)
- [Linkerd](#linkerd)
- [Nginmesh](#nginmesh)
- [Aspenmesh](#aspenmesh)
- [华为ServiceMesher](#华为)
- [新浪微博MotanMesh](#MotanMesh)
- [腾讯ServiceMesh](#tencent)
- [UCloud](#ucloud)
- [Meshery](https://meshery.io/)

## ServiceMesh

### 文章

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2018-06-11 | [The Enterprise Path to Service Mesh Architectures](https://layer5.io/books/the-enterprise-path-to-service-mesh-architectures) | Lee Calcote | - | - |
| 2018-05-20 | [Service Mesh：重塑微服务市场](https://www.servicemesher.com/blog/service-mesh-rebuild-microservice-market/)![](images/new_red.png) | 敖小剑   | - | 南京全球技术周互联网技术架构论坛 |
| 2018-1 |   [解读2017之Service Mesh：<br>群雄逐鹿烽烟起](https://mp.weixin.qq.com/s?__biz=MzIwMzg1ODcwMw==&mid=2247487273&idx=1&sn=f654a9a8cb85d8cf2d06e469585cce8a&chksm=96c9b949a1be305f3eaa18e3fcb29cf66b4f51f37869e7ccd8c080a8ded8f4ecfe78e3de8ac6&mpshare=1&scene=1&srcid=1227PrB5dA8Hr3CHPv6B9PEN&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd)  | 敖小剑   | - | Infoq年度总结系列文章 |
| 2017-12 |   [山雨欲来风满楼：<br>Service Mesh时代的选边与站队](https://mp.weixin.qq.com/s?__biz=MzU0MTMyMDg1NQ==&mid=2247483697&idx=1&sn=b5fdd3af4ae352942820cec9280257c3&chksm=fb2af2c9cc5d7bdf05b7a58ba9120f4390de52c9c74e3d5e6932ca6b9367677234dbf8af06c1&mpshare=1&scene=1&srcid=1220gyaL6UP5ZUFpMn0UgPke&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd)  | 敖小剑   | - | 北京meetup演讲实录 |
| 2017-10 |   [Service Mesh：下一代微服务](https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652136254&idx=1&sn=bba9bbd24ac8e5c1f6ef5d1125a6975b&chksm=84d53304b3a2ba12f88675c1bf51973aa1210d174da9e6c2ddcd1f3c84ec7e25987b3bce1071&mpshare=1&scene=1&srcid=1020GPmfbEVP9QDNlZBHg47I&pass_ticket=vR63tjXqn9DTRAEWRKRMIB8O1ybqCamYyCza7%2BE5YRJRfpf%2F5OwphFKHGOiDiS6u#rd)  | 敖小剑   | - | QCON演讲实录 |
| 2017-08|   [Pattern: Service Mesh](http://philcalcado.com/2017/08/03/pattern_service_mesh.html)  | Phil Calçado | [模式之服务网格](http://www.infoq.com/cn/articles/pattern-service-mesh?from=awesome-servicemesh) | 详细介绍Service Mesh模式和演进过程，强烈推荐 |
| 2017-08 |  [Application Network Functions With ESBs, API Management, and Now.. Service Mesh?](http://blog.christianposta.com/microservices/application-network-functions-with-esbs-api-management-and-now-service-mesh/)  | Christian Posta   | [应用网络功能，EBS，API管理，而现在..Service Mesh?](https://mp.weixin.qq.com/s?__biz=MzI5MDEzMzg5Nw==&mid=2660396277&idx=1&sn=e3fd0e49b4947e80fbfd3cdd781bad96&chksm=f7424e13c035c705401b08795eb5c494cd1001c39760bc603c377f550f999d5dc8355229b2f9&mpshare=1&scene=1&srcid=1108KXT47jsSir7gXXN7x1yj&pass_ticket=5n8O9dw5nrNWdp91I1Ex8q0wFqwN7oHELYvWuTB%2BJGXvmM0y3ASvIhOn%2FU9zG29J#rd)  | - |
| 2017-07| ![](images/ppt.png)  [O'Reilly 2017: "Introduction to Service Meshes"](https://www.slideshare.net/dbryant_uk/oreilly-2017-introduction-to-service-meshes)  | Daniel Bryant | [PPT的中文版本](https://github.com/thomaslwq/publicfiles/tree/master) | 演讲的PPT |
| 2017-04|   [What’s a service mesh? And why do I need one?](https://buoyant.io/2017/04/25/whats-a-service-mesh-and-why-do-i-need-one/)  |  William Morgan  | [什么是服务网格以及为什么我们需要服务网格？](http://www.infoq.com/cn/news/2017/11/WHAT-SERVICE-MESH-WHY-NEED) | 应该是业界第一篇详细介绍Service Mesh理念的文章，强烈推荐 |

## Istio

### 文档

- [istio官方文档中文版](https://preliminary.istio.io/zh/)

### 工具

- [istio-service-mesh-workshop](https://github.com/layer5io/istio-service-mesh-workshop)
- [在线体验istio](https://katacoda.com/courses/istio/): 实测可用
- [istio-workshop](https://github.com/retroryan/istio-workshop)

### 文章

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2018-6 | [Istio: Up and Running](https://layer5.io/books/istio-up-and-running)  |  Lee Calcote, Zack Butcher  | - | - |  
| 2017-11 | ![](images/ppt.png) [8 Steps to Becoming Awesome with Kubernetes](https://docs.google.com/presentation/d/1ij64THksTygvifW5BD-n0ipc6MDF4cGBRQcV3BRYaoM/edit#slide=id.g12c8aac1e6_0_890)   | Burr Sutter  | - | [PPT国内下载（免翻墙）](http://www.servicemesh.cn/?/article/11?notification_id=34&item_id=4) |
| 2017-10 |  [Kubernetes, Microservices, and Istio  — A Great Fit!](https://thenewstack.io/kubernetes-microservices-istio%E2%80%8A-%E2%80%8Aa-great-fit/)  | Animesh Singh  | - | - |
| 2017-09 |   [什么是Service Mesh（服务网格）](https://jimmysong.io/posts/what-is-a-service-mesh/)  |  宋净超  | - | - |
| 2017-09 |   [服务网格新生代--Istio](https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652136078&idx=1&sn=b261631ffe4df0638c448b0c71497021&chksm=84d532b4b3a2bba2c1ed22a62f4845eb9b6f70f92ad9506036200f84220d9af2e28639a22045&scene=21#wechat_redirect)  | 敖小剑   | - | 线上分享实录 |
| 2017-09|   [What is Istio? It’s a service mesh. Great. What’s a service mesh?](https://www.mirantis.com/blog/what-is-istio-its-a-service-mesh-whats-a-service-mesh/)  |  Nick Chase  | [什么是Istio? 它是服务网格。棒极了，那什么是服务网格？](https://my.oschina.net/u/2562868/blog/1563506)  | 访谈录 |
| 2017-05|  [Google, IBM and Lyft launch Istio, an open-source platform for managing and securing microservices](https://techcrunch.com/2017/05/24/google-ibm-and-lyft-launch-istio-an-open-source-platform-for-managing-and-securing-microservices/?utm_source=tuicool&utm_medium=referral)   |  Frederic Lardinois   | [Istio开源平台发布，Google、IBM和Lyft分别承担什么角色？](https://www.leiphone.com/news/201705/RwRlyAs7Mi8pqhSb.html) | - |
| 2017-05|  [Google, IBM, Lyft partner on open source microservices management platform Istio](https://www.techrepublic.com/article/google-ibm-lyft-partner-on-open-source-microservices-management-platform-istio/)   |  Conner Forrest   | - | _ |
| 2017-11 | [一个商用级Service Mesh服务的设计之道](https://blog.csdn.net/karamos/article/details/80133231)   | 田晓亮  | - | [相关PPT](http://servicecomb.incubator.apache.org/assets/slides/20171209/PracticeOfServiceMeshOnHuaweiPublicCloud.pdf) |


## Conduit

### 文档

- [conduit官方文档](https://conduit.io/)

### 文章

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2018-07-06 | [Conduit 0.5.0 and the future of Conduit](https://blog.conduit.io/2018/07/06/conduit-0-5-and-the-future/) | [Oliver Gould](https://blog.conduit.io/author/oliver/) | [Conduit 0.5 发布 —— 以及 R.I.P. Conduit](Conduit 0.5 发布 —— 以及 R.I.P. Conduit) | Conduit最后一个版本，将合并入Linkerd 2.0 |
| 2017-12 |   [Conduit AMA session recap](https://buoyant.io/2017/12/27/conduit-ama-session-recap/) ![](images/new_red.png) | George Miranda | [Conduit AMA 活动回放](https://mp.weixin.qq.com/s?__biz=MzIxMDY5ODM1OA==&mid=2247483950&idx=1&sn=9c1ac2317a744f4071b14f9e1575558b&chksm=9761eb37a0166221de9827ff430e6ee3d164e73145d42009f5f6f4d9f4146deb0899524b894d&mpshare=1&scene=1&srcid=0101VEm8cn0KyNSem88rXHPU&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd) | 介绍conduit项目的各种情况 |
| 2017-12 |   [Introducing Conduit](https://buoyant.io/2017/12/05/introducing-conduit/) | William Morgan | [Conduit 登场](https://blog.fleeto.us/post/conduit-ann/) |  |

## Consul

| 时间       | 标题                                                         | 作者              | 中文翻译                                                     | 备注                       |
| ---------- | ------------------------------------------------------------ | ----------------- | ------------------------------------------------------------ | -------------------------- |
| 2018-06-26 | [HashiCorp Consul 1.2: Service Mesh](https://www.hashicorp.com/blog/consul-1-2-service-mesh) | Michell Hashimoto | [Service Mesh新成员：Consul 1.2](http://www.servicemesher.com/blog/consul-1-2-service-mesh/) | Consul宣布支持Service Mesh |

## Envoy

### 文档

[Envoy官方文档中文版](http://www.servicemesher.com/envoy/)

### 工具

- [Ambassador](https://github.com/envoy/Ambassador) - 基于 Envoy 的开源的用于微服务的 Kubernetes 原生 API 网关
- [squash](https://github.com/solo-io/squash) - 微服务调试器
- [rotor](https://github.com/turbinelabs/rotor) - Rotor 是一个在服务发现与 Envoy 配置 API 之间的快速、轻量级的桥接代理。它将您的基础设施分组到 Envoy 集群中，并为每个服务定义简单路由。它直接从您的服务发现注册表中收集实例，用标记或标签将实例分组来创建集群。实例和集群信息通过 Envoy 的端点和集群发现服务 CDS 和 EDS 提供。

## Linkerd

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-10 |   [A SERVICE MESH FOR KUBERNETES](https://buoyant.io/2016/10/04/a-service-mesh-for-kubernetes-part-i-top-line-service-metrics/)  | Alex Leong | [Kubernetes的service mesh](http://blog.csdn.net/hty46565/article/details/78179005) | Linkerd官方博客上连载的系列文章，部分内容有翻译 |

## Nginmesh

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2018-02 |  [O'Reilly: Istio & NginMesh](https://www.oreilly.com/pub/e/3926)  | Lee Calcote | - | [deck](https://calcotestudios.com/talks/decks/slides-istio-the-extensible-service-mesh-nginmesh.html)  |
| 2017-09 |   [NGINX Releases Microservices Platform, OpenShift Ingress Controller, and Service Mesh Preview](https://www.infoq.com/news/2017/09/nginx-platform-service-mesh)  | Daniel Bryant | [NGINX 发布微服务平台、OpenShift Ingress Controller 和Service Mesh预览版](http://www.infoq.com/cn/news/2017/09/nginx-platform-service-mesh) | _ |

## Aspen Mesh

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-12 |   [REDtalks.live – Aspen Mesh](https://buoyant.io/2017/12/05/introducing-conduit/) | Shawn Wormke | - | 对Aspen Mesh的Sr. Director的采访视频  |

## SofaMesh

| 时间    | 标题                                                         | 作者 | 备注             |
| ------- | ------------------------------------------------------------ | ---- | ---------------- |
| 2018-07 |[蚂蚁金服开源SOFAMesh—一款基于Istio改进和扩展而来的Service Mesh大规模落地实践方案](http://www.servicemesher.com/blog/introducing-sofamesh-a-solution-for-large-scale-service-mesh-by-ant-financial/)|蚂蚁金服中间件团队||
| 2018-06 | [蚂蚁金服是如何实现经典服务化架构向Service Mesh方向演进的？](http://www.servicemesher.com/blog/migrating-from-classical-soa-to-service-mesh-in-ant-financial/) | 黄挺 | GIAC大会演讲实录 |

## 华为

| 时间    | 标题                                                         | 作者   | 备注                                                         |
| ------- | ------------------------------------------------------------ | ------ | ------------------------------------------------------------ |
| 2017-12 | [Service Mesh 在华为公有云的实践](http://gitbook.cn/books/5a1e7dca387c5b4ee351790b/index.html) | 田晓亮 | [PDF下载](https://servicecomb.incubator.apache.org/assets/slides/20171209/PracticeOfServiceMeshOnHuaweiPublicCloud.pdf) |
| 2017-12 | [一个商用级Service Mesh服务的设计之道](https://blog.csdn.net/karamos/article/details/80133231) | 田晓亮 |                                                              |

## MotanMesh

| 时间    | 标题                                                         | 作者 | 备注 |
| ------- | ------------------------------------------------------------ | ---- | ---- |
| 2017-12 | [明星分分合合的洪荒点击量，微博Mesh服务化改造如何支撑？](http://dockone.io/article/2996) | 周晶 |      |

## Tencent

| 时间    | 标题                                                         | 作者   | 备注                                   |
| ------- | ------------------------------------------------------------ | ------ | -------------------------------------- |
| 2018-05 | [腾讯云TSF微服务平台及ServiceMesh技术实践](http://dockone.io/article/5803) | 单家骏 | 根据2018年05月15日晚微信群分享内容整理 |

## UCloud

| 时间    | 标题                                                         | 作者 | 备注                                 |
| ------- | ------------------------------------------------------------ | ---- | ------------------------------------ |
| 2018-05 | [轻量ServiceMesh实践](https://www.csdn.net/article/a/2018-05-04/15947689) | 徐亮 | 对Aspen Mesh的Sr. Director的采访视频 |

