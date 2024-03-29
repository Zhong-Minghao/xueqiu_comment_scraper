# xueqiu_comment_scraper

This is the scraper of xueqiu(雪球) comment under stock in Chinese stock market. 

[Xueqiu Comment example](https://xueqiu.com/S/SZ000001)

## Usage

To set the local proxy, please refer to the project [ProxyPool](https://github.com/Python3WebSpider/ProxyPool?tab=readme-ov-file)

Set the address where you want to store the data in

```bash
result_df.to_csv(r'./result/'+stock+'xueqiu.csv')
```

To change the target stock pool, please change the file 000300pool.xlsx

Then

```bash
python xueqiu_scrape.py
```
