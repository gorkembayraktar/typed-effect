
![](typed-anime.gif)


DEMO
[Codepen örnek](https://codepen.io/pfoduk/pen/yZgXQX)

Kullanýmý


1.Seçici id tipinde olmalýdýr.
2.Seçicinin alt itemlarýnda <text></text>
 olmalýdýr.
3.Seçici seçildikten sonra .run(); denilerek
script aktif edilmelidir.


html tarafýnda

<div id="typed">
	<text>Metin</text>
</div>


script tarafýnda

$("#typed").run();