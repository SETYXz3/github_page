## 無料利用はpublicなrepositoryのみとなります。

### How to Generate Documentation Sites with GitHub and Docsify

#### 1. Check node.js is installed.
```
$ node -v
$ npm -v
```

#### 2. Install docsify
```
$ npm i docsify-cli -g
```

#### 3. Initialize the docs subdirectory
```
$ cd path/to/your/working folder
$ docsify init ./docs
```

#### 3. Initialize the docs subdirectory
```
$ cd path/to/your/working_directory
$ docsify init ./docs

-----
index.html
README.md
.nojekyll
-----

```

#### 4. Run your local server.
```
$ docsify serve ./docs
```

#### 5. Push your code to GitHub.
```
eg.
// change github account(isoda_docs or isoda_src)
$ ssh -T git@isoda_docs
$ git@isoda_docs:"username"/"repository-name.git"

// commit and push
$ git clone git@isoda_docs:username/repository-name.git
$ git remote add origin_docs git@isoda_docs:username/repository-name.git
$ git config remote.orign_docs.url

$ git config --global user.name {ユーザー名}
$ git config --global user.email {メールアドレス}

$ git add .
$ git commit -m "sample commit comments"
$ git push orign main
```

#### 6. Generate the GitHub page.
Setting -> GitHub Pages ->

Source:
master branch / docs folder

#### 7. open with Browser

URL:
[https://setyxz3.github.io/github_page/](https://setyxz3.github.io/github_page/)

