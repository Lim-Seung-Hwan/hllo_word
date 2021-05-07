## 필수로 알아두어야 할 명령어
 * git add [파일명]
 	 * 수정된 파일을 추가
 * git commit -m [코멘트] 
 	 * git push 전 코멘트 추가
 * git push 
 	 * github에 반영

## git 처음 사용시
git config --global user.email "you@example.com"
혹은 
git config --global user.name "Your Name"
으로 아이디를 입력해줘야합니다.

## 주의사항
push할 때 저장소에 이미 변경된 내용이 있으면 push가 되지 않습니다. 이 때 강제로 push하게 하면 다른 분들이 변경한 내용이 되돌아가버릴 수 있으니 본인의 변경사항을 백업후 git pull 한번 해주세요
