<div align="center">

## Bust the cache\!


</div>

### Description

This code allows you to force a page to reload from the server, rather than the user's browser cache. You can use this to make sure the content the user sees is always current.

http://www.truegeeks.com/asp/mam/osdoc/osframe.asp
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Found on the World Wide Web](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/found-on-the-world-wide-web.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/found-on-the-world-wide-web-bust-the-cache__4-41/archive/master.zip)





### Source Code

```
<%Response.Expires = -1
Response.AddHeader "Pragma", "no-cache"
Response.AddHeader "cache-control", "no-store"
%>
```

