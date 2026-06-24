Professors give to me feedback to modify our website : 

1. [x] KIST 상주 Fellow는 Research Area - Bioinformatics(Single cell transcriptome/Spatial transcriptome analysis)로 recruit할 예정
   → Project D를 "Bioinformatics — Single-cell & Spatial Transcriptome Analysis"로 변경 (project/index.html)
2. [x] euiheon.chung@gist.ac.kr 이라고 되어있는거 전부 바꿔. 정의헌 교수님 메일은 ogong50@gist.ac.kr이야
   → contact/index.html, member/index.html 전부 ogong50@gist.ac.kr로 교체
3. [x] 김재관 교수님 연구실 랩 웹사이트는 tedi.gist.ac.kr이야
   → 팀 페이지 Prof. Jaegwan Kim에 링크 추가 (member/index.html)
4-1. [x] Benefit -> KRW 90M+/yr => Upto KRW 90M+/yr 변경 (fellowship/index.html)
4-2. [x] Benefit -> KRW 60M/yr => Upto KRW 60M/yr 변경 (fellowship/index.html)
4-3. [x] Benefit -> GIST x KIST : Dual mentorship => "Multiple mentorship" 변경 (fellowship/index.html 등)
5. [x] banner.png를 넣어뒀는데 이걸 각 페이지 맨 위에 항상 뜨게 두면 좋을 것 같아. 메인 그림이라서
   → 모든 페이지 헤더 아래 .site-banner로 추가
6. [x] logo.png도 넣어놨으니 추가해줘
   → 모든 페이지 헤더 브랜드에 .brand-logo로 추가
7. [x] 김재관 교수님 성함 kwan이 아니라 gwan임(프로젝트와 팀에 있음)
   → Jaekwan → Jaegwan (member/index.html, project/index.html)
8. [x] 팀에서 교수님 사진들은 정의헌과 류 훈 빼고는 사진 전부 삭제해도돼.
   → Jiyeon Kang, Hyuksang Kwon, Tae Kim, Jaegwan Kim 사진 삭제 (정의헌·류훈만 유지)
9. [x] 모바일로 많이들 보는 것 같은데 모바일로도 볼 수 있게 flex되면 좋을 것 같아. 꺠진다는 말이 많네
   → 전역 img max-width, 반응형 헤더/배너, 480px 브레이크포인트 보강
10. [x] REMAP 배너가 사진 크기대로라 중간에 잘린 느낌 → 가로 끝까지 구성
   → .site-banner img의 max-width(1300px)/가운데 정렬 제거, width 100% 풀-블리드 (assets/css/style.css)
11. [x] Logo 조금만 더 키워줘 / (재요청) 더 키우고 가로도 제대로
   → .brand-logo 30px → 44px → 60px; 배너 풀-블리드 확정 (헤드리스 렌더로 1600px 가로 꽉 참 확인)
   → 캐시 미반영 대비 모든 페이지 style.css 링크에 ?v=3 캐시 버스팅 추가
