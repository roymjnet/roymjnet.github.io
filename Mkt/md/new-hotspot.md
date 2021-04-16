### Template Hotspot 

New Template Hotspot  base on default hotspot MikroTik v6.47

----

#### New Hotspot 01

![](./img/new-hotspot-01.png)

config : edit file conf.js

- setCase : untuk mengatur input huruf besar(uppercase) atau huruf kecil(lowercase).
- defaultMode : mengatur tampilan utama login page, voucher atau member(user & password).

```javascript
var config = {

loginvc : "Masukkan Kode Voucher kemudian klik Connect.",
loginup : "Masukkan Username dan Password <br> kemudian klik Connect.",
voucherCode : "Kode Voucher",
setCase : "none", // lowercase, uppercase or none
defaultMode : "voucher", // voucher or member
theme : "default", // default, dark, lite

}
```


[![](./assets/img/book.png) Kumpulan template lama](./?templatehotspot)
