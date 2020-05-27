---
title: "OSI 7 Layer"
date: 2020-05-28 15:00:00 -0400
categories: Study Network
---

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