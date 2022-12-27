# imgur-on-render

[英文版](../../README.md)
## Table of content

- [部署的專案](#部署的專案)
- [立刻部署](#立刻部署)
- [環境變數](#環境變數)

一鍵部署至render，即可馬上操作Imgur空間上的圖片

## 部署的專案

| 前端 | 後端 |
|:----:|:----:|
| [connectshark/image-manager(github.com)](https://github.com/connectshark/image-manager)| [connectshark/image-uploader(github.com)](https://github.com/connectshark/image-uploader)|

## 立刻部署

### 服務使用方案為 `free` 不會被收取費用
若日後有需要可自行至服務後台更改方案內容

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


## 環境變數
部署同時須設定環境變數，將IMGUR上的相關資訊填入即可
![環境變數](/cover/env.png)


|         key         |      value      |
|:-------------------:|:---------------:|
|   IMGUR_ALBUM_ID    |   <IMGUR_ALBUM_ID>    |
|   IMGUR_CLIENT_ID   |   <IMGUR_CLIENT_ID>   |
| IMGUR_CLIENT_SECRET | <IMGUR_CLIENT_SECRET> |
| IMGUR_REFRESH_TOKEN | <IMGUR_REFRESH_TOKEN> |

所有需要的環境變數可參考[此篇文章](https://israynotarray.com/nodejs/20220517/432259079/)的教學取得
