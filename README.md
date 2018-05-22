# Awesome Service Mesh

Service Mesh 又译“服务网格”，本站创建并维护这份Awesome Service Mesh资料清单供大家交流学习。

资料内容来自国内国内公开媒体，转载时我们会指明出处，标注原作者和原译者，如果是原创或者原创翻译也会标明作者或者译者身份。

- [Service Mesh](#servicemesh)
- [Istio](#istio)
- [Conduit](#conduit)
- [Envoy](#envoy)
- [Linkerd](#linkerd)
- [Nginmesh](#nginmesh)
- [Aspenmesh](#aspenmesh)

## ServiceMesh

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2018-05-20 | [Service Mesh：重塑微服务市场](https://skyao.io/publication/service-mesh-rebuild-microservice-market/)![](images/new_red.png) | 敖小剑   |  | 南京全球技术周互联网技术架构论坛 |
| 2018-1 |   [解读2017之Service Mesh：<br>群雄逐鹿烽烟起](https://mp.weixin.qq.com/s?__biz=MzIwMzg1ODcwMw==&mid=2247487273&idx=1&sn=f654a9a8cb85d8cf2d06e469585cce8a&chksm=96c9b949a1be305f3eaa18e3fcb29cf66b4f51f37869e7ccd8c080a8ded8f4ecfe78e3de8ac6&mpshare=1&scene=1&srcid=1227PrB5dA8Hr3CHPv6B9PEN&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd)  | 敖小剑   |  | Infoq年度总结系列文章 |
| 2017-12 |   [山雨欲来风满楼：<br>Service Mesh时代的选边与站队](https://mp.weixin.qq.com/s?__biz=MzU0MTMyMDg1NQ==&mid=2247483697&idx=1&sn=b5fdd3af4ae352942820cec9280257c3&chksm=fb2af2c9cc5d7bdf05b7a58ba9120f4390de52c9c74e3d5e6932ca6b9367677234dbf8af06c1&mpshare=1&scene=1&srcid=1220gyaL6UP5ZUFpMn0UgPke&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd)  | 敖小剑   |  | 北京meetup演讲实录 |
| 2017-10 |   [Service Mesh：下一代微服务](https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652136254&idx=1&sn=bba9bbd24ac8e5c1f6ef5d1125a6975b&chksm=84d53304b3a2ba12f88675c1bf51973aa1210d174da9e6c2ddcd1f3c84ec7e25987b3bce1071&mpshare=1&scene=1&srcid=1020GPmfbEVP9QDNlZBHg47I&pass_ticket=vR63tjXqn9DTRAEWRKRMIB8O1ybqCamYyCza7%2BE5YRJRfpf%2F5OwphFKHGOiDiS6u#rd)  | 敖小剑   |  | QCON演讲实录 |
| 2017-08|   [Pattern: Service Mesh](http://philcalcado.com/2017/08/03/pattern_service_mesh.html)  | Phil Calçado | [模式之服务网格](http://www.infoq.com/cn/articles/pattern-service-mesh?from=awesome-servicemesh) | 详细介绍Service Mesh模式和演进过程，强烈推荐 |
| 2017-08 |  [Application Network Functions With ESBs, API Management, and Now.. Service Mesh?](http://blog.christianposta.com/microservices/application-network-functions-with-esbs-api-management-and-now-service-mesh/)  | Christian Posta   | [应用网络功能，EBS，API管理，而现在..Service Mesh?](https://mp.weixin.qq.com/s?__biz=MzI5MDEzMzg5Nw==&mid=2660396277&idx=1&sn=e3fd0e49b4947e80fbfd3cdd781bad96&chksm=f7424e13c035c705401b08795eb5c494cd1001c39760bc603c377f550f999d5dc8355229b2f9&mpshare=1&scene=1&srcid=1108KXT47jsSir7gXXN7x1yj&pass_ticket=5n8O9dw5nrNWdp91I1Ex8q0wFqwN7oHELYvWuTB%2BJGXvmM0y3ASvIhOn%2FU9zG29J#rd)  |  |
| 2017-07| ![](images/ppt.png)  [O'Reilly 2017: "Introduction to Service Meshes"](https://www.slideshare.net/dbryant_uk/oreilly-2017-introduction-to-service-meshes)  | Daniel Bryant | [PPT的中文版本](https://github.com/thomaslwq/publicfiles/tree/master) | 演讲的PPT |
| 2017-04|   [What’s a service mesh? And why do I need one?](https://buoyant.io/2017/04/25/whats-a-service-mesh-and-why-do-i-need-one/)  |  William Morgan  | [什么是服务网格以及为什么我们需要服务网格？](http://www.infoq.com/cn/news/2017/11/WHAT-SERVICE-MESH-WHY-NEED) | 应该是业界第一篇详细介绍Service Mesh理念的文章，强烈推荐 |

## Istio

### 文档

- [istio官方文档中文版](http://istio.doczh.cn/)

### 工具

- [在线体验istio](https://katacoda.com/courses/istio/): 实测可用
- [istio-workshop](https://github.com/retroryan/istio-workshop)

### 文章

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-11 | ![](images/ppt.png) [8 Steps to Becoming Awesome with Kubernetes](https://docs.google.com/presentation/d/1ij64THksTygvifW5BD-n0ipc6MDF4cGBRQcV3BRYaoM/edit#slide=id.g12c8aac1e6_0_890)   | Burr Sutter  |  | [PPT国内下载（免翻墙）](http://www.servicemesh.cn/?/article/11?notification_id=34&item_id=4) |
| 2017-10 |  [Kubernetes, Microservices, and Istio  — A Great Fit!](https://thenewstack.io/kubernetes-microservices-istio%E2%80%8A-%E2%80%8Aa-great-fit/)  | Animesh Singh  |  |  |
| 2017-09 |   [什么是Service Mesh（服务网格）](https://jimmysong.io/posts/what-is-a-service-mesh/)  |  宋净超  |  |  |
| 2017-09 |   [服务网格新生代--Istio](https://mp.weixin.qq.com/s?__biz=MzA3MDg4Nzc2NQ==&mid=2652136078&idx=1&sn=b261631ffe4df0638c448b0c71497021&chksm=84d532b4b3a2bba2c1ed22a62f4845eb9b6f70f92ad9506036200f84220d9af2e28639a22045&scene=21#wechat_redirect)  | 敖小剑   |  | 线上分享实录 |
| 2017-09|   [What is Istio? It’s a service mesh. Great. What’s a service mesh?](https://www.mirantis.com/blog/what-is-istio-its-a-service-mesh-whats-a-service-mesh/)  |  Nick Chase  | [什么是Istio? 它是服务网格。棒极了，那什么是服务网格？](https://my.oschina.net/u/2562868/blog/1563506)  | 访谈录 |
| 2017-05|  [Google, IBM and Lyft launch Istio, an open-source platform for managing and securing microservices](https://techcrunch.com/2017/05/24/google-ibm-and-lyft-launch-istio-an-open-source-platform-for-managing-and-securing-microservices/?utm_source=tuicool&utm_medium=referral)   |  Frederic Lardinois   | [Istio开源平台发布，Google、IBM和Lyft分别承担什么角色？](https://www.leiphone.com/news/201705/RwRlyAs7Mi8pqhSb.html) |  |
| 2017-05|  [Google, IBM, Lyft partner on open source microservices management platform Istio](https://www.techrepublic.com/article/google-ibm-lyft-partner-on-open-source-microservices-management-platform-istio/)   |  Conner Forrest   |  | _ |

## Conduit

### 文档

- [conduit官方文档中文版](http://conduit.doczh.cn/)

### 文章

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-12 |   [Conduit AMA session recap](https://buoyant.io/2017/12/27/conduit-ama-session-recap/) ![](images/new_red.png) | George Miranda | [Conduit AMA 活动回放](https://mp.weixin.qq.com/s?__biz=MzIxMDY5ODM1OA==&mid=2247483950&idx=1&sn=9c1ac2317a744f4071b14f9e1575558b&chksm=9761eb37a0166221de9827ff430e6ee3d164e73145d42009f5f6f4d9f4146deb0899524b894d&mpshare=1&scene=1&srcid=0101VEm8cn0KyNSem88rXHPU&pass_ticket=K%2FYVK4frKmQIBjzOKz2fFYc%2BwxcpMJV4d14ui%2BayOESnQJD%2BLr5DtBVa12t1Zu2N#rd) | 介绍conduit项目的各种情况 |
| 2017-12 |   [Introducing Conduit](https://buoyant.io/2017/12/05/introducing-conduit/) | William Morgan | [Conduit 登场](https://blog.fleeto.us/post/conduit-ann/) | conduit第一次亮相 |

## Envoy

### 文档

[Envoy官方文档中文版](https://servicemesher.github.io/envoy)

## Linkerd

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-10 |   [A SERVICE MESH FOR KUBERNETES](https://buoyant.io/2016/10/04/a-service-mesh-for-kubernetes-part-i-top-line-service-metrics/)  |  | [Kubernetes的service mesh](http://blog.csdn.net/hty46565/article/details/78179005) | Linkerd官方博客上连载的系列文章,部分内容有翻译 |

## Nginmesh

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-09 |   [NGINX Releases Microservices Platform, OpenShift Ingress Controller, and Service Mesh Preview](https://www.infoq.com/news/2017/09/nginx-platform-service-mesh)  | Daniel Bryant | [NGINX 发布微服务平台、OpenShift Ingress Controller 和Service Mesh预览版](http://www.infoq.com/cn/news/2017/09/nginx-platform-service-mesh) | _ |

## Aspenmesh

| 时间 | 标题 | 作者 | 中文翻译 | 备注 |
|--|--------|--------|----|----|
| 2017-12 |   [REDtalks.live – Aspen Mesh](https://buoyant.io/2017/12/05/introducing-conduit/) ![](images/new_red.png) | Shawn Wormke |  | 对Aspen Mesh的Sr. Director的采访视频  |