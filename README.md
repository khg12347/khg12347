# 매년 성장하는 유니티 클라이언트 프로그래머입니다.

Unity 6 · C# 기반 게임 개발을 하고 있습니다.  
설계 의도가 명확한 구조, 유지보수 가능한 코드를 지향합니다.

---

## 🎮 Mine Mine Mine

> 광물을 캐고 곡괭이를 성장시켜 최강의 곡괭이를 만드는 2D 도트아트 모바일 캐주얼 게임 (개인 프로젝트 · 개발 중)

<a href="https://github.com/khg12347/MineMineMine">
  <img src="https://github.com/khg12347/MineMineMine/raw/main/docs/gameplay.gif" width="300" alt="Mine Mine Mine gameplay"/>
</a>

**Unity 6 · URP 2D · C# · New Input System**

### 핵심 설계

| 시스템 | 요약 |
|---|---|
| **레이어 아키텍처** | Presentation → Domain → Data → Core 단방향 의존 구조 |
| **서비스 로케이터** | 씬 전환 시 초기화 순서 문제 해결, DI 전환 대비 설계 |
| **제네릭 오브젝트 풀링** | HashSet 병행 O(1) 중복 반환 방지, 자동 확장 |
| **무한 하강 스테이지** | Flood Fill 기반 청크 버퍼 + 풀 경유 스폰/컬링 |
| **타일 파괴** | Model/View 분리, IMIBreakable 인터페이스로 곡괭이·터치 통합 |
| **데이터 설계** | ScriptableObject 팩토리 패턴, 기획자 친화 에디터 구성 |

➡️ **[레포 바로가기 · 상세 README](https://github.com/khg12347/MineMineMine)**

---

### 📫 Contact

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:khg12347@gmail.com)
