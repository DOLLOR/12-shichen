# 12-shichen
十二时辰转换|Convert time to Chinese 12 hours / Shichen

time2shiChen(hour:number, minute:number) : [''shichen, 'chu or zheng', 'ke']
time2shiChen(hour:number, minute:number) : ['hour', 'former or formal', 'quarter']
time2shiChen(时:number, 分:number) : ['时辰', '初或正', '刻']
```javascript
time2shiChen(17,10)//=>["酉", "初", "初"]
time2shiChen(0,15)//=>["子", "正", "一"]
time2shiChen(12,45)//=>["午", "正", "三"]
```
