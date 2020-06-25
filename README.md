# 3학년 1학기 운영체제론 프로젝트1

## Reader-Writer 문제
Reader와 writer가 공유자원에 접근할 때, reader는 다른 reader와 동시에 접근할 수 있지만, writer
가 다른 writer나 reader와 동시에 접근하면 문제가 발생할 수 있는 것을 reader-writer 문제라고
한다. 이 문제를 해결하기 위한 해법에는 reader 선호, writer 선호, 공정한 reader-writer, 세 가
지가 있다. 어떤 방식이든 모두 writer에게는 상호배타를 보장하고, reader에게는 다른 reader와
최대한 중복을 허용하는 것을 목표로 한다.

## Reader 선호
readfirst.c

## Writer 선호
writerfirstconval.c

## 공정한 reader-writer
samepriority.c

