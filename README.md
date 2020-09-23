<div align="center">

## External frame killer


</div>

### Description

This code will ensure that if anyone accesses your page from frames it will get rid of them....
 
### More Info
 
If you are using frames then only put this on your main frame page (before the <frameset> stuff) or a pre-site page...


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Java\_Hunter](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/java-hunter.md)
**Level**          |Unknown
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/java-hunter-external-frame-killer__2-1679/archive/master.zip)





### Source Code

```
// designed by Java_Hunter (java_hunter@hotmail.com)
if (window != window.top) top.location.href = location.href;
```

