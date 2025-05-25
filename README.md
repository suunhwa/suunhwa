## Hi there 👋
### 저는 이런 개발자입니다
- 팀 중심의 개발을 지향하며, 협업과 커뮤니케이션을 중요하게 생각합니다.
- 상황에 맞게 역할을 찾아 주도적으로 행동하고, 문제 해결에 적극적으로 참여합니다.
- 새로운 기술과 도구는 직접 다뤄보며 배웁니다.

### 📬 Channel
[<img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white" height="20"/>](mailto:snna628@gmail.com)
&nbsp;
[<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" height="20"/>](https://github.com/suunhwa)

### 📂 개발 경험 요약
- Unity 기반 생존 게임 프로젝트를 직접 기획하고 구현
- 플레이어 이동, 카메라 제어, 상호작용, 드랍 아이템, 인벤토리, 간단한 AI 구현
- GitHub Projects를 활용해 작업을 정리하고 일정 계획 수립
- 공식 문서, Udemy 강의, 기술 블로그를 참고해 기능 학습 및 구현

### 🛠️ 기술 스택 <br>
개발 언어: <br>
<img src="https://img.shields.io/badge/C%23-FFFFFF?style=for-the-badge&logo=dotnet&logoColor=512BD4"/>
<img src="https://img.shields.io/badge/C++-FFFFFF?style=for-the-badge&logo=cplusplus&logoColor=00599C"><br>
게임 엔진: <br>
<img src="https://img.shields.io/badge/Unity-FFFFFF?style=for-the-badge&logo=unity&logoColor=black"/><br>
프론트엔드 스택:<br>
<img src="https://img.shields.io/badge/HTML5-FFFFFF?style=for-the-badge&logo=html5&logoColor=E34F26"/>
<img src="https://img.shields.io/badge/CSS3-FFFFFF?style=for-the-badge&logo=css3&logoColor=1572B6"/>
<img src="https://img.shields.io/badge/JavaScript-FFFFFF?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
<img src="https://img.shields.io/badge/Vue.js-FFFFFF?style=for-the-badge&logo=vue.js&logoColor=4FC08D"/>
<img src="https://img.shields.io/badge/React-FFFFFF?style=for-the-badge&logo=react&logoColor=61DAFB"/><br>
백엔드 / 서버:<br>
<img src="https://img.shields.io/badge/Node.js-FFFFFF?style=for-the-badge&logo=node.js&logoColor=339933"/><br>
데이터 및 모니터링:<br>
<img src="https://img.shields.io/badge/MySQL-FFFFFF?style=for-the-badge&logo=mysql&logoColor=4479A1"/>
<img src="https://img.shields.io/badge/Grafana-FFFFFF?style=for-the-badge&logo=grafana&logoColor=F46800"/><br>

## 프로젝트
### 🌳 Survival 프로젝트 (3인칭 생존 게임)
---
**개요**
- 장르: 3인칭 서바이벌 어드벤처 (TPS 요소 포함)
- 엔진: Unity Engine 6000.0.04f1
- 언어: C#
- 기간: 2025.04 ~ (개인 프로젝트)

**주요 구현 & 해결 경험**
1. 플레이어 조작 및 카메라 시스템 구현
    - 카메라가 플레이어를 부드럽게 따라오며 자동 회전하도록 구현
    - 3인칭 시점에서 WASD 이동과 마우스 회전을 자연스럽게 처리
    - 🎯 문제: Cinemachine 없이 직접 구현하다 보니 카메라 회전과 이동이 따로 놀았음
    - ✅ 해결: 마우스 회전을 기준으로 이동 방향을 연동해 자연스러운 조작감 완성
      
2. 자원 채집과 드랍 시스템 설계
    - 나무나 돌과 상호작용 시 자원을 드랍하도록 구현
    - 사과 등 보조 자원은 랜덤 드랍되도록 설정
    - 🎯 문제: 드랍 아이템이 많아질수록 퍼포먼스 저하
    - ✅ 해결: Object Pooling을 적용해 드랍 아이템을 효율적으로 관리

3. 인벤토리 시스템 구성
    - CSV 기반 아이템 데이터를 불러와 UI에 연동
    - 아이템 드랍 → 줍기 → 인벤토리에 추가하는 일련의 흐름을 제작
    - 🎯 문제: 데이터가 하드코딩되어 수치 수정이 번거로움
    - ✅ 해결: CSV 파일을 통해 코드 수정 없이 데이터 변경 가능하게 개선

4. 근접 전투와 무기 충돌 처리 구현
    - 몬스터가 일정 거리 내 플레이어를 추적하고 공격하는 간단한 AI 구현
    - 플레이어 무기의 콜라이더와 충돌 시 데미지 계산 및 사망 처리
    - 🎯 문제: 애니메이션 타이밍과 충돌 판정이 어긋나 전투 타격감 저하
    - ✅ 해결: 애니메이션 이벤트를 활용해 정확한 충돌 시점에 데미지를 주도록 개선

5. GitHub Projects를 활용한 개발 흐름 정리
    - 작업 단위를 기능별로 나누고, 이슈로 정리하며 일정 관리를 시도  
    - 🎯 문제: 초기에는 개발 순서와 우선순위가 명확하지 않아 흐름이 중간에 끊어졌음  
    - ✅ 해결: 이후 GitHub Projects의 시각적 도구를 도입해 작업을 체계적으로 정리하기 시작함

🔗 [GitHub Repository](https://github.com/suunhwa/survival-game)
<br/>
<br/>
### 📊 PLC 대시보드 프로젝트
---
#### 개요
PLC 이더넷 포트를 통해 수신한 실시간 데이터를 시각화하고, 웹 기반 대시보드에서 다양한 그래프와 UI로 표현하는 시스템을 구현했습니다.
- 기간: 2022.12
- 인원 구성: 3명 
- 역할:  프론트엔드 구조 설계, 실시간 데이터 시각화, 인증 및 페이지 구성 등

#### 주요 기술 스택
- 프론트엔드: Vue.js, three.js, Bootstrap
- 백엔드: Node.js, Express
- 데이터베이스: PostgreSQL
- 데이터 시각화: Grafana
- 통신 프로토콜: MQTT
- 기타: Docker, Flexing Edukit (PLC 장비)

#### 주요 기능 및 역할
1. 프론트엔드 구조 설계 및 구현
    - Vue.js를 사용해 대시보드 레이아웃 구성
    - 실시간 데이터 조회, 차트/그래프 UI 구성

2. Grafana 연동 시각화 대시보드 구성
    - 다양한 그래프를 이용해 실시간 수집 데이터를 시각화
    - 백엔드와 연동해 시스템 데이터를 정확하고 직관적으로 표시되도록 구성

3. 사용자 인증 및 권한 시스템
    - JWT 기반 로그인 / 회원가입 기능 구현
    - 권한에 따라 가능한 기능 제한

4. PLC 데이터 수신 및 처리
    - C# 기반 Ethernet 수신 프로그램과 연동
    - Node.js 서버로 데이터를 전달하고 실시간 반영

🔗 [GitHub Repository](https://github.com/suunhwa/smart_factory)
