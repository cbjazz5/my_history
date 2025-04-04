# 자기 소개

삼성전자 MX사업부에서만 10년 넘게 개발을 해왔습니다.<br>
주로 머신러닝을 이용한 AI기술을 서비스로 활용하기 위해 노력했으며, 적잖은 성과도 냈습니다.<br>
하루가 다르게 발전하는 AI 환경에서, 기술 하나하나에 집착하면, 오히려 도태될 수 있다고 생각했습니다.<br><br>
이제는, bottom-up으로 개발하는 것이 아니라,<br>
**고객이 뭘 필요로하는지 먼저 파악하고, 그에 맞는 기술을 발굴**하고 싶습니다.<br>
제가 가진 AI 기술 개발 지식과 상품화 경험이 AI 기획에 큰 도움이 되었으면 좋겠습니다.<br>

---------------------------------------------------------
<br>

# 핵심 역량

* UX 시나리오 및 UI가이드 이해 및 구현 가능 (Android 어플리케이션)
* 머신러닝 툴(tensorflow, pytorch)을 이용한 데이터 학습 및 예측
* Python, C/C++, Java 등 프로그래밍 언어 이해
* SW 구조 및 아키텍쳐 (클래스/시퀀스/패키지 다이어그램 등) 이해

---------------------------------------------------------
<br>

# 직무경력

| 회사명 | 삼성전자 |
| ------| --------|
| 부서명 | MX사업부 / Application개발팀 |

<br>

## 주요업무1. 필기인식 기술개발, 상용화 (2015 ~ 2018)

**1. 기술 개요**
* 스타일러스펜으로 스마트폰 화면에 문구를 적으면, **텍스트로 변환**해주는 기술 (삼성노트, 삼성키보드 등에 적용중)

**2. 담당 업무**
* 한국어/중국어/일본어 필체 데이터셋 수집, 머신러닝으로 학습된 모델 최적화
* 스마트폰 Framework 에 적용 및 호환성 설계
* 언어 별로 학습된 모델 DB를 다운로드로 지원하기 위한 설계

**3. 문제 해결**
* 스마트폰에 모든 언어의 모델 DB를 포함할 수 없는 상황 (메모리 사이즈 부족)
* 서버를 따로 운영할 수도 없는 상황에서, 갤럭시스토어를 사용하여 다운로드 가능하도록 적용
  - 갤럭시 스토어 : 앱설치 없이 백그라운드로 다운로드 될 수 있도록 담당자와 협의
  - 검증팀: 갤럭시 스토어에 모델DB를 등록하기 위한 절차 간소화 협의

<br>

## 주요업무2. 좌표예측을 이용한 SPen Latency 개선, 상용화 (2019~2021)

**1. 기술 개요**
* SPen과 화면에 표시되는 **획의 드로잉 격차를 AI를 통해 줄여**주는 기술 (삼성노트, 심성키보드 등에 적용중)

**2. 담당 업무**
* 다량의 다양한 드로잉 데이터셋 수집을 위한 설계 (데이터 전처리, 관리 체계 구축)
* GPU서버에서 학습한 결과를 평가하여 모델 최적화 튜닝

**3. 문제 해결**
* SPen으로 드로잉 시, 예측이 어긋나 획이 이상한 방향으로 튀는 현상 발생
* 하루 이상 걸리는 학습 시간으로 빠르게 원인 파악이 힘든 상황
* 학습 샘플을 경량화하여, 학습 시간 단축 -> 학습 과정 오류의 신속 원인 파악에 도움

<br>

## 주요업무3. OCR (광학 문자 인식) 기술개발, 상용화 (2021~2024)

**1. 기술 개요**
* 사진으로 촬영한 **이미지에서 텍스트 및 영역 추출** (갤러리, 브라우저, 카메라 등 적용중)

**2. 담당 업무**
* 이미지에서 손글씨 텍스트에 대한 인식 기술 개발 (해외연구소 협업)
* 스마트폰 Framework 에 적용 및 호환성 설계
* 학습된 모델 DB를 효과적으로 관리할 수 있는 로직 설계

**3. 문제 해결**
* 전체 언어에 대한 모델 DB를 메모리에 올리는 상황에서, 과부하 발생
* 해외연구소 담당자와 아이디어 교환 및 협업하여 인식 과정에서 필요한 DB만 메모리로 올리도록 변경
* 이와 관련된 아이디어로 특허 출원 및 등록
