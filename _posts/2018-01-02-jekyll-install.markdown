# jekyll 인스톨과 Github Pages 에 공개하기

## jekyll 인스톨하기

```shell
$ gem install jekyll
$ jekyll new my-site
$ cd my-site
$ jekyll serve
```

## 로컬 페이지 확인
http://localhost:4000


## Github Pages 에 공개하기

```shell
$ git remote add origin <리포지토리URL>
$ git init
$ git add --all
$ git commit -m "init"
$ git push origin master
```

## 실제 페이지 확인
http://<유저명>.github.io/
