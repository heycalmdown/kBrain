---
{"dg-publish":true,"dg-permalink":"baeecbf7-7acb-42ad-9d84-1488ecf495d5","permalink":"/baeecbf7-7acb-42ad-9d84-1488ecf495d5/","dgHomeLink":true,"dgPassFrontmatter":false}
---

obsidian-digital-garden [원문](https://github.com/oleeskild/obsidian-digital-garden#configuration) 참조

# 준비
- [Digital Garden](https://obsidian.md/plugins?search=publish%20digital%20garden) 플러그인을 설치한다
- https://app.netlify.com/ GitHub 아이디로 로그인 하기
- [여기](https://github.com/oleeskild/digitalgarden)에서 `Deploy to Netlify` 버튼 눌러서 사이트 설정하기
- [여기](https://github.com/settings/tokens/new?scopes=repo)에서 GitHub Personal Access Token 만들기 - (유효기한 무제한)
- 플러그인 세팅에서 GitHub 설정 입력하기

# 배포
```
---
dg-home: true
dg-publish: true
dg-permalink: c0b77cb5-9d66-4415-b51c-c33ea8173179
---
```
- [Front matter](https://help.obsidian.md/Advanced+topics/YAML+front+matter)에 위 세 개만 입력하면 됨
- `dg-publish` - 게시하겠다는 뜻
- `dg-home` - 여기가 홈이라는 뜻
- `dg-permalink` - 한글 문서는 [Slug](https://en.wikipedia.org/wiki/Clean_URL#Slug) 못 만들어서 링크가 깨지므로 유니크한 아이디를 따로 넣어주자
- 팔레트에서 `Publish Multiple Notes` 선택해서 게시해주자
!Pasted image 20220611070921.png
