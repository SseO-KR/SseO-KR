


# 개선에 보람을 느끼는 개발자, 서경원입니다.


📧 **Email :** skw4223@naver.com

📚 **Blog :** [https://gyeongwons.tistory.com/](https://gyeongwons.tistory.com/)

🧑🏻 **PortFolio :** [PortFolio Link](https://curly-crowberry-6e3.notion.site/42c446ede7134f3ea43a116e6ff7fda9?pvs=4)

</br>
</br>
</br>

# :clipboard: Projects

</br>

__RunWithMe(리팩토링)__

RunWithMe는 Android 모바일로 제공되는 비대면 러닝 챌린지 어플리케이션입니다. 동기 부여를 얻기 위해 러닝 크루에 참가한다는 소비자의 니즈를 파악하고 동기 부여에 초점을 맞춘 차별화된 어플리케이션입니다. 포인트를 내고 챌린지에 가입하고 챌린지 기간 동안 목표를 달성해야 합니다. 7월 1일부터 7월 21일까지 3주간의 기간 동안, 목표가 주 3회 거리 3km라면 3주 동안 매주 3번 이상 3km를 달려야 목표에 성공합니다. 학습을 목표로 최적화를 위해 리팩토링하고 있습니다.
- [https://github.com/7SideProject/RunWithMe-AOS](https://github.com/7SideProject/RunWithMe-AOS)
</br>

1.	GPS 오차로 경로가 부정확하고 좌표 데이터가 너무 많아지는 문제를 경로 최적화를 적용하여 좌표 데이터를 약 73% 감소하고 경로 방향의 정확성 개선
2.	Service와 Activity와 통신으로 companion object를 사용하면서 할당 해제되지 않는 객체가 존재하던 문제를 bindService를 활용하여 3600개의 좌표 리스트가 GC에 의해 수거되도록 변경
3.	Service와 LifecycleService와의 차이점을 파악하고 LifecycleScope를 활용해 해제되지 않은 CoroutineScope를 해제하면서 메모리 누수 방지
4.	파일 크기로 이미지를 보낼 수 없던 문제를 파일 확장자 변경으로 해결
5.	보일러 플레이트 제거하기 위해 CustomView, Extensions, 확장 class 등을 적용하며 재사용에 대해 고민
   
</br></br>

__우리집__

우리집은 Android 모바일로 제공되는 가족 소통 활성화 어플리케이션입니다. 가족 소통 단절을 개선하고자 하였고 서로의 관심사를 파악하여 소통을 활성화할 수 있도록 했습니다.
- [https://github.com/6Android/OurHome](https://github.com/6Android/OurHome)

</br>

1.	JSON 트리 구조의 단점을 가진 Firebase Realtime Database 대신 Document Model Database 구조인 FireStore 사용

</br></br>

__InDive__

InDive(인다이브)는 Android 모바일로 제공되는 블록체인 기반 인디 가수 후원 어플리케이션입니다. 음원 스트리밍 사이트의 수수료가 비싸기 때문에 인디 가수를 후원하고자 하였고 수수료 횡령 사건이 있었기 때문에 투명하게 후원 시스템을 운영하고자 블록체인 기반의 인디 가수 후원 서비스를 개발하게 되었습니다.
- [https://github.com/InDiveTeam/InDive](https://github.com/InDiveTeam/InDive)

</br>

1.	음원 Streaming 요청 시 약 2초 정도의 딜레이가 있던 MediaPlayer 문제를 ExoPlayer 적용하여 Streaming 속도 개선
2.	블록체인 지갑의 개인 키, 토큰 탈취 위험을 보완하기 위해 지문 인증, KeyStore를 사용하여 보안성 강화
3.	버스킹 현장에서 직접 가수를 검색해야 하는 불편함을 QR 기능으로 편하게 후원할 수 있도록 개선

</br></br>

__RunWithMe__

RunWithMe는 Android 모바일로 제공되는 비대면 러닝 챌린지 어플리케이션입니다. 동기 부여를 얻기 위해 러닝 크루에 참가한다는 소비자의 니즈를 파악하고 동기 부여에 초점을 맞춘 차별화된 어플리케이션입니다. 
- [https://github.com/skw4223/RunWithMe](https://github.com/skw4223/RunWithMe)

1.	동기 부여를 위한 의욕을 저하하는 비정상적인 움직임을 막아 확실한 인증을 하도록 함
2.	데이터가 유실되어 보이는 기존 Paging 문제를 커서 페이징을 이용하여 해결
3.	Wearable App을 제공하여 러닝에 대한 편의성 제공

</br>
</br>
</br>


# :pencil2: Education
__삼성 청년 SW 아카데미 (2022.01 ~ 2022.12)__

</br>

__오픈 소스 스터디 1기 (GDG SongDo)__
- Coroutine Open Source 코드를 분석하고 Coroutine의 특징과 분석 내용, Kotlin 문법을 함께 발표

</br>

__오픈 소스 스터디 2기 (GDG SongDo)__
- 각자 오픈 소스 PR 기여를 목표로 진행하였고 android-maps-utils PR 요청으로 목표 달성


</br>
</br>
</br>



# 🥇 Awards
</br>

__SSAFY 공통 프로젝트 우수상 (2022.08.19)__
</br>
__SSAFY 관통 프로젝트 우수상 (2022.05.27)__

</br></br>


<!--
**skw4223/skw4223** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
