### 새 탭 추가법
- data/navigation.yml에 추가
- publications.md를 복사해서 새 탭 만들기. permalink, redirect_from를 navigation.yml이랑 맞추기
- Q) 기본 navigation.yml에 있는 페이지들 말고 내 페이지를 새로 추가하려면 어떻게 해야되지? cv로는 잘 가지는데 about_me로는 redirect가 안됨...


- excerpt 없애니까 해결됨...
- includes/archive-single.html --> 페이지 layout. 
- page width 조절하기: _sass/_page.scss의 span-suffix 비율 조절
https://github.com/mmistakes/minimal-mistakes/issues/384

마크다운 글씨체
https://support.discordapp.com/hc/ko/articles/210298617-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%ED%85%8D%EC%8A%A4%ED%8A%B8-101-%EC%B1%84%ED%8C%85-%EC%84%9C%EC%8B%9D-%EA%B5%B5%EA%B2%8C-%EA%B8%B0%EC%9A%B8%EC%9E%84%EA%BC%B4-%EB%B0%91%EC%A4%84-