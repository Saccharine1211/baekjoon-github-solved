# Baekjoon Solutions

[Baekjoon Online Judge](https://www.acmicpc.net/)에서 해결한 문제와 제출 코드를 보관하는 개인 알고리즘 풀이 저장소입니다. 코드는 [BaekjoonHub](https://github.com/BaekjoonHub/BaekjoonHub)를 통해 자동 업로드됩니다.

## 저장소 구조

```text
백준/
├── Bronze/
│   └── <문제 번호>. <문제 제목>/
│       ├── README.md
│       └── <문제 제목>.cc
└── Silver/
    └── <문제 번호>. <문제 제목>/
        ├── README.md
        └── <문제 제목>.cc
```

- 난이도별 디렉터리로 문제를 분류합니다.
- 각 문제는 문제 번호와 제목으로 된 디렉터리를 가집니다.
- 풀이 코드는 현재 모두 C++이며 `.cc` 확장자를 사용합니다.
- 문제별 README에는 BaekjoonHub가 문제 링크, 분류, 설명, 제출 성능 등을 기록합니다.

## 업데이트 흐름

1. Baekjoon에서 문제를 풉니다.
2. 풀이를 제출해 정답을 받습니다.
3. BaekjoonHub가 정답 제출을 감지합니다.
4. 코드와 문제 메타데이터가 이 저장소에 업로드됩니다.

## 이 저장소를 읽는 방법

문제 번호나 제목으로 디렉터리를 찾고, 해당 디렉터리의 `.cc` 파일에서 풀이를 확인하세요. 문제 설명과 제출 시간·메모리는 문제별 `README.md`에서 확인할 수 있습니다.

## 주의 사항

- 일반 애플리케이션 프로젝트가 아니므로 공통 실행 명령이나 단일 테스트 명령은 제공하지 않습니다.
- BaekjoonHub가 생성한 디렉터리와 파일 이름은 임의로 변경하지 않는 편이 좋습니다.
- 문제별 README를 직접 수정하면 이후 자동 동기화에서 덮어써질 수 있습니다.
- 관련 없는 애플리케이션 코드나 설정을 추가하지 마세요.

## BaekjoonHub

BaekjoonHub는 정답 제출 코드와 문제 정보를 GitHub로 업로드하는 브라우저 확장 프로그램입니다. 자세한 설정과 문제 해결은 [BaekjoonHub 저장소](https://github.com/BaekjoonHub/BaekjoonHub)를 참고하세요.

현재 저장소의 풀이 코드는 C++로 작성되어 있습니다.
