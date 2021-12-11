# Welcome to Hyunwoo Song Page!
---
## Build 과정
1. Repositiory(github.io) 생성하기
2. Jekyll 설치하기
3. Gitgub에 Jekyll 적용하기
4. favicon 수정하기
5. 댓글 기능 추가
6. Google Analytics 추가하기

## 1. Repository(github.io) 생성하기
Github page를 만들기 위해선 Github 계정이 필요하다.   
-> 이미 Github 계정이 있었으므로 Pass  
Github page를 만들기 위해선 Repository의 이름을 `<username.github.io>`로 설정한다.  
본인은 username이 hwstage 이므로 `hwstage.github.io`로 설정했다.   
이제 이 Repository를 이용해 Gitpage를 build하겠다.

## 2. Jekyll 설치하기
https://rubyinstaller.org/downloads/   
위 페이지에서 Ruby와 DevKit을 설치한다.   
Ruby가 정상적으로 설치되면 Start Command Prompt with Ruby를 실행한다.   
1. ` gem install jekyll bundler` 를 입력해 패키지를 설치한다.  
2. ` jekyll -v` 를 입력해 jekyll이 잘 설치되었는지 확인한다.
3. 자신의 블로그 Directory로 이동한다.  
4. ` jekyll new .` 를 입력해 현재 디렉토리 내부에 블로그 파일 생성  
5. ` jekyll serve` 를 입력해 지킬 실행  

## 3. Github에 Jekyll 적용하기
http://jekyllthemes.org/  
https://jekyllthemes.io/free    

두 사이트에서 마음에 드는 테마를 선택 후 ZIP파일을 설치한다.  
그 다음 ZIP 파일 내부의 파일을 복사해 Repository에 붙여넣는다.  

페이지의 제목을 수정하기 위해 _config.yml의 title을 LUCE IN ALTIS로 수정했다.  
navigation과 social도 적절하게 수정하였다.  
_includes 폴더의 header 파일에서 내 github와 velog로 교체하였다.