<h3 align="center">
  
  <p align="center"><img src="https://img.shields.io/badge/𝗪𝗟𝗖𝗠 𝗧𝗢 -𝗔𝗟𝗜𝗙 𝗔𝗟𝗟 𝗗𝗢𝗪𝗡𝗟𝗢𝗔𝗗𝗘𝗥-green?colorA=%23ff0000&colorB=%23017e40&style=flat-square">
    
</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Neuton&size=25&color=30FF40&background=000000&center=true&vCenter=true&width=360&height=60&lines=Hello+Worl+I'm+ALIF-HOSSON+Here+🥵;𝙸𝚃'𝚜+𝙽𝙾𝚃+𝙰+𝙹𝚄𝚂𝚃+𝙽𝙰𝙼𝙴+𝙱𝚁𝙾+😼;𝙸𝚃'𝚜+𝙰+𝙱𝚁𝙰𝙽𝙳+🔥;Respect+Alif-Hosson+🥀;Thanks+My+All+Friend+😙+😌)](https://git.io/typing-svg)

[![npm version](https://img.shields.io/npm/v/alif-all-downloader.svg?style=flat-square)](https://www.npmjs.com/package/alif-all-downloader)
[![GitHub version](https://img.shields.io/github/package-json/v/Alifhosson/alif-all-downloader?label=github&style=flat-square)](https://github.com/Alifhosson/alif-all-downloader)
[![npm downloads](https://img.shields.io/npm/dm/alif-all-downloader.svg?style=flat-square)](https://www.npmjs.com/package/alif-all-downloader)
[![jsDelivr](https://data.jsdelivr.com/v1/package/npm/alif-all-downloader/badge)](https://www.jsdelivr.com/package/npm/alif-all-downloader)

[![GitHub contributors](https://img.shields.io/github/contributors/Alifhosson/alif-all-downloader)](https://github.com/Alifhosson/alif-all-downloader/graphs/contributors) [![GitHub issues](https://img.shields.io/github/issues/Alifhosson/alif-all-downloader)](https://github.com/Alifhosson/alif-all-downloader/issues) [![HitCount](https://views.whatilearened.today/views/github/Alifhosson/alif-all-downloader.svg)](https://github.com/Alifhosson/alif-all-downloader)


## Instalation :
```bash
> npm i alif-all-downloader
```
## Last Update 
```print
• pintarest (fix)
• capcut (fix)
```

## Example (install)
```js
const alif = require("alif-all-downloader");

const videoUrl = "https://www.facebook.com/reel/1013006933531489/"; // Provide your video link.

alif.alldown(videoUrl)
  .then((data) => {
    console.log(data)
  })
  .catch((error) => {
    console.error("Error:", error.message);
  });
```
## Output Example
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "status": true,
    "data": [
        {
            "resolution": "720p (HD)",
            "thumbnail": "https://scontent-ber1-1.xx.fbcdn.net/v/t15.5256-10/400486200_1343033686353383_5174403316165836536_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=dd673f&_nc_ohc=2xRWTn71BMQAX8u2-qw&_nc_ht=scontent-ber1-1.xx&oh=00_AfCzw-5oUCmwmFGGT3_tmPTy0KTuYtmMD4--Ed1gZbXubg&oe=6586FB4E",
            "url": "https://video-ber1-1.xx.fbcdn.net/o1/v/t2/f1/m69/",
            "shouldRender": false
        }
    ]
}
```
## Instagram Usage 
```js
const {instagram} = require("alif-all-downloader");

const link = "https://www.instagram.com/p/DAxzjkAyWOm/?igsh=MTZ5eThrMXpteTFpOA==" //past video link

  instagram(link).then(data => {

    console.log(data)

});
```
## Example (TikTok)
```js
const { tikdown } = require("alif-all-downloader")
let URL = await tikdown("https://vt.tiktok.com/ZSNvs6h6o/")
console.log(URL)
```
## Output Example (tikTok)
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "status": true,
    "data": {
        "author": {
            "id": "7021670496278447110",
            "unique_id": "rowdy__baby_212",
            "nickname": "Rasel_official_97⚡",
            "avatar": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-avt-0068/d673e8357d05f3599741c7c974ec3e9a~c5_300x300.jpeg?lk3s=45126217&x-expires=1704636000&x-signature=z2SNWwaql50uUONx2NIzt8Pn8GY%3D"
    }
}
```
## Example (YouTube)
```js
const { ytdown } = require("alif-all-downloader")
let URL = await ytdown("https://youtu.be/aRSuyrZFu_Q?si=bsfzgeeGmRpsHqnF")
console.log(URL)
```
## Example (Twitter)
```js
const { twitterdown } = require("alif-all-downloader")
let URL = await twitterdown("https://twitter.com/TeamAbhiSha/status/1743351410761019794?t=vms8wxcU0mQuhVxwGCHjFw&s=19")
console.log(URL)
```
## Output Example (Twitter)
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "status": true,
    "data": {
        "HD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/810x720/gKWI2KEyLdRMQBFa.mp4?tag=12",
        "SD": "https://video.twimg.com/ext_tw_video/1743351351898181632/pu/vid/avc1/404x360/dtDrE8AqyxXhoRhO.mp4?tag=12"
    }
}
```
## Example Fbdown 
```js
const { fbdown } = require("alif-all-downloader");
const request = require('request')

const key = "Alif" //dont change key

const cookie = "cookie" //past your fb cookie here

const link = "url" //past video link

fbdown(link, cookie, key).then(data => {
  console.log(data)
});
```
## Output Example (fbdown)
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "url": "https://www.facebook.com/saroj.dwivedi.7121/videos/691539259851175/?idorvanity=213813760197847",
    "thumbnail": "https://scontent.fkul8-4.fna.fbcdn.net/v/t15.5256-10/427275886_286050634275782_6523162309266122490_n.jpg?stp=dst-jpg_p960x960&_nc_cat=104&ccb=1-7&_nc_sid=dd673f&_nc_ohc=8gfhuR00MokAX9K7Xoa&_nc_ht=scontent.fkul8-4.fna&oh=00_AfA0TUr_aw2q146jhqW3Fs-Yd5z0C3O75Hthf7qdLbXKmg&oe=65DB995F",
    "status": true,
    "media": {
        "title": "The real master.\\ud83d\\ude06\\ud83d\\ude06",
        "hd": "https://video.fkul8-2.fna.fbcdn.net/o1/v/t2/f1/m69/GAflixlLP9JH0IMCAFfy"
}
 ```
## Example Fbdown2
```js
const { fbdown2 } = require("alif-all-downloader");
const request = require('request')

const key = "Alif" //dont change key

const link = "url" //past video link

fbdown2(link, key).then(data => {
  console.log(data)
});
```
## Output Example (fbdown2)
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "status": true,
    "media": {
               title: video title,
                hd: Hd video link,
                sd: normal video link
              }
}
```

## Usage GDLink 
```js
const {GDLink} = require("alif-all-downloader");

const url = 'url' // Public Google Drive Url

GDLink(url).then(data => {
  console.log(data)

});
```
## Usage Pintarest 
```js
const {pintarest} = require("alif-all-downloader");

const url = 'url' // pintarest post url

  pintarest(url).then(data => {
  console.log(data)
    });
```
## Usage CapCut 
```js
const { capcut } = require("alif-all-downloader");

const url = "link" // capcut link

capcut(url).then(data => {
  console.log(data)
});
```
## Usage Likee 
```js
const { likee} = require("alif-all-downloader");

 const url = "link" // past url
likee(url).then(data => { 
  console.log(data) 
});
```
## Usage Threads
```js
const { threads } = require("alif-all-downloader");

 const url = "link" // past url
threads(url).then(data => { 
  console.log(data) 
});
```
## Usage All Media Down
```bash
support url: facebook, tiktok, twitter, instagram, youtube, pinterest, gdrive, capcut, likee, threads
note: Let me know if any of the platforms you use are missing
```
```js
const {alldown} = require("alif-all-downloader");
const url = 'url' // past url

  alldown(url).then(data => {
  console.log(data)
    });
```
## Output Example (alldown)
```
{
    "developer": "𝗔𝗟𝗜𝗙 𝗛𝗢𝗦𝗦𝗢𝗡",
    "devfb": "https://www.facebook.com/100075421394195",
    "devwp": "wa.me/+8801615623399",
    "status": true,
    "media": {
        "title": "video title",
        "low": "normal video link",
        "high": "hd video link"
    }
}
```

[![WhatsApp](https://img.shields.io/badge/WhatsApp-green?style=for-the-badge&logo=whatsapp)](https://wa.me/+8801615623399)
[![Facebook](https://img.shields.io/badge/Facebook-green?style=for-the-badge&logo=facebook)](https://www.facebook.com/100075421394195)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/100075421394195)
[![Github](https://img.shields.io/badge/Github-MrDarkYTgreen?style=for-the-badge&logo=github)](https://github.com/Alifhosson)

