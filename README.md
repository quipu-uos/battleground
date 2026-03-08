# QUIPU Web Game

서울시립대학교 컴퓨터 학술 중앙동아리 QUIPU의 실시간 멀티플레이 타자 게임 프로젝트입니다.  
사용자는 게임 방에 입장해 단어 입력 속도와 정확도로 경쟁할 수 있습니다.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Development Timeline](#development-timeline)
- [Getting Started](#getting-started)

## Overview

본 프로젝트는 웹 기반 실시간 타자 대결 서비스를 제공하기 위해 개발되었습니다.  
프론트엔드는 React 기반 클라이언트로 구성되며, 백엔드는 Express와 Socket.IO 서버로 동작합니다.  
플레이어는 로비에서 방을 생성하거나 참여하고, 게임 진행 중 채팅과 점수 현황을 확인할 수 있습니다.

## Features

- 최대 3인 실시간 멀티플레이 타자 대결
- 게임 방 생성, 입장, 대기 기능
- 게임 중 실시간 채팅 및 진행 상태 동기화
- 단어 입력 결과 기반 점수 집계 및 순위 표시
- 게임 종료 화면에서 결과 확인

## Tech Stack

- Frontend: React
- Backend: Express, Socket.IO
- Database: MySQL

## Development Timeline

| Project | Period |
|---|---|
| Web Game | 2024.07 - 2024.08 |

## Getting Started

### Install

```bash
cd frontend && npm install
cd ../backend && npm install
```

### Run

```bash
# backend
cd backend
npm start

# frontend
cd ../frontend
npm start
```
