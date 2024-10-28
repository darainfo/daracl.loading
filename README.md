# Loading

Simple loading message

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/darainfo/@daracl%2Floading/blob/main/LICENSE)
[![npm version](https://badge.fury.io/js/@daracl%2Floading.svg)](https://img.shields.io/npm/v/@daracl%2Floading)
[![npm](https://img.shields.io/npm/dt/@daracl%2Floading)](https://github.com/darainfo/daracl.loading/releases)
[![minzipped size](https://img.shields.io/bundlephobia/minzip/@daracl%2Floading)](https://bundlephobia.com/package/@daracl%2Floading)


## Browser Support

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Internet Explorer](https://raw.githubusercontent.com/alrra/browser-logos/main/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png)  
--- | --- | --- | --- | --- |  --- | 
Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |   ie 11 > |


<p>
<img src="https://github.com/darainfo/daracl.loading/blob/main/demo.gif?raw=true"/>
</p>



# build
```
npm run build

```

# 사용방법
```
 
Daracl.loading.create("selector", {})

Daracl.loading.create("selector", { "content": "content" })

Daracl.loading.create("selector", { "content": "content", timeout: 2000 });

Daracl.loading.create("selector", {
"enableCancelButton": true, callback: function () {
    console.log('1111111')
}
})

Daracl.loading.create("#sample5", { "enableCancelButton": true, enableTime: true })
 
```
  

# loading 옵션
| key | 설명 | 기본값 | 옵션값 |
|-----|------|-----|-----|
| timeout | 자동으로 사라지는 Milliseconds  | -1 |  |
| enableTime | 초 보일지 여부 | false |  |
| content | 보여질 컨텐츠  | "" |  |
| bgColor | 백그라운드 컬러 | "#ffffff" |  |
| zIndex | z-index  | 9999998 |  |
| opacity | opacity | "0.3" |  |
| loadingImg | 이미지 경로 및 base64 코드  | "" |  |
| cursor | css cursor  | "wait" |  |
| enableCancelButton | 취소 버튼 활성화 여부 | false |  |
| callback | 취소 벼튼 활성화시  callback 메소드 | undefined |  |


```