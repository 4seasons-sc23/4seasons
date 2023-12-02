# InStream.

### 프로젝트 개요
'Instream. 실시간 스트리밍 SaaS 플랫폼'(이하 'InStream')은 실시간 라이브 스트리밍 및 대규모 라이브 채팅 서비스를 제공하는 SaaS 플랫폼입니다.
<br/>
<br/>
<img width="30%" src="https://github.com/4seasons-sc23/4seasons/assets/46314169/144dec6e-2b85-4dc2-91b6-eb27696b80fe">
<br/>
<br/>
'InStream'은 크게 다음과 같은 세 가지 주요 기능을 통해 사용 기업에게 편의를 제공합니다.  

**1. 멀티테넌시**
  - 사용자간의 완벽한 격리 기능을 제공합니다.
  - 콘솔을 통해 사용자의 이용내역 및 빌링내역을 상세히 확할 수 있습니다.
  - 기존 기업의 유저 정보와 통합할 수 있는 API를 제공합니다.
  - 고객 문의 및 관리자 페이지를 제공합니다.
  
**2. 라이브 스트리밍 파이프라인**
  - rtmp를 이용한 영상 스트림을 처리합니다.
  - nginx, ffmpeg, dash shell을 이용하여 영상을 hls형식으로 업로드합니다.
  - minio 스토리지를 통해 영상을 저장하고 1차 배포합니다. webhook을 통해 빌링 매트릭 정보를 확인합니다.

**3. 대규모 채팅 처리 파이프라인**
  - pubsub을 이용한 스케일링 가능한 채팅 서버
  - 대규모 채팅 업데이트를 위해 sse 기반의 sync 서버 제공, 1초에 데이터 10번 이내 제공으로 UX 성능 향상.
  - 채팅 요청 횟수에 따른 과금 정책.


<br/>


이 프로젝트는 아주대학교 SW캡스톤디자인 과목의 일환으로, 4인으로 구성된 4season 팀이 2023년 9월부터 12월까지 진행하였습니다.

아래는 아주대학교 소프트콘 링크로 보다 자세하게 프로젝트를 확인할 수 있습니다.
- softcon: https://softcon.ajou.ac.kr/works/works.asp?uid=1105

이 레포는 전체 프로젝트 레포로, 프론트엔드 및 백엔드 레포를 열람하고 싶으시다면 아래 링크를 확인해주세요.

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
|장성호|백엔드 개발|qq9725@ajou.ac.kr|https://https://github.com/Long9725|
|최민석|인프라, DevOps|alstjr1642@ajou.ac.kr|https://github.com/sigee-min|

<br/>

### 서비스 세부 설명

<img width="90%" src="https://github.com/4seasons-sc23/4seasons/assets/46314169/7fa08c7d-6935-41ba-a071-38729846b443">

