## 기본정보
- 교육장소: CG5
- 교육대상: 매치무브 파트 취업준비 중인 학생(직장인 X)
- 교육기간: 5주 (주 1회, 토요일, 3~4시간)
- 준비물: Autodesk Maya, 3DEqualizer

## 내용

### 1주차

1. [카메라 기초](https://www.youtube.com/watch?v=xgx8jMrGARg)
    1. [역사](https://youtu.be/-Y4YZlEQafs)
    1. 카메라 종류
        - Compact, Mirrorless, DSLR, Film, Cinema 등
    1. 카메라 구조
        1. [렌즈](https://youtu.be/dg3kIKphB5E)
            - 카메라의 눈.
            - 렌즈를 통해 카메라 안으로 빛이 들어온다.
        2. 바디
            - 촬상면(이미지 센서 또는 필름)
    1. 셔터 스피드 & ISO & 조리개
        1. 셔터 스피드(Shutter Speed)
            - 바디에서 제어
        1. ISO
            - 바디에서 제어
        1. 조리개
            - 렌즈를 통해 들어오는 빛의 양을 조절하는 구멍.
            - 렌즈에서 제어
    
1. [영상 기초](https://youtu.be/ZKmNUP_5TFQ)
    - 영상: 이미지(Image). 정지 사진(Still Picture).
        > ![The_Horse_in_Motion_high_res_qtr.jpg](imgs/The_Horse_in_Motion_high_res_qtr.jpg)
        > <br>[Eadweard Muybridge - Wikipedia](https://en.wikipedia.org/wiki/Eadweard_Muybridge)
    - 동영상: 시간상 연속된 정지 사진들의 모음. 마치 움직이는 듯한 느낌의 착각.
        > ![The_Horse_in_Motion-anim.gif](imgs/The_Horse_in_Motion-anim.gif)
        > <br>[Eadweard Muybridge - Wikipedia](https://en.wikipedia.org/wiki/Eadweard_Muybridge)
    1. 화소(Pixel, 픽셀)
        - 이미지를 구성하고 있는 최소 단위
            > ![Pixel-example.png](imgs/Pixel-example.png)
            > <br>[Pixel - Wikipedia](https://en.wikipedia.org/wiki/Pixel)
    1. 해상도
        - 이미지의 픽셀개수
        - 표기법: <가로줄 픽셀개수> × <새로줄 픽셀개수>
        - 1920 × 1080 = 2,073,600
    1. 종횡비(Aspect Ratio)
        - <가로> ÷ <새로>
        - 이미지 종횡비(Image Aspect Ratio)
            - 6000 ÷ 4000 = 1.5
            - 1920 ÷ 1080 = 1.778
        - 픽셀 종횡비(Pixel Aspect Ratio)
            - 1 ÷ 1 = 1
    1. 프레임 레이트(Frame Rate)
        - 초당 프레임 수(FPS, Frames Per Second)
    1. [이미지 파일 형식(Image file formats)](https://ko.wikipedia.org/wiki/이미지_파일_형식)
        - 많이 쓰는 확장자 - jpg , png , dpx , exr 등 
    1. 이미지 시퀀스(Image Sequence) & 비디오 파일(Video File)
        - 이미지 시퀀스
            - 동영상을
            - <네임(Name)>.<패딩(Padding)>.<확장자(Extention)>
            - my_video.0001.jpg , my_video.0002.jpg , my_video.0003.jpg ...
        - 비디오 파일
            - 이미지 시퀀스를 단일 파일로 압축한 파일.
            - 많이 쓰는 확장자 - mp4 , mov 등
        - CG툴(Autodesk Maya, 3DEqualzier 등)은 보통 이미지 시퀀스 친화적. 반대로, 편집툴(Premiere Pro, Final Cut Pro)은 비디오 파일 친화적.
     
1. [탑임랩스(Time Lapse) 동영상](https://youtu.be/_Ecxt_W96x0) 만들기
    - 카메라를 움직이면 더 다이나믹 하고 재미있는 [하이퍼랩스(Hyperlapse) 동영상](https://upload.wikimedia.org/wikipedia/commons/9/98/Brisbane_Hyperlapse_2013_%28trimmed%29.ogv)을 만들 수 있다.
    - 이미지 시퀀스(Image Sequence) 만들기
        - XnViewMP로 리네이밍(Renaming)
        - [XnViewMP Download Page Link](https://www.xnview.com/en/xnviewmp/)
    - 'DJV Imaging'으로 이미지 시퀀스 재생하기
        - [DJV Imaging Download Page Link](http://djv.sourceforge.net/Download.html)

### 2주차

1. 카메라 심화
    - 초점거리(Focal Length, 포컬랭스)
        - [렌즈의 제2주점 부터 촬상면(센서 또는 필름) 까지의 거리.](https://guzene.tistory.com/147)
        - 표기법: (초점거리)mm. 예) 8mm, 35mm, 100mm.
        - 초점거리가 길다 = 배율이 높다 = 화각이 좁다
        - 초점거리가 짧다 = 배율이 낮다 = 화각이 넓다
        - 포커스 디스턴스(Focus Distance)와 혼동하지 말 것. 카메라부터 피사체 까지의 거리.
    - 필름백(Film Back)
        - !!! 센서 사이즈 ≠ 필름백 사이즈 !!!
        - 표기법: (필름백 가로) × (필름백 새로)mm. 예) 36 × 24mm. 'mm(미리미터)' 또는 'inch(인치)' 사용.
        - 카메라는 사진을 만들때 센서(또는 필름)의 전체 또는 일부분만 사용한다. 이때 촬영시 사용한 센서의 영역(Effective Sensor Area)이 필름백 사이즈다.
        - 필름백이 크다 = 배율이 낮다 = 화각이 넓다
        - 필름백이 작다 = 배율이 높다 = 화각이 좁다
    - 화각(Angle of View, 앵글 오브 뷰)

1. 매치무브 기초
    - 매치무브 이해
        1. What? 3D to 2D & 2D to 3D
        1. Why? CG요소를 실촬영본에 배치하고자 할때(그 반대도) 매치무브 작업은 필수다. 
        1. Who? Matchmove Artist, Matchmover, Integration Artist
        1. How?
            - 손으로(By Hand)
            - [MCC(Motion Control Camera)](https://youtu.be/UIwdCN4dV6w)
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

1. 카메라 트래킹 in 3DEqualizer (기초)
    - 3DEqualizer 살펴보기
        - Windows
        - Controls
    - 카메라 트래킹
        - 이미지 불러오기(import)
            - Reference Camera
        - Attribute Editor에 정보 입력하기
            - Focal Length: 24mm
            - Film Back: 36 × 24mm
        - 2D Point

### 3주차

1. 카메라 심화
    - 렌즈 디스토션(Lens Distortion)

1. 카메라 트래킹 in 3DEqualizer (심화)
    - 카메라 트래킹
        1. 이미지 불러오기(import)
            - Sequence Camera
            - 파일: trackboy
        1. Attribute Editor에 정보 입력하기
            - Focal Length: ?mm (Metadata, 메타데이터)
            - Film Back: ? × ?mm
        1. 2D Point
            - Manual Tracking Controls(F2)
            - Basic Hotkeys
                - <kbd>t</kbd>: Track all frames
                - <kbd>,</kbd>,<kbd>.</kbd>: Track backward 1 frame, Track foreward 1 frame
                - <kbd>e</kbd>: Start Point & End Point
                - <kbd>ctrl + r</kbd>: Remove Keyframe
         1. Solving
         1. Parameter Adjustment
         1. 

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
