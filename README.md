E:\Anaconda\PC\PC的代码文件夹\pac爬虫\dangdangoachong\dangdangoachong\spiders>scrapy crawl dangdang
2023-08-17 23:35:11 [scrapy.utils.log] INFO: Scrapy 2.8.0 started (bot: dangdangoachong)
2023-08-17 23:35:11 [scrapy.utils.log] INFO: Versions: lxml 4.9.1.0, libxml2 2.9.14, cssselect 1.1.0, parsel 1.6.0, w3lib 1.21.0, Twisted 22.2.0, Python 3.10.9 | packaged by Anaconda, Inc. | (main, Mar  1 2023, 18:18:15) [MSC v.1916 64 bit (AMD64)], pyOpenSSL 23.0.0 (OpenSSL 1.1.1u  30 May 2023), cryptography 39.0.1, Platform Windows-10-10.0.22621-SP0
2023-08-17 23:35:11 [scrapy.crawler] INFO: Overridden settings:
{'BOT_NAME': 'dangdangoachong',
 'FEED_EXPORT_ENCODING': 'utf-8',
 'NEWSPIDER_MODULE': 'dangdangoachong.spiders',
 'REQUEST_FINGERPRINTER_IMPLEMENTATION': '2.7',
 'ROBOTSTXT_OBEY': True,
 'SPIDER_MODULES': ['dangdangoachong.spiders'],
 'TWISTED_REACTOR': 'twisted.internet.asyncioreactor.AsyncioSelectorReactor'}
2023-08-17 23:35:11 [asyncio] DEBUG: Using selector: SelectSelector
2023-08-17 23:35:11 [scrapy.utils.log] DEBUG: Using reactor: twisted.internet.asyncioreactor.AsyncioSelectorReactor
2023-08-17 23:35:11 [scrapy.utils.log] DEBUG: Using asyncio event loop: asyncio.windows_events._WindowsSelectorEventLoop
2023-08-17 23:35:11 [scrapy.extensions.telnet] INFO: Telnet Password: 4734e727412358f4
2023-08-17 23:35:11 [scrapy.middleware] INFO: Enabled extensions:
['scrapy.extensions.corestats.CoreStats',
 'scrapy.extensions.telnet.TelnetConsole',
 'scrapy.extensions.logstats.LogStats']
2023-08-17 23:35:11 [scrapy.middleware] INFO: Enabled downloader middlewares:
['scrapy.downloadermiddlewares.robotstxt.RobotsTxtMiddleware',
 'scrapy.downloadermiddlewares.httpauth.HttpAuthMiddleware',
 'scrapy.downloadermiddlewares.downloadtimeout.DownloadTimeoutMiddleware',
 'scrapy.downloadermiddlewares.defaultheaders.DefaultHeadersMiddleware',
 'scrapy.downloadermiddlewares.useragent.UserAgentMiddleware',
 'scrapy.downloadermiddlewares.retry.RetryMiddleware',
 'scrapy.downloadermiddlewares.redirect.MetaRefreshMiddleware',
 'scrapy.downloadermiddlewares.httpcompression.HttpCompressionMiddleware',
 'scrapy.downloadermiddlewares.redirect.RedirectMiddleware',
 'scrapy.downloadermiddlewares.cookies.CookiesMiddleware',
 'scrapy.downloadermiddlewares.httpproxy.HttpProxyMiddleware',
 'scrapy.downloadermiddlewares.stats.DownloaderStats']
2023-08-17 23:35:11 [scrapy.middleware] INFO: Enabled spider middlewares:
['scrapy.spidermiddlewares.httperror.HttpErrorMiddleware',
 'scrapy.spidermiddlewares.offsite.OffsiteMiddleware',
 'scrapy.spidermiddlewares.referer.RefererMiddleware',
 'scrapy.spidermiddlewares.urllength.UrlLengthMiddleware',
 'scrapy.spidermiddlewares.depth.DepthMiddleware']
2023-08-17 23:35:11 [scrapy.middleware] INFO: Enabled item pipelines:
[]
2023-08-17 23:35:11 [scrapy.core.engine] INFO: Spider opened
2023-08-17 23:35:11 [scrapy.extensions.logstats] INFO: Crawled 0 pages (at 0 pages/min), scraped 0 items (at 0 items/min)
2023-08-17 23:35:11 [scrapy.extensions.telnet] INFO: Telnet console listening on 127.0.0.1:6023
2023-08-17 23:35:11 [scrapy.core.engine] DEBUG: Crawled (200) <GET http://category.dangdang.com/robots.txt> (referer: None)
2023-08-17 23:35:12 [scrapy.core.engine] DEBUG: Crawled (200) <GET http://category.dangdang.com/> (referer: None)
+++++++++++++++++++++++
2023-08-17 23:35:12 [scrapy.core.engine] INFO: Closing spider (finished)
2023-08-17 23:35:12 [scrapy.statscollectors] INFO: Dumping Scrapy stats:
{'downloader/request_bytes': 472,
 'downloader/request_count': 2,
 'downloader/request_method_count/GET': 2,
 'downloader/response_bytes': 50558,
 'downloader/response_count': 2,
 'downloader/response_status_count/200': 2,
 'elapsed_time_seconds': 0.58473,
 'finish_reason': 'finished',
 'finish_time': datetime.datetime(2023, 8, 17, 15, 35, 12, 326723),
 'httpcompression/response_bytes': 428822,
 'httpcompression/response_count': 2,
 'log_count/DEBUG': 5,
 'log_count/INFO': 10,
 'response_received_count': 2,
 'robotstxt/request_count': 1,
 'robotstxt/response_count': 1,
 'robotstxt/response_status_count/200': 1,
 'scheduler/dequeued': 1,
 'scheduler/dequeued/memory': 1,
 'scheduler/enqueued': 1,
 'scheduler/enqueued/memory': 1,
 'start_time': datetime.datetime(2023, 8, 17, 15, 35, 11, 741993)}
2023-08-17 23:35:12 [scrapy.core.engine] INFO: Spider closed (finished)
