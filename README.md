## VimGolf #1
![vimgolf-1](https://user-images.githubusercontent.com/94420917/144644256-4fa112aa-fbda-43cc-b598-6a42496a6a19.gif)


<img width="626" alt="vimgolf-1" src="https://user-images.githubusercontent.com/94420917/144644521-f94d298c-38ef-4ff6-8e54-d910c849cede.png">

> GWi"< End ><C-@>ZZ

  G : 문서 마지막 라인으로 이동

  W : 다음 단어 처음으로 이동
  
  i : inseart mode
  
  < End > : ($와 동일) 라인의 끝으로 이동

  <C-@> : 직전에 입력한 단어를 삽입하고 입력 모드 종료
    
  ZZ : (:wq와 동일) 저장하고 나가기




## VimGolf #2
![vimgolf-2](https://user-images.githubusercontent.com/94420917/144652531-2ec6766e-d4bf-4993-8356-f0f1fbf59d4e.gif)


<img width="655" alt="vimgolf-2" src="https://user-images.githubusercontent.com/94420917/144652568-8783753f-65aa-4bd5-a215-bd27ec84ad24.png">

> wcevim< Esc >:%s/emavs/vim/g<CR>ZZ
  
  w : 다음 단어의 처음으로 이동
  
  ce : 현재 커서 단어의 다음 단어까지 삭제하고 입력 모드
  
  %s/str/replace/g : str 단어를 replace로 치환

  
  

## VimGolf #3
![vimgolf-3](https://user-images.githubusercontent.com/94420917/144655091-9d282ac7-2861-4978-bb11-e279593c613f.gif)

<img width="627" alt="vimgolf-3" src="https://user-images.githubusercontent.com/94420917/144655205-30035036-e5e6-4c81-90ab-0b7b68793ac0.png">
  
> /V< CR >O// < C-N > TODO< Esc >yyjpwcw< C-N >< C-N >< Esc >ZZ
  
  /V : 'V' 단어 검색
  
  < CR > : Enter. 줄바꿈 또는 현재 상태 적용
    
  O : 현재 라인을 다음 줄로 밀고 입력 모드
    
  < C-N > : insert mode에서 사용. 자동 완성 (Ctrl + p 는 버퍼에서 뒤로 검색, Ctrl + n 은 앞으로 검색)
    
  yy : 현재 라인 복사
    
  j : 커서 아래로 이동
    
  p : 현재 위치 다음에 붙여넣기
    
  w : 다음 단어의 처음으로 이동
    
  cw : 현재 커서 단어의 다음 시작까지 삭제하고 입력 모드
  


## VimGolf #4

## VimGolf #5
![vimgolf-5](https://user-images.githubusercontent.com/94420917/144642803-5c73ccca-34b9-4bcb-9dc5-2df8be84f5af.gif)
