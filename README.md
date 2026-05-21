# kotlin-learning-week1

Kotlin 학습 1주차 - 기본 문법과 예제를 정리하는 저장소입니다.

## 📚 학습 목표

- Kotlin의 기본 문법 익히기
- - 변수, 자료형, 제어문, 함수, 컬렉션 이해
  - - 매일 작은 예제 코드로 손에 익히기
   
    - ## 🗓️ 주차별 커리큘럼
   
    - | Day | 주제 | 폴더 |
    - |-----|------|------|
    - | Day 1 | Hello World & 프로젝트 세팅 | `src/day1_hello_world` |
    - | Day 2 | 변수와 자료형 (val, var, 기본 타입) | `src/day2_variables_and_types` |
    - | Day 3 | 제어 흐름 (if, when, for, while) | `src/day3_control_flow` |
    - | Day 4 | 함수 (기본/확장/람다) | `src/day4_functions` |
    - | Day 5 | 컬렉션 (List, Set, Map) | `src/day5_collections` |
    - | Day 6 | 종합 연습 문제 | `src/day6_practice` |
    - | Day 7 | 1주차 회고 | `notes/week1_summary.md` |
   
    - ## 🛠️ 개발 환경
   
    - - Kotlin 1.9+
      - - JDK 17+
        - - IntelliJ IDEA Community Edition (권장) 또는 VS Code + Kotlin Extension
         
          - ## 🚀 실행 방법
         
          - ```bash
            # 저장소 클론
            git clone https://github.com/lsk30323/kotlin-learning-week1.git
            cd kotlin-learning-week1

            # Kotlin 파일 컴파일 & 실행 (예시)
            kotlinc src/day1_hello_world/Hello.kt -include-runtime -d Hello.jar
            java -jar Hello.jar
            ```

            ## 📁 폴더 구조

            ```
            kotlin-learning-week1/
            ├── README.md
            ├── .gitignore
            ├── src/
            │   ├── day1_hello_world/
            │   ├── day2_variables_and_types/
            │   ├── day3_control_flow/
            │   ├── day4_functions/
            │   ├── day5_collections/
            │   └── day6_practice/
            └── notes/
                └── week1_summary.md
            ```

            ## 📝 학습 노트

            매일 배운 내용을 `notes/` 폴더에 마크다운으로 정리합니다.

            ## 📌 참고 자료

            - [Kotlin 공식 문서](https://kotlinlang.org/docs/home.html)
            - - [Kotlin Koans](https://play.kotlinlang.org/koans/overview)
             
              - ## 📄 라이선스
             
              - 학습용 저장소입니다.
              
