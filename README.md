# 755-Crawler
A web crawler that visit [755 website][1] for download photo and video.

Last Modified: 2018.11.28

## Requirements
* Python >= 3.6, 3.7
* requests >= 2.20.1

## How to Use
#### [Run by source code]
```
$ git clone https://github.com/grtfou/755-crawler.git
$ cd 755-crawler
$ pip install -r requirements.txt

$ python crawler.py <url> <start_download_post_date>

# ex.
# 1. Default only download today
$ python crawler.py https://7gogo.jp/hori-miona

# 2. Download if the post after 181101
$ python crawler.py https://7gogo.jp/kuranoo-narumi 181101
```

## License
MIT License

[1]: http://7gogo.jp "755"
