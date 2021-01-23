# resume

## 링크

Github : https://github.com/HyoyeolJo

## 자기소개
    5년간 내비게이션 UI 개발 및 서비스를 구현하였습니다.
    내비게이션은 GPS, Draw, Search, Network, 경로 엔진 등 다양한 모듈로 구성되어 있습니다.
    이러한 Multi-Thread 기반의 프로젝트를 수행하며 대규모 베이스의 코드 개발을 경험할 수 있었습니다. 
    또한, Window, Linux, Android OS 환경에서 개발한 경험이 있어 Cross Platform에도 익숙합니다.
    협업을 중시하고 사용자에게 최고의 서비스를 제공하는 UI 개발자가 될 수 있도록 오늘도 최선을 다하고 있습니다.

## 경력

[맵퍼스](http://www.mappers.kr)
- 전임연구원 - 2016.01 ~ 재직중

## 보유기술
+ C/C++
  + Native Navigation UI & Scenario 구현
+ Java
  + Android Framwork에서 Native App을 동작하기 위한 MainActivity 구현
+ XML
  + XML 기반의 Navigation UI Tool을 이용한 UI Script 구현
+ 기타
  + JIRA
    + Project Issue 처리
  + Confluence
    + WBS 기반의 일정 관리
    + 산출물 업로드
  + Git/Gerrit
    + Source Code 관리

## 개인 프로젝트
### GLSurfaceView을 이용한 Rendering 방식 변경
+ 진행기간
  + 2017.01 - 2017.02
+ 주요내용
  + SurfaceView 방식에서 GlSurfaceView 방식으로 전환
+ 역할
  + SurfaceView에서 GLSurfaceView로 전환
  + Naive 렌더링에서 JNI 렌더링 방식 변경
+ 개발환경
  + OS : Android
  + IDE : Android Studio
+ 개발언어
  + C/C++
  + Java
  + JNI
+ 성과
  + 생명주기에 따른 화면 전환 시간 단축 (2초 -> 1초)
### Gradle을 이용한 Atlan Project IDE 전환
+ 진행기간
  + 1차 2016.01 - 2016.03
  + 2차 2018.07 - 2018.08
+ 주요내용
  + Eclipse ADT 업데이트 지원종료
  + Atlan Project를 AndrodiStudio로 IDE 전환 및 빌드
+ 역할
  + Android Studio로 Atlan Project IDE 전환
    + Eclipse환경에서 Gradle 추출
    + Java파일 ANSI에서 UTF-8로 파일 Incoding 변경
    + Android Studio 전환 가이드 문서 작성
  + Android Studio에서 Atlan Project 빌드
    + Gradle을 이용한 build.Gradle 파일 수정
    + Android Studio 빌드 가이드 문서 작성
+ 개발환경
  + OS : Android
  + IDE : Eclipse, Android Studio
+ 개발언어
  + Gradle
+ 성과
  + 최신 ADT 적용 가능
  + Gradle을 이용한 빌드 자동화 시스템 도입
  
## 팀 프로젝트

### Atlan 5 CL Navigation 개발
+ 진행기간
    + 2019.10 - 진행중
+ 주요내용
    + 해외 기업 Navigation SW 개발
+ 역할
    + OpenGL 2.0 기반의 Navigation UI Engine을 활용한 UI 개발
        + 내비게이션 주행 화면 안내 서비스
        + USB Upgrade 진행상황 표출
        + OTA Update 진행상황 표출
        + 사용자 설정 데이터 AES 256 암호화 저장 기능
        + 온라인 SDI 업데이트 기능
+ 개발환경
    + OS : Linux, WinCE
    + IDE : Eclipse, Visual Studio 2008
+ 개발언어(또는 Library)
    + C/C++
    + Wayland Library
    
### Atlan 5 AndroidAuto Navigation 개발 
[Atlan 5 AndroidAuto](http://www.fine-drive.com/product/finedrive_AI2.do)
+ 진행기간
    + 2020.03 - 2020.09
+ 주요내용
    + Android Auto용 Navigation 개발
+ 역할
    + GPS 수신 방식 변경
        + Fused Location Provider를 이용한 GPS정보 수신 구현
    + Android Service 기반의 Floating Window UI 개발
        + 단속카메라, 스쿨존, 회전정보, 구간단속 안내
+ 개발환경
    + OS : Android, WinCE
    + IDE : AndroidStudio, Visual Studio 2008
+ 개발언어(또는 Library)
    + C/C++
    + Java
    + JNI
    + XML
    
### Atlan 5 C-ITS Navigation 개발
[Atlan 5 C-ITS](https://www.c-its.kr/getMain.do)
+ 진행기간
    + 2020.03 - 2020.09
+ 주요내용
    + 차량이 주행 중 운전자에게 주변 교통상황과 급정거, 낙하물 등의 사고 위험 정보를 실시간으로 제공
+ 역할
    + OpenGL 2.0 기반의 Navigation UI Engine을 활용한 UI 개발
        + 도로위험상황 경고 알림
        + 도로통제정보알림
        + 노면 기상정보
        + 교차로 신호위반 경고
        + 보행자 추돌방지 경고
        + 스클존, 실버존 속도 제어
        + 도로작업구간 정보알림
        + 고장차량
        + 사고비상차량
        + 긴급차량 우선신호 시나리오
        + 급정거차량 주의
        + 급감속차량 주의
        + 서행차량 주의
        + VMS 서비스
        + 관광지 대기질 서비스
    + 서비스 검증
        + C-ITS 서비스 별 동작 확인
+ 개발환경
    + OS : Android, WinCE
    + IDE : AndroidStudio, Visual Studio 2008
+ 개발언어(또는 Library)
    + C/C++
    + Java
    + JNI
    + XML
+ 성과
    + [C-ITS 인증](https://www.c-its.kr/board/getBoardDetail.do?seq=1308) 단말기 Navigation 탑재
    
### Atlan 5 MirrorLink Navigation 개발
[Atlan 5 MirrorLink](http://www.atlan.co.kr/products/pnd/atlanAuto.do)
+ 진행기간
    + 2018.08 - 2019.07
+ 주요내용
    + MirrorLink용 Navigation 개발
+ 역할
    + OpenGL 2.0 기반의 Navigation UI Engine을 활용한 UI 개발
        + 주행 안내 서비스
        + Navigation 사용자 설정
        + 안전운전 업데이트 서비스
        + 음성인식 서비스
    + 배포
        + 주간 배포데이터 생성
        + ReleaseNote 작성
    + MirrorLink API 적용
        + MirrorLink Menifest 추가
        + Audio 송출 방식 변경
        + App 실행 및 종료 동작
    + MirrorLink CCC 인증
        + MirrorLink PlugIn 적용
        + CCC 인증 
        + ECO 문서 작성
    + 기타
        + MirrorLink 테스트환경 구축
        + Android 9.0 정책에 따른 [변경사항](https://developer.android.com/about/versions/pie/android-9.0-changes-all?hl=ko) 반영 
            + Navigation Bar Hide 시 전체화면 영역 계산 수정
            + TLS 사용하지 않도록 예외처리
            + Background Service 불가
+ 개발환경
    + OS : Android, WinCE
    + IDE : AndroidStudio, Visual Studio 2008
+ 개발언어(또는 Library)
    + C/C++
    + Java
    + JNI
    + XML
    + MirrorLink Plugin
+ 성과
    + 한국정보통신기술협회[TTA] CCC 인증 취득
    + MirrorLink 단말기 Navigation 탑재

### Atlan 5 Taba Navigation 개발
### Atlan 5 Truck 추천 POI 기능 개발
### Atlan 5 EV Navigation 개발
### Atlan 5 Truck Navigation 개발
### Atlan 5 Navigation 개발
  
## 기타 프로젝트

### Standard Coding Rule 적용
  
## 대학 프로젝트

### Galaxy S6 스마트 커버 앱 개발
### Android LMK Memory Swap 개선
### 웹 컴파일러 제작
### 바야바 엔진을 이용한 도둑잡기 게임
  
## 학력사항
### 세종대학교 컴퓨터공학과 졸업
