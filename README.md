# Lunch Overflow

Lunch Overflow는 사용자의 기분과 선호도를 분석하여, 오늘 먹고 싶은 음식을 AI가 맞춤형으로 추천해주는 오프라인 기반 맛집 추천 서비스입니다. 간단한 입력만으로, 걸어서 15분 거리 이내의 최적의 음식점을 찾아드립니다. 어디에서 무엇을 먹을지 고민될 때, Lunch Overflow가 당신의 기분에 딱 맞는 맛집을 제안해 드립니다.

### Main Repository

이 메인 레포지토리는 Lunch Overflow 프로젝트의 중심 허브로서, 각기 독립적으로 관리되는 프론트엔드, 백엔드, 그리고 AI 시스템을 통합적으로 관리하고 협업을 촉진하기 위해 설계되었습니다. Git Submodule을 활용하여 web, server, ai 세 개의 주요 구성 요소를 하나의 레포지토리에서 일관되게 관리할 수 있도록 하며, Docker Compose를 통해 전체 시스템을 쉽게 빌드하고 배포할 수 있는 환경을 제공합니다.

이 레포지토리는 개발자들이 각 구성 요소를 효율적으로 협력하여 개발할 수 있도록 지원하며, Lunch Overflow 서비스가 사용자에게 최상의 맛집 추천 경험을 제공할 수 있도록 하는 데 중요한 역할을 합니다.

#### Branching

본 프로젝트는 git-flow 를 따릅니다. 따라서 작업을 위한 브랜치는 `feature/KLO-xxx-branch-name` 과 같이 `feature/` 로 시작하도록 하며, Jira 이슈와의 연동을 위해 Jira의 이슈 번호로 (`KLO-xxx`) 브랜치 이름을 시작합니다.

#### Commit Messages

커밋 메시지는 아래와 같은 포맷으로 작성합니다.

```
[KLO-xxx] feat: commit message goes here
```

- `KLO-xxx`: Jira의 이슈 번호를 적습니다. ~~자동으로 Jira 이슈에 연동됩니다.~~ (autolinks reference 기능은 유료 플랜에서만 지원)
- `commit message goes here`: 커밋 메시지의 내용이며, 첫 글자가 영문일 경우 소문자로 작성합니다.
