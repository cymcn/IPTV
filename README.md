# 网络电视


GitHub 代理加速

https://ghproxy.com/

代码托管：pastebin                       

https://pastebin.com/u/xiajiang8**    

代码 短网址 IPTV：

https://wmlabs.net/


0，EPG-电子节目单：

 网站A
 http://124.223.212.38:83/
 http://124.223.212.38:83/douyu/xxx
 http://124.223.212.38:83/huya/xxx

 网站B
 http://diyp.112114.xyz/
 http://diyp.112114.xyz/douyu/yyy
 http://diyp.112114.xyz/huya/yyy

 网站C
 http://epg.112114.xyz/
 http://epg.112114.xyz/douyu/zzz
 http://epg.112114.xyz/huya/zzz



1，IPTV链接搜索引擎:

https://www.foodieguide.com/iptvsearch/



2，IPTV批量生成器：

http://tools.jb51.net/aideddesign/ljscq


3，直播源列表格式转换 - 黑鸟博客：

https://guihet.com/tvlistconvert.html

4，EPG的频道LOGO列表，实时更新：

http://epg.51zmt.top:8000/

5，EPG节目预告源地址，实时更新：

http://epg.51zmt.top:8000/e.xml

6，VLC：官方网站：

http://www.videolan.org/

7，M3U地区有效检测：

http://17ce.com/site

8，七米蓝的仓库

https://al.chirmyram.com/

9，tivimate

https://tivimatepremiumapk.com/
 

10，TVBox：

 https://raw.githubusercontent.com/cymcn/IPTV/main/TVBox%E8%AE%BE%E7%BD%AE%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95  
 
 11.用代码自动化
 
#EXTM3U x-tvg-url="https:.......epg.xml,https:.......epg.xml,.....epg.xml,......epg.xml"
#EXTINF:-1 tvg-id="AlJazeeraEnglish.qa" tvg-country="INT" tvg-language="English" tvg-logo="https:......png" group-title="News",Al Jazeera English (1080p)
https://.........m3u8

#EXTINF:-1 tvg-id="BabyTV.uk" tvg-country="INT" tvg-language="English" tvg-logo="https:......png" group-title="Kids" user-agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.131 Safari/537.36",Baby TV Asia (Vietnamese dub) (1080p)
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.131 Safari/537.36
https://livecdn.fptplay.net/hda3/babytvhd_vhls.smil/chunklist.m3u8

#EXTINF:-1 tvg-id="BBCEarthAsia.uk" tvg-country="ASIA" tvg-language="Chinese;English;Thai;Vietnamese" tvg-logo="https://i.imgur.com/xXM60fa.png" group-title="Undefined" user-agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.131 Safari/537.36",BBC Earth (Vietnamese dub) (1080p)
#EXTVLCOPT:http-user-agent=Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.131 Safari/537.36
https:/.........m3u8


#EXTM3U这一行作为文件头声明m3u8文件格式以及引用一些电子节目单，通过这个电子节目单你就可以在播放列表中看到对应资源会显示当前播放的节目。

#EXTIN 这一行是直播资源的相关信息，比如语言，节目名等。 #EXTVLCOPT 似乎可以用来指定user-agent, 并不是每一个资源都有。

http://或https://开头的行就是具体的播放资源链接了。
 
