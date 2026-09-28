# fhr-signal-viewer
fhr-signal-viewer

## FHR Signal Viewer

브라우저에서 바로 여는 단일 HTML 기반의 FHR(Fetal Heart Rate)·UC(Uterine Contraction) 시계열 열람 도구입니다.

## 사용 방법

1. Chrome 또는 Edge에서 `FHR_Signal_Viewer.html`을 엽니다.
2. 압축을 푼 FHR 데이터의 최상위 폴더를 선택합니다.
3. 왼쪽 패널에서 레코드 ID, 병원, 데이터셋, Label JSON, 길이로 케이스를 좁힙니다.
4. 케이스를 선택한 뒤 이전/다음 케이스로 순차 검토합니다.

## 주요 기능

- IHU/NIA, KMU, SNU 데이터를 병원 및 Raw/Processed 버전별로 분리해 조회
- FHR·UC 차트와 Label 구간을 함께 표시
- 프레젠테이션에 바로 사용할 수 있는 흰색 차트 배경
- 레코드 검색, 목록 스크롤, 길이 범위 필터, 이전/다음 케이스 이동
- 서버 없이 실행하며, 선택한 데이터는 브라우저 안에서만 읽고 수정하거나 외부로 전송하지 않음

## 공개 저장소 원칙

이 저장소에는 뷰어 소스와 문서만 포함합니다. 환자 데이터, 레이블 파일, 압축파일, 로컬 테스트 데이터 및 검사 로그는 절대 커밋하지 않습니다. 실제 입력은 ZIP이 아니라 압축을 푼 데이터의 상위 폴더입니다.
