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
