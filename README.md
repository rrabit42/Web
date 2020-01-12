# Web
초심으로


## 인터넷-웹 관계?  
* 인터넷이 도시면 웹은 그 위에 있는 건물  
Internet 안에 FTP, WEB, EMAIL 등 여러 서비스가 존재  
통신시스템 -> Internet  
중앙이 없음  
수많은 통신 장비들이 점처럼 존재, 서로 연결되어 있음  
저 중에 하나가 없어져도 통신 가능  

* 군사기관에서만 쓰이던 Internet은 웹의 출현으로 새로운 길을 걷게 됨(대중화)  
World Wide Web  
http://info.cern.ch/  
웹의 메소포타미아  

* 웹의 동작 원리  
WEB Browser <--> WEB Server  
1. web browser가 인터넷을 통해 http://info.cern.ch/index.html을 요청(http://info.cern.ch라는 컴퓨터한테)  
2. web server가 하드디스크 등에서 찾아서 index.html 파일을 찾아서 web browser가 설치된 컴퓨터에 쏴줌(모든건 전기적 신호로 주고받는거임)  
3. web browser에 index.html의 코드가 도착함 그 코드를 web browser가 읽어서 그것을 해석해서 화면에 표시해줌  


* 클라이언트(WEB browser, 서비스 요청)가 보내는 요청은 request  
서버(WEB server, 서비스 제공)가 보내는 응답은 response  


* WEB server : 내 컴퓨터에 있는 자료를 Web browser만 있는 모두가 가져다가 볼 수 있게 하는 것!  
1. 직접 web server 설치  
2. web hosting, 회사에게 맡김


# 무료 호스팅 업체 : github pages  
웹 서버 역할을 github가 해주는 것  
HTML은 웹브라우저가 해석하기 때문에 서버 쪽에서 특별히 해줄 일이 없음. 이런 특성을 **정적(static)**이라고 함  
자연스럽게 HTML만으로 만들어진 웹사이트를 호스팅하는 서비스 중에는 무료가 많음.


동적(dynamic)은 php, python, ruby, java와 같은 언어를 이용하여 만드는 것 대체로 비용을 내야함  


# 웹서버 직접 운영  
내 컴퓨터에 웹 서버 프로그램을 깔아야함  
웹브라우저가 제품군인 것 처럼 웹서버도 제품군임  
ex) Apache, IIS, Nginx  
Apache는 오픈소스, 무료  
설치방법 검색 : how to install apache http server *os*  


Window  
Apache  
Mysql(db)  
Php(middleware)  
~~나는 XAMPP 깜..ㅎㅎ~~  
~~X(크로스 플랫폼), 아파치, mariadb(mysql에서 바뀜), php, perl~~  
