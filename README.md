# 마스크 인식 출입통제 시스템



### Contests

📌 2019 한이음 공모전 본선 진출


<br>

### Summary


* 카메라로 마스크 착용 유무 파악

* 마스크를 착용한 인원만 체온 측정

* 정상 체온인 경우에만 매장에 입장
  <br>

  <br>
  
  
### Block diagram


![캡처](https://user-images.githubusercontent.com/75367132/202906560-fd848be9-3e60-4067-a4a6-99de3c5b7b98.PNG)


<br>

## About Project

### Container

<img src="https://img.shields.io/badge/Language-C / C++-green?style=flat"/><img src="https://img.shields.io/badge/Platform-Arduino-blue?style=flat"/>

* 각종 센서를 통한 컨테이너 내부 상태 수집

* 펠티어 소자를 이용하여 설정한 컨테이너 내부 온도를 유지

* RFID, KEYPAD를 사용한 컨테이너 도어 LOCK / UNLOCK 보안 기능

* 태양널 패널을 통한 배터리 충전

  <br>

### 3D printing

<img src="https://img.shields.io/badge/Platform-Fusion360-blue?style=flat"/>

* 아두이노 및 각종 센서, 펠티어 소자가 장착될 수 있는 컨테이너 모형 제작

  <br>

### Web

<img src="https://img.shields.io/badge/Language-PHP-green?style=flat"/><img src="https://img.shields.io/badge/Platform-RaspberryPi-blue?style=flat"/><img src="https://img.shields.io/badge/DB-MySQL-yellow?style=flat"/>

* 사용자 / 관리자로 로그인

* 컨테이너 별 접근 가능한 사용자 설정 가능

* 각 컨테이너의 시간별 상태 및 위치 정보 모니터링

  <br>

### BE

<img src="https://img.shields.io/badge/Language-C-green?style=flat"/><img src="https://img.shields.io/badge/DB-MySQL-yellow?style=flat"/>

* 아두이노로부터 데이터를 수신하는 Socket Programming

* MySQL 사용자 및 컨테이너 Table 생성

* 컨테이너 정보 DB에 업로드

  <br>

  <br>

## Results

### H/W

- Container Model

| <img src=images/container.png  width="100%"/> |
| --------------------------------------------- |



|                        front                        |                        inside                        |
| :-------------------------------------------------: | :--------------------------------------------------: |
| <img src=images/container_front.png  width="100%"/> | <img src=images/container_inside.png  width="100%"/> |
|                      **back**                       |                       **top**                        |
| <img src=images/container_back.png  width="100%"/>  |  <img src=images/container_top.png  width="100%"/>   |



<br>

- Circuit

<img src=images/circuit1.png  width="30%"/><img src=images/circuit2.png  width="30%"/>  <img src=images/circuit3.png  width="30%"/>

<br>

<img src=images/circuit4.png  width="80%"/>



<br>

<br>

### Web page

|         기능         |                       화면                        |
| :------------------: | :-----------------------------------------------: |
|     로그인 화면      |   <img src=images/web_login.png  width="80%"/>    |
|  접근 가능 컨테이너  | <img src=images/web_containers.png  width="80%"/> |
| 선택한 컨테이너 정보 |  <img src=images/web_coninfo.png  width="80%"/>   |

<br>

<br>

<br>





