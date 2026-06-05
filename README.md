# Smart Voice Assistant — API Inteligente com Reconhecimento de Fala

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-Framework-6DB33F?style=flat)
![Docker](https://img.shields.io/badge/Docker-Infrastructure-2496ED?style=flat&logo=docker&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=flat)

API Inteligente com integração de inteligência artificial e reconhecimento de fala, desenvolvida como projeto prático para o Bootcamp Santander 2026 - Java Backend na plataforma DIO.

---

## Sobre o Projeto

O Smart Voice Assistant é uma API REST projetada para orquestrar fluxos de inteligência artificial, integrando o ecossistema Spring Boot com recursos de processamento de áudio e modelos de linguagem (LLMs). O projeto utiliza o Antigravity como agente inteligente para interpretar comandos de voz, realizar transcrições (Audio-to-Text), sintetizar respostas (Text-to-Speech) e executar funções de negócio via Tool Calling.

---

## Conceitos e Tecnologias Aplicadas

| Módulo / Conceito | Aplicação |
|---|---|
| **Spring AI & LLMs** | Integração e configuração do ecossistema de inteligência artificial com ChatModel. |
| **ChatClient & Contexto** | Gerenciamento de fluência, memória e contexto das interações com o agente. |
| **Tool Calling** | Capacidade da IA de identificar e executar funções reais no sistema. |
| **Transcription API** | Componente responsável por transformar áudio em texto (Speech-to-Text). |
| **Speech API** | Componente de síntese de voz (Text-to-Speech) para resposta do assistente. |
| **Infraestrutura** | Persistência de dados e serviços auxiliares configurados via Docker. |
| **Exposição REST** | Implementação de endpoints e controllers para processamento dos fluxos. |

---


*Desenvolvido por [Deduv](https://github.com/Deduv) · Graduando em Engenharia de Softwar*
