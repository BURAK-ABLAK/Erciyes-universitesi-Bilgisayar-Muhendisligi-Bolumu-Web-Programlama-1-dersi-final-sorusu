# Erciyes-niversitesi-Bilgisayar-M-hendisli-i-B-l-m-Web-Programlama-1-dersi-final-sorusu
Sayın Dr. Öğr. Üyesi Fehim KÖYLÜ Hocamızın isteği üzerine yapılmıştır.
<div class="block">
    <div class="urun">
        <img src="resim/urun.jpg">
            <div class="buton">
            <a class="satin-al" href="#">Sepete Ekle</a>
            <a class="on-izleme" href="#">Ürünü İncele</a>
        </div>
    </div>
 
    <div class="bilgi">
        <h4>BŞ Alışveriş Uygulaması<br /> # 5 Farklı Renk Seçeneği # 100% Valid</h4>
        <span class="aciklama">
        </span>
        <span class="fiyat">49.99</span>
        <a class="satin-al_s" href="#">Satın Al</a>
    </div>
 
    <div class="detaylar">
        <span class="zaman">12 dakika önce</span>
        <ul class="oylama">
            <li class="oylandi"></li>
            <li class="oylandi"></li>
            <li class="oylandi"></li>
            <li class="oylandi"></li>
            <li></li>
        </ul>
    </div>
</div>
@font-face {
    font-family: 'AbakuTLSymSansRegular';
    src: url('../font/abakutlsymsans.eot');
    src: url('../font/abakutlsymsans.eot?#iefix')format('opentype'),
            url('../font/abakutlsymsans.woff')format('woff'),
            url('../font/abakutlsymsans.ttf')format('truetype'),
            url('../font/abakutlsymsans.svg#AbakuTLSymSansRegular')format('svg');
    font-weight: normal;
    font-style: normal;
}

.urun {
    display: block;
    position: relative;
}

.urun img {
    width: 100%;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
}
.bilgi {
    display: block;
    position: relative;
    padding: 20px;
}
 
.detaylar {
    border-top: 1px solid #e5e5e5;
    padding: 18px 20px;
}
.buton {
    display: block;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    background: rgba(255, 255, 255, .5);
    opacity: 0;
    -webkit-transition: opacity .25s ease-in;
    -ms-transition: opacity .25s ease-in;
    -moz-transition: opacity .25s ease-in;
    -o-transition: opacity .25s ease-in;
    transition: opacity .25s ease-in;
}
 
.urun:hover .buton, .urun:hover a {
    opacity: 1;
}
.buton a {
    display: block;
    position: absolute;
    left: 50px;
    width: 115px;
    border-radius: 2px;
    padding: 15px 10px 15px 65px;
    font-family: Helvetica, sans-serif;
    font-size: 15px;
    font-weight: bold;
    text-transform: uppercase;
    color: #fff;
    text-decoration: none;
    opacity: 0;
}
 
.buton a::after {
    content: &quot;&quot;;
    display: block;
    position: absolute;
    height: 48px;
    width: 50px;
    border-right: 1px solid rgba(0, 0, 0, .25);
    box-shadow: 1px 0 0 rgba(255, 255, 255, .17);
    top: 0;
    left: 0;
    z-index: 1;
}
a.satin-al {
    top: 20%;
    background: #414141;
    background: rgba(0, 0, 0, .85);
    -webkit-transition: background .2s ease-in;
    -ms-transition: background .2s ease-in;
    -moz-transition: background .2s ease-in;
    -o-transition: background .2s ease-in;
    transition: background .2s ease-in;
}
.satin-al:hover {
    background: #515151;
    background: rgba(45, 45, 45, .85);
}
.satin-al::after {
    background: url(&quot;../resim/sepete-ekle.png&quot;);
    background-repeat: no-repeat;
    background-position: 16px 18px;
}
a.on-izleme {
    bottom: 20%;
    text-shadow: 0 -1px 1px rgba(0, 0, 0, .4);
 
    background: #286398;
    background: -webkit-linear-gradient(bottom, #1d4970, #639ed3);
    background: -ms-linear-gradient(bottom, #286398, #639ed3);
    background: -moz-linear-gradient(bottom, #286398, #639ed3);
    background: -o-linear-gradient(bottom, #286398, #639ed3);
    background-position: 0 -15px;
    background-size: 400px 80px;
    background-repeat: no-repeat;
    box-shadow: 0 2px 0 #165181;
 
    -webkit-transition: background-position .2s ease-in;
    -ms-transition: background-position .2s ease-in;
    -moz-transition: background-position .2s ease-in;
    -o-transition: background-position .2s ease-in;
    transition: background-position .2s ease-in;
}
 
.on-izleme:hover, .satin-al_s:hover {
    background-position: 0 0;
}
 
.on-izleme:active, .satin-al_s:active {
    -webkit-transform: translateY(2px);
    -ms-transform: translateY(2px);
    -moz-transform: translateY(2px);
    -o-transform: translateY(2px);
    transform: translateY(2px);
    box-shadow: none;
}
.on-izleme::after {
    background: url(&quot;../resim/on-izleme.png&quot;);
    background-repeat: no-repeat;
    background-position: 16px 17px;
}
.bilgi::after {
    display: block;
    position: absolute;
    top: -12px;
    left: 23px;
    content: &quot;&quot;;
    width: 15px;
    height: 15px;
    background: #fff;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}
.bilgi h4 {
    position: relative;
    padding: 0 0 20px 0;
    margin: 0 0 20px 0;
    font-family: &quot;Open Sans&quot;, sans-serif;
    font-weight: 700;
    font-size: 15px;
    line-height: 25px;
    color: #372f2b;
    letter-spacing: -1px;
}
 
.bilgi h4::after {
    display: block;
    position: absolute;
    bottom: 0px;
    content: &quot;&quot;;
    width: 40px;
    height: 2px;
    background: #3b86c4;
}
.bilgi .aciklama {
    display: block;
    padding-bottom: 20px;
    font-family: &quot;Open Sans&quot;, sans-serif;
    font-size: 14px;
    font-weight: 600;
    color: #5f5f5f;
}
.bilgi .fiyat {
    font-family: &quot;Open Sans&quot;, Helvetica, Arial, sans-serif;
    font-size: 24px;
    font-weight: 700;
    color: #372f2b;
    line-height: 26px;
}
.fiyat:before {
    font-family: &quot;AbakuTLSymSansRegular&quot;;
    content: &quot;t&quot;;
    padding-right: 5px;
}
.zaman {
    padding-left: 25px;
    font-family: &quot;Open Sans&quot;, sans-serif;
    font-size: 14px;
    font-weight: 700;
    color: #372f2b;
    background: url(&quot;../resim/tarih.png&quot;) no-repeat;
    background-position: 0 2px;
}
.oylama {
    position: relative;
    top: 2px;
    float: right;
    margin: 0;
    padding: 0;
}
.oylama li {
    float: left;
    display: block;
    height: 16px;
    width: 16px;
    margin-left: 5px;
    background: url(&quot;../resim/puan.png&quot;) no-repeat 0 0;
}
 
.oylama li.oylandi {
    background-position: 0px -16px;
}
