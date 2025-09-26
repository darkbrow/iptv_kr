# iptv_kr

기본적인 iptv 채널을 모아놓은 파일입니다.

## 플레이리스트
```
https://raw.githubusercontent.com/darkbrow/iptv_kr/refs/heads/main/KOR-TV-Rev1.m3u
```
다음 파일을 참조하여 작성했습니다.

https://github.com/skylover007/iptv/blob/main/kor.m3u

https://github.com/iptv-org/iptv/blob/master/streams/kr.m3u

## EPG
```
https://raw.githubusercontent.com/darkbrow/iptv_kr/refs/heads/main/kr_epg.xml.gz
```
EPG 파일은 2, 3일 간격으로 업데이트할 예정입니다.

[epg2xml](https://github.com/epg2xml/epg2xml)을 사용해서 생성했습니다.
```
epg2xml run --config epg2xml.json --xmlfile kr_epg.xml
```
