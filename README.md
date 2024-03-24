# ImageRepository
Blog Image Repository
图床

参考： 

https://zhuanlan.zhihu.com/p/673581555

https://zhuanlan.zhihu.com/p/652533486


```json
{
  "picBed": {
    "uploader": "github",
    "current": "github",
    "github": {
      "repo": "usrfan/ImageRepository",
      "token": "token密钥",
      "path": "img/",
      // "customUrl": "https://raw.githubusercontent.com/usrfan/ImageRepository/master",
      //"customUrl": "https://cdn.jsdelivr.net/gh/usrfan/ImageRepository@master",
      // "customUrl": "https://raw.gitmirror.com/usrfan/ImageRepository/master",
      "customUrl": "https://jsd.cdn.zzko.cn/gh/usrfan/ImageRepository@master",
      // "customUrl": "https://cdn.jsdelivr.us/gh/usrfan/ImageRepository@master",
      "branch": "master"
    },
    "transformer": "path"
  },
  "picgoPlugins": {
    "picgo-plugin-rename-file": true
  },
  "picgo-plugin-gitee-uploader": {
    "lastSync": "2024-03-08 03:12:48"
  },
  "picgo-plugin-rename-file": {
    "format": "{y}/{m}/{d}/{timestamp}_{rand}_{origin}"
  }
}
```

