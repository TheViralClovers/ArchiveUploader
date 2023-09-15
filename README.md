# ArchiveUploader
Simple javascript to speedup and auto resume archive.org uploads
```js
function autoResume() {
    if(document.getElementsByClassName("blue_button").length){
        IA_UPLOADER.resume()
         console.log("Auto resumed for you")
    }
}

function speedUp(){
  IA_UPLOADER.resume()
}

setInterval(speedUp,1000*300)
setInterval(autoResume,10000)
```

Paste the above code in the console of your broswer while uploading , how to access browser console tutorial: https://www.youtube.com/watch?v=msedCSGSA4A
