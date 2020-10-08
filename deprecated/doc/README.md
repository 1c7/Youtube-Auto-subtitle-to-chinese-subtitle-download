## 文档
备忘


## 2020-10-7

## 启用自动字幕时发出的请求
返回的是一个 json
```
https://www.youtube.com/api/timedtext?v=Z1fyeIFaEN8&asr_langs=de%2Cen%2Ces%2Cfr%2Cit%2Cja%2Cko%2Cnl%2Cpt%2Cru&caps=asr&xorp=true&xoaf=5&hl=zh-CN&ip=0.0.0.0&ipbits=0&expire=1602072316&sparams=ip%2Cipbits%2Cexpire%2Cv%2Casr_langs%2Ccaps%2Cxorp%2Cxoaf&signature=2524109ADE0B6539AB442F49FBFB4180C8311CD9.E25B3E1519D29D417E6C75D265EAC8F875C18F55&key=yt8&kind=asr&lang=en&fmt=json3&xorb=2&xobt=3&xovt=3
```

## 获取播放器的配置 JSON
var raw_string = ytplayer.config.args.player_response;
json = JSON.parse(raw_string);


