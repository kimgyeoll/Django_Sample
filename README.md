# Django Sample

Django Grundmodell.
Das kann als Hauptsache verwendet werden.

Linux (either VScode or Pycharm )
pip install pyton 
pip install django 


django-admin startproject [프로젝트 이름]

python manage.py runserver
서버실행

python manage.py startapp [앱 이름]


https://velog.io/@gndan4/Django-%EC%9B%B9-%ED%94%84%EB%A0%88%EC%9E%84%EC%9B%8C%ED%81%AC-%EC%9E%A5%EA%B3%A0-%EA%B8%B0%EB%B3%B8-%EC%84%A4%EC%A0%95-Template-HTML-Form-URL


파이프(|)를 사용하여 적용: 

django.contrib.admin: 관리자 페이지 제공
django.contrib.auth: 인증 시스템 제공
django.contrib.contenttypes: 컨텐트 타입 프레임워크
django.contrib.sessions: 세션 프레임워크
django.contrib.messages: 메세지 프레임워크
django.contrib.staticfiles: 정적 파일 관리 프레임워크


{% load static %} = 최상단  HTML에 박으센 
 <link rel="stylesheet" href="{% static 'bootstrap/css/bootstrap.css' %}">
    <link rel="stylesheet" href="{% static 'css/blog.css' %}">



 linebreaksbr 필터를 사용하면 줄바꿈이 일어나는 곳에 <br> 테그를 추가해준다.
 
 
 
 
 ✍🏻장고 명령어 & 리눅스 명령어(Django)
👨🏻‍💻장고명령어


django-admin startproject [프로젝트명] : 새로운 프로젝트 생성


python manage.py startapp [앱이름] : 새로운 장고앱 생성


python manage.py runserver : 개발 서버 실행


python manage.py makemigrations [앱이름] : 마이그레이션 파일 생성


python manage.py migrate [앱이름] : 마이그레이션 적용


python manage.py collectstatic : static 파일들을 settings.STATIC_ROOT 경로로 모음


python manage.py —help : 지원하는 명령어 목록


⭐django-admin VS manage.py


django-admin 은 DJANGOSETTINGSMODULE 가 셋팅되어있길
기대하며 사용하는 것이고 manage.py를 사용하는게 좀더편리하다


그래서 처음에 프로젝트 만들때는 django-admin 으로 만들고
다음부터는 manage.py를 쓰는 것 같다


manage.py가 thin wrapper라고 하는데…
자세한 내용은 너무 어려우므로 더 궁금하신 분들은 구글링 하시길 바랍니다


⭐리눅스 명령어


clear : command 창 깨끗하게 정리


pwd : 현재 내가 위치한 path 위치를 보여줌


cd : directory 이동 할때 사용


ls : 현재 위치한 곳에 file 및 folder 보여줌


touch : 크기가 0인 file생성


mkdir : directory생성


rm 또는 rm -R
: 파일 및 폴더 삭제(폴더를 삭제할때는 하위 file까지 삭제해줘야하므로 -R을 붙여줌)


cat : 파일내용을 보여줌


mv <바꿀filename> : filename을 바꿔준다
: file을 directory로 이동시켜준다



url - view - templates 구조 임 
