<span style="color:brown; font-size:1.2em;background-color:lightyellow">Git Bash</span>에서 사용하는 `명령어` 모음
=================================
<b><i>Git</i></b>을 처음 접하는 사람들에게
---------------------------------
> <b><i>Git</i></b>은 리눅스 개발자가 프로젝트를 효율적으로 관리하기 위한 저장소 분산 관리 도구이다. <b>GitHub</b> 뿐 아니라 GitLab, BitBucket 등 원격저장소를 지원하는 여러 플랫폼과 연동하여 사용할 수 있다.  
> <b><i>Git</i></b>은 처음부터 리눅스 개발자의 편의성을 위해 만들었으므로, <b>Git Bash</b>는 Linux의 CLI 환경과 비슷하다고 한다. 그래서 명령 프롬프트처럼 <s>한 줄씩 일일이</s> 명령어로 처리하도록 되어 있다.   
> <b><i>Git</i></b>의 가장 기본적인 기능 중 하나인 **Commit**은 파일의 버전을 저장하고 관리할 수 있게 해준다.   

> [!NOTE]   
> <b>Commit 명령어</b>로 생성된 '커밋 파일'은 <u>한 번 생성되면 영원히 지워지지 않는다</u>는 것을 항상 명심하자.    
---
## Git 설치 이후 처음 환경설정
### git config 명령어
1. git config --global user.name "사용자이름"
    + 명령어를 입력하고 큰따옴표("")안에 원하는 닉네임을 입력한다.
2. git config --global user.email "이메일이름"
    + 명령어를 입력하고 큰따옴표("") 안에 원격 저장소(깃허브)의 계정으로 사용할 이메일 주소를 입력한다.
3. git config --list
    + 상위에 입력한 이름과 주소 등의 git에 등록되어 있는 정보 목록이다. <u>커밋을 등록할 때마다 </u>
3. git config --global core.editor "~\AppData\Local\Programs\Microsoft VS Code\bin\code"