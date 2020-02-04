# Markdown

## 1. Markdown?
>`Markdown` 은 웹에서 컨텐츠를 편하게 작성하기 위해 만들어진 마크업언어이다.
>이렇게 만들어진 `Markdown`은 HTML같은 다른 문서로 변환이 가능하다.

## 2. How?
>`Pycharm` 설치과정은 생략

### 2-1) Build-up
* `GitHub`에서 만든 프로젝트에서 Clone 주소를 복사한다.
* `Pycharm`의 `Terminal`에 'git clone 주소'를 입력한다. (Error 1)
* 프로젝트가 있는 디렉토리로 설정을 한다.
* 그후 프로젝트 이름을 입력하여 `master` 권한을 갖는다.

### 2-2) Syntax
* 글머리 사이즈 (#~######) : #~~~
# Header 1
## Header 2
### Header 3
#### Hearder 4
##### Hearder 5
###### Header 6
####### Hearder 7 (#7개 헸을 경우)

* BlockQuote
`>`문자를 사용   
여러개 사용 가능
> 1개
>>2개
>>>3개
>>>>4개
>>>>>5개

* 줄바꿈   
띄워쓰기 3번을 해주면 된다.

* 리스트
`*`, `+`, `-` 를 사용가능

* `*`을 썼을때
+ `+`를 썼을때
- `-`를 썼을때

* * : * 두번
+ + : + 두번
- - : - 두번
* - : *, - 한번씩

결론 : 문자의 종류보다 개수가 중요하다.


* 외부 언어 불러오기

'문자를 3번 쓰고 python을 입력한다. : ```python   
그 후 입력하고 싶은 코드를 적고 마무리를 할 떄는 `를 3번 쳐준다.   
(Error 2)
>
# `pycharm`, `python`
```python
print("Hello world")
```

* 코드블럭   
`3번으로 시작하고 마무리 할 때도 같은 방법으로 해준다.
```buildoutcfg
Codeblock
```


### 2-3) Update
문서를 다 정리하고 `GitHub`에 올리기 위해 명령어를 적어야한다.
순서는 Add-Commit-Push 이다.


#### 2-3-1) Add : 추가한다고 선언
```
git add .
```

#### 2-3-2) Commit : 파일 저장
```
git commit -m "설명"
```
#### 2-3-3) Push : 전송
```
git push origin master
```

## 3. Error
Error 1 : 제대로된 디렉토리를 설정하지 못했을 경우 에러발생.
>`cd 경로`를 통하여 경로 설정   
>이때 설정이 안되는 경우가 있는데 그럴땐 새로운 `Terminal` 창을 만들어서 한다.

Error 2 : 외부 언어를 불러오고 끝내지 않았을 경우
> 외부 언어를 불러오고 나서 반드시 ```를 입력하여 마무리 해야한다. 

## 4. Reference
[마크다운 사용법][Link]

[Link]:https://gist.github.com/ihoneymon/652be052a0727ad59601