# 🚀 Real-Time Sentiment Analysis API

A production-grade REST API for sentiment analysis of product reviews, built with FastAPI and deployed with MLOps best practices. This system processes customer reviews in real-time, providing sentiment scores with sub-150ms latency at scale.

[![Live API](https://img.shields.io/badge/API-Live-success)](https://your-api-url.com)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104.1-009688.svg)](https://fastapi.tiangolo.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Architecture](#architecture)
- [Performance Metrics](#performance-metrics)
- [Quick Start](#quick-start)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)
- [Monitoring](#monitoring)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Development](#development)
- [Future Enhancements](#future-enhancements)

## 🎯 Overview

This project demonstrates end-to-end machine learning engineering skills by building a scalable sentiment analysis system that goes beyond Jupyter notebooks. It showcases:

- ✅ Production-ready ML model deployment
- ✅ Cloud infrastructure with auto-scaling
- ✅ Real-time monitoring and observability
- ✅ Performance optimization (ONNX Runtime)
- ✅ CI/CD pipeline automation
- ✅ MLOps best practices

**Business Use Case:** E-commerce companies, SaaS platforms, and customer support teams can integrate this API to automatically analyze customer feedback sentiment at scale.

## ✨ Key Features

### Core Functionality
- **Single & Batch Prediction**: Analyze one review or thousands simultaneously
- **Multi-class Sentiment**: Positive, Negative, Neutral with confidence scores
- **Fast Response Time**: 95th percentile latency < 150ms
- **Smart Caching**: Redis-based caching for frequent queries (3x speedup)

### Production Features
- **Async Processing**: Handle high concurrent loads efficiently
- **Input Validation**: Pydantic models ensure data integrity
- **Error Handling**: Comprehensive exception management
- **Rate Limiting**: Prevent API abuse (100 requests/minute per user)
- **Health Checks**: Kubernetes-ready liveness/readiness probes
- **API Versioning**: Backwards compatibility support

### MLOps Pipeline
- **Model Monitoring**: Track prediction distribution and confidence scores
- **Drift Detection**: Alert on input data distribution changes
- **Performance Tracking**: Real-time latency and throughput metrics
- **Automated CI/CD**: GitHub Actions for testing and deployment
- **Containerization**: Docker for consistent environments

## 🏗️ Architecture
