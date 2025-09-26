# Azure Arc 활용 가이드
본 페이지는 Azure Arc를 이용해서 Windows & Linux 서버 그리고 Azure Local 관련한 내용을 담고 있습니다.

### 1. 로컬 정책 과 프로그램 설치
Azure Arc에 연결된 서버에서 Azure Policy 또는 Machine Configuration 기능을 이용해서, "로컬 정책, 레지스트리 값 적용, 프로그램 설치/제거"를 이용할 수 있습니다. 이런 기능을 구현하기 위해서는 , DSC(Desired State Configuration)이용해서 패키지를 생성해서 구현할 수 있습니다.
- “Machine Configuration + DSC”으로 적용하는 방법 – 적용 범위는 개별 서버단위로 적용
- “Azure Policy + DSC”으로 적용하는 방법 – 적용 범위는 구독/리소스 그룹 단위로 적용

