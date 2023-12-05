<div align=center>
	<img src="https://capsule-render.vercel.app/api?type=rect&color=auto&height=130&section=header&text=Instream&fontSize=80&fontAlignY=53" />
</div>
<div align=center>
	<h3>📚 Tech Stack 📚</h3>
	<p>✨ Platforms & Languages ✨</p>
</div>
<div align="center">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
	<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" />
	<img src="https://img.shields.io/badge/Java-47A248?style=flat&logo=Conda-Forge&logoColor=white" />
    <br/>
    <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white" />
	<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=Spring&logoColor=white" />
    <img src="https://img.shields.io/badge/NGINX-009639?style=flat&logo=NGINX&logoColor=white" />
    <img src="https://img.shields.io/badge/Shell-5391FE?style=flat&logo=powershell&logoColor=white" />
    <br/>    
    <img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white" />
    <img src="https://img.shields.io/badge/redis-DC382D?style=flat&logo=redis&logoColor=white" />
    <img src="https://img.shields.io/badge/minio-C72E49?style=flat&logo=minio&logoColor=white" />
<br/>
	<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white" />
 	<img src="https://img.shields.io/badge/openstack-ED1944?style=flat&logo=openstack&logoColor=white" />
    <img src="https://img.shields.io/badge/Argo-EF7B4D?style=flat&logo=argo&logoColor=white" />

</div>
<br>
<div align=center>
	<p>🛠 Tools 🛠</p>
</div>
<div align=center>
	<img src="https://img.shields.io/badge/IntelliJ%20IDEA-2C2255?style=flat&logo=intellijidea&logoColor=white" />
	<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white" />
<br/>
	<img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=flat&logo=VisualStudioCode&logoColor=white" />
	<img src="https://img.shields.io/badge/OBS%20Studio-302E31?style=flat&logo=obsstudio&logoColor=white" />



</div>
<br>

## 프로젝트 개요
실시간 스트리밍 SaaS 플랫폼(이하 'INSTREAM')
<br/>
실시간 라이브 스트리밍 및 대규모 라이브 채팅 서비스를 제공하는 SaaS 플랫폼입니다.

<br/>
<br/>
<div align="center">
  <img width="30%" src="https://github.com/4seasons-sc23/4seasons/assets/46314169/144dec6e-2b85-4dc2-91b6-eb27696b80fe">
</div>
<br/>

## 프로젝트 주요 기능
'InStream'은 크게 다음과 같은 세 가지 주요 기능을 통해 사용 기업에게 편의를 제공합니다.  

**1. 멀티테넌시**
  - 사용자간의 완벽한 격리 기능을 제공
  - 콘솔을 통해 사용자의 이용내역 및 빌링내역을 제공
  - 기존 기업의 유저 정보와 통합할 수 있는 API를 제공
  - 고객 문의 및 관리자 페이지를 제공
  
**2. 라이브 스트리밍 파이프라인**
  - rtmp를 이용한 영상 스트림을 처리
  - nginx, ffmpeg, dash shell을 이용하여 영상을 hls형식으로 업로드
  - minio 스토리지를 통해 영상을 저장하고 1차 배포합니다. webhook을 통해 빌링 매트릭 정보 확인

**3. 대규모 채팅 처리 파이프라인**
  - pubsub을 이용한 스케일링 가능한 채팅 서버
  - 대규모 채팅 업데이트를 위해 sse 기반의 sync 서버 제공, 1초에 데이터 10번 이내 제공으로 UX 성능 향상.
  - 채팅 요청 횟수에 따른 과금 정책.


<br/>

## 프로젝트 상세정보
아주대학교 SW캡스톤디자인 과목의 일환으로, 4인으로 구성된 4season 팀이 2023년 9월부터 12월까지 진행하였습니다.

아래의 링크에서 보다 자세하게 프로젝트를 확인할 수 있습니다.
- softcon: https://softcon.ajou.ac.kr/works/works.asp?uid=1105 (아주대학교 소프트콘)
<br/>

<img width="90%" src="https://github.com/4seasons-sc23/4seasons/assets/46314169/7fa08c7d-6935-41ba-a071-38729846b443">
<br/>
<br/>

## 프로젝트 레포지토리
현재 레포는 프로젝트의 전체 개요를 설명하는 레포입니다.
<br/>
프론트엔드 및 백엔드 레포를 열람하고 싶으시다면 아래 링크를 확인해주세요.
<br/>

- web-client: https://github.com/4seasons-sc23/web-tenant
- tenant-server: https://github.com/4seasons-sc23/server-tenant
- rtmp-server: https://github.com/4seasons-sc23/nginx-rtmp
- chat-server: https://github.com/4seasons-sc23/server-chat
- argocd-manifest: private
- devops: private (openstack, k8s, tekton, harbor 설정 등)

<br/>

### 팀 소개

|이름|역할|email|github|
|---|---|---|---|
|강동하|프론트엔드 개발|kmh0913@ajou.ac.kr|https://github.com/KNamuuu|
|유진|백엔드 개발|dbwls30131@ajou.ac.kr|https://github.com/YooJin919|
|장성호|백엔드 개발|qq9725@ajou.ac.kr|https://github.com/Long9725|
|최민석|인프라, DevOps|alstjr1642@ajou.ac.kr|https://github.com/sigee-min|

<br/>

