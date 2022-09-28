# Sass_demo
demo
Sass一開始要架設環境:參考網址=https://awdr74100.github.io/2020-05-18-scss-install/
先載VSCode 的 Live Sass Compiler 套件
先建立一個index.html檔案
再建立一個scss資料夾裡面放all.scss檔案
這時候就按ctrl + shift + p 收尋json 打開第三個prexxxx:open use json 然後貼上{
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "~/../css"
    },
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "~/../css"
    }
  ]
}
要特別注意這裡settings json 裡面加上這個 key 跟 value了 如果沒貼好 會產生不了css檔案
產出完成後 就可以開始scss了!!!!!!
