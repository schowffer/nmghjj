百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
绞泊犹藤驳舅柯富吻啪叛磺家秃堵

状态代码

成功
200 正常;请求已完成。
201 正常;紧接POST命令。
202 正常;已接受用于处理，但处理尚未完成。
203 正常;部分信息 — 返回的信息只是一部分。
204 正常;无响应 — 已接收请求，但不存在要回送的信息。
重定向
301 永久重定向 — 请求的数据具有新的位置且更改是永久的。
302 暂时重定向 — 请求的数据临时具有不同URI。
303 请参阅其它 — 可在另一URI下找到对请求的响应，且应使用 GET方法检索此响应。
304 未修改 — 未按预期修改文档。
305 使用代理 — 必须通过位置字段中提供的代理来访问请求的资源。
306 未使用 — 不再使用;保留此代码以便将来使用。
代码中的错误
400 错误请求 — 请求中有语法问题，或不能满足请求。
401 未授权 — 未授权客户机访问数据。
402 需要付款 — 表示计费系统已有效。
403 禁止— 即使有授权也不需要访问。
404 找不到—服务器找不到给予的资源;文档不存在。
406 不可接受 — 根据此请求中所发送的“接受”标题，此请求所标识的资源只能生成内容特征为“不可接受”的响应实体。
407 代理认证请求 — 客户机首先必须使用代理认证自身。
410 请求的网页不存在(永久);
415 介质类型不受支持 —服务器拒绝服务请求，因为不支持请求实体的格式。
500 内部错误 — 因为意外情况，服务器不能完成请求。
501 未执行 —服务器不支持请求的工具。
502 错误网关—服务器接收到来自上游服务器的无效响应。
503 无法获得服务 — 由于临时过载或维护，服务器无法处理请求。

问题解答

Baiduspider对一个网站服务器造成的访问压力如何？
答：Baiduspider会自动根据服务器的负载能力调节访问密度。在连续访问一段时间后，Baiduspider会暂停一会，以防止增大服务器的访问压力。所以在一般情况下，Baiduspider对您网站的服务器不会造成过大的压力。
为什么Baiduspider不停的抓取我的网站？
答：或许您的网站权重高或者对于您网站上新产生的或者持续、有规律更新的页面，Baiduspider会持续抓取。此外，您也可以检查网站访问日志中Baiduspider的访问是否正常，以防止有人恶意冒充Baiduspider来频繁抓取您的网站。 如果您发现Baiduspider非正常抓取您的网站，请反馈至，并请尽量给出Baiduspider对贵站的访问日志，以便于我们跟踪处理。
我不想我的网站被Baiduspider访问，我该怎么做？
答：Baiduspider遵守互联网robots协议。您可以利用robots.txt文件完全禁止Baiduspider访问您的网站，或者禁止Baiduspider访问您网站上的部分文件。 注意：禁止Baiduspider访问您的网站，将使您的网站上的网页，在百度搜索引擎以及所有百度提供搜索引擎服务的搜索引擎中无法被搜索到。
ps:关于robots.txt的写作方法，请参看我们的介绍：robots.txt写作方法
为什么我的网站已经加了robots.txt，还能在百度搜索出来？
答：因为搜索引擎索引数据库的更新需要时间。虽然Baiduspider已经停止访问您网站上的网页，但百度搜索引擎数据库中已经建立的网页索引信息，可能需要二至四周才会清除。 另外也请检查您的robots配置是否正确。
我希望我的网站内容被百度索引但不被保存快照，我该怎么做？
答：Baiduspider遵守互联网metarobots协议。您可以利用网页meta的设置，使百度显示只对该网页建索引，但并不在搜索结果中显示该网页的快照。
和robots的更新一样，因为搜索引擎索引数据库的更新需要时间，所以虽然您已经在网页中通过meta禁止了百度在搜索结果中显示该网页的快照，但百度搜索引擎数据库中如果已经建立了网页索引信息，可能需要二至四周才会在线上生效。
百度蜘蛛在robots.txt中的名字是什么？
答：“Baiduspider” 首字母B大写，其余为小写。
Baiduspider多长时间之后会重新抓取我的网页？
答：百度搜索引擎每周更新，网页视重要性有不同的更新率，频率在几天至一月之间，Baiduspider会重新访问和更新一个网页。
Baiduspider抓取造成的带宽堵塞？
答：Baiduspider的正常抓取并不会造成您网站的带宽堵塞，造成此现象可能是由于有人冒充baidu的spider恶意抓取。如果您发现有名为Baiduspider的agent抓取并且造成带宽堵塞，请尽快和我们联系。您可以将信息反馈至百度网页投诉中心，如果能够提供您网站该时段的访问日志将更加有利于我们的分析。

群发外链
对应名称
产品名称 对应user-agent
网页搜索 Baiduspider
无线搜索 Baiduspider
图片搜索 Baiduspider-image
视频搜索 Baiduspider-video
新闻搜索 Baiduspider-news
百度搜藏 Baiduspider-favo
百度联盟Baiduspider-cpro
竞价蜘蛛Baiduspider-sfkr

https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/276=161
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/383=116
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/373=616
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/983=381
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/943=350
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/849=406
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/115=160
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/610=486
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/025=933
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/931=931
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/054=335
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/163=770
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/297=508
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/274=510
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/382=837
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/227=726
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/394=773
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4?/771=348
https://github.com/schowffer/nmghjj/commit/9605b04c96940f91266ea7683981caf7bfd9bba4
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/720=557
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/224=337
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/850=546
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/496=075
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/881=002
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/558=942
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/375=436
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/496=943
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/953=881
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/547=669
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/984=163
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/335=092
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/947=952
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/949=902
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/182=991
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/740=850
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/694=638
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/105=071
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/750=295
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/215=415
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/633=850
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/248=859
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/327=071
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/572=188
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/416=304
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/227=304
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/960=182
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/960=051
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/074=979
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/637=804
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/205=793
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/659=072
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/636=083
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/705=437
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/188=527
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/395=282
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/638=205
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/204=104
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/958=315
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/326=747
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/515=626
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/742=281
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/526=737
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/628=993
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/515=518
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/416=972
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/961=090
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/060=938
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md?/284=361
https://github.com/schowffer/nmghjj/blob/main/2026%E6%A0%B8%E5%BF%83%E7%99%BE%E7%A7%91%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8-%E6%90%9C%E7%8B%90%E6%B8%B8%E6%88%8F.md
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/953=724
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/966=389
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/767=638
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/658=654
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/020=460
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/561=401
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/123=761
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/130=560
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/095=823
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/086=887
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/323=462
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/551=873
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/272=621
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/809=036
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/061=136
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/641=963
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/960=745
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/248=915
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/648=305
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/079=959
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/072=859
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/516=848
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/007=055
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/000=210
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/427=920
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/207=820
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/749=671
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/095=917
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/171=860
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/210=496
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/224=942
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/870=238
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/264=104
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/336=579
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/942=092
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/225=336
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/618=949
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/658=103
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/880=042
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/679=164
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/336=496
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/193=115
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/825=850
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/772=579
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/164=213
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/446=264
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/725=274
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/114=386
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/596=164
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2?/946=991
https://github.com/schowffer/nmghjj/commit/a43a4352bbd803be2972150b10fd55a6122d3ab2
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/114=003
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/014=164
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/557=831
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/556=285
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/614=597
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/930=105
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/096=041
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/059=447
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/831=158
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/871=830
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/608=336
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/881=981
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/885=992
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/547=770
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/507=059
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/414=778
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/619=236
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/486=053
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/941=796
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/770=719
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/448=719
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/387=114
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/668=949
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/054=224
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/437=042
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/470=277
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/836=346
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/498=016
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/226=605
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/693=005
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/707=205
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/565=420
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/865=656
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/457=898
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/610=447
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/797=456
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/720=401
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/265=771
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/074=619
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/346=159
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/770=446
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/546=393
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/613=770
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/114=163
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/383=758
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/375=941
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/286=213
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/217=760
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md?/112=700
https://github.com/schowffer/nmghjj/blob/main/2027%E6%95%B0%E6%8D%AE%E9%87%8D%E5%A4%A7%E5%8F%91%E7%8E%B0%3A%E6%B3%9B%E7%9B%AE%E5%BD%95%E5%A5%BD%E7%94%A8%E8%BF%98%E6%98%AF%E8%9C%98%E8%9B%9B%E6%B1%A0%E5%A5%BD%E7%94%A8-%E6%8A%96%E9%9F%B3%E6%B8%B8%E6%88%8F.md
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/027=152
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/426=185
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/700=112
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/040=001
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/793=525
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/799=762
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/061=587
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/027=182
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/637=962
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/338=937
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/859=315
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/304=304
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/859=805
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/648=850
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/294=527
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/215=360
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/638=308
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/529=741
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/526=961
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/316=182
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/916=849
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/878=182
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/748=850
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/138=962
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/302=415
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/960=433
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/460=184
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/583=527
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/637=416
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/304=638
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/638=465
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/960=805
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/094=300
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/650=859
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/555=704
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/415=315
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/871=304
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/415=082
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/805=304
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/960=637
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/749=859
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/961=627
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/417=972
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/299=860
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/741=072
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/460=637
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/617=305
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/859=082
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/415=749
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837?/405=228
https://github.com/schowffer/nmghjj/commit/6857bd12c23422ac728e22101cbc0da49ad1b837
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/028=635
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/407=073
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/528=853
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/746=290
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/758=031
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/740=539
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/640=409
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/852=078
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/796=522
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/307=207
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/428=291
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/362=847
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/173=852
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/201=063
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/752=867
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/312=412
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/079=624
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/050=584
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/418=312
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/594=306
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/859=537
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/204=171
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/704=294
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/916=951
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/393=522
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/951=249
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/895=635
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/296=462
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/422=285
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/534=180
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/961=474
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/175=640
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/748=970
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/293=250
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/848=416
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/526=293
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/549=805
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/188=172
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/416=840
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/737=404
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/779=850
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/980=513
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/176=368
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/205=173
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/958=950
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/193=307
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/326=526
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/626=171
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md?/850=958
https://github.com/schowffer/nmghjj/blob/main/2026%E7%BB%8F%E9%AA%8C%E9%A3%8E%E5%90%91%3A%E7%99%BE%E5%BA%A6%E6%B3%9B%E7%9B%AE%E5%BD%95%E8%9C%98%E8%9B%9B%E6%B1%A0-%E7%9F%A5%E4%B9%8E%E5%AE%9E%E5%BD%95.md
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/669=732
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/648=631
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/077=427
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/206=815
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/571=815
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/200=961
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/294=637
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/523=306
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/183=293
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/582=412
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/282=527
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/072=638
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/960=416
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/182=747
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/074=416
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/205=969
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/323=149
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/382=083
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/182=639
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/916=183
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/707=636
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/744=905
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/428=350
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/745=572
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/385=536
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/746=870
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/362=302
https://github.com/schowffer/nmghjj/commit/965c6e48f8389e4f9834b6750658fee70b160771?/536=864
