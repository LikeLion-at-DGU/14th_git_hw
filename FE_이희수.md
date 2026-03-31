## 깃, 깃허브
깃은 개발 코드 관리/기록, 깃허브는 깃을 기록하는 플랫폼
1. 폴더 생성 후 code로 열기 > 터미널 > git bash
2. git init으로 폴더-깃허브 연동
3. git remote add origin 개인 레포
4. git remote add upstream 중앙레포
5. git remote -v 연결된 저장소 확인
6. git branch -M main으로 브랜치 이름 main으로 바꾸기
7. git branch 브랜치 이름: 브랜치 이름 만들기
8. git switch 브랜치 이름: 브랜치 이동
9. git pull upstream main 중앙레포로 최신 반영
10. git add . / commit -m 으로 수정사항 반영
11. git push origin 브랜치명 으로 깃허브에 반영

## 장고
장고는 소프트웨어 개발의 효율성을 높임

1. 깃과 동일하게 터미널 열어서 git bash 선택
2. 장고가 다른 파일에 영향X, 내 컴퓨터 파일 중 쓸데없는 파일을 venv로 올리지 않기 위해 python -m venv venv 후 source venv/Scripts/activate
3. gitignore 생성해서 충돌 방지(사이트 내에서 macOS, Windows, VSCode, venv, Django 추가)
4. settings.py 설정 시 필요한 요소 검색 단축어: ctrl+F
