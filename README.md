### 기업연계 프로젝트 (2022.09 ~ 2022.11)

코로나 대처 어플리케이션(안드로이드를 이용한 헬스케어 어플 저작권 등록[C-2022-054014])

- 상세 내용
    
    LINK : https://github.com/vahallla/covid
    
    ![기연프1_사진1 PNG](https://github.com/user-attachments/assets/6c7b9b8b-b4c8-4f12-a93c-5e949f02cef0)

    
    ## **현재 코로나 확진자수 , 주변 선별진료소 위치등 확진자와 사람들의 편의를 제공하는 APP**
    
    ### 프로젝트 진행 인원
    
    → 총 6명 진행  
    
    ### 프로젝트 목적
    
    신규 확진자 및 고위험군을 대상으로 선별진료소 위치를 최신화된 데이터를 제공하여 해당 사람들이 빠르게 의료 서비스를 제공받을 수 있게 정보를 제공하는 목적
    
    ---
    
    ### 맡은 역할 내용
    
    - **Android Studio를 활용한 Client Application 제작**
        - kakao Map API를 이용한 선별진료소 위치 마커
        
        ![기연프1_사진3 PNG](https://github.com/user-attachments/assets/95516f26-3618-47e9-909f-e5091198a25a)

        
        - ListView로 가까운 순으로 선별진료소 정렬
        
        ![기연프1_사진2 PNG](https://github.com/user-attachments/assets/4156799b-c417-4ef0-8f19-bd0f31b0e3e6)

        
        ---
        
    
    ### 문제 해결 내용
    
    - kakao Map API 와 안드로이드 클라이언트 사이의 연동과정에 대한 이해가 부족하여 , 카카오 지도 정보를 안드로이드 컴포넌트에 적용하는데 어려움을 겪음
    
          → UI구성 및 해당 UI에 대한 액티비티 구성을 우선으로 프로젝트 진행
    
    - kakao Map API를 구성하는 과정에서 지도 화면이 계속 나오지 않았던 문제 발생
    
          → 원인을 찾던중 , AndroidManifiest.xml 파일에 네이티브 앱키가 작성되지 않아 출력되지 않았음을 발견하였고 , 올바른 위치에 작성하여 해결
    
    - 개발 과정중 작성한 언어인 JAVA와 정보를 검색하여 개발한 내용의 언어가 Kotlin 이어서 소스코드가 서로 상이한 상태가 발생하여 프로젝트 진행에 어려움 발생
    
          → JAVA 기반으로 만들어진 프로젝트에 Kotlin 소스코드를 사용가능하게 하는 플러그인 내용을 추가하여 적용후 문제 해결
    
    ### 아쉬운 점
    
    - 만약 kakao Map API의 데이터가 최신화 되어있지 않아서 발생하는 정보 공백 문제
    
          → 버튼을 생성해 수동적으로 선별진료소 마커를 등록하게 하고 , 해당 정보를 별도의 로컬DB에 저장하게 계획을 진행하였으나 시간부족 및 첫 REST API 적용에 대한 이해 부족으로 진행하지 못한점
    
    → **추후 DB를 사용하는 앱 프로젝트 진행과 , REST API를 사용한 웹 프로젝트를 진행하였음.**
    
    - 카카오 지도 마커의 ‘인포윈도우’ 클릭시 해당 선별진료소 지점에 Uri를 연결해 역학조사 등의 서비스를 편리하게 제공하려고 시도
    
          → 더 편의성을 높이기 위해 각 선별진료소의 URL로 연결해 바로 역학조사를 진행할 수 있게 계획 하였으나 시간 부족으로 진행하지 못한점
    
    ### 발전한 내용
    
    1. **첫 과제 진행형 프로젝트이자 , 첫 개발 팀 프로젝트**
    2. **완성된 안드로이드 어플을 만들고 , 테스트 및 서비스를 하는 모든 과정이 처음 겪는것이기에 난항을 겪기도 했지만 , 그 과정에서 진행이 될수록 자신감이 붙고 , 새로 무언가를 만들고 적용한다는 것에 재미를 느꼈음.**
    3. **REST API를 안드로이드 프로젝트에 적용하는 방식과 , 추가 라이브러리를 사용하려면 어떻게 프로젝트에 적용해야하는지 , 안드로이드 프로젝트 구성에 대한 것을 깨달았던 첫 프로젝트**
