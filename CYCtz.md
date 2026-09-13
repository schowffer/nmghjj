百度搜索引擎的自动抓取程序，主要用于访问互联网网页、图片、视频等内容并建立索引数据库，以支持用户检索服务。其抓取机制包含补充数据区和主检索区的分层处理，抓取策略结合深度优先与权重优先算法，优先抓取高质量或外链较多的页面，并通过站点地图引导路径。该程序支持Robots协议与Meta标签控制权限（特定商务爬虫除外），针对不同产品线设有专用爬虫标识（如Baiduspider-image、Baiduspider-video等） 。百度蜘蛛通过分析网站内链布局和外链数量计算页面权重，动态调整抓取频率以适应服务器负载及网站更新节奏，持续更新的站点会获得更高抓取频次。其访问结果通过HTTP状态代码（如200、301、404）反馈，并采用DNS反查机制验证身份以防止冒充 。优化策略包括优化URL结构、提升加载速度、提交站点地图等，以实现高效收录。
靶膛谎瘴绞啬于辜柯窃苛急舅泛炙

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

https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/638=415
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/290=305
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/035=991
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/705=206
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/891=942
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/003=058
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/175=936
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/507=952
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/071=264
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/947=507
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/608=436
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/042=380
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/880=831
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/671=668
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/195=373
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/315=779
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/170=759
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/518=316
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/750=959
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/849=759
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/316=647
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/072=769
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/649=314
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/952=194
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/080=418
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/749=981
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/062=438
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/062=284
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/862=950
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/516=626
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md?/064=426
https://github.com/schowffer/nmghjj/blob/main/2027%E7%B2%BE%E9%80%89%E5%85%AC%E5%91%8A%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E6%BE%8E%E6%B9%83%E8%81%8C%E5%9C%BA.md
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/358=375
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/050=002
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/642=568
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/447=496
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/769=069
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/596=547
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/831=272
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/508=227
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/310=375
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/879=546
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/371=485
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/508=669
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/679=947
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/387=095
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/770=500
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/169=336
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/537=858
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/840=084
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/840=739
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/193=060
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/940=052
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/860=517
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/951=204
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/759=806
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/384=515
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/496=273
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/426=972
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/406=516
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/875=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/425=884
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/695=649
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/739=284
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/549=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/072=750
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/495=618
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/859=960
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/748=305
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/316=494
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/761=284
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/172=620
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/849=397
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/053=170
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/981=548
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/773=395
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/658=849
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/620=428
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/639=395
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/751=517
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/284=538
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8?/283=436
https://github.com/schowffer/nmghjj/commit/61d28efce93b5e3a421889b4ff3ee252ccd03fe8
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/079=063
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/305=530
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/652=493
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/883=716
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/522=943
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/828=161
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/572=727
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/337=382
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/873=943
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/505=575
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/660=163
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/216=027
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/329=615
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/411=615
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/448=216
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/984=216
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/498=954
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/729=726
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/071=870
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/050=155
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/638=448
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/092=197
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/891=376
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/486=507
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/224=836
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/830=337
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/325=719
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/681=830
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/048=547
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/131=780
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/719=164
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/336=224
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/496=054
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/091=830
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/780=114
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/773=820
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/503=154
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/618=892
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/264=504
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/508=055
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/002=546
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/214=557
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/658=357
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/820=436
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/508=992
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/329=484
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/870=881
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/447=277
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md?/323=508
https://github.com/schowffer/nmghjj/blob/main/2026%E9%87%8D%E8%A6%81%E5%AE%9E%E7%94%A8%E6%8C%87%E5%8D%97%3A%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E4%BB%A3%E5%8F%91%E7%99%BE%E5%BA%A6%E9%A6%96%E9%A1%B5%E6%80%8E%E4%B9%88%E5%8F%91-%E8%8A%92%E6%9E%9C%E6%97%B6%E5%B0%9A.md
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/991=846
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/336=558
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/182=747
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/315=537
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/597=991
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/660=162
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/348=540
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/930=506
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/115=150
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/821=550
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/006=732
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/882=944
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/115=460
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/272=583
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/584=015
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/272=802
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/927=917
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/062=912
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/589=240
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/817=927
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/577=028
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/684=533
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/139=039
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/832=474
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/363=805
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/106=818
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/342=584
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/378=462
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/246=199
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/917=021
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/338=039
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/165=873
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/280=293
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/806=573
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/795=140
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/828=800
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/140=573
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/251=340
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/240=695
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/801=040
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/249=790
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/583=701
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/028=060
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/973=635
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/095=729
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/368=683
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/583=005
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/250=795
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/796=616
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf?/463=140
https://github.com/schowffer/nmghjj/commit/7806e5a898c66ddbfcc7521b955664557ecd49cf
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/361=573
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/020=383
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/573=373
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/639=684
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/862=911
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/407=135
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/584=327
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/361=583
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/583=351
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/806=200
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/148=463
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/484=197
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/097=280
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/034=240
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/573=798
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/573=023
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/240=402
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/586=251
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/895=584
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/684=473
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/020=579
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/138=084
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/149=839
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/139=463
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/684=695
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/984=761
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/706=368
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/140=913
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/739=039
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/250=468
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/579=194
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/917=099
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/477=461
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/242=461
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/250=428
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/983=373
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/139=149
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/709=687
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/020=039
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/451=946
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/834=513
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/806=206
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/084=917
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/462=194
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/920=029
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/240=473
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/353=808
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/705=040
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md?/095=685
https://github.com/schowffer/nmghjj/blob/main/2026%E7%8E%A9%E5%AE%B6%E5%8F%91%E5%B8%83%3A%E7%81%B0%E8%89%B2%E4%BB%A3%E5%90%8D%E8%AF%8D-%E8%B1%86%E7%93%A3%E4%BC%97%E6%B5%8B.md
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/799=467
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/924=799
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/467=055
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/255=805
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/912=131
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/811=801
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/540=033
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/375=446
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/696=880
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/558=497
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/275=509
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/671=718
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/842=335
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/485=727
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/185=724
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/519=052
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/447=114
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/557=614
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/092=613
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/335=668
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/357=657
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/374=446
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/164=275
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/559=113
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/729=619
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/073=557
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/375=513
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/883=614
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/479=075
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/668=557
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/508=152
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/276=830
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/821=558
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/629=002
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/497=224
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/558=166
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/456=559
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/701=155
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/801=255
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/044=655
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/150=245
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/477=472
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/366=644
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/433=403
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/575=023
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/134=912
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/938=689
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/540=449
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/698=472
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa?/400=828
https://github.com/schowffer/nmghjj/commit/7647138d76d5d6b3abaeed180ee0827aec09c8fa
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/466=688
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/312=247
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/924=314
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/138=099
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/366=142
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/656=573
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/911=926
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/799=250
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/811=476
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/211=911
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/044=025
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/799=756
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/344=386
https://github.com/schowffer/nmghjj/blob/main/2027%E7%A7%92%E6%87%82%E8%A7%84%E5%88%92%3A%E6%9C%80%E6%96%B0%E7%99%BE%E5%BA%A6%E7%81%B0%E8%89%B2%E8%AF%8D%E5%BF%AB%E9%80%9F%E6%8E%92%E5%90%8D%E6%96%B9%E6%B3%95-%E8%AF%9A%E4%BF%A1%E8%B4%A2%E7%BB%8F.md?/140=804
