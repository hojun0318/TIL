# TIL
Today I Learn at SSAFY

![SSAFY](https://user-images.githubusercontent.com/104968672/179149515-a69da45f-a605-4eb8-8725-e98046bbbbbf.png)

# TIL (Today I Learned)

- 매일 내가 배운 것을 마크다운으로 정리해서 문서화하는 것
- 신입 개발자에게 요구되는 가장 큰 능력, 꾸준히 학습할 수 있나요?
- Github  관리의 가장 첫 걸음, 제일 중요한 장기 프로젝트

# 개발자로 성장하기

- 대체 어디서부터 시작해서 어디까지 해야할까?
- Python과 Java를 배우면 개발자가 되는걸까?

제일 중요한건 **꾸준한 학습**을 할 수 있는 사람인지를 보여줘야한다!

![git](https://user-images.githubusercontent.com/104968672/179149811-bf641e02-c106-4da9-89ba-4b71f1c18ab4.png)

Git: 분산 버전관리 프로그램
- 버전: 컴퓨터 소프트웨어의 특정 상태
- 관리: 어떤 일의 사무, 시설이나 물건의 유지, 개량
- 프로그램: 컴퓨터에 실행될 때 특정 작업을 수행하는 일련의 명령어들의 모음

'Git: 분산 버전관리 프로그램'
- 1. 코드의 히스토리(버전)을 관리하는 도구
- 2. 개발되어온 과정 파악 가능
- 3. 변경 사항 비교 분석

### 중앙 집중식 버전 관리 vs 분산 버전 관리(Git)

Github: Git기반의 저장소 서비스를 제공하는 서버

- 1.  GitLab
- 2. GitHub(MS)
- 3. Bitbucket

GitLab: 저장하는 서버 자체를 내 마음대로 구축할 수 있음

![CLI](https://user-images.githubusercontent.com/104968672/179149883-f7dff4a9-a9f7-4846-bf4e-942ba00f7657.png)

CLI : Command Line Interface <-> GUI: Graphic User Interface : (공통) 컴퓨터한테 명령내리기
- CLI : 그래픽을 통해 사용자와 컴퓨터가 상호 작용하는 방식
       컴퓨터 리소스 절약이 됨(경제적)

- GUI : 명령어를 통해 사용자와 컴퓨터가 상호 작용하는 방식

GUI는 CLI에 비해 사용하기 쉽지만 단계가 많고 컴퓨터의 성능을 더 많이 소모
수 많은 서버/개발 시스템이 CLI를 통한 조작 환경을 제공

- touch : 파일 생성하는 명령어
- mkdir : 새 폴더를 생성하는 명령어
- ls : 현재 작업 중인 디렉토리의 폴더/파일 목록을 보여주는 명령어
- cd :  현재 작업 중인 디렉토리를 변경하는 명령어
- start(Windows) open(Mac) :  폴더/파일을 여는 명령어
- rm : 파일을 삭제하는 명령어
- -r : 옵션을 주면 폴더 삭제 가능
- cd .. : 상위로 가기
- start . : 현재 위치 열기

(C:\Users\multicampus : Home Directory = ~ )

상위로 이동 후  폴더를 지우려면 r옵션 적용!

절대 경로 :

- 루트 디렉토리부터 목적 지점까지 거치는 모든 경로를 전부 작성한 것
- 윈도우 바탕 화면의 절대 경로 -C:/Users/ssafy/Desktop

상대 경로 :

- 현재 작업하고 있는 디렉토리를 기준으로 계산된 상대적 위치를 작성한 것
- 현재 작업하고 있는 디렉토리가  C:/Users일 때

       윈도우 바탕화면으로의 상대 경로는 ssafy/Desktop

- ./ : 현재 작업하고 있는 폴더
- ../ : 현재 작업하고 있는 폴더의 부모 폴더

![mark](https://user-images.githubusercontent.com/104968672/179149968-6c8f8bab-ccd7-4180-a7e3-64744dd799bd.jpg)

### 마크다운(Markdown)

텍스트 기반의 가벼운 마크업(markup) 언어
문서의 구조와 내용을 같이 쉽고 빠르고 적고자 탄생

- 마크업(Markup) : 태그(tag)를 이용하여 문서의 구조를 나타내는 것

![github](https://user-images.githubusercontent.com/104968672/179150044-10a2cf29-ac79-41a9-8159-f05fef6b337d.png)

Github 문서의 시작과 끝!

- [README.md](http://readme.md/) 파일을 통해 오픈 소스의 공식 문서 작성
- 개인 프로젝트의 소개 문서 작성
- 매일 학습한 내용 정리
- 마크다운을 이용한 블로그 운영

                                                                                            = 개발문서의 시작과 끝

개발 문서의 시작과 끝!

- 대부분의 웹 에디터에서 지원(각종 블로그 사이트 등)
- Jupyter Notebook, Notion 등

### Typora

- 실시간 마크다운 변환(미리보기) 제공
- 이미지 또는 표 삽입시 매우 편한 UI 제공
- VS Code등의 프로그램도 마크다운을 지원하지만 전용 프로그램을 사용하면 더 편하게 사용 가능

# 헤딩(Headig)

문서의 제목이나 소제목으로 사용해요

- #의 개수에 따라 제목의 수준을 구별(h1 ~ h6)
- 문서 구조의 기본
- 글자 크기를 키우기 위해서 사용하면 안돼요

# 리스트(List)

순서가 있는 리스트와 순서가 없는 리스트

- 목록을 표시하기 위해 사용
- 많이 사용하는 태그 중 하나

# 코드 블럭(Code Block)

일반 텍스트와 다르게 코드를 이쁘게 출력해요

- 개발자가 마크다운을 사랑하는 이유 중 하나
- 사용하는 프로그램에 따라 특정 언어를 명시하면 구문 강조(Syntax Highlighting) 지원

# 링크(link)

string은 보여지는 부분, url은 연결할 부분

- 다른 페이지로 이동하는 링크를 삽입
- 필요하다면 파일의 경로를 넣어 다운로드 가능한 링크로 만들 수 있어요

# 이미지(image)

링크와 비슷하지만 이미지를 삽입합니다

- 이미지의 너비와 높이는 조절할 수 없어요
- 조절이 필요하다면 HTML을 사용해야 합니다.

# 텍스트 강조(Text Emphasis)

순서대로 굵게, 기울임, 취소선을 이용해 텍스트를 강조합니다.

- *를 _(underbar)로 대체할 수 있어요
- 취소선은 프로그램에 따라 지원하지 않을 수 있습니다.

# 수평선 (Horizontal line)

가로로 긴 수평선을 작성합니다
대개 단락을 구분할 때 사용해요

- -(hypen)을 *나 _(underbar)로 대체할 수 있어요

# Git 기본기

## Repository

![99EB36495E381BF706](https://user-images.githubusercontent.com/104968672/179150124-0b6a7373-a4c7-4533-9933-3d57212ee477.png)

특정 디렉토리를 버전 관리하는 저장소

- git init 명령어로 로컬 저장소를 생성
- .git 디렉토리에 버전 관리에 필요한 모든 것이 들어있음

[README.md](http://README.md) 생성하기

- 새 폴더를 만들고 [README.md](http://README.md) 파일을 생성해주세요.
- 이 파일을 버전 관리하며 Git을 사용해 봅시다

 → 특정 버전으로 남긴다 = “커밋(Commit)한다” [아래 3가지 영역을 바탕으로 동작!]

1. Working Directory : 내가 작업하고 있는 실제 디렉토리
2. Staging Area : 커밋(Commit)으로 남기고 싶은, 특정 버전으로 관리하고 싶은 파일이 있는 곳
3. Repository : 커밋(Commit)들이 저장되는 곳 = Git이 Commit을 저장하는 곳

Working Directory → git add → Staging Area → git commit → Repository

* git add (변경사항)

* git commit (변경사항 기록)

* git log

* git status : 현재 git으로 관리되고 있는 파일들의 상태를 알 수 있어요

* git diff  (A)    (B)  :  A를 기준으로 B가 어떻게 변경 되었는 가를 알려준다

* git push (A)   (B)  :  A는 어디로 Push할 건지 (origin), B는 (Master branch)

## Staging Area 왜?

![1_diRLm1S5hkVoh5qeArND0Q](https://user-images.githubusercontent.com/104968672/179150203-9b30ea35-6df7-43d5-b8f9-4ce0d0fee9a4.png)

특정 변경된 사항들만 뽑아서 남기고 싶은, commit으로 찍고 싶은애들만 올리는
* git remote add origin {remote_repo}

* git push -u origin master

* git clone {remote_repo} : remote repo를 local로 복사합니다

* git push origin master : local repo의 최신 커밋을 remote repo로 push 합니다