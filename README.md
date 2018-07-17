# BlockChain-news

环境依赖：flask,mongodb,pymongo,bs4,requests,selenium

1. 创建数据库
mongodb> use blockchain_news
2. 配置settings.py
抓取媒体的配置在news_crawler/media_config.py
3. 运行爬虫
python3 news_crawler/main.py
4. 运行web
python3 web/app.py
