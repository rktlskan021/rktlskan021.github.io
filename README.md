## 깃 페이지 Build 과정
1. Repository 생성하기 (Username.github.io)
2. Jekyll 설치하기
3. Github에 Jekyll 테마 포크 후 적용
4. 댓글 기능 추가
5. Google Analytics 추가

## 1. Repository 생성하기 (Username.github.io) 후 클론
1-1. New repository 클릭
1-2. Repository 이름을 `<username.github.io> 로 지정
1-3. 생성 완료
1-4. 생성한 repository를 클론

## 2. Jekyll 설치하기
1. [ruby site](https://rubyinstaller.org/downloads/) 페이지 접속
2. Ruby+Devkit 설치
3. cmd 실행 후 `gem install jekyll bunler` 입력
4. `jekyll -v`를 입력해 설치 확인
5. 클론한 Directory로 이동
6. jekyll new . --force 를 입력해 블로그 파일 생성
7. bundle exec jekyll serve 로 지킬 실행

## 3. Github에 Jekyll 테마 포크 후 적용
1. 자신이 사용하고 싶은 Jekyll 테마를 선택 후 fork
2. fork 한 repository를 클론
3. 클론된 파일들을 자신의 블로그 directory에 복사
4. `bundle install` 를 입력
5. 페이지 제목, 포스트 등 작성

## 4. 댓글 기능 추가
1. [disqus](https://disqus.com) 가입
2. I Want to install Disqus on my 선택
3. Website Name (나중에 필요)
4. Category를 선택하고 Create Site 클릭
5. Basic을 선택하고 Subscribe Now 클릭
6. Jekyll 선택
7. configure 클릭 후 이전에 Website Name, Website URL, 입력, Next 버튼 클릭
8. 원하는 정책 선택
9. Universal Embed Code 클릭
10. _config.yml 파일에
```
comment:
    provider:"disqus"  
    disqus:  
        shortname: "<username>"
```
코드 입력
11. _layouts/post.html 에 복사해둔 Universal 코드 입력
12. 댓글 기능을 추가하고 싶은 post 파일에 `comment: true` 추가

## 5. Google Analytics 추가
[이 사이트 참고](https://rktlskan021.github.io/blog/google-analytics/)