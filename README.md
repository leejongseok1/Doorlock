# Raspberry Pi와 Dlib 기반 얼굴 인식 도어락

🗓️ 프로젝트 기간 : 2023.04 ~ 2023.10

<br>

📢**팀명** : SCV

🧑‍🦲**팀원** : 오세학, 이종석, 안진원, 소순성 

## 소개

RaspberryPi와 dlib기반 python 라이브러리인 [**face_recognition**](https://github.com/ageitgey/face_recognition), AWS 클라우드, Android 애플리케이션을 활용해 구축된 도어락 시스템

<br>


## 주요 기능

1. **얼굴 인식을 통한 도어락 제어**
    - face_recognition 라이브러리를 사용해 등록된 얼굴 사진과 입력된 얼굴 사진을 비교하여 인증

2. **Android 애플리케이션**
    - 출입 허가자 명단 관리 (추가/삭제)
    - 원격 잠금/해제
    - 잠금 해제 기록 조회

3. **AWS 클라우드 연동**
    - AWS 웹 서버와 데이터베이스(MySQL)를 통해 얼굴 데이터 및 출입 기록 관리
    - 웹소켓을 활용해 원격 잠금 해제 구현

4. **도어락 제작**
    - 초음파 센서를 통해 사물의 거리를 인지하여 동작
    - 잠금장치 역할을 하는 모터
    - 도어락 잠금 해제, 인증실패 시 사운드 부저 알림


<br>
<br>

## 프로젝트 시연 영상

https://www.youtube.com/watch?v=f0IGTcsKD9g