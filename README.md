# 챗스테이란? 

사용자 정보를 기반으로 적절한 숙소를 추천해주는 **LLM 기반 채팅형 숙소 어플리케이션**입니다. 팀원은 **백엔드 1명, AI 1명, 프론트(앱) 1명**으로 이루어져 있습니다. 

# 구현 기능 - 1학기(05/01 ~ 06/15) 
1. 소셜 로그인 기능 (카카오)
2. 온보딩 기능 (사용자 추가 정보)
3. 채팅 기능 (AI 챗봇 대화, 숙소 추천, 필터링)
4. 숙소 정보 제공

# 구현 기능 - 2학기(09/22 ~ 11/12)
1. 소셜 로그인 기능 (구글, 네이버)
2. 녹음 기능 (음성 → 텍스트 변환)
3. 지도에 숙소 및 관광지 표시
4. 실시간 위치 파악 (GPS 연동)
5. 장소 통합 검색 기능 (POI)
6. 길찾기 기능 + 고속도로 경로 안내 (자동차 길안내)
7. 게스트 로그인

# 사용 기술
- UI(User Interface) : Material Design 3 (Slider, ProgressBar, CardView, Chip), Lottie Animation
- Server API 연동 : Retrofit, OkHttp3, Gson
- Open API : Google Login, Kakao Login, Naver Login, OpenAI STT, TMAP, TMAP 대중교통, 지오비전 퍼즐(국내여행)
- Android Jetpack : Navigation, ViewModel, LiveData(Observer)
- 기타 : ViewPager2, Glide, RecyclerView(Multi View Type)

# 개선할 부분 - 그 이후
- 길찾기 기능(지하철, 버스, 도보)
- POI 기능 개선 - 실시간 조회 가능

# 구현 기술 블로그
- [bottom navigation view] https://soung-appdeveloper.tistory.com/145
- [kakao login api] https://soung-appdeveloper.tistory.com/147
- [naver map api] https://soung-appdeveloper.tistory.com/149
- [bottom sheet dialog, progressbar, slider] https://soung-appdeveloper.tistory.com/151
- [chat] https://soung-appdeveloper.tistory.com/152
