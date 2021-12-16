---
layout: post
title:  "Markdown"
date:   2021-12-14
description: about Markdown
comments: true
---

## Markdown 이란?
일반텍스트로 서식이 있는 문서를 작성하는 방법으로 일반 텍스트 기반의 경량 마크업 언어다. 일반 텍스트로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업 언어에 비해 문법이 쉽고 간단한 것이 특징이다. HTML과 리치 텍스트(RTF) 등 서식 문서로 쉽게 변환되기 때문에 응용 소프트웨어와 함께 배포되는 README 파일이나 온라인 게시물 등에 많이 사용된다.

## 문법
#### 1. Header : #, ##, ###, ... 으로 제목 작성
#: 
# 큰제목
##: 
# 중간 제목
###: 
### 작은 제목

#### 2. Italic : *...*, _..._으로 기울임체 작성
*Italic*
<br/>_also-italic_

#### 3. Bold : **...**, __...__ 으로 강조체 작성
**Bold**
<br/>__also-Bold__

#### 4. Strikethrough : \~~...\~~ 으로 취소선 작성
~~Strikethrough~~

#### 5. Unordered List : - ..., * ... 으로 순서없는 리스트 작성
- 1 : ... 
- 2 : ...

#### 6. Ordered List : 1. ... 으로 순서 리스트 작성
1. ~~
2. ~~

#### 7. Code : \`...\` 으로 코드 작성
We can print some value with `print()`

#### 8. Code Block : \`\`\`...\`\`\` 으로 코드 블록 작성
We can get by this function:
```python
def power(x: int):
	return x ** 2
```

이러한 기능 뿐만 아니라 더 다양한 문법들이 있으니
<br/>[Markdown Guide - Basic Syntax](https://www.markdownguide.org/basic-syntax#code) 에서 필요한 문법을 찾아볼 수 있다.