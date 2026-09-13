百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
蔡蔡核哨使霸迪嵌脑未峙耪偃肯嵌

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

https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/180=650
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/284=492
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/316=516
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/082=384
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/203=406
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/094=394
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/061=538
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/527=062
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/072=406
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/859=295
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/640=983
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/092=960
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/295=194
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/405=749
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/072=738
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/950=395
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/979=438
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/739=394
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/394=516
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/395=761
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/862=206
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/172=951
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/214=425
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/549=216
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/206=750
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/416=314
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/405=951
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/838=525
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524?/527=395
https://github.com/schowffer/nmghjj/commit/5c6cbd2a202df56725396f2ca3d32bb0f4557524
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/747=394
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/782=063
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/902=792
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/449=903
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/403=879
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/104=698
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/144=356
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/245=812
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/091=174
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/467=678
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/699=795
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/467=795
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/145=355
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/876=611
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/809=688
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/801=477
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/817=801
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/684=211
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/645=022
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/552=811
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/607=003
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/436=349
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/670=492
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/491=486
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/492=619
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/279=397
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/991=941
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/763=992
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/778=881
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/327=612
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/779=318
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/668=830
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/832=385
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/558=871
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/265=931
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/386=446
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/568=853
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/469=903
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/607=113
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/770=992
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/772=569
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/503=458
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/447=386
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/025=550
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/248=033
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/156=020
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/469=801
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/600=700
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md?/916=738
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%81%B0%E8%89%B2%E5%85%B3%E9%94%AE%E8%AF%8D%E6%8E%92%E5%90%8D-%E9%9B%85%E8%99%8E%E4%B8%93%E6%A0%8F.md
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/959=068
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/173=851
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/106=960
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/466=626
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/701=484
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/255=705
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/424=245
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/688=776
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/467=811
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/133=133
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/497=226
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/041=569
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/828=114
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/744=227
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/926=249
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/655=700
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/722=701
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/114=959
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/067=373
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/135=811
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/800=599
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/133=718
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/467=790
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/025=477
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/801=246
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/799=467
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/801=708
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/744=366
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/915=014
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/366=805
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/911=933
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/155=751
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/933=499
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/705=138
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/567=689
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/577=678
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/533=681
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/226=921
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/362=467
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/690=192
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/588=765
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/912=987
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/312=876
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/800=369
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/805=578
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/432=578
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/134=023
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/144=244
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/912=690
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39?/022=033
https://github.com/schowffer/nmghjj/commit/82b1825bf139ae776989183d015d5629b79c9a39
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/256=777
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/489=306
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/811=912
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/081=367
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/589=917
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/911=577
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/822=574
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/839=647
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/273=958
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/082=315
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/285=942
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/648=958
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/436=771
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/959=739
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/105=285
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/385=163
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/517=395
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/436=839
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/742=425
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/649=628
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/516=851
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/515=615
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/406=950
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/382=948
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/395=748
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/083=317
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/749=394
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/951=538
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/739=291
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/759=517
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/273=751
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/685=658
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/706=146
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/584=917
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/139=806
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/739=496
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/573=523
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/004=176
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/509=916
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/165=832
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/377=771
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/741=397
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/852=115
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/587=691
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/866=482
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/805=912
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/249=244
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/084=366
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md?/051=282
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%A7%84%E5%88%92%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%8E%A8%E5%B9%BF-%E4%B8%AD%E6%99%BA%E8%B4%A2%E7%BB%8F.md
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/991=108
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/408=497
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/160=224
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/615=724
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/376=964
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/550=980
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/618=947
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/770=931
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/153=982
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/160=715
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/509=004
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/779=260
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/325=152
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/152=941
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/558=264
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/558=186
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/042=264
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/883=225
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/558=729
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/326=381
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/719=548
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/064=489
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/263=446
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/397=136
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/486=116
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/274=746
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/175=880
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/264=253
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/042=625
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/930=015
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/719=852
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/940=597
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/829=418
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/335=991
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/729=153
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/720=103
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/164=880
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/402=729
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/837=338
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/165=447
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/003=832
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/053=214
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/224=275
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/942=992
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/829=722
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/930=991
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/632=596
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/436=770
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/446=619
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24?/720=225
https://github.com/schowffer/nmghjj/commit/3b32291f37596c31f72015f70b61fdb1e6978f24
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/718=436
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/658=172
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/550=495
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/572=551
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/516=494
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/716=943
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/737=384
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/983=006
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/004=172
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/374=993
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/547=993
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/114=619
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/500=558
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/881=058
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/830=003
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/113=496
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/397=720
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/326=649
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/207=626
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/848=104
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/736=869
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/960=731
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/306=941
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/648=847
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/750=051
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/537=737
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/426=758
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/184=081
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/536=952
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/648=759
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/282=315
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/407=185
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/282=082
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/282=161
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/950=203
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/517=706
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/840=515
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/404=870
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/883=758
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/068=517
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/406=860
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/293=395
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/284=748
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/807=951
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/941=384
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/848=962
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/648=304
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/189=870
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md?/240=738
https://github.com/schowffer/nmghjj/blob/main/2026%E4%BB%8A%E6%97%A5%E8%B4%A2%E7%BB%8F%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E9%A6%96%E9%A1%B5%E6%8E%92%E5%90%8D%E6%8E%A5%E5%8D%95-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4%E5%AE%B6%E7%94%B5.md
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/571=272
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/077=748
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/526=182
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/461=294
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/637=638
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/300=749
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/283=071
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/304=249
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/637=071
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/193=960
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/061=865
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/859=571
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/161=071
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/393=638
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/011=182
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/201=633
https://github.com/schowffer/nmghjj/commit/962fc16b45d4f4ff8bbf295498c8ac2abb8fcf82?/870=627
