# imgur-on-render

[中文版](/readme/zh-tw/README.md)
## Table of content

- [Deploy now](#Deploy-now)
- [Deployed projects](#Deployed-projects)
- [Environment Variables](#Environment-Variables)

Deploy to render and immediately manipulate images on Imgur space

## Deploy now

### Service use plan `free` and will not be charged
Change options in the setting page if necessary in the future

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

## Deployed projects

| Frontend | Backend |
|:----:|:----:|
| [connectshark/image-manager(github.com)](https://github.com/connectshark/image-manager)| [connectshark/image-uploader(github.com)](https://github.com/connectshark/image-uploader)|



## Environment Variables
Environment variables must be set at the same time as deployment, and the relevant information on IMGUR can be filled in.
![Environment Variables](/cover/env.png)


|         key         |      value      |
|:-------------------:|:---------------:|
|   IMGUR_ALBUM_ID    |   <IMGUR_ALBUM_ID>    |
|   IMGUR_CLIENT_ID   |   <IMGUR_CLIENT_ID>   |
| IMGUR_CLIENT_SECRET | <IMGUR_CLIENT_SECRET> |
| IMGUR_REFRESH_TOKEN | <IMGUR_REFRESH_TOKEN> |

All required environmental variables may be referred to [this Article](https://israynotarray.com/nodejs/20220517/432259079/)

