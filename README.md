
---
|[K014_김지훈](https://github.com/jay200333)|[K022_모영민](https://github.com/moyeongmin)|[K023_문유리](https://github.com/915dbfl)|[K041_이훈](https://github.com/pengcon)|[K051_천일영](https://github.com/Cheonilyeong)|
|:-----:|:-----:|:-----:|:-----:|:-----:|
|<img src= https://github.com/user-attachments/assets/6e7b38c8-c6f6-451c-a233-83f9007256ab width=190 height=200 >|<img src= https://github.com/user-attachments/assets/1dc9f39a-edda-4665-bf5a-d01fba4924d3 width=190 height=200 >|<img src="https://github.com/user-attachments/assets/4215d583-1690-4c23-8330-5b5bd8ad125a" width=190 height=200>|<img src="https://github.com/user-attachments/assets/83af745e-f77e-4032-97f4-2cadf0d99556" width=180 height=200>|<img src="https://github.com/user-attachments/assets/46cdda87-30d9-4e51-a9b2-d29f5d5b87b3" width=180 height=200>|
|즐거운 마음으로 | 말 많은 감자입니다 | (스텝 바이 스텝🎶🎶) | 7시간은 자야합니다 | 100010 |
---
# WeQuiz~?🍦

스터디 그룹 내에서 학습을 더욱 **효과적으로** 그리고 **즐겁게** 진행할 수 있는 퀴즈 기반 학습 서비스 **WeQuiz~?🍦**에 오신 것을 환영합니다!

<br>

<div align="center">

| 📚 리소스              | 🔗 링크                                                                                                                         | 설명                                   |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
| 📖 **GitHub 위키**     | [WeQuiz GitHub Wiki](https://github.com/boostcampwm-2024/and02_weQuiz/wiki)                                                     | 프로젝트 문서화 및 개발 가이드          |
| 📃 **팀 노션**         | [WeQuiz 팀 노션](https://trite-ice-00b.notion.site/we-kids-1275bfe2c24f801e88c0efe0f0fb1071?pvs=4)                             | 프로젝트 계획 및 일정 관리              |
| 🎨 **피그마 디자인**   | [WeQuiz Figma 디자인](https://embed.figma.com/design/OM2OS94tdFHdJ5PnWnxKeZ/%EC%9C%84%ED%80%B4%EC%A6%88?node-id=0-1&theme=system) |    UI 및 UX 디자인 참고                 |
| 📋 **백로그**          | [WeQuiz 백로그](https://github.com/orgs/boostcampwm-2024/projects/4)                                                                                   | 프로젝트 작업 및 우선순위 관리          |

</div>
<br>
저희 팀원들은 스터디를 하면서 **학습에만 초점이 맞춰져 있어, 정리와 복습에 대한 시간이 부족**하다는 문제를 느꼈습니다. 이를 보완하고자, 스터디 그룹 내에서 **퀴즈 형식으로 학습을 정리하고 복습할 수 있는 서비스**를 구상했습니다.

---

**WeQuiz**는 다음 두 가지의 퀴즈 형식을 통해, 더욱 효율적이고 유익한 학습을 제공합니다:

1. **자유롭게 원하는 시간대에 진행할 수 있는 퀴즈**
2. **한 명의 주도 아래 실시간으로 참여 가능한 퀴즈** (Slido 방식과 유사)

---

<br>

## 기술 스택 
| Category  | TechStack | 관련 문서 |
| ------------- | ------------- | ------------- |
| Architecture  | Clean Architecture, Multi Module, MVVM  | [클린 아키텍쳐 선택 근거](https://www.notion.so/65af7f3ff4de425ba5ef818a123c13c3?pvs=4#57687e8fd3c044dca88f700553ed6326)⎮[gradle plugin 활용하기(1)](https://915dbfl.github.io/android/gradle-plugin(1)/) ⎮[gradle plugin 활용하기(2)](https://915dbfl.github.io/android/gradle-plugin(2)/)
| DI | Hilt | [Why Hilt?](https://www.notion.so/65af7f3ff4de425ba5ef818a123c13c3?pvs=4#b8490660e7954618b8817af465ada612)
| Network | Retrofit, OkHttp, Kotlin Serialization?? (수정 해야됨) | 
| Asynchronous | Coroutines, Flow | [load 데이터를 언제 하면 좋을까?](https://www.notion.so/1315bfe2c24f8064837fc11fa838e586?p=13d5bfe2c24f8019b310f3d195174655&pm=s)
| Jetpack |  Compose, Navigation | [LazyColumn/Row의 사실과 오해](https://www.notion.so/1315bfe2c24f8064837fc11fa838e586?p=3c6f5b41183a4962b1338c1e582b07ee&pm=s)⎮[Compose Navigation 적용하기](https://trite-ice-00b.notion.site/Compose-navigation-cca9b5763d77445a9288a03831b26352?pvs=74)⎮ [full compose 프로젝트에 navigation compose 적용기](https://915dbfl.github.io/compose/compose-navigation/) (둘중 하나만 사용하기)
| Image | Coil | [Why Coil? (with Glide)](https://www.notion.so/65af7f3ff4de425ba5ef818a123c13c3?pvs=4#6936b41d1c0e44d58641343c9c0343dd)
| CI/CD | Github Actions |[Ktlint 적용기](https://jay20033.tistory.com/31)
- 🔧 Architecture
<img width="450" alt="image" src="https://github.com/boostcampwm2023/and04-catchy-tape/assets/62279741/6ba75222-1cd6-417a-b8ec-2aef6bbf1deb">

<details>
<summary>✏️ 그 외 기록</summary>

- [프로젝트 생성](https://github.com/boostcampwm2023/and04-catchy-tape/wiki/Android#%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%83%9D%EC%84%B1%EC%8B%9C-%EA%B3%A0%EB%A0%A4%ED%95%9C-%EB%82%B4%EC%9A%A9)

</details>
<br>





