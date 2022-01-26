

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Oscar](#oscar)
  - [Introducing GUI](#introducing-gui)
  - [Introducing CUI (chat user interface)](#introducing-cui-chat-user-interface)
  - [예제 계정](#%EC%98%88%EC%A0%9C-%EA%B3%84%EC%A0%95)
- [Examples of how to use the chat interface](#examples-of-how-to-use-the-chat-interface)
  - [Greetings](#greetings)
  - [Help](#help)
  - [Personal Questions](#personal-questions)
    - [Introducing Himself](#introducing-himself)
    - [Asking - Age](#asking---age)
    - [Asking - Where he is](#asking---where-he-is)
  - [Basic functions](#basic-functions)
  - [1. Basic - Add a task](#1-basic---add-a-task)
    - [by Title (DEFAULT)](#by-title-default)
    - [by Title and Person](#by-title-and-person)
    - [by Title and Groupname](#by-title-and-groupname)
    - [by Title and Deadline date](#by-title-and-deadline-date)
    - [by Title and #SUPERIMPORTANT](#by-title-and-superimportant)
    - [by Title, deadline and groupname](#by-title-deadline-and-groupname)
    - [by Title, deadline and #SUPERIMPORTANT](#by-title-deadline-and-superimportant)
    - [by Title, groupname and #SUPERIMPORTANT](#by-title-groupname-and-superimportant)
    - [by Title, deadline, groupname and #SUPERIMPORTANT](#by-title-deadline-groupname-and-superimportant)
  - [2. Basic - Delete a task](#2-basic---delete-a-task)
    - [by Title and groupname (DEFAULT)](#by-title-and-groupname-default)
  - [3. Basic - Add a Group](#3-basic---add-a-group)
    - [by Groupname (DEFAULT)](#by-groupname-default)
  - [4. Basic - Delete a Group](#4-basic---delete-a-group)
    - [by Groupname (DEFAULR)](#by-groupname-defaulr)
  - [Advanced functions](#advanced-functions)
  - [1. Searching - Searching tasks](#1-searching---searching-tasks)
    - [by Deadline Date](#by-deadline-date)
    - [by Person](#by-person)
    - [by Groupname and Deadline date](#by-groupname-and-deadline-date)
    - [by Priority (#SUPERIMPORTANT)](#by-priority-superimportant)
    - [by #SUPERIMPORTANT and deadline date](#by-superimportant-and-deadline-date)
    - [by #SUPERIMPORTANT and groupname](#by-superimportant-and-groupname)
    - [by #SUPERIMPORTANT, groupname and deadline date](#by-superimportant-groupname-and-deadline-date)
  - [2. Recommendation - Finding tasks](#2-recommendation---finding-tasks)
- [Small Talk](#small-talk)
- [Step-by-step guidline](#step-by-step-guidline)
- [Introducing the Mobile Service (on Kakaotalk)](#introducing-the-mobile-service-on-kakaotalk)
- [Future FAQ](#future-faq)
  - [회원가입이 안돼요](#%ED%9A%8C%EC%9B%90%EA%B0%80%EC%9E%85%EC%9D%B4-%EC%95%88%EB%8F%BC%EC%9A%94)
  - [회원 탈퇴는 어떻게하나요](#%ED%9A%8C%EC%9B%90-%ED%83%88%ED%87%B4%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C%ED%95%98%EB%82%98%EC%9A%94)
  - [개인 정보가 우려됩니다](#%EA%B0%9C%EC%9D%B8-%EC%A0%95%EB%B3%B4%EA%B0%80-%EC%9A%B0%EB%A0%A4%EB%90%A9%EB%8B%88%EB%8B%A4)
  - [What is the tasktitle?](#what-is-the-tasktitle)


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Oscar
오스카는 트렐로, wunderlist 형태의 웹 to-do 플랫폼이 챗봇과 결합되면 어떻게 될까? 라는 생각에서 출발한 to-do 웹 서비스입니다. 기본적 UI는 다른 to-do 웹서비스와 크게 다르지 않지만 챗봇 인터페이스가 함께 존재하고, 그를 통해 더욱 직관적이게 기존 서비스를, 그리고 기존 to-do 앱에는 존재하지 못했던 서비스를 이용가능합니다.

Oscar is a chat assistant that helps you manage your prioritized tasks way more effectively. the principal concept of the project is "a chat interface combines with a normal to-do platform". so basically you can use functions such as adding or deleting tasks through GUI like normal to-do platforms, but I'v added a chat interface into the project, so you can use way more advanced and fun functions through it.

## Introducing GUI
GUI로는 다른 to-do 앱과 같이, 태스크와 그룹(태스크의 모음) 추가가 가능합니다.

__GUI는 일종의 데이터베이스 뷰어로 사용됩니다__

As I told you, you sure can use GUI like normal to-do platforms. you can add tasks or groups to the website through it

## Introducing CUI (chat user interface)
챗을 통해 오스카를 더 편하게 이용하고싶으시다면 하단의 talk to me 버튼을 눌러주세요. 웹 플랫폼 내부의 작은 채팅창을 이용해서 오스카의 GUI로는 접근할 수 없는 많은 숨겨진 기능을 이용할 수 있습니다.

press "Talk to me" button to start using the chat interface. you can use lots of advanced functions (which is not allowed to use on GUI) through it.

## 예제 계정

예제 계정을 사용할 수 있습니다. req.sessionID로 브라우저 별로 다른 세션아이디를 가져와 대화가 섞이지 않습니다. 단, 다른 사람이 수정한 데이터베이스의 비동기적 변화를 실시간으로 보기 어렵기 때문에 새로고침을 잘 이용하시고 가급적이면 계정을 만드세요

id `bobby@tarantino.com`

pw `havanaonana`

# Examples of how to use the chat interface
Here're great examples of how to start talking with him. Enjoy! ;-)

## Greetings

```md
Hi!
Howdy!
Greetings!
Good evening!
How are you?
How are you doing?
How ya doin?
What's up
sup
```

## Help

<img src="https://user-images.githubusercontent.com/10420159/33828558-f957145a-deaf-11e7-8d11-c181d470c0ca.gif" width="500"/>

```md
What can you help me with?
What can you do?
Could you show me the examples?
```
or you can just say "Help" or "Examples" to show the examples!

## Personal Questions

### Introducing Himself

```md
So, Who's this
Who are you?
Here he is
What is your name
```

### Asking - Age

```md
Can I ask you how old you are?
How old are you?
Ohh, I was wondering if I could ask you how old you are
If you don't mind me asking how old are you
```

### Asking - Where he is

```md
Where do you live
Where are you?
I can't find where you are
```


## Basic functions

## 1. Basic - Add a task

<img src="https://user-images.githubusercontent.com/10420159/33806064-a2e6cae8-de05-11e7-8e8d-6e45dca133a0.gif" width="500"/>

### by Title (DEFAULT)

```md
I'd like to add a task ride a bike
```
*서로 다른 title간 공통점이 없어 한 엔티티로 인식이 어려워 task ____ 의 형태로 엔티티를 저장해 엔티티 간 공통점을 만들어 인식률을 높였습니다 (웹훅에서 끊어서 사용) 꼭 앞에 task를 붙여주세요*


### by Title and Person

```md
I'd like to add a task ride a bike with angelica
```
*I recommend you to use names on nameberry.com. names exist on nameberry.com are mostly supposed to be recognized here*


### by Title and Groupname

```md
I'd like to add a task ride a bike in a Group called [EXISTING-GROUPNAME]
```
*only groups that you've already made are supposed to be recognized through the chat interface (exp for adding groups)*

*서로 다른 그룹이름간 공통점이 없어 한 엔티티로 인식이 어려워 group called ____ 의 형태로 엔티티를 저장해 엔티티 간 공통점을 만들어 인식률을 높였습니다 (웹훅에서 끊어서 사용) 꼭 앞에 group called를 붙여주세요*

그룹이름 대소문자 구분합니다 - (issue : 전부 소문자 처리)

### by Title and Deadline date

```md
I'd like to add a task ride a bike, this Friday
I'd like to add a task ride a bike, next Thursday
I'd like to add a task ride a bike, Tomorrow
```

*for your reference*
```md
this Monday
this Sunday
next Monday
next Sunday
Tomorrow
Today
```


### by Title and #SUPERIMPORTANT

```md
I'd like to add a SUPER IMPORTANT task ride a bike
I'd like to add an important task ride a bike
I'd like to add a superimportant task wowowo
```


### by Title, deadline and groupname

```md
I'd like to add a task ride a bike in a group called [EXISTING-GROUPNAME], this Friday
```


### by Title, deadline and #SUPERIMPORTANT

```md
I'd like to add a superimportant task hanging out, tomorrow
id like to add a super important task ride a bike, next thursday
id like to add an important task ride a bike, this sunday
```

### by Title, groupname and #SUPERIMPORTANT

```md
I'd like to add a super important task ride a bike in a group called [EXISTING-GROUPNAME]
```

### by Title, deadline, groupname and #SUPERIMPORTANT

```md
I'd like to add an important task Hang out in a group called [EXISTING-GROUPNAME], this tuesday
```

## 2. Basic - Delete a task

<img src="https://user-images.githubusercontent.com/10420159/33806067-a578b7b2-de05-11e7-9565-91fffa17c9b4.gif" width="500"/>

### by Title and groupname (DEFAULT)

```md
I'd like to delete a task Hang out in a group called [EXISTING-GROUPNAME]
```



## 3. Basic - Add a Group

<img src="https://user-images.githubusercontent.com/10420159/33806068-a8a9ba30-de05-11e7-8fb4-1cf2c8d03297.gif" width="500"/>

### by Groupname (DEFAULT)

```md
I'd like to add a group called [GROUPNAME]
```

*서로 다른 그룹이름간 공통점이 없어 한 엔티티로 인식이 어려워 group called ____ 의 형태로 엔티티를 저장해 엔티티 간 공통점을 만들어 인식률을 높였습니다 (웹훅에서 끊어서 사용) 꼭 앞에 group called를 붙여주세요*


## 4. Basic - Delete a Group

<img src="https://user-images.githubusercontent.com/10420159/33821760-728b345e-de98-11e7-9913-9292345f49b1.gif" width="500"/>

### by Groupname (DEFAULR)

```md
I'd like to delete a group called [EXISTING-GROUPNAME]
```

*only groups that you've already made are supposed to be recognized through the chat interface (exp for adding groups)*

__Unsorted CANNOT BE DELETED__


## Advanced functions

## 1. Searching - Searching tasks

<img src="https://user-images.githubusercontent.com/10420159/33826026-f2d96e38-dea6-11e7-8289-122613f36286.gif" width="500"/>

### by Deadline Date

```md
I'm looking for tasks tomorrow
I'm looking for tasks next Wednesday
I'm looking for tasks I gotta do today
I'm looking for tasks I gotta do next Friday
I'm looking for tasks I need to do next Monday
the tasks I have to do next Tuesday
im looking for tasks this monday
im looking for tasks for today
```

*for your reference*
```md
this Monday
this Sunday
next Monday
next Sunday
Tomorrow
Today
```

### by Person

```md
I'm looking for tasks associated with Angelica
```
*I recommend you to use names on nameberry.com. names exist on nameberry.com are mostly supposed to be recognized here*

### by Groupname and Deadline date

```md
I'm looking for tasks in a group called [EXISTING-GROUPNAME], next wednesday
```

### by Priority (#SUPERIMPORTANT)

//#### by Priority and Groupname
```md
I'm looking for important tasks
```

### by #SUPERIMPORTANT and deadline date

```md
I'm looking for super important tasks today
I'm looking for SUPERIMPORTANT tasks next monday
```

### by #SUPERIMPORTANT and groupname

```md
I'm looking for superimportant tasks in a group called [EXISTING-GROUPNAME]
```

*only groups that you've already made are supposed to be recognized through the chat interface (exp for adding groups)*

### by #SUPERIMPORTANT, groupname and deadline date

```md
I'm looking for important tasks in a group called [EXISTING-GROUPNAME], next wednesday
```

## 2. Recommendation - Finding tasks

<img src="https://user-images.githubusercontent.com/10420159/33806071-ac08a5c4-de05-11e7-9fca-27107607838c.gif" width="500"/>

```md
What do you think I should do first?
What do you think I should do
```


# Small Talk

```md
Answer my question.
Can you get smarter?
Aww, you're cute
What's your birth date?
Who's your boss
Are you busy?
```
and so on...

# Step-by-step guidline

# Introducing the Mobile Service (on Kakaotalk)
is now being prepared

카카오서비스 준비중

그래도 궁금하시다면

@oscartheasstnt on Kakaotalk


# Future FAQ

## 회원가입이 안돼요
회원가입시 validation 요건에 충족되지 않았을 경우 알림 메시지가 뜨질 않습니다🤔 겹치는 이메일이 있거나 비밀번호 요건 (최소 1 - 최대 15자), 안 채운 폼이 있는지 확인해 주세요

*** 비밀번호 요건 (특수문자 1개 영어 1개 숫자1개 ...) 는 무시해주세요 UI디자인상 넣었습니다 (ㅋㅋㅋㅋㅋㅋ)

## 회원 탈퇴는 어떻게하나요
/delete 로 이동하면 탈퇴가 가능합니다 -- > //탈퇴하면 회원개인정보만 사라지고 task 데이터베이스 추후 삭제구현

__탈퇴 기능이 약간 이상해서 안하는것을 추천합니다__

## 개인 정보가 우려됩니다
비밀번호는 암호화되어 저장됩니다. ... 그리고 db를 처음 써봐서 보고싶어도 못봐요 (ㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋㅋ)

## What is the tasktitle?
what is the tasktitle? 만 계속 나올떄는 __침착하게 정확한 명령어로 다른 명령을 시키면__ 됩니다


