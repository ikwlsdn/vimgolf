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
  입력 : %s/sublime\|emacs/vim/g<CR>ZZ
  
  %s : 치환 명령어
  
  /sublime\|emacs : sublime 또는 eamcs 문자열
  
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
  
  p : TODO를 
  
  ---
  ### 4) Plotting some variables in python
  
  ---
  ### 5) Python dataclasses
