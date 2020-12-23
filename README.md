# django_api_and_db using docker compose

### django api server templete
원래는 문화재청 공모전을 준비하기 위해 준비한 백단 서버지만 docker
compose를 이용해서 만든 django api 서버 및 postgres 서버이기에
template으로 사용하기 적당하다고 판단하여 이렇게 올리게 되었다.

### 사용방법
1. git clone을 이용하여 해당 서버를 받는다
2. pip install -r requirements.txt
3. python manage.py runserver
4. 입맛에 맞게 django를 세팅
5. docker-compose.yml의 postgres 관련 설정 변경
6. 서버에 해당 템플릿 올리기

