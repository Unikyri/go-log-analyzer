# go-log-analyzer
## 🧩 Problem

Servers can generate thousands of log entries per minute.
Manually inspecting these logs is impractical and does not scale,
making it difficult to understand the system’s behavior and health.


## 🎯 Goal

The goal of this project is to build a log analysis tool in Go that can
efficiently process large log files and provide insights into system health.

This project is designed as a hands-on exercise to practice Go fundamentals,
with a strong focus on concurrency and performance.


## 🚀 Why Go?

- High performance
- Native concurrency (goroutines and channels)
- Ideal for processing large volumes of data in parallel

## 🛠️ What this tool does

This project focuses on:

- Parsing structured log files
- Processing logs concurrently using goroutines and channels
- Aggregating metrics such as errors, warnings, and request counts
- Generating a system health summary

