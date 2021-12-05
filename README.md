# vimgolf

### 1) Add quotes to ansible playbook
입력 : GWi"<End>"<Esc>ZZ

  G : 마지막 줄로 이동
  
  W : {앞으로 이동
  
  i : 입력모드 시작 
  
  END : 입력모드에서 줄의 마지막으로 이동
    
  ZZ : :wq와 동일한 기능(버튼수가 더 적음)
  
  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/68582617/144746789-05040f91-ab1b-4051-a251-4fdff0d2f24b.gif)


  ---

  ### 2) simple replacements
  입력 : %s/sublime\\|emacs/vim/g<CR>ZZ
  
  %s : 치환 명령어
  
  /sublime\\|emacs : sublime 또는 eamcs 문자열
  
  /vim : vim문자열로 치환
  
  /g : 모든 줄에 적용
  
  ZZ : :wq와 동일한 기능(버튼수가 더 적음)
  
  ![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/68582617/144748060-d37c7bf5-4b9b-43a7-bfd5-9d518f7bff80.gif)
  
  ---
  ### 3) Satisfy the go linter
  입력 : 4GywO// <Esc>pATODO<Esc>byw<Down>o// Debug <Esc>pZZ
  
  4G : 4번째 라인으로 이동
  
  yw : Version 단어를 복사
  
  O : 현재 위치한 라인의 윗라인부터 편집모드
  
  p : 복사해둔 Version을 붙여넣기
  
  A : 다음 칸부터 편집모드 사용
  
  b: TODO의 제일 뒤로 이동
  
  yw : TODO를 복사
  
  o : 현재 위치한 라인의 아래라인부터 편집모드
  
  p : TODO를 붙여넣기
  
  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/68582617/144748316-479224ea-f7aa-4a5b-83b0-5a0baa6940e8.gif)
  ---
  ### 4) Plotting some variables in python
  입력 : %s/y1/abs(y1)/g<CR>3Gfa<C-A><Down><C-A><C-A><Down><C-A><C-A><C-A>W<C-A><C-A><C-A><Up><C-A><C-A><Up><C-A>Fkrb<Down>rr<Down>rgZZ
  
  %s/y1/abs(y1)/g : y1을 abs(y1)로 치환
  
  3G : 3번째 라인으로 이동
  
  fa : a를 찾아 이동
  
  컨트롤 a : 숫자를 하나씩 늘린다 아래로 내려가면서 늘려주었음
  
  W : 단어 단위 앞으로 이동
  
  이후 위로 올라가면 숫자를 늘려주었음
  
  Fk : 뒤쪽에서 k를 찾아 이동
  
  r : 한글자만 치환 할때 이용 아래로 내려가며 한글자씩 치환하였음
  
  ![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/68582617/144751555-d260f965-ede3-4701-bc34-3b4cdc599497.gif)
  
  내용이 틀린게 없는데 에러가 나는 이유를 모르겠습니다.
  
  ---
  ### 5) Python dataclasses
  입력 : 5G4yyGP<Up>5J0WW<Right><Del><Del>WdwWdwWdwWdwi<BS>"<Esc>:.s/: /,/g<CR>ZZ
  
  5G : 5번째 라인으로 이동
  
  4yy : 위치한 라인부터 아래 4라인을 복사
  
  G: 제일 아래 라이능로 이동
  
  P: 복사한 라인들 붙혀넣기
  
  5J : 위치한 라인부터 아래로 5라인을 한줄로 병합
  
  0 : 라인의 제일 앞으로 이동
  
  W : 단어의 앞으로 이동해가며
  
  dw : word 잘라내기 
  
  :.s/: /,/g : 현재 위치한 라인만 : 를 ,로 치환
  
  ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/68582617/144750512-cdd03ecb-3927-4980-bc1a-7b254eea8b9c.gif)
  
  이 문제는 내용을 다 맞췄는데 왜 계속 오류가 나오는지 모르겠습니다.
  
  
