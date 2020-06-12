# apache-starter
apache web server start helper

## Start
### macOS
설치: 기본 내장  
버전 확인: `apachectl -v` 명령어로 버전 확인 가능.  
구동: `sudo launchctl load -w /System/Library/LaunchDaemons/org.apache.httpd.plist`  
웹 페이지 경로: `/Library/WebServer/Documents`  
설정파일 경로: `/private/etc/apache2`  
기본설정 파일: httpd.conf  

### Ubuntu
설치: `sudo apt-get install -y apache2`  
버전 확인: `apache2 -v`  
구동: `sudo systemctl start apache2`  
웹 페이지 경로: `/var/www/html`  
설정파일 경로: `/etc/apache2`  
기본설정 파일: (이전) httpd.conf -> (현재) apache2.conf  

## 참조사이트
[Apache : macOS 에서 아파치 웹서버 실행하기](https://xho95.github.io/macos/apache/webserver/mod_wsgi/2016/10/02/Apache-WebServer.html)
[[Ubuntu] 우분투 Apache(아파치) 이해](https://webdir.tistory.com/196)
