### github 사용 연습
---
SourceTree : git 관리 툴

Working Directory : 작업하는 파일이 있는 디렉토리

Staging Area : Git에 등록할 (커밋) 파일들이 올라가는 영역

Local Repository : 로컬 Git 프로젝트의 메타데이터와 데이터 정보가 저장되는 영역

Remote Repository : Github 등의 서비스를 통한 온라인 상의 저장소

---

Clone : Remote Repository를 복제해 내 PC에 Local Repository로 저장
	-> 이후 로컬에서 작업 가능
	
---

Add : Working Directory -> Staging Area (Commit 준비 단계)

Commit : Staging Area -> Local Repository (Push 준비 단계)

Push : Local Repository -> Remote Repository (원격 저장소 [Github]에 정보를 전송?하는 단계)

Fetch : Remote Repository -> Local Repository

Merge : Local Repository -> Working Directory

Pull : Fetch + Merge && Branch들을 합치는 작업

---

Branch : 독립적으로 어떤 작업을 따로 진행하기 위한 "가지"

Head : 현재 작업하고 있는 로컬 프랜치

Checkout : 사용할 다른 브랜치를 지정
