# YAPIC - Yet another python image crawler #

Just execute `python crawler.py http://start-url-to-crawl`

Specify options in `config.ini`:

    ; start url for crawler
    starturl=http://pic.kdslife.com/
    
    ; regexes for links and image urls
    linkregex=http://pic.kdslife.com/content_.*.html
    imgregex=http://img.club.pchome.net/.*.jpg
    
    ; integer>=1, larger politeness means slower crawling
    ; but also less likely to be denied service
    politeness=3
    
    ; the directory to store the downloaded images
    imgdir=E:/kds/
    
    ; the min size of images that you want to download
    minwidth=200
    minheight=200
     