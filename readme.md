# HOW TO

## A. config.ini 

1. config.파일에서 본인의 계정,비밀번호를 입력합니다.
2. 다운로드 받고 싶은 계정, 또는 url을 입력합니다 (이때 계정또는 url 앞에는 tab을 넣어야합니다)
3. 계정 또는 url 뒤에 ' // n' 을 넣을경우 n개만큼만 다운로드 합니다
4. DEFAULT_PATH 는 기본다운로드 폴더입니다.  기본값은 .으로 되어있으며 현재 폴더 위치(파일 실행한 위치)로 되있습니다.

## B .ipynb

1. **insta.ipynb**
   1. insta.ipynb는 인터넷창을 직접 켜서 하나하나씩 수동으로 다운로드 받는 방식입니다.
   2. 이 방법은 동영상은 다운로드 되지 않습니다.
   3. insta2.ipynb가 작동되지 않을경우 사용하는 것을 권장합니다.
   
2. **insta2.ipynb**
   1. insta2.ipynb는 api를 사용하여 다운로드 받는 방식입니다.
   2. 사진 및 동영상 모두 다운로드 지원합니다.
   3. 많은양을 한번에 다운로드 받으려 할 시 에러가 발생할 수 있습니다.



## A. config.ini

1. Enter your account and password in the config file.
2. Input the Instagram account or URL you want to download from (make sure to add a tab before the account or URL).
3. If you want to limit the download to a specific number, add ' // n' after the account or URL, where n is the number of posts to download.
4. DEFAULT_PATH is the default download folder. The default value is set to '.' which represents the current folder location (the folder where the file is executed from).
   
## B. .ipynb

1. **insta.ipynb**
    1. insta.ipynb requires manually downloading posts by opening the web browser and downloading them one by one.
    2. This method does not support video downloads.
    3. It is recommended to use this method if insta2.ipynb is not working.

2. **insta2.ipynb**
    1. insta2.ipynb uses the API to download posts.
    2. It supports downloading both photos and videos.
    3. If you attempt to download a large quantity of posts at once, an error may occur.
