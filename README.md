# JLDHistory
시뮬레이션 과정을 JLD 포맷으로 기록합니다.

## 기능 목표

### A. 시뮬레이션 히스토리 Save 기능
1. 시뮬레이션 history 파일을 serialization하여 저장
- 개별 파일 용량은 default value를 사용 (최적 값이 따로 있나?)
- 추후 7-zip으로 묶거나 압축하는 기능도 고려...

2. medtadata에서 각 history 파일의 정보를 관리
- 파일별 시작점과 끝점 (내 시뮬레이션에서는 TimePeriod인데...)
- 각 파일의 기본 정보를 사용자 필요에 따라 저장

### B. 시뮬레이션 히스토리 Load 기능
1. 시계열 분석
 - 분석에 적절한 단위로 잘라서....
 - 잘... 불러와서 잘... 비교해서 요약하도록...

### C. 예상 어려움?
~~Sim별 로그 파일을 따로 저장하는가? (한 파일에 여러 Sim이 들어 있으면 시계열 분석 힘들 텐데)~~
naming: tag냐... entry냐...
