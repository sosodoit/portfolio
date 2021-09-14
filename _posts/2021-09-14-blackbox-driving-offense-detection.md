---
layout: post
title: "블랙박스 운전 범칙행위 감지 신고 서비스"
date: 2021-09-14 11:10:49
image: '/assets/img/'
description:
main-class: 'team'
color:
tags:
- python
- "object detection"
- segmentation
categories: 
twitter_text:
introduction: abc
---

[시연](#) Blackbox driving offense detection

## 🚀 Algorithm

### 중앙선 침범, 끼어들기 범칙행위 탐지
1. 차량 및 번호판 Detection
- yolov3, v4, v5, Resnet, EffiecntNet :mAP을 통한 성능비교
- tesseract ocr 활용한 번호판 인식(한글 포함) 

2. 차선 Detection
- mask r cnn, segmentation :mAP을 통한 성능비교

3. 최종 모델 결합

4. 신고 서비스 제안

<br>

## 🚀 Getting Started

### Install
#### npm 설치
```
cd frontend
npm install
```
> `frontend` 디렉토리에서 수행해야 합니다.

### Usage
#### webpack server 구동
```
npm run dev
```
#### application 구동
```
./gradlew bootRun
```
<br>

## ✏️ Code Review Process
[텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](#)

<br>

## 🐞 Bug Report

버그를 발견한다면, [Issues](#) 에 등록해주세요 :)

<br>

## 📝 License

This project is [MIT](#) licensed.