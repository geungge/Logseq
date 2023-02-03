- ### GIT
	- https://github.com/geungge/logseq.git
	- ### …or create a new repository on the command line
		- echo "# logseq" >> README.md
		  git init
		  git add README.md
		  git commit -m "first commit"
		  git branch -M main
		  git remote add origin https://github.com/geungge/logseq.git
		  git push -u origin main
	- ### …or push an existing repository from the command line
		- git remote add origin https://github.com/geungge/logseq.git
		  git branch -M main
		  git push -u origin main
	- 확인
		- logseq에서 고친후 commit 을 안하고 바로 push 해도 되네.. 정상인가?
		- logseq 설정을 enable 하면 commit 까지는 자동으로 하는 것 같다 -> 백업하고자 할 때 git push 만 하면 될 것 같으다
- ### 특수목적
	- `Note`
		- #+BEGIN_NOTE
		  Note
		  #+END_NOTE
	- `Tip`
		- #+BEGIN_TIP
		  Tip
		  #+END_TIP
	- `Important`
		- #+BEGIN_IMPORTANT
		  Important
		  #+END_IMPORTANT
	- `Caution`
		- #+BEGIN_CAUTION
		  Caution
		  #+END_CAUTION
	- `Warning`
		- #+BEGIN_WARNING
		  Warning
		  #+END_WARNING
	- `Quote`
		- #+BEGIN_QUOTE
		  Quote
		  #+END_QUOTE
	- `Src`
		- ``` 
		  Src
		  ```
	- `Example`
		- #+BEGIN_EXAMPLE
		  Example
		  #+END_EXAMPLE
	- `Verse`
		- #+BEGIN_VERSE
		  Verse
		  #+END_VERSE
	- `Comment`
		- #+BEGIN_COMMENT
		  Comment
		  #+END_COMMENT
- ### 링크
	- #### 페이지 열기
-
-