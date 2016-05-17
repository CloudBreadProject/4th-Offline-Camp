# Welcome to CloudBread Camp 4th

### CloudBread Camp 는 CloudBread 프로젝트 소개와 더불어, 참여자분들과 함께 CloudBread 를 사용해보는 시간입니다.
이 문서에서는 CloudBread 설치 작업 전 미리 수행해야 할 작업들을 소개합니다.

### CloudBread 캠프 참여 전 필수 준비 과정
**1. Unity3d 설치**
- Unity3d 5.0 이상 설치 : [Unity 다운로드 페이지](http://unity3d.com/kr/get-unity/download?ref=personal)에서 받으실 수 있습니다.

**2. PostMan 설치**
- CloudBread 캠프에서는 CloudBread 와의 API 호출 테스트 툴로써 PostMan 을 사용합니다.
- http://www.getpostman.com 에서 Mac 용 앱 또는 Chrome 용 앱을 다운받아 설치해주세요.

**3. Github 회원가입**
- Github 가입 : https://github.com/ 에서 가입 하세요. 자신의 Repository로 Fork 할때 필요합니다.
- Github Desktop 설치 : https://desktop.github.com/ 에서 자신의 OS에 맞는 Github 데스크톱을 설치합니다.

**4. Facebook 가입하기**
- CloudBread Project 공식 페이스북 그룹에 가입해주세요. https://www.facebook.com/groups/cloudBreadProject/

### CloudBread 배포
CloudBread 를 Azure 에 배포를 하시고 캠프에 참여하시면, 캠프에서 개인 서버를 사용한 게임 개발이 가능합니다.
(캠프에서는 시간 관계상 개인 CloudBread 배포가 어렵기 때문에, 캠프에서는 데모용 CloudBread 서버를 제공합니다.)
- Microsoft ID 가입 후 체크 : 가입 여부 확인은, https://mail.live.com 에 접속해 메일박스가 보이면 정상 계정입니다.
- Microsoft Azure 등록 : CloudBread는 Microsoft Azure 클라우드 서비스의 PaaS 플랫폼을 이용해 개발되었습니다. CloudBread를 배포하기 위해서 먼저, Azure 등록을 수행해야 하며 무료 등록을 다음 링크에서 수행 가능합니다.(Chrome 브라우저에서 불가하며, IE도 버전에 따라 설치가 안될 수 있다고 합니다.) https://azure.microsoft.com/ko-kr/free/
 - 무료로 Azure를 사용하기 위해 추가적으로, MSDN 구독이 있거나, Startup - BizSpark 가입자일 경우에도 무료로 사용 가능합니다.
 - 2015년 4월 공개된 [Visual Studio Dev Essentials](https://myprodscussu1.app.vssubscriptions.visualstudio.com)에서 매월 충전되는 25불 무료 크레딧도 가능합니다.
 - (게임 서버 개발자 선택 설치)SQL Server 2014 클라이언트 : Azure의 SQL Database 관리를 위한 툴입니다. [SQL 2014 다운로드 링크](https://www.microsoft.com/ko-KR/download/details.aspx?id=42299)에서 32비트 또는 64비트 버전에 맞는 관리도구를 다운로드 합니다. “MgmtStudio 32BIT\SQLManagementStudio_x86KOR.exe” 또는, “MgmtStudio 64BIT\SQLManagementStudiox64_KOR.exe”를 선택해 설치합니다.
  -  **게임 서버 개발자라면**, 전체 기능을 자신의 개발 환경에서 사용하기 위해 관리 툴만 설치가 아니라 ExpressAndTools 32BIT\SQLEXPRWT_**x86**_KOR.exe 또는 ExpressAndTools 64BIT\SQLEXPRWT_**x64**_KOR.exe을 설치합니다.
 - node.js 설치 https://nodejs.org/en/ 사이트에서 v5.7 이상의 Stable 버전을 설치합니다.(2016년 3월 기준 5.7.1 버전)
 - (게임 서버 개발자 선택 설치)Visual Studio 커뮤니티 2015 : [Visual Studio 2015 커뮤니티 다운로드](https://www.visualstudio.com/ko-kr/products/visual-studio-community-vs.aspx)에서 받으실 수 있으며 페이지 하단 용도에 맞게 설치하세요.(설치에 30분 가량 소요됩니다.)
 - (게임 서버 개발자 선택 설치)Visual Studio 2015 업데이트 : [Visual Studio 업데이트 페이지](https://www.microsoft.com/en-US/download/details.aspx?id=49989)에서 버전에 맞는 설치가 가능합니다.
 - (게임 서버 개발자 선택 설치)Azure SDK 2.8 for Visual Studio 2015 설치 : [Azure SDK 다운로드 페이지](https://azure.microsoft.com/en-us/downloads/)에서 VS 2015 버전용 다운로드를 설치 하시면 됩니다.
