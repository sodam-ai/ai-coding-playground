# knowledge-ai-guide

> **Developed by 소담 AI 스튜디오**

비개발자를 위한 AI 지식 시스템 가이드 에이전트입니다.
코딩을 전혀 모르는 사람도 RAG, 지식 그래프, AI 챗봇을 만들 수 있도록 도와줍니다.

## 설치 방법

`knowledge-ai-guide.md` 파일을 아래 경로에 복사하세요:

```
~/.claude/agents/knowledge-ai-guide.md
```

- Windows: `C:\Users\사용자이름\.claude\agents\`
- Mac/Linux: `~/.claude/agents/`

CLAUDE.md 설정 없이 파일만 복사하면 자동으로 작동합니다.

## 지원 기술

| 분류 | 기술 |
|------|------|
| RAG 프레임워크 | LangChain, LangGraph, LlamaIndex, GraphRAG |
| 그래프 DB | Neo4j, Memgraph, NetworkX, Gephi, ArangoDB, TigerGraph, JanusGraph |
| 벡터 DB | ChromaDB, Pinecone, FAISS, Weaviate, Qdrant, Milvus |
| 로컬 LLM | Ollama |
| 웹 UI | Streamlit |
| 쿼리 언어 | Cypher, SPARQL, Gremlin |
| 개념 | 온톨로지, 토폴로지, 임베딩, 청킹, 리랭킹, 하이브리드 검색 |
| 평가 | RAGAS |

## 에이전트 구성 (25+ 섹션)

| 섹션 | 내용 |
|------|------|
| 자동 라우팅 규칙 | CLAUDE.md 없이 자동 활성화를 위한 키워드 내장 |
| 역할 정의 | 비개발자 대상 친절한 가이드 역할 |
| 핵심 원칙 5가지 | 한국어 100%, 비유 우선, 복사-붙여넣기 원칙 등 |
| OS 자동 감지 | Windows/Mac/Linux 환경별 자동 설정 |
| 비유 사전 | 어려운 개념을 일상 비유로 설명하는 사전 |
| 학습 로드맵 | 입문 → 중급 → 고급 단계별 안내 |
| 6단계 워크플로우 | 환경 파악 → 목표 → 개념 → 설정 → 코드 → 확장 |
| 그래프 도구 종합 가이드 | Neo4j, NetworkX 등 8종 도구별 코드 예제 |
| LangChain vs LlamaIndex | 두 프레임워크 비교 + 코드 |
| Ollama 로컬 LLM | 무료 AI 로컬 실행 가이드 |
| Streamlit 웹 UI | RAG 챗봇을 웹으로 배포 |
| 파인튜닝 vs RAG | 어떤 방식을 선택할지 비교 |
| Excel/CSV → 그래프 | 엑셀 데이터를 관계도로 변환 |
| Notion/Obsidian → 지식그래프 | 노트앱 데이터를 그래프로 변환 |
| 통합 아키텍처 | RAG + 그래프 + 벡터 통합 설계 |
| 1등급 추가 기능 | 하이브리드 검색, 리랭킹, 스트리밍 등 |
| 에러 자동 진단 | 에러 발생 시 자동 수정 워크플로우 |
| 프로젝트 원클릭 생성기 | 프로젝트 유형별 자동 생성 |
| 코드 생성 규칙 | 현대 LangChain import 경로 준수 |
| 품질 체크리스트 | 응답 품질 자체 검증 |

## 사용 예시

Claude Code에서 다음과 같이 말하면 자동으로 이 에이전트가 활성화됩니다:

```
"RAG가 뭐야?"
"챗봇 만들어줘"
"Neo4j 설치하고 싶어"
"벡터 검색이 뭐야?"
"엑셀을 관계도로 만들어줘"
"내 데이터로 AI 만들고 싶어"
"코딩 몰라도 할 수 있어?"
```

## 특징

- 한국어 100% 응답
- 일상 비유로 개념 설명 (도서관, 택배, 레고 등)
- 복사-붙여넣기로 바로 실행 가능한 Python 코드
- 에러 발생 시 자동 진단 및 수정
- 비개발자/초보자 대상 설계

## 라이선스

소담 AI 스튜디오
