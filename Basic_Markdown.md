# Basic_Markdown

  * Github의 README.md 작성뿐만 아니라 파일 작성에 있어 Markdown 문법이 필요할 수 있다. 

  * 본 문서에서는 Markdown 기초 문법을 정리함과 동시에 Markdown에 친숙해지기 위함을 목적으로 작성되었다. 

  * 작성자가 생각하기에 자주 쓸 것 같은 내용 위주로 정리하였다.

  * 많은 Markdown 에디터가 있지만 작성자는 Typora를 이용하여 작성하고 있다.  Typora는 완벽히Markdown의 문법을 알지 못해도 충분히 사용할 수 있는 장점이 있다. ~~문법에 익숙해지기는 힘들 수도 있겠다..~~

---------------



## Markdown 문법

### 1. 헤더(Header) = 제목

  * 헤더 크기는 6단계로 이루어졌다. 원하는 단계의 숫자만큼 #을 붙여 작성하면 된다. 

  * (참고) 특정 Markdown 문법을 적용하고 싶지 않다면 앞, 뒤로 역슬래쉬(\\)를 붙여준다.

# \# 제목크기 1단계

## \## 제목크기 2단계

### \### 제목크기 3단계

#### \#### 제목크기 4단계

##### \##### 제목크기 5단계

###### \###### 제목크기 6단계

####### 7개부터는 적용되지 않는다.



### 2. 목록

####   2.1. 순서가 있는 목록

  * 순서가 있는 목록은 숫자 뒤에 마침표를 붙여준다. 

1. 1번 목록
   1. 1-1번 목록
   2. 1-2번 목록
2. 2번 목록
3. 3번 목록

####   2.2. 순서가 없는 목록

  * 순서가 없는 목록은 \*, \+, \- 를 사용한다. 

- 목록
  * 내부 목록
    + 내내부 목록



### 3. 인용

  * 인용은 \> 를 사용한다. 여러층의 인용이 가능하며 \> 
사용개수만큼 들여쓰기 된다. 

  * 인용문구 안에는 다른 Markdown 문법을 혼합해서 사용할 수 있다. 

> # 1단계 인용 + 1단계 헤더
>
> >  ##  2단계 인용 + 2단계 헤더
> >
> > > + 3단계 인용 + 순서없는 목록
> > >
> > > > ~~4단계 인용 +  취소선~~
> > > >
> > > > > 5단계 인용



### 4. 글자 서식

  * 글자 서식에는 *기울기*, **굵게**, ~~취소선~~ 이 있다. 

####   4.1. 기울기

  * 기울기를 원하는 글자 앞 뒤로 \*를 붙여주면 된다. 

  *\*내용*\*

####   4.2. 굵게 

  * 굵게를 원하는 글자 앞뒤로 \** 또는 \__ 를 붙여주면 된다. 

  __\**내용**__

  **\__내용__**

####   4.3. 취소선

  * 취소선을 원하는 글자 앞뒤로 \~~ 를 붙여주면 된다. 

  ~~ ~~내용~~ ~~



### 5. 구분선 

  * 내용 구분 등을 위한 수평선을 위해서는 \- 또는 \* 3개 이상을 붙여서 사용한다. 

---

***

---



### 6. 줄바꿈 

  * 문단 구분 또는 줄 구분을 하기 위해서는 3칸 이상 띄어쓰기를 해준다.



### 7. 코드

  * 기본적으로 코드를 포함하기 위해서는 백틱(`)을 사용한다.

#### 7.1. 인라인코드(1줄 코드)

  * 원하는 코드를 1개의 백틱(`) 사이에 작성한다.

`print("Hello Markdown!")`

#### 7.2 코드블록(여러줄 코드)

  * 원하는 코드를 3개의 백틱(```)사이에 작성한다.

  * 사용한 언어를 표시해줄 수 있다. 

```python
print("Hello Markdown!")
print("Hello python!")
```



### 8. 체크 박스

  * 체크 박스를 사용하기 위해 -, *, + 중 하나를 사용한 뒤 띄어쓰기 후  대괄호([])를 사용한다. 

  * 대괄호 사이에 x를 넣으면 체크 표시가 된다. 

- [x] 해야 할 일 1

- [ ] 해야 할 일 2



### 9. 표 그리기

* 표는 |와 -를 사용해서 그릴 수 있다. 

| 제목1 | 제목2 | 제목3 |
| ----- | ----- | ----- |
| 내용1 | 내용2 | 내용3 |



### 10. 링크

  * 링크는 글자에 링크를 걸 수 있는 인라인 링크 , URL 주소에 링크를 걸 수 있는 URL 링크가 있다. 

####   10.1. 인라인 링크

  * 인라인 링크는 링크를 걸  수 있는 글자를 대괄호([]) 안에 작성한 후 바로 뒤에 소괄호() 안에 원하는 링크를 작성한다. 

[네이버](https://www.naver.com)

####   10.2. URL 링크

  * URL 링크는 꺽쇠괄호(<>) 안에 원하는 링크를 작성한다. 

<https://www.naver.com>

