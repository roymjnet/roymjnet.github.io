### MJQR | QR Code scanner for login hotspot MikroTik

#### Cara pakai

1. Tambahkan button di login.html

```html
<button onclick="window.location='https://roymjnet.github.io/mjqr';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.

```
/ip hotspot walled-garden ip
add action=accept comment="MJNET QR Code Scanner" disabled=no dst-host=roymjnet.github.io

```
3. Centang HTTP PAP di hotspot server profile.

![HTTPS PAP MikroTik](./img/mjqr-http-pap.png "HTTPS PAP MikroTik")

>_QR Code Scanner hanya bisa dipakai pada browser yang memiliki hak akses kamera._

<div>
	<script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
	<!-- ads3 -->
	<ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-17239884" data-ad-slot="472"
	 data-ad-format="auto" data-full-width-responsive="true"></ins>
	<script>
		(adsbygoogle = window.adsbygoogle || []).push({});
	</script>
</div>


![MYQR | QR code scanner](./img/mjqr.jpg "MJQR | QR code scanner")


Powered by [webqr.com](//webqr.com)

