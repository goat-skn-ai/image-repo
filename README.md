# SKN AI 교안 이미지 자산

이 저장소는 SKN AI 공개 교안용 Jupyter Notebook에서 사용하는 이미지와 도식을 관리한다. 일반 목적의 이미지 업로드나 백업 저장소로 사용하지 않는다.

## 폴더 규칙

교안의 과정·단원 구조를 따라 다음 형식으로 저장한다.

```text
<과목>/<대단원>/<소단원>/<파일명>
```

예시:

```text
08_llm/08_langgraph/01_langgraph_basics/02_official_single_node_graph.png
```

## jsDelivr 사용 규칙

배포한 노트북은 재현성을 위해 업로드 커밋 SHA를 고정한다.

```text
https://cdn.jsdelivr.net/gh/goat-skn-ai/image-repo@<commit-sha>/<저장소 내부 경로>
```

제작 중 `@main` URL은 사용할 수 있지만 branch 캐시가 적용된다. 배포된 파일은 같은 이름으로 덮어쓰기보다 새 파일명과 새 커밋을 사용한다.

## 출처와 이용 조건

외부 공식 문서에서 가져온 이미지와 공식 문서를 바탕으로 재구성한 도식은 [ATTRIBUTIONS.md](ATTRIBUTIONS.md)에 출처를 기록한다. 각 자산의 이용 조건은 원출처의 라이선스와 정책을 따른다.
