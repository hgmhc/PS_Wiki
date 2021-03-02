# PS_Wiki

## 기본적으로 필요한 문서 목록
 
### 대분류
C, C++ 기초 문법
문제 유형
STL - compiler extension은 따로 작성
알고리즘
대회
알고리즘 동아리 - 학교 이름 주석으로 기재
용어 - 뜻 or 유래 주석으로 간단하게 기재 권장
 
### C, C++ 기초 문법
- [[프로그래밍 언어]]
- [[C]]
- [[C++]]
- [[표준 입출력]]
- [[배열]]
- [[반복문]]
- [[함수]]
- [[Lambda]]
- [[문자열]]
- [[실수]]
- [[구조체]]
- [[클래스]]
- [[헤더]]
- [[포인터]]
- [[참조]]
- [[매크로]]
 
### 문제 유형
- [[Batch]]
- [[Batch with Grader]]
- [[Interactive]]
- [[Output Only]]
- [[Communication]] //Codeforces-Style interactive
- [[Two Step]]
 
### STL
#### Container / ADT
- [[stack]] / [[vector]]
- [[queue]] / [[priority_queue]]
- [[list]] / [[deque]]
- [[set]] / [[multiset]]
- [[map]] / [[multimap]]
- [[unordered_set]] / [[unordered_map]]
- [[pair]] / [[tuple]]
#### STL 내장 함수
- [[sort]]
- [[unique]]
- [[reverse]]
- [[iterator]]
- [[iota]]
- [[accumulate]]
- [[to_string]] / [[atoi]] / [[atof]]
- [[gcd]] / [[lcm]]  //C++17
- [[fill]] / [[fill_n]]
- [[memset]]
- [[sample]] //C++17
- [[clamp]]  //C++17
- builtin 함수 시리즈
- numeric에 유용한 거 많던데…
- string이랑 cmath에도 유용한 거 많아요… 솔직히 이 글에서 유용한 함수들을 모두 담기에는 무리가 아닌가 싶어요
#### Compiler Extensions
- [[__gnu_pbds::tree]]
- [[__gnu_cxx::rope]]
- [[builtin functions]]
 
### 알고리즘
#### 초급 (기초 개념)
- [[정렬]]
- [[백트래킹]]
- [[비트마스크]]
- [[DFS]]
- [[BFS]]
- [[이분탐색]] / [[삼분탐색]]   //삼분 탐색 여기 있어도 되나요?
- [[그리디]]
- [[Prefix Sum]]
- [[DP]] 기초
#### 중급 (골드5~)
- [[그래프 이론]]
- [[위상 정렬]]
- [[분리 집합]]
- [[최소 신장 트리]] (prim, kruskal)
- [[최단 경로 알고리즘]] (Dijkstra, Floyd-Warshall, Bellman-Ford/SPFA, 0-1 BFS)  //그냥 BFS를 넣을지 확인 부탁드려요
- [[Strongly Connected Component]] (Kosaraju, Tarjan)
- [[Biconnected Component]]
- [[Sparse Table]]
- [[최소 공통 조상]]
- [[조합론]]  //조합론이 스펙트럼이 너무 넓은 것 같습니다
- [[스위핑]]
- [[분할 정복]]
- [[세그먼트 트리]]
- [[Binary Indexed Tree]]  //a.k.a. fenwick tree
- [[Lazy Propagation]]
- [[KMP]]
- [[Trie]]
- [[Manacher]]
- [[Z Algorithm]]
- [[CCW]]
- [[Point in Polygon]]
- [[Convex Hull]]
- [[Rotating Calipers]]
- [[Sqrt Decomposition]]
- [[Mo's Algorithm]]
- [[Merge Sort Tree]]
- [[중국인의 나머지 정리]]
- [[잉여 역수]]
- [[확장 유클리드 알고리즘]]
- [[에라토스테네스의 체]]
- [[Smaller to Larger Technique]]
- [[행렬 거듭제곱을 이용한 선형 점화식 계산]]
- [[Tree DP]] / [[Bitmask DP]]
- [[Precomputation]]
#### 고급 (플래3?~)
- [[랜덤으로 문제 풀기]]
- [[병렬 이분 탐색]]
- [[접미사 배열]]
- [[LCP 배열]]
- [[아호코라식]]
- [[이분 매칭]]
- [[Network Flow]] // 플로우 계열 알고리즘의 개요
- [[Network Flow/Max Flow]] //Ford Fulkerson, Dinic
- [[Network Flow/MCMF]] //spfa 등을 이용한 일반적인 mcmf 알고리즘
- [[Network Flow/MCMF/zkw MCMF]] //Hell Joseon Style MCMF
- [[Network Flow/LR Flow]]
- [[Hungarian Algorithm]]
- [[Minimum Cut]] //Network Flow 하위문서에서 분리
- [[Minimum Cut/Global Min Cut]]
- [[Euler Tour Trick]]
- [[Heavy Light Decomposition]]
- [[Centroid Decomposition]]
- [[Persistent Segment Tree]]
- [[Multidimensional Segment Tree]]
- [[Convex Hull Optimization]]
- [[Divide and Conquer Optimization]]
- [[Knuth Optimization]]
- [[Sprague-Grundy Theorem]]
- [[Discrete Logarithm]]
- [[Miller Rabin Primarity Test]] / [[Pollard Rho Algorithm]]
- [[Fast Fourier Transform]]
- [[Fast Fourier Transform/NTT]]
- [[Fast Fourier Transform/FWHT]] // and or xor convolution
- [[Burnside’s Lemma]]
- [[Berlekamp-Massey Algorithm]]
- [[Kitamasa]] // O(M^2 log N)
- [[Offline Dynamic Connectivity]]
#### 고인물 (다이아3~)
- [[Dual of Planar Graph]]
- [[Offline Dynamic MST]]
- [[Segment tree beats]]
- [[Fast Fourier Transform/응용]] // 다항식 나눗셈 등등 ex) multipoint evaluation
- [[Kitamasa/FFT]] // (M log M log N) ex) RNG/목공 / 문서 분리 or FFT 언급만 하기 결정 필요
- [[Matroid]]
- [[Matroid/Matroid Partition]]
- [[Matriod/Matroid Intersection]]
- [[K-d Tree]]
- [[Rope]]
- [[Treap]]
- [[Splay Tree]]
- [[Link Cut Tree]]
- [[Dominator Tree]]
- [[Connection Profile DP]] 
- [[Hirschberg]]
- [[Monotone queue optimization]]
- [[Slope Trick]]
- [[Alien's Trick]]
- [[Discrete Square Root]] / [[Discrete kth root]]
- [[Discrete Log]]
- [[Xudyh’s Sieve]]
- [[Fast Prime Counting Algorithm]]//  Lucy-Hedgehog 기준으로 쓸 예정
- [[bitset 최적화/LCS]]
- [[Ad-Hoc/Circular LCS]]
- [[Blossom Algorithm]] //General Matching
- [[Directed Minimum Spanning Tree]]
- [[Voronoi Diagram]] / [[Delaunay Triangulation]]
- [[Weighted General Matching]] // 이거 루비 3이에요
- [[Online Dynamic Connectivity]] // 이건 루비 1이에요
#### 실행 시간을 줄이는 여러 가지 기법
- [[Fast IO]]
- [[SIMD]]
- [[bitset 최적화]] // 이것도 bitset 태그 있지않나요? / 고급~고인물에 넣을지, 여기에 그대로 유지할지 논의 필요 // 고급이나 중급? / 그대로 유지하는 게 좋을 것 같아요
- [[컴파일러 최적화]] // -O2, -O3, -Ofast, -funrolling-loops, -ffast-math 등 / -mavx 등은 SIMD에 기재
- [[Barrett Reduction - 모듈로 최적화]]
 
### 대회
#### Olympiad
- [[IOI]]
- [[APIO]]
- [[CEOI]]
- [[Balkan OI]]
- [[Baltic OI]]
- [[KOI]]
- [[JOI]]
- [[POI]]
- [[USACO]]
- [[COCI]] //(Croatian Open Competition in Informatics) Is it OI? // IOIinformatics에 홍보글이 올라오던데 highschool contest라보는게 맞는데 어디넣지 - COCI는 크로아티아 usaco라 보면 됩니다
#### Camp
- [[JOI OC]] //Not Camp
- [[JOI SC]]
- [[ONTAK]]
- [[Algorithm Engagement]]
- [[Petrozavodsk Programming Camp]]
#### ICPC
- [[ACM-ICPC World Finals]]
##### 아시아 지역
- [[세미 월파]]
- [[Korea Regional]]
- [[Japan Regional]]
##### 유럽 지역
- [[CERC]]
- [[NWERC]]
- [[NEERC]]
- [[SWERC]]
- [[SEERC]]
#### 기업 대회
- [[Samsung Collegiate Programming Cup]]
- [[Nexon Youth Programming Challenge]]
- [[Kakao Code Festival]]
- [[Google Code Jam]]
- [[Facebook Hacker Cup]]
#### 교내 대회
- [[SNUPC]] - 서울대학교
- [[KAIST RUN Spring Contest]] - 카이스트
- [[KCPC]] - 고려대학교
- [[HOLICS]] - GIST
- [[Sogang Programming Contest]] - 서강대학교
- [[SCCC Programming Contest]] - 숭실대학교
- [[숭고한 연합 Algorithm Camp]] - 숭실/고려/한양
- [[나는 코더다 송년대회]] - 경기과학고등학교
- [[SciOI]] - 서울과학고등학교
- [[천하제일 코딩대회]] - 선린인터넷고등학교
- [[UCPC]] - 전국 대학생 프로그래밍 대회 동아리 연합
#### 온라인 커뮤니티 대회
- [[Codeforces]]
- [[Atcoder]]
- [[Topcoder]]
- [[Codechef]]
#### 개인 주최 대회
- [[키파컵]]
- [[Good Bye, BOJ]]
- [[소프트콘]]
- [[웰노운컵]]
- [[꼬마컵]]
- [[네블컵]]
- [[구데기컵]]
- [[kriiicon]]
- [[FunctionCup]]
- [[HYEA Cup]]
- [[IDTCup]]
 
### 알고리즘 동아리
- [[SNUPS]] - 서울대학교
- [[RUN]] - 카이스트
- [[ALPS]] - 고려대학교
- [[ALKOR]] - 고려대학교
- [[ALOHA]] - 한양대학교
- [[Sogang ICPC Team]] - 서강대학교 
- [[SCCC]] - 숭실대학교
- [[나는 코더다]] - 경기과학고등학교
- [[SciCom]] - 서울과학고등학교
- [[SHARC]] - 선린인터넷고등학교
- [[UCPC]] - 전국 프로그래밍 대회 동아리 연합 (UCPC 대회와 같은 문서)
 
### 용어
#### 줄임말+일상 용어
- [[데추주]] 데이터를 추가해주세요
- [[맞왜틀]] / [[틀왜맞]] 맞았는데(틀렸는데) 왜 틀려(맞아)
- [[예예출맞]] 예제는 예제만 출력해도 맞아
- [[좌셋]]
#### 웰논 드립
- [[notorious coincidence]] (https://codeforces.com/blog/entry/52348?#comment-364302)
- [[unethical and ugly behavior]] (https://codeforces.com/contest/1120)
- [[매운 음식]] (https://koosaga.com/217#comment14636312)
- [[temporarily available]]
- [[twice]] (https://codeforces.com/blog/entry/62775)
- [[good tester]] (https://codeforces.com/blog/entry/69006?#comment-533760)
- [[Is it rated?]]
- [[semi-rated]]
- [[JUST USE BITSET]] (https://codeforces.com/blog/entry/53168) 이 문서는 비트셋으로 최적화 안 되나요? \infty 차원 bitset으로 최적화하면 O(1)에 작성 가능합니다. 감사합니다. (대충 제리 인사짤) / O(L)
