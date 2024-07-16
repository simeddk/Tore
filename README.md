# 우리가 그동안 무엇을 배었나?

## Tore01_Start
- 레벨 블프와 액터 블프
- 액터의 모빌리티
- 블프 클래스와 인스턴스
- 변수 연산 및 디버깅
- 시뮬레이트 피직스
- 에셋 이주

## Tore02_SideScroll
- 축 이벤트 및 액션 이벤트 바인딩
- 스켈레탈 메시와 애니메이션
- 애님인스턴스의 스테이트머신
- 몽타쥬 및 노티파이
- 대미지 시스템
- 글로벌 게임모드와 월드오버라이드 게임모드
- UMG - 메인메뉴, 포즈메뉴, 승리메뉴 등
- 게임인스턴스 - 스테이지 해금 상태 저장
- 세이브게임 - 스테이지 해금 상태 저장
- 사운드 - PlaySound 및 노티파이
- 디스트럭터블 메시
- 포션, 함정, 움직이는 발판 등 월드 디자인

## Tore03_ThirdPersonBP
- 3D 공간 - 월드 공간, 로컬 공간
- 액터, 컴포넌트의 어타치/디태치
- 충돌 프리셋 및 채널
- 애님노티파이스테이트에 의한 콤보 시스템
- 인터페이스를 활용한 캐릭터/무기의 상태 참조
- 데이터테이블을 활용한 몽타쥬 및 무기 공격력, 크리티컬 관리
- 컴포넌트를 활용한 캐릭터 수치, 무기 수치 관리
- 파티클 시스템의 활용 및 편집
- AI - AIController와 BehaviorTree
- 스플라인을 활용한 순찰 및 프로젝타일 궤적
- 이벤트 디스패처를 활용한 체력 위젯

## Tore04_BasicSyntaxCPP
- 언리얼C++ 상용구 매크로
- 변수와 함수의 직렬화 - UPROPERT, UFUNCTION
- 로깅 및 스크린 프린트
- 타이머 시스템
- 다이나믹 머티리얼 관리
- 언리얼 딜리게이트 - Delegate, Multicast, Event, Dynamic
- 블프에서 재정의 가능한 이벤트 - BlueprintImplementable, BlueprintNative
- C++ 충돌과 트레이스 기능
- 무기 조준 및 발사(단발, 연사)

## Tore05_ThirdPersonCPP
- 범용 ActorComponent를 활용한 참조 관리 - Attribute, Option, Montages, Action
- 데이터에셋을 활용한 무기/스킬 관리 - Equipment, Attachment, DoAction
- Dynamic Delegate 애님인스턴스 포즈 변경
- AIController 및 BehaviorTree Node - Service, Task
- 감지 컴포넌트와 ActorComponent를 활용한 블랙보드 에셋 읽고/쓰기
- 높이맵과 레이어맵이 적용된 LandScape
- Cull 적용된 Folige
- Material 프로그래밍 - Dissolve, LandScape, Panner 등
- 포스트프로세스

# 앞으로 무엇을 더 배우나
## Tore06_OnlineSubsystem
- 멀티플레이의 Travle - ServerTravle, ClientTravle
- 상태의 복제 - Replicates, ReplicatesMovement
- Dedicated Server와 Listen Server
- Host 및 Join 기능
- LAN과 Internet 환경의 접속
- Null 서브시스템
- 세션의 생성과 삭제
- 세션의 검색
- 최대 인원 도달과 세션의 시작
- 스팀 온라인 서비스
- (가능하다면) 간단한 멀티플레이 게임 - RPC, PlayerState, GameState 프레임워크 활용

## Tore07_Gameplay Ability System
- 지금까지 한 것들의 종합
- 게임플레이 태그를 활용한 액션 관리
- 멀티플레이 심화 기능 - RepNotity, LocalRole
- 변수와 월드 액터의 직렬화
- 하드 레퍼런스와 소프트 레퍼런스
- 에셋의 비동기 로드
- 최적화를 위한 프로파일링 - Stat, Insights
- 패키징 관련 버그

## Tore_Features
- 게임 플레이 이외의 것들
- 플러그인 - 툴바버튼, 디테일패널, 에셋툴, 디버거카테고리 커스터마이징
- 아카이브 시스템을 활용한 렌더링 데이터 저장
- 자체 에셋 팩토리 기능
- 라이팅맵과 밉맵, 큐브맵 최적화
- LOD 생성 및 관리
- Actor Merging, HLOD를 활용한 최적화
- POM 등 차세대 렌더링 기법
