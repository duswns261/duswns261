# 안녕하세요, Android Developer 정연준입니다

```kotlin
object DeveloperPhilosophy {

    val codeQuality = listOf(
        "가독성",      // 나 혼자만 읽는 코드는 없다
        "재사용성",    // 한 번 잘 만들면 계속 쓴다
        "캡슐화",      // 알 필요 없는 건 숨긴다
        "높은 응집도", // 관련된 것끼리 모은다
        "낮은 결합도"  // 서로 덜 의존할수록 좋다
    )

    val mindset = """
        작은 메모리 누수도, 비정상 종료도 가볍게 넘기지 않습니다.
        정밀 산업 시스템에서 쌓은 꼼꼼함을 앱 개발에 그대로 적용합니다.
    """.trimIndent()
}
```

<br>

---

## 🛠️ Tech Stack

### Android
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

### Architecture & Jetpack
![MVVM](https://img.shields.io/badge/MVVM-FF6F00?style=for-the-badge&logo=android&logoColor=white)
![ViewModel](https://img.shields.io/badge/ViewModel-1565C0?style=for-the-badge&logo=android&logoColor=white)
![Room](https://img.shields.io/badge/Room-43A047?style=for-the-badge&logo=sqlite&logoColor=white)
![Hilt](https://img.shields.io/badge/Hilt-E53935?style=for-the-badge&logo=google&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=for-the-badge&logo=square&logoColor=white)
![Coroutine](https://img.shields.io/badge/Coroutine-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Flow](https://img.shields.io/badge/Flow-0097A7?style=for-the-badge&logo=kotlin&logoColor=white)

### Database & Tools
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Previous Experience (Industrial S/W)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

---

## 📱 Featured Projects

### 1) [InOutManager](https://github.com/duswns261/InOutManager)
> **Compose 기반 재고 관리 앱**

- Jetpack Compose, Room, Coroutines, Flow 기반으로 구현한 안드로이드 앱
- MVVM 패턴과 단방향 데이터 흐름(UDF)을 적용해 구조를 분리했습니다.
- `AppContainer`, 커스텀 `Application`, `InventoryViewModelFactory`를 통해 의존성 주입 구조를 정리했습니다.
- UML 및 아키텍처 문서를 함께 정리하며, **코드뿐 아니라 구조를 설명할 수 있는 프로젝트**로 발전시키고 있습니다.

**Tech**: `Kotlin` `Compose` `Room` `MVVM` `Coroutines` `Flow`

### 2) [Kakao-API-Image-Search](https://github.com/duswns261/Kakao-API-Image-Search)
> **카카오 API 기반 이미지 검색 앱**

- Retrofit2를 활용한 네트워크 통신과 Glide 기반 이미지 로딩을 실습한 프로젝트입니다.
- `ViewPager2`, `TabLayout`, `RecyclerView`를 사용해 검색/보관함 흐름을 구성했습니다.
- API Key를 분리하여 관리하며, **기능 구현뿐 아니라 보안과 구조 개선 포인트**도 함께 정리했습니다.

**Tech**: `Kotlin` `Retrofit2` `Glide` `RecyclerView` `ViewPager2`

### 3) [Hilt-Practice-with-AI](https://github.com/duswns261/Hilt-Practice-with-AI)
> **Hilt 학습 및 비교 실험 저장소**

- Hilt 학습 과정을 여러 방식으로 비교하며 기록하는 저장소입니다.
- 단순히 기능 구현에 그치지 않고, **DI 구조를 이해하고 설명 가능한 수준까지 학습하는 과정**을 정리하고 있습니다.

**Tech**: `Kotlin` `Hilt` `Android Architecture`

---

## 🧠 What I Bring

- **문제 해결 집요함**  
  복잡한 시스템 환경에서 원인 분석, 디버깅, 트러블슈팅을 반복하며 해결해왔습니다.

- **안정성에 대한 높은 감각**  
  작은 누수나 예외도 가볍게 넘기지 않고, 실행 환경에서의 안정성을 중요하게 생각합니다.

- **협업 경험**  
  영업, 설계, 제조사, 고객사와 협업하며 요구사항 조율과 문서화를 주도한 경험이 있습니다.

- **학습을 구조화하는 습관**  
  단순히 구현만 하지 않고 README, UML, 구조 문서를 함께 정리하며 학습 내용을 자산화하고 있습니다.

---

## ⭐️ 2026 Focus

- Android 권장 아키텍처를 더 깊게 이해하기
- Hilt, Domain Layer, 테스트 코드까지 확장하기
- 프로젝트 README와 문서화를 꾸준히 개선하기
- 사용자 관점에서 안정적인 앱을 만드는 개발자로 성장하기

---

## 🤳 Contact

- Email: `duswns261@naver.com`
- GitHub: [github.com/duswns261](https://github.com/duswns261)
