# How it works

Deep mode: what the site's JavaScript is made of and what its start page did while we watched.

## Its JavaScript

Analysed 16 script(s) from https://www.larkplayer.com/: 15 module(s), 58 endpoint(s), 3 route(s), bundled with webpack.

Evidence ev_4e33966391495cf1db745f1671e4b9beb45638e7bb74302b6de1279e6dd88b40.

```json
{
  "api_operations": [],
  "app_kind": "unknown",
  "bundlers": [
    "webpack"
  ],
  "edges": [
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1450",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1450@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1450"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1664"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3357"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3967"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4374"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#7294"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#8196"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a.Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#e@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1824",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#onClick@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a.Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#onClick@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3967"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4645"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#d@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#h@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#l@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#m@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#u@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3357"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#339"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3967"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4374"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#7294"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#_@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a.Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#e@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2472",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#onClick@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#339",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#339@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#224"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3967"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#9145"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#_@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#d@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#p@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#s@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4439",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#u@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4645",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4645@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#474",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#474@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#8348",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#8348@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1163"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#1664"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#2223"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#3967"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#4374"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#474"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#5893"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#7294"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#8196"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "requires",
      "to": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#9755"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a.Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#a@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#j@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#onClick@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#857",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#onKeyDown@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#9145",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js#9145@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#$@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#F@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#H@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#J@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#K@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#W@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#X@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#Z@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#ii.ua.get@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#ii.ua.set@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#this.getBrowser@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
      "to": "fn:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#this.getCPU@1"
    },
    {
      "from": "bundle-module:www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js#2238",
      "kind": "defines",
     
```

## Ten seconds of it

Watched https://www.larkplayer.com/ for 10000ms: 0 request outline(s), 2 console entr(y/ies).

Evidence ev_c06b89a3b77d286e5503f12ba8e78b3496373efefc6c1b52a78099805e341eaa.

```json
{
  "accessibility": null,
  "console": {
    "count": 2,
    "entries": [
      {
        "level": "error",
        "source": "network"
      },
      {
        "level": "error",
        "source": "network"
      }
    ],
    "has_text": false
  },
  "dom": {
    "attribute_names": [
      "alt",
      "aria-controls",
      "aria-describedby",
      "aria-expanded",
      "aria-hidden",
      "aria-label",
      "aria-labelledby",
      "aria-live",
      "aria-pressed",
      "aria-selected",
      "aria-valuemax",
      "aria-valuemin",
      "aria-valuenow",
      "aria-valuetext",
      "as",
      "charset",
      "class",
      "clip-rule",
      "content",
      "crossorigin",
      "cx",
      "cy",
      "d",
      "data-cue",
      "data-current",
      "data-direction",
      "data-dragging",
      "data-feature-region",
      "data-home-reviews",
      "data-immersed",
      "data-liked",
      "data-lyrics",
      "data-mode",
      "data-motion-state",
      "data-n-css",
      "data-n-g",
      "data-n-p",
      "data-next-font",
      "data-nimg",
      "data-on",
      "data-panel",
      "data-phase",
      "data-preview-state",
      "data-reached",
      "data-reveal",
      "data-rh",
      "data-shown",
      "data-small",
      "data-tab",
      "data-visible",
      "data-wide",
      "decoding",
      "defer",
      "dir",
      "draggable",
      "fill",
      "fill-opacity",
      "fill-rule",
      "height",
      "hidden",
      "href",
      "hreflang",
      "id",
      "imagesizes",
      "imagesrcset",
      "lang",
      "loading",
      "loop",
      "muted",
      "name",
      "nomodule",
      "pathlength",
      "playsinline",
      "poster",
      "preload",
      "preserveaspectratio",
      "property",
      "r",
      "rel",
      "role",
      "rx",
      "sizes",
      "src",
      "srcset",
      "stroke",
      "stroke-dasharray",
      "stroke-dashoffset",
      "stroke-linecap",
      "stroke-linejoin",
      "stroke-opacity",
      "stroke-width",
      "style",
      "tabindex",
      "target",
      "type",
      "viewbox",
      "width",
      "x",
      "xmlns",
      "y"
    ],
    "elements_by_name": {
      "a": 33,
      "article": 8,
      "audio": 1,
      "b": 6,
      "bdi": 1,
      "body": 1,
      "button": 61,
      "canvas": 17,
      "circle": 15,
      "div": 332,
      "figcaption": 1,
      "figure": 1,
      "footer": 1,
      "h1": 1,
      "h2": 7,
      "h3": 18,
      "head": 1,
      "header": 1,
      "html": 1,
      "i": 50,
      "img": 132,
      "li": 10,
      "link": 25,
      "main": 1,
      "meta": 9,
      "nav": 1,
      "next-route-announcer": 1,
      "noscript": 29,
      "p": 66,
      "path": 43,
      "rect": 10,
      "script": 18,
      "section": 7,
      "small": 6,
      "span": 415,
      "strong": 20,
      "sup": 1,
      "svg": 39,
      "title": 1,
      "ul": 2,
      "video": 1
    },
    "text_nodes": 315,
    "total_nodes": 1711,
    "truncated": false
  },
  "dropped_events": 0,
  "frame_origins": [
    "https://www.larkplayer.com"
  ],
  "network": {
    "request_count": 0,
    "requests": []
  },
  "origin": "https://www.larkplayer.com/",
  "resources": [
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic3-5.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20800%20360%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M731.2%200c24.082%200%2036.123%200%2045.322%204.687a43%2043%200%200%201%2018.792%2018.792c4.687%209.198%204.687%2021.239%204.687%2045.322L800%20291.2c0%2024.082%200%2036.123%20-4.687%2045.322a43%2043%200%200%201%20-18.792%2018.792c-9.198%204.687%20-21.239%204.687%20-45.322%204.687L68.8%20360c-24.082%200%20-36.123%200%20-45.322%20-4.687a43%2043%200%200%201%20-18.792%20-18.792c-4.687%20-9.198%20-4.687%20-21.239%20-4.687%20-45.322L0%2068.8c0%20-24.082%200%20-36.123%204.687%20-45.322a43%2043%200%200%201%2018.792%20-18.792c9.198%20-4.687%2021.239%20-4.687%2045.322%20-4.687Z%22%2F%3E%3C%2Fsvg%3E"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-drive.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic2-5.webp"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/pLce1EyqDmFSdIcX6rgnT/_buildManifest.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%27592%27%20height=%27518%27/%3e"
    },
    {
      "mime_type": "image/gif",
      "type": "Image",
      "url": "data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-like-filled.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20376%20816%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M294.4%200c28.563%200%2042.844%200%2053.754%205.559a51%2051%200%200%201%2022.288%2022.288c5.559%2010.909%205.559%2025.191%205.559%2053.754L376%20734.4c0%2028.563%200%2042.844%20-5.559%2053.754a51%2051%200%200%201%20-22.288%2022.288c-10.909%205.559%20-25.191%205.559%20-53.754%205.559L81.6%20816c-28.563%200%20-42.844%200%20-53.754%20-5.559a51%2051%200%200%201%20-22.288%20-22.288c-5.559%20-10.909%20-5.559%20-25.191%20-5.559%20-53.754L0%2081.6c0%20-28.563%200%20-42.844%205.559%20-53.754a51%2051%200%200%201%2022.288%20-22.288c10.909%20-5.559%2025.191%20-5.559%2053.754%20-5.559Z%22%2F%3E%3C%2Fsvg%3E"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic-bg-all.webp"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-3-m.webp"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.googletagmanager.com/gtm.js?id=GTM-5L9P3R3"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-eq.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-4.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2748%27%20height=%2748%27/%3e"
    },
    {
      "mime_type": "text/css",
      "type": "Stylesheet",
      "url": "https://www.larkplayer.com/_next/static/css/bd381f7aed1aa5a8.css"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-video.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-loop.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-menu-shuffer.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-2-m.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-next-song.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-menu1.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20360%20800%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M291.2%200c24.082%200%2036.123%200%2045.322%204.687a43%2043%200%200%201%2018.792%2018.792c4.687%209.198%204.687%2021.239%204.687%2045.322L360%20731.2c0%2024.082%200%2036.123%20-4.687%2045.322a43%2043%200%200%201%20-18.792%2018.792c-9.198%204.687%20-21.239%204.687%20-45.322%204.687L68.8%20800c-24.082%200%20-36.123%200%20-45.322%20-4.687a43%2043%200%200%201%20-18.792%20-18.792c-4.687%20-9.198%20-4.687%20-21.239%20-4.687%20-45.322L0%2068.8c0%20-24.082%200%20-36.123%204.687%20-45.322a43%2043%200%200%201%2018.792%20-18.792c9.198%20-4.687%2021.239%20-4.687%2045.322%20-4.687Z%22%2F%3E%3C%2Fsvg%3E"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic3-6.webp"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/pages/index-6b5946c0cdd58438.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-logo.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-backup-arrow.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-setting.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/pages/_app-07b5b893d73bc84f.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/google-play/en.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-wordmark.svg"
    },
    {
      "mime_type": "image/png",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-cover-midnight.png"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/300-451b9d65507a9413.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-device-phone.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/238-a824d31c788e5251.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-search.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/framework-64ad27b21261a9ce.js"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/121-ed9d1900f1432c70.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-last-song.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-7.webp"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic3-2-m.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-backup-cloud.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-play.svg"
    },
    {
      "mime_type": "image/png",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-cover-silence.png"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-5.webp"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/766-71114a298ec3be48.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-ic-left.svg"
    },
    {
      "mime_type": "image/png",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/cover-welcome.png"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20822%20382%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M735.6%200c30.243%200%2045.364%200%2056.915%205.886a54%2054%200%200%201%2023.599%2023.599c5.886%2011.551%205.886%2026.673%205.886%2056.915L822%20295.6c0%2030.243%200%2045.364%20-5.886%2056.915a54%2054%200%200%201%20-23.599%2023.599c-11.551%205.886%20-26.673%205.886%20-56.915%205.886L86.4%20382c-30.243%200%20-45.364%200%20-56.915%20-5.886a54%2054%200%200%201%20-23.599%20-23.599c-5.886%20-11.551%20-5.886%20-26.673%20-5.886%20-56.915L0%2086.4c0%20-30.243%200%20-45.364%205.886%20-56.915a54%2054%200%200%201%2023.599%20-23.599c11.551%20-5.886%2026.673%20-5.886%2056.915%20-5.886Z%22%2F%3E%3C%2Fsvg%3E"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-ic-more.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic2-2-m.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/ic-like.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/94726e6d-4274838723863c7e.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/landscape-needle.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/status-icons.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/native/ic-night.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/465-21db8b11a99a5e7d.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2744%27%20height=%2744%27/%3e"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic1-6-wallpaper.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20382%20822%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M295.6%200c30.243%200%2045.364%200%2056.915%205.886a54%2054%200%200%201%2023.599%2023.599c5.886%2011.551%205.886%2026.673%205.886%2056.915L382%20735.6c0%2030.243%200%2045.364%20-5.886%2056.915a54%2054%200%200%201%20-23.599%2023.599c-11.551%205.886%20-26.673%205.886%20-56.915%205.886L86.4%20822c-30.243%200%20-45.364%200%20-56.915%20-5.886a54%2054%200%200%201%20-23.599%20-23.599c-5.886%20-11.551%20-5.886%20-26.673%20-5.886%20-56.915L0%2086.4c0%20-30.243%200%20-45.364%205.886%20-56.915a54%2054%200%200%201%2023.599%20-23.599c11.551%20-5.886%2026.673%20-5.886%2056.915%20-5.886Z%22%2F%3E%3C%2Fsvg%3E"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic2-7-wallpaper.webp"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic2-4.webp"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/main-11033db4c2e2b60d.js"
    },
    {
      "mime_type": "image/jpeg",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/mv-allday.jpg"
    },
    {
      "mime_type": "image/png",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/hero-cover-polaroids.png"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3csvg%20xmlns=%27http://www.w3.org/2000/svg%27%20version=%271.1%27%20width=%2720%27%20height=%2720%27/%3e"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/native/ic-lightness.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic3-3-m.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-ic-restore.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic3-4.webp"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic2-6-m-wallpaper.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/native/ic-volume-loud.svg"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/larkplayer-logo.svg"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/chunks/webpack-527576ff117bb29f.js"
    },
    {
      "mime_type": "image/png",
      "type": "Image",
      "url": "https://www.larkplayer.com/_next/image/?url=%2F_next%2Fstatic%2Fassets%2Fd6e4a3b91d308444c84d6dbfc38dce91.png&w=828&q=75"
    },
    {
      "mime_type": "application/javascript",
      "type": "Script",
      "url": "https://www.larkplayer.com/_next/static/pLce1EyqDmFSdIcX6rgnT/_ssgManifest.js"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/import-ic-connected.svg"
    },
    {
      "mime_type": "image/webp",
      "type": "Image",
      "url": "https://www.larkplayer.com/images/features-2027/theme-pre/pic-frame-all.webp"
    },
    {
      "mime_type": "image/svg+xml",
      "type": "Image",
      "url": "data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20816%20376%22%20preserveAspectRatio%3D%22none%22%3E%3Cpath%20d%3D%22M734.4%200c28.563%200%2042.844%200%2053.754%205.559a51%2051%200%200%201%2022.288%2022.288c5.559%2010.909%205.559%2025.191%205.559%2053.754L816%20294.4c0%2028.563%200%2042.844%20-5.559%2053.754a51%2051%200%200%201%20-22.288%2022.288c-10.909%205.559%20-25.191%205.559%20-53.754%205.559L81.6%20376c-28.563%200%20-42.844%200%20-53.754%20-5.559a51%2051%200%200%201%20-22.288%20-22.288c-5.559%20-10.909%20-5.559%20-25.191%20-5.559%20-53.754L0%2081.6c0%20-28.563%200%20-42.844%205.559%20-53.754a51%2
```
