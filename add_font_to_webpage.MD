1 Add to the head section of web page.
<link href="https://db.onlinewebfonts.com/c/4361c3ce34740903e3af9d48d8a941ff?family=Helvetica+Neue+W01+66+Medium+It" rel="stylesheet">
or Using @import CSS directive, put the following line in add to your css file.(http | https)
@import url(https://db.onlinewebfonts.com/c/4361c3ce34740903e3af9d48d8a941ff?family=Helvetica+Neue+W01+66+Medium+It);
or Use font-face declaration Fonts.(http | https)
@font-face {
    font-family: "Helvetica Neue W01 66 Medium It";
    src: url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.eot");
    src: url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.eot?#iefix")format("embedded-opentype"),
    url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.woff2")format("woff2"),
    url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.woff")format("woff"),
    url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.ttf")format("truetype"),
    url("https://db.onlinewebfonts.com/t/4361c3ce34740903e3af9d48d8a941ff.svg#Helvetica Neue W01 66 Medium It")format("svg");
}
2 CSS rules to specify fonts
font-family: "Helvetica Neue W01 66 Medium It";
