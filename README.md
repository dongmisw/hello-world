# hello-world

markdown language - 글 서식 편집용 언어




# [그림 1] Human-AI 상호작용 순환 모델 (Interaction Loop)

이 다이어그램은 **Human(학생)**과 **AI(도구)**가 단절된 것이 아니라, 지속적인 피드백을 주고받으며 결과물의 품질을 높여가는 **순환적 프로세스(Loop)**임을 시각적으로 보여줍니다.

## 1. 다이어그램 (Mermaid)

```mermaid
graph LR
    %% 스타일 정의 (파란색: Human, 주황색: AI, 초록색: 최종결과)
    classDef human fill:#e3f2fd,stroke:#1565c0,stroke-width:2px,color:#000,rx:10,ry:10;
    classDef ai fill:#fff3e0,stroke:#ef6c00,stroke-width:2px,color:#000,rx:10,ry:10;
    classDef goal fill:#e8f5e9,stroke:#2e7d32,stroke-width:4px,color:#000,rx:5,ry:5;

    %% 영역 설정
    subgraph Human_Zone [Human Zone (주도성/검증/심화)]
        direction TB
        S1("<b>Step 1. 기획 및 질문</b><br/>(문제 정의, 질문 설계)"):::human
        S3("<b>Step 3. 비판적 검증</b><br/>(팩트체크, 논리 점검)"):::human
        S5("<b>Step 5. 심화 및 결정</b><br/>(인간의 통찰 추가)"):::human
    end

    subgraph AI_Zone [AI Zone (생성/분석/보조)]
        direction TB
        S2("<b>Step 2. 생성 및 제안</b><br/>(초안 작성, 데이터 분석)"):::ai
        S4("<b>Step 4. 재구성 및 보완</b><br/>(피드백 반영, 수정 제안)"):::ai
    end

    %% 흐름 연결 (지그재그 구조)
    S1 -->|Prompt (명령/질문)| S2
    S2 -->|Output (초안/답변)| S3
    S3 -->|Feedback (재질문/지적)| S4
    S4 -->|Refined Output (수정본)| S5
    S5 -->|Final Touch| G((<b>최종 산출물</b>)):::goal

    %% 배경 스타일 (선택사항)
    style Human_Zone fill:#f5faff,stroke:#bbdefb,stroke-width:2px,stroke-dasharray: 5 5
    style AI_Zone fill:#fffaf5,stroke:#ffe0b2,stroke-width:2px,stroke-dasharray: 5 5
```

## 2. 도식화 가이드 (보고서/PPT 작성용)


# 반려동물
## 고양이와 강아지 보여주는 화면입니다.

### 고양이
<img src="cat.jpg"/>


## 🛠 기술 스택

| 구분 | 기술 |
|------|------|
| **Frontend** | HTML, CSS, JavaScript (jQuery, Ajax), React |
| **Backend** | Python, Django REST Framework |
| **Database** | SQLite (개발용) |
| **Deploy** | GitHub Pages (프론트), Render (백엔드) |
| **Tools** | VSCode, Git, Postman |

---

### 반려동물 시스템 발표자료
[네이버검색](https://www.naver.com)<br>
[동물병원시스템프로젝트](https://github.com/dongmisw/hello-world/)<br>

[발표자료](/project.pptx)<br>

### 시스템 시연영상

<iframe width="535" height="296" src="https://www.youtube.com/embed/m--MXud9XdI" title="[최신가요 실시간 인기차트] 2025년 10월 19일 3주차, 멜론차트 X, 차트둥이 공식채널, 노래모음 KPOP 플레이리스트 종합차트" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


[글씨1](주소)<br>
[글씨2](파일)<br>

> 들여쓰기
> > 한번더 들여쓰기
> > > 두번 들여쓰기

1. 첫번째 메뉴
2. 두번째 메뉴
3. 세번째 메뉴 
  
