---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
![rogo](assets/images/D3NS.png)
&nbsp;

D3NS font は流星をイメージして作られたフォントです。ファイルをダウンロード、またはCDNから利用できます。テーマについてこちらのページで紹介しています。[D3NS font's Theme][d3ns_thema]


Download
---

| format | source URL |
| woff2 | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3NS_monospaced_A2Z.woff2][D3NS_monospaced_A2Z.woff2] |
# | woff | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3NS_monospaced_A2Z.woff][D3NS_monospaced_A2Z.woff] |
# | svg | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3NS_monospaced_A2Z.svg][D3NS_monospaced_A2Z.svg] |
# | TrueType | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3NS_monospaced_A2Z.ttf][D3NS_monospaced_A2Z.ttf] |
# | OpenType | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3NS_monospaced_A2Z.otf][D3NS_monospaced_A2Z.otf] |
# | woff | [https://github.com/tsukasa-u/D3NS/blob/main/font/D3DN.woff][d3ns_woff] |

CDN
---
css exmaple
{% highlight css %}
@font-face {
    font-family: 'D3NS';
    src: url("https://cdn.jsdelivr.net/gh/tsukasa-u/D3NS@main/font/D3DN.woff") format('woff');
}
body {
    font-family:'D3NS';
}
{% endhighlight %}

Caution
---
D3NS fontは2022/12/18現在、D, N, e, o, s の5文字のみ実装されています。カーニングはまだしてないです…。

[d3ns_woff]: https://github.com/tsukasa-u/D3NS/raw/main/font/D3DN.woff
[d3ns_thema]: theme/
