# Task Management Mobile
![React Native](https://img.shields.io/badge/React_Native-Mobile-blue)
![Expo](https://img.shields.io/badge/Expo-53-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
## Overview

This project is a full-stack task management system built with:

- Laravel REST API
- Next.js web frontend
- React Native mobile app

The system supports task CRUD operations, filtering, pagination, search, and task status management.

## Architecture Decisions

- Used Service Pattern in Laravel to separate business logic
- Used reusable components for maintainability
- Used Axios service layer for centralized API requests
- Used TypeScript for better type safety
- Used pagination to improve scalability
- Used debounced search for optimized API calls

## Future Improvements

- Authentication & authorization
- Drag and drop task management
- Real-time updates using WebSockets
- Offline support for mobile app
- Automated testing
- Docker support
- CI/CD pipeline

## Setup

npm install

npx expo start

## Features

- Task list
- Pull to refresh
- Mark completed
- API integration
- React Native + TypeScript
