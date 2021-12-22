При ответе вашего сервера посылайте некоторые основные заголовки:
Date
Content-type
Server
Content-length
Connection: close.
![image](https://user-images.githubusercontent.com/90459151/147120672-0cc23d38-ec58-4a98-a416-51304eb6439f.png)
Создайте файл настроек вашего веб-сервера, в котором можно задать прослушиваемый порт, рабочую директорию, максимальный объем запроса в байтах. Можете добавить собственные настройки по желанию.
![image](https://user-images.githubusercontent.com/90459151/147120829-a786df43-b250-48bc-aa7e-3d653482ed96.png)
Если файл не найден, сервер передает в сокет специальный код ошибки - 404.
![image](https://user-images.githubusercontent.com/90459151/147121609-9a0c9400-75b8-43ce-ad9f-2cd7ee7bfd97.png)
Сервер должен вести логи в следующем формате: Дата запроса. IP-адрес клиента, имя запрошенного файла, код ошибки.
![image](https://user-images.githubusercontent.com/90459151/147121194-d4f3d6a6-f1de-4b64-a219-f3cebc4bae84.png
Добавьте возможность запрашивать только определенные типы файлов (.html, .css, .js и так далее). При запросе неразрешенного типа, верните ошибку 403.
![image](https://user-images.githubusercontent.com/90459151/147121673-b0cd5f6e-8e61-4708-ab65-85238aa584b9.png)
Реализуйте поддержку бинарных типов данных, в частночти, картинок.![image](https://user-images.githubusercontent.com/90459151/147120518-277efa2b-86c6-465b-8e8c-4327e89f7c76.png)
