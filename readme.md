[![Build status](https://travis-ci.com/icasimpan/quicktasks-mysql.svg)](https://travis-ci.com/icasimpan/quicktasks-mysql)

*What is this*

Is my personal notes, written using with the help of hugo.

*Adding Blog Post*
1. Make sure you have hugo installed, refer to https://gohugo.io/getting-started/installing/
2. Clone the Project
```
git clone https://github.com/icasimpan/quicktasks-mysql.git
```
3. Add a new article to your blog
```
hugo new posts/your-new-blog-post.md
```
4. Edit your post
5. Commit changes to git
```
git commit "My new awesome post!"
```


*Publish*

1. Clone the raw blog
```
git clone https://github.com/icasimpan/quicktasks-mysql.git
```
2. Go inside it
```
cd quicktasks-mysql
```
3. Get the current "public" from "gh-pages" branch:
```
git clone --branch gh-pages https://github.com/icasimpan/quicktasks-mysql.git public
```
4. Regenerate
```
hugo
```
5. Commit changes to git
```
cd public
git commit "blogpost update"
```

Hugo version tested: v0.49.2
Theme version used: https://github.com/icasimpan-oss/basics (HEAD: 2afe098) as it has fixes not applied yet
                    to upstream https://github.com/arjunkrishnababu96/basics (HEAD: 93d2a49) that I need, as follow:
                    * #8 - css breaks when baseURL is not /
