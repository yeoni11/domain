## 목표 (Object)
개인 도메인 서버를 활용하여 인터넷에 웹사이트를 배포

## 로컬 PC 작업 (노트북)
index.html 파일을 프로젝트 루트 디렉토리에 추가한 후
PowerShell 또는 명령 프롬프트(CMD)를 열고 아래 명령어를 순서대로 입력

git init                                  # 저장소 초기화

git add .                                 # 모든 변경 파일 스테이징 영역에 추가

git commit -m "first commit"              # 첫 번째 커밋 생성

git branch -M main                        # 기본 브랜치 이름을 main으로 변경

git remote add origin "repository 주소"   # 원격 저장소(GitHub 등) 연결

git push -u origin main                   # 원격 저장소의 main 브랜치로 푸시 (기본 스트림 설정)


## Vercel 배포 및 도메인 설정
Vercel 대시보드에 접속

[Add Existing]을 클릭 -> 위에서 푸시한 깃허브 저장소 가져오기

프로젝트 설정 또는 대시보드에서 [Add Domain]을 선택하해 구매한 개인 도메인을 연결

## 출처
플래티콘 출처 표기 (작은 글씨)
<sub>Icons made by [Flaticon](https://www.flaticon.com/kr/authors/creartive)</sub>
