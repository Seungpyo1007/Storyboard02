# TabBar Controller 및 핵심 뷰 구성
### 이 섹션에서는 앱의 주 탐색 구조를 담당하는 TabBar Controller의 구현 및 초기 화면 구성을 설명합니다.

## 🗺️ 탐색 구조 개요
### 앱의 최상위 탐색은 TabBar Controller를 중심으로 이루어지며, 사용자에게 다음의 세 가지 주요 화면으로의 접근을 제공합니다.

### 구현 방식: Swift 및 Storyboard를 사용하여 구현되었습니다.

### 메인 진입점: TabBar Controller가 앱의 초기 뷰 컨트롤러(Initial View Controller)로 설정되어 있습니다.

## 🔍️ 탭 구성 상세
### TabBar에는 총 세 개의 뷰 컨트롤러가 연결되어 있으며, 각 탭은 다음과 같은 역할을 수행합니다.

* 탭 이름 (ViewController)    역할 및 내용
* Home    앱의 시작 화면 또는 주요 콘텐츠를 표시합니다.
* Search    사용자에게 검색 기능을 제공하는 화면입니다.
* More    설정, 도움말, 계정 정보 등 기타 부가 기능을 모아둔 화면입니다.

## 🔗 Storyboard 연결
### TabBar Controller는 Storyboard에서 다음과 같이 뷰 컨트롤러들을 참조하고 있습니다.

* TabBar Controller → Home ViewController

* TabBar Controller → Search ViewController

* TabBar Controller → More ViewController
