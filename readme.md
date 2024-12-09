# HOW TO

## A. config.ini 

1. config.파일에서 본인의 계정,비밀번호를 입력합니다.
2. 다운로드 받고 싶은 계정, 또는 url을 입력합니다 (이때 계정또는 url 앞에는 tab을 넣어야합니다)
3. 계정 또는 url 뒤에 ' // n' 을 넣을경우 n개만큼만 다운로드 합니다
4. DEFAULT_PATH 는 기본다운로드 폴더입니다.  기본값은 .으로 되어있으며 현재 폴더 위치(파일 실행한 위치)로 되있습니다.
5. INCLUDE_STORY는 현재 걸려있는 스토리 다운로드입니다. 다만 현재 사용시 막대한 문구를 출력해서 .ipynb가 아닌 .py형태로 만들어 사용하는것을 권장합니다
6. OVERWRITE는 이전에 다운받았더라도 다시 다운받을지 여부입니다. (중복 다운로드 방지)

## B .ipynb

1. insta2.ipynb는 api를 사용하여 다운로드 받는 방식입니다.
2. 사진 및 동영상 모두 다운로드 지원합니다.
3. 많은양을 한번에 다운로드 받으려 할 시 에러가 발생할 수 있습니다.



## A. config.ini

1. Enter your account and password in the config file.
2. Input the Instagram account or URL you want to download from (make sure to add a tab before the account or URL).
3. If you want to limit the download to a specific number, add ' // n' after the account or URL, where n is the number of posts to download.
4. DEFAULT_PATH is the default download folder. The default value is set to '.' which represents the current folder location (the folder where the file is executed from).
5. INCLUDE_STORY refers to downloading the currently active story. However, when used, it generates a large amount of output, so it is recommended to use it in a .py file rather than a .ipynb file.
6. OVERWRITE determines whether to download again even if the file was previously downloaded (to prevent duplicate downloads).
   
## B. .ipynb

 1. insta2.ipynb uses the API to download posts.
 2. It supports downloading both photos and videos.
 3. If you attempt to download a large quantity of posts at once, an error may occur.
