# A.N.N.A powered armor OS

## Introduction

This OS integrate A.N.N.A in armor as modular part

A.N.N.A : https://github.com/anna-ai-assistant

## Technologies

- Uplink :
  - Uplink to main instance of A.N.N.A, give access to librarian and other model as support
  - Uplink to track position in A.N.N.A system
- Database :
  - statistic : Database used to store statistic about system to be uploaded in Inspector for optimizing usage of armor module and track issues
- Libraries :
  - AiWrapper : Structured AI usage, use Langchain and Ollama
- AI :
  - Ollama : LLM for basic task
  - Whisper : To manage speak
  - Piper : To manage voice recognition
  - ...

## TODO

- Finishing a functional software featuring:
  - A.N.N.A uplink.
  - HUD.
  - Auto update.
  - System stats and issues tracking.
  - micro controller as slave module.
  - energy management
  - environnemental condition and mapping
  - position tracking
