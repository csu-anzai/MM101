## 기본정보
- 교육장소: CG5
- 교육대상: 매치무브 파트 취업준비 중인 학생(직장인 X)
- 교육기간: 5주 (주 1회, 토요일, 3~4시간)
- 준비물: Autodesk Maya, 3DEqualizer

## 내용

### 1주차

1. 매치무브 기초
    - 매치무브 이해
        1. What? 3D to 2D & 2D to 3D
        1. Why? CG요소를 실촬영본에 배치하고자 할때(그 반대도) 매치무브 작업은 필수다. 
        1. Who? Matchmove Artist, Matchmover, Integration Artist
        1. How?
            - 손으로(By Hand)
            - MCC(Motion Control Camera)
            - Matchmove Software(3DEqualizer, PFTrack, Syntheyes 등)
    - 매치무브 작업 과정
        1. 푸티지 평가 (Evaluating the Footage)
        1. 정보 적용 (Applying Information)
            - 촬영장 실측 (Set Measurements)
            - Survey Data
        1. 카메라 규정하기 (Define the Camera)
            - 카메라 내부 파라미터: 포컬랭스(Focal Length), 필름백(Film Back) 등
            - 카메라 외부 파라미터: 위치(Translation 또는 Position), 회전(Rotation 또는 Orientaion)
        1. 셋 피팅 (Set Fitting)
        1. 매치무브 테스트 (Testing the Matchmove)
        1. 딜리버 (Delivering the Scene)
    - 매치무브와 파이프라인
        - 프로덕션(Production)과 포스트 프로덕션(Post Production)을 이어주는 다리 역할.
        - 포스트 프로덕션 파이프라인 첫 단추.
    - 퍼스펙티브 매칭(Perspective Matching) 연습
        - 매치무브 소프트웨어를 사용하지 않고 **Maya에서 손으로 카메라의 위치를 찾는 연습**. 한장.
        - 3D 카메라를 생성하고, 초점거리(Focal Length) & 필름백(Film Back) 값 적용하기.
            - Focal Length: 16mm
            - Film Back: 18 × 12mm
        - 3D 카메라에 잘못된 정보가 들어갔을 때 결과 살펴보기.

1. 매치무브 소프트웨어
    - 사진측량
        - Photogrammetry(포토그래미트리) = Photos(빛) + Grama(형상) + Metry(재다)
        - 사진들로부터 물체를 측정하는 기술.
        - 시차(Parallax)
            - 사람은 2D 비디오만 봐도 카메라의 궤적과 3D 공간을 어느정도 유추 할 수 있다.
            

1. 카메라 & 사진
    - 카메라 종류
        - Compact, Mirrorless, DSLR, Film, Cinema 등
    - 렌즈(Lens) & 바디(Body)
        - 렌즈는 빛을 굴절 시키는 역할.
        - 바디에는 렌즈를 통과한 빛을 형상화하는 "이미지 센서"가 들어있다.
    - 사진은 어떻게 만들어지는가?
    - 사진(이미지) 관련 용어 정리
        - 이미지 종횡비(Image Aspect)
            - 이미지 가로(Width) ÷ 이미지 세로(Height)
            - 1920 ÷ 1080 = 1.7778
        - 픽셀 종횡비(Pixel Aspect)
            - 픽셀 가로(Width) ÷ 픽셀 세로(Height)
            - 보통은 1
            - 아나몰픽 렌즈를 사용한 경우 1.33, 1.5 또는 2
    - 초점거리(Focal Length, 포컬랭스)
        - [렌즈의 제2주점 부터 촬상면(센서 또는 필름) 까지의 거리.](https://guzene.tistory.com/147)
        - 초점거리가 길다 = 배율이 높다 = 화각이 작다
        - 초점거리가 짧다 = 배율이 낮다 = 화각이 크다
        - 포커스 디스턴스(Focus Distance)와 혼동하지 말 것. 카메라부터 피사체 까지의 거리.
    - 필름백(Film Back)
        - 필름백이 크다 = 배율이 낮다 = 화각이 크다
        - 필름백이 작다 = 배율이 높다 = 화각이 작다
    - 화각(Angle of View, 앵글 오브 뷰)
    
1. 카메라 트래킹 in 3DEqualizer (기초)
    - 3DEqualizer 살펴보기
        - Windows
        - Controls
    - 카메라 트래킹    
        - Attribute Editor에 정보 입력하기
            - Focal Length: 24mm
            - Film Back: 36 × 24mm
        - 2D Point

### 2주차

1. 카메라 트래킹 in 3DEqualizer (심화)

### n주차

1. 오브젝트 트래킹 in 3DEqualizer




















---
## OLD

### 1주차
1. 매치무브
    - 매치무브 & 파이프라인
    - 매치무브 툴 원리
1. 3DEqualizer
    - 유저 인터페이스(UI) 살펴보기
    - 포컬랭스(Focal Length) & 필름 백(Film Back) & 앵글 오브 뷰(Angle of View) 이해하기
    - 카메라 트래킹(기초)
        - 2D 포인트 트래킹(기초)
        - 솔빙(기초)
        - 오리엔트(Orient) & 스케일(Scale)
1. Maya
    - 프레퍼런스(Preference) 셋팅
    - 프리뷰 만들기(기초)
        - 플레이 블라스트(Playblast)
        - 뷰포트 2.0(Viewport 2.0)
            1. 홀드 아웃(Hold Out)
            1. 안티앨리어싱(Anti-aliasing)
1. 과제
    - cam_track_v02 플레이트 카메라 트래킹
    - 프리뷰 만들기(Hold-out) & 유튜브 업로드    
    - 매치무브 관련 영상들 조사(키워드: Matchmove, Camera Tracking, Object Tracking, Face Tracking, Rotomation 등)

### 2주차
1. 3DEqualizer
    - 카메라 트래킹(심화)
        - 2D 포인트 트래킹(심화)
        - 솔빙(심화)
            - Parameter Adjusment Window
        - 렌즈 디스토션 워크플로우
1. Maya
    - 더미 모델링
        - Triangulate Points
    - 아웃라이너 정리하기
        - 카메라 베이킹(Baking)
    - 프리뷰 만들기(심화)
        - 콘(Cone)
        - 체커(Checker)
1. 과제
    - 더미 모델 완성하기
    - 프리뷰 만들기(Hold-out & Cone & Checker) & 유튜브 업로드

### 3주차
1. 3DEqualizer
    - 오브젝트 트래킹
        - 포인트 그룹(Point Group) 이해하기
1. Maya
    - 월드 스페이스(World Space) & 로컬 스페이스(Local Space) & 스크린 스페이스(Screen Space)
    - 로테이션 오더(Rotation Order) & 짐벌락(Gimbal Lock)
1. 과제
    - 프리뷰 만들기(Hold-out & Cone & Checker) & 유튜브 업로드


### 4주차
1. About On-set
    - 현장 업무에 대한 이해 및 수행 요령
        - Shoting
        - VFX Notes
        - Tracking Markers
        ```실습을 통한 상황별 Marker들의 특성 이해```
        - Grid Shot
        - Survey Data
    - 현장 정보에 대한 중요성
        - VFX Note의 정보를 이용한 원근매치 (in Maya)
1. Survey data 제작
    - Image modelling (in 3DE)
        - Creating Survey out of Reference Frames
1. 과제
    - 같은 공간에서 서로 다른 각도로 3컷 이상 촬영해 오기
        - 24fps
        - Cut 당 3초 이하  
    - 촬영이 선행된 장소에 해당하는 공간 Image modelling 제작 해오기
        - Camera 데이터가 존재하는 .ma 파일 및 Undistort IMAGES
    
    
### 5주차
1. Ready Survey
    - 과제로 진행 됐던 Survey 데이터 점검 및 보충
1. 3DEqualizer
    - Tracking & Lineup & Solving
        - 3shot 이상 Lineup Survey data 및 Solving
1. Maya
    - 아웃라이너 정리하기
        - 카메라 베이킹(Baking)
        - 그룹핑(Grouping)
1. 과제
    - 프리뷰 만들기(Hold-out & Cone & Checker) & 유튜브 업로드
