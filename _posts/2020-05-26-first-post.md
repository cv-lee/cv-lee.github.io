---
title: "네트워크"
date: 2020-05-27 15:00:00 -0400
categories: 공부 네트워크
---

## 네트워크
위 강의는 [한국직업방송 강의 (안성진 교수님)](https://www.youtube.com/playlist?list=PLFpZ7zSiHhPxrib8i4XPRKxB6FR9_NlCo)를 토대로 정리하였음을 밝힙니다.

## 1강 네트워크 구조와 종류

* 노드(장치): 통신하고자(or 통신을 가능하게) 하는 기기
* 링크: 기기들을 연걸하는 선
* 평가기준: 
  - 성능: 처리량(throughput)과 지연시간(delay) 측면에서 네트워크와 성능을 측정 가능
    + 경유시간: 한 장치에서 다른 장치로 데이터가 전달 되는데 걸리는 시간
    + 응답시간: 요청에 대한 응답이 오는데까지 걸리는 시간
    + 왕복시간: 출발지에서 목적지까지 갔다가 돌아오는데 걸리는 시간
    + 따라서 성능이 좋은 네트워크는 처리량이 높고 지연시간이 작은 네트워크
  - 신뢰성
  - 보안성
* 연결형태: 
  - 일대일 (point to point): 선 하나에 두 개의 시스템만 연결된 형태
  - 멀티포인트 (multi-point): 선 하나에 여러 개의 시스템들이 상호 공유하는 연결형태
* 네트워크 토폴로지 (topology): 노드와 링크가 어떻게 배치되어 있는가를 의미
  - 스타형 (star): 허브를 중심으로 컴퓨터들이 일대일 연결되어 있는 형태
  - 버스형 (bus): 하나의 긴 케이블에 여러개의 장치들이 멀티포인트 링크로 연결된 형태
  - 링형 (ring): 노드와 링크들이 링의 형태로 연결 되어있는 형태
  - 그물형 (mesh): 여러 개의 장치들이 서로 상관성 없이 연결되어 있는 형태
  - 실제 네트워크들은 다양한 형태의 토폴로지르 구성되어 있다.
* 네트워크 분류 
  - LAN (Local Area Network): 사무실, 건물 등의 개인소유의 규모에서의 네트워크
  - MAN (Metropolitan Area Network): 도시정도의 규모에서의 네트워크
  - WAN (Wide Area Network): 국가, 전세계의 규모에서의 네트워크

## OSI 7계층 

* **네트워크에서 통신이 일어나는 과정**을 7단계로 나눈 것을 말한다.
* 계층을 나눈 이유는 통신이 일어나는 과정이 **단계별로 파악**할 수 있기 때문이다.


## 1. 물리 계층 (Physical layer)

* 역할: 물리적으로 데이터 전송
* 단위: 비트
* 장비: 허브, 리피터
* (프로토콜: RS-232)
<details>
<summary>자세한 설명</summary>
<div markdown="1">
* 역할: 전기적, 기계적, 기능적인 특성을 이용하여 통신 케이블로 데이터를 전송. 단순히 전송이 목적이기에 에러, 흐름 등에 신경쓰지 않음.
* 허브: 연걸된 노드들에게 신호를 전달해주는 장치
  - 장점: 저렴함
  - 단점: 여러명 동시 사용 시, 느림 (요즘 사용 않함)

* 리피터: 신호 증폭을 통해서 먼 케이블까지 데이터를 전달할 수 있게 해주는 장치 

</div>
</details>


## 2. 데이터링크 계층 (Data link layer)

* 역할: 포인트 투 포인트 간 전송 보장 (오류&흐름제어)
* 단위: 프레임
* 장비: 브릿지, 스위치
* 프로토콜: 이더넷 (Ethernet)
<details>
<summary>자세한 설명</summary>
<div markdown="1">
* 역할:
* 브릿지: 
* 스위치: 허브와
  - 장점: 여러명 동시 사용하더라도 느려지지 않음
* 이더넷:
</div>
</details>


## 3. 네트워크 계층 (Network layer)

* 역할: 경로 탐색, 상위 데이터를 캡슐화
* 단위: 패킷
* 장비: 라우터
* 프로토콜: IP
<details>
<summary>자세한 설명</summary>
<div markdown="1">
* 역할:
* 라우터:
* IP: 
</div>
</details>


## 4. 전송 계층 (Transport layer)

* 역할: 종단간 전송 보장 (오류&흐름제어)
* 단위: 세그먼트 (TCP), 데이터그램 (UDP)
* 장비: 게이트웨이
* 프로토콜: TCP, UDP
<details>
<summary>자세한 설명</summary>
<div markdown="1">
* 역할: 
* 게이트웨이:
* TCP:
* UDP:
</div>
</details>


## 5. 세션 계층 (Session layer)


## 6. 표현 계층 (Pressentation layer)


## 7. 응용 계층 (Application layer)


## 출처 

* [링크 1](https://hahahoho5915.tistory.com/12)
* [링크 2](https://shlee0882.tistory.com/110)
* [링크 3](https://www.youtube.com/playlist?list=PLFpZ7zSiHhPxrib8i4XPRKxB6FR9_NlCo)