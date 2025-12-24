# Aleksandr Mordvinov

<div align="center">

**AI Architect & Product Builder**  
Building decision-making AI systems from noisy real-world data

[Portfolio](https://scanovich.ai) • [Telegram](https://t.me/ScanovichAI) • [Email](mailto:iamfuyoh@gmail.com) • [🇷🇺 Русская версия](#русская-версия)

</div>

---

## Overview

I architect and build AI systems that transform business challenges into measurable outcomes. My work focuses on production-ready solutions that deliver concrete ROI through automation, intelligent analysis, and scalable infrastructure.

**Core Expertise:**
- **Business AI Systems** — Production-ready agents, LLM applications, and ML pipelines
- **Healthcare AI** — Medical imaging analysis, radiology assistants, DICOM processing
- **Voice & Audio AI** — ASR, TTS, and voice-to-text systems with privacy-first approach
- **System Architecture** — Scalable, maintainable infrastructure from concept to deployment

---

## Key Metrics

| Metric | Value |
|--------|-------|
| **MVP Delivery Time** | 24 hours |
| **Call Analysis Coverage** | 100% (vs. traditional 1-5%) |
| **Cost Savings (Call Analysis)** | $51,000/year |
| **Processing Time Reduction (GTD)** | 8 hours → 15 minutes |
| **Data Extraction Accuracy** | 95%+ |
| **Languages Supported** | 5 (Russian, English, Thai, Chinese, Spanish) |

---

## Featured Projects

### Healthcare & Medical AI

**[Scanovich.ai - MRI Radiology Assistant](https://github.com/FUYOH666/Scanovich.ai-MRI_radiology_assistant)**

Local AI assistant for radiologists in MRI centers. Automates medical report generation, reduces diagnostic errors through AI-assisted segmentation, and ensures patient data privacy through local deployment.

**Tech:** Python, MedSAM2, DICOM, Medical AI  
**Status:** MVP ready, seeking medical partners & investors

---

### Business Intelligence & Automation

**[MindTech-Platform](https://github.com/FUYOH666/MindTech-Platform)**

Objective assessment of counterparties through AI-powered business communication analysis. Provides protection from scammers, fraud detection, and unbiased talent evaluation for HR departments.

**Tech:** Python, FastAPI, vLLM, LLM, ASR, RAG  
**Status:** Open-core model available

**📰 Related Article:** [How AI helps identify scammers and hidden leaders in teams](https://vc.ru/workdays/2314109-kak-ii-pomogaet-vyyavit-moshennikov-i-skrytykh-liderov-v-komande)

---

#### Call Analysis System *(Private Repository)*

**Problem:** Call centers struggle with quality control — manually reviewing calls is expensive and covers only 1-5% of conversations.

**Solution:** AI-powered system that analyzes 100% of calls automatically, extracting business entities, comparing against sales scripts, and generating actionable insights.

**Results:**
- $51,000/year saved in manual review costs
- 100% call coverage vs. traditional 1-5% sampling
- Real-time insights for immediate quality improvement

**Tech:** Python, FastAPI, FasterWhisper (GPU), vLLM, PostgreSQL  
**Status:** Production-ready

**📰 Related Article:** [Call center analysis automation with AI](https://vc.ru/ai/2303058-avtomatizatsiya-analiza-zvonkov-v-call-tsentrah-s-pomoshchyu-ii)

---

#### Customs Declaration Automation (GTD) *(Private Repository)*

**Problem:** Customs brokers spend 6-8 hours manually filling out customs declarations, prone to errors and delays.

**Solution:** AI-powered system that automatically extracts data from invoices, packing lists, and contracts, determines TN VED codes using RAG, and generates valid GTD XML according to official XSD schema.

**Results:**
- 8 hours → 15 minutes processing time reduction
- 95%+ accuracy in data extraction and classification
- XSD-validated XML ensuring compliance

**Tech:** Python, OCR (Chandra), vLLM, RAG (Qdrant), XSD validation  
**Status:** Production-ready

**📰 Related Articles:**
- [AI assistant for customs declaration automation in EAEU](https://vc.ru/ai/2300507-ai-pomoshchnik-dlya-avtomatizatsii-tamozhennykh-deklaratsiy-v-eaes)
- [How AI helps with TN VED codes and customs declarations](https://vc.ru/ai/2609452-kak-ii-pomogaet-s-kodami-tn-ved-i-tamozhennymi-deklaratsiyami)

---

### Voice & Audio AI

**[VoiceToText](https://github.com/FUYOH666/VoiceToText)**

Free alternative to paid dictation services ($10-20/month savings). Fully offline and private — no data leaves your device. Optimized for Apple Silicon (M1/M2) with 8GB RAM.

**Tech:** Python, Whisper, MLX, Privacy-first  
**Status:** Production-ready

**📰 Related Articles:**
- [Free alternative to dictation for MacBook Air M1 8GB](https://vc.ru/apple/2316030-besplatnaya-alternativa-diktovkam-dlya-macbook-air-m1-8gb)
- [How to avoid SuperWhisper subscription and use free alternatives](https://vc.ru/apple/2314173-kak-izbezhat-podpiski-na-superwhisper-i-ispolzovat-besplatnye-alternativy)

---

**[ai-agent-tts](https://github.com/FUYOH666/ai-agent-tts)**

Low-latency voice AI agents for real-time customer interactions. Streaming ASR/TTS for natural conversations. Production-ready microservices architecture.

**Tech:** FastAPI, LangGraph, vLLM, F5-TTS, Streaming ASR  
**Status:** Production-ready

---

#### ASR Service *(Private Repository)*

High-performance ASR service for commercial applications, part of sales agent infrastructure.

**Tech:** FasterWhisper, GPU acceleration, FastAPI  
**Status:** Production-ready

---

### AI Sales Agents *(Private Repositories)*

**AI Sales Agent for WhatsApp** — Production-ready AI sales agent with RAG-powered knowledge base, supporting 5 languages (Russian, English, Thai, Chinese, Spanish), voice message processing, and intelligent conversation management.

**AI Sales Agent for Telegram** — Similar to WhatsApp agent, optimized for Telegram with MCP tools integration, profile-based configuration, and advanced security features.

**Vibe Residence AI Agent** — LLM-First real estate sales agent with long-term memory and personalization for property sales.

**Results:**
- 24/7 availability without additional staff costs
- Consistent quality across all languages
- Scalable to thousands of concurrent conversations

**Tech:** Python, vLLM (Qwen3-30B), RAG (Qdrant), WhatsApp/Telegram APIs, FasterWhisper  
**Status:** Production-ready, deployed in commercial projects

**📰 Related Article:** ["5-minute bot" vs. mature AI agent: how businesses can avoid confusing toys with infrastructure](https://vc.ru/money/2644261-vzroslyj-ai-agent-protiv-bota-za-5-minut)

---

### System Tools & Infrastructure

**[Cleaner-OS](https://github.com/FUYOH666/Cleaner-OS)** — Universal CLI tool for system cleanup and audit. Reclaims gigabytes of disk space from ML caches (Hugging Face, PyTorch, TensorFlow), identifies unused dependencies and security vulnerabilities.

**📰 Related Article:** [Creating system cleanup tool](https://vc.ru/dev/2317100-sozdanie-instrumenta-dlya-ochistki-sistemy)

**Tech:** Python 3.12, macOS/Linux  
**Status:** Active development

---

**[linux-defender](https://github.com/FUYOH666/linux-defender)** — Unified security management for Linux servers. Intrusion detection, ClamAV integration, Telegram notifications.

**📰 Related Article:** [Home server and security: Defender project](https://vc.ru/ai/2339520-domashnij-server-i-bezopasnost-proekt-defender)

**Tech:** Python, Linux, Security, ClamAV  
**Status:** Production-ready

---

**[voip-calls-downloader](https://github.com/FUYOH666/voip-calls-downloader)** — Automated call recording download from CloudPBX (Rostelecom, Svyaztransit). Saves hours of manual work for call center managers, enables automated call analysis workflows.

**📰 Related Article:** [Call recording download automation](https://vc.ru/dev/2319312-avtomatizatsiya-zagruzki-zapisei-zvonkov)

**Tech:** Python, CloudPBX API, CLI tools  
**Status:** Production-ready

---

### Business Applications

**[SiamStay](https://github.com/FUYOH666/SiamStay)** — Villa rental management platform for Thailand market. Automatic TM30 registration (immigration requirement), booking system, and payment integration.

**Tech:** Python 3.12, FastAPI, PostgreSQL  
**Status:** Production-ready

---

## Commercial Products & Services

### AI Sales Agents
Production-ready multilingual sales agents for WhatsApp and Telegram with RAG-powered knowledge bases. Support 5 languages, process voice messages, maintain conversation context, and integrate with company knowledge bases.

### Call Analysis Systems
AI-powered call analysis that processes 100% of calls automatically, extracts business entities, compares against sales scripts, and generates actionable insights for quality improvement.

### Customs Automation
AI-powered system for automating customs declaration (GTD) preparation. Automatically extracts data from documents, determines TN VED codes using RAG, and generates XSD-validated XML declarations.

### Voice AI Platform
Low-latency voice AI agents with streaming ASR/TTS for real-time customer interactions. Production-ready microservices architecture designed for high-volume deployments.

*These are private repositories. Contact me for commercial inquiries.*

---

## Articles & Publications

My articles demonstrate deep understanding of business problems and practical AI solutions:

**Business Automation:**
- [Call center analysis automation with AI](https://vc.ru/ai/2303058-avtomatizatsiya-analiza-zvonkov-v-call-tsentrah-s-pomoshchyu-ii) → Call Analysis System | $51,000/year saved, 100% coverage
- [AI assistant for customs declaration automation in EAEU](https://vc.ru/ai/2300507-ai-pomoshchnik-dlya-avtomatizatsii-tamozhennykh-deklaratsiy-v-eaes) → Customs Declaration Automation | 8 hours → 15 minutes
- [How AI helps with TN VED codes and customs declarations](https://vc.ru/ai/2609452-kak-ii-pomogaet-s-kodami-tn-ved-i-tamozhennymi-deklaratsiyami) → Customs Declaration Automation | Technical deep-dive
- ["5-minute bot" vs. mature AI agent](https://vc.ru/money/2644261-vzroslyj-ai-agent-protiv-bota-za-5-minut) → AI Sales Agents | Production-ready vs. demo solutions
- [How AI helps identify scammers and hidden leaders](https://vc.ru/workdays/2314109-kak-ii-pomogaet-vyyavit-moshennikov-i-skrytykh-liderov-v-komande) → MindTech-Platform | Business intelligence applications

**Voice & Audio:**
- [Free alternative to dictation for MacBook Air M1 8GB](https://vc.ru/apple/2316030-besplatnaya-alternativa-diktovkam-dlya-macbook-air-m1-8gb) → VoiceToText | Free alternative, $10-20/month savings
- [How to avoid SuperWhisper subscription and use free alternatives](https://vc.ru/apple/2314173-kak-izbezhat-podpiski-na-superwhisper-i-ispolzovat-besplatnye-alternativy) → VoiceToText | Cost-effective solutions
- [Voice AI assistant: quick solution for business](https://vc.ru/ai/2308203-golosovoj-ii-pomoschnik-bystroe-resheniye-dlya-biznesa) → Voice AI Platform | Business applications

**System Tools:**
- [Creating system cleanup tool](https://vc.ru/dev/2317100-sozdanie-instrumenta-dlya-ochistki-sistemy) → Cleaner-OS | ML cache management
- [Home server and security: Defender project](https://vc.ru/ai/2339520-domashnij-server-i-bezopasnost-proekt-defender) → linux-defender | Security automation
- [Call recording download automation](https://vc.ru/dev/2319312-avtomatizatsiya-zagruzki-zapisei-zvonkov) → voip-calls-downloader | Workflow automation

**Health & Productivity:**
- [Telegram bot for health on WHOOP data](https://vc.ru/ai/2597655-telegram-bot-dlya-zdorovya-na-dannykh-whoop) → whoop-telegram-bot-ai | Health data integration

---

## Consulting & Services

I offer paid business consultations and rapid MVP development. Ready to share my knowledge, energy, and resources to help people solve real business problems.

**Services:**
- **24-Hour MVP Development** — From concept to working prototype in 24 hours
- **Business AI Consulting** — Architecture reviews, solution design, ROI analysis
- **Technical Collaborations** — Complex AI/ML projects, system architecture
- **Mentoring** — Helping developers grow in AI/ML and system design
- **Co-founder Opportunities** — Especially in healthcare AI, business intelligence, or infrastructure

**Contact:**
- **Telegram:** [@ScanovichAI](https://t.me/ScanovichAI) *(Preferred)*
- **Email:** [iamfuyoh@gmail.com](mailto:iamfuyoh@gmail.com)
- **Portfolio:** [scanovich.ai](https://scanovich.ai)

---

## Technology Stack

Technologies are chosen based on business requirements, not trends. Every tool serves a specific purpose in delivering measurable value.

**Languages & Frameworks:** Python 3.12+ (Primary), TypeScript/Node.js, Shell/Bash

**AI/ML:** vLLM, GPT-OSS, LangChain, LangGraph, MedSAM2, DICOM processing, Whisper, FasterWhisper, TTS models, PyTorch, TensorFlow, MLX

**Infrastructure:** FastAPI, PostgreSQL, Redis, Docker, Kubernetes, Linux, macOS, Cloud platforms

**Architecture Patterns:** Microservices, Event-driven architecture, RAG (Retrieval-Augmented Generation), On-premise & hybrid deployments

---

## Engineering Philosophy

My engineering principles translate directly to business value:

- **One source of truth** → Predictability for business stakeholders
- **No hidden fallbacks** → Transparency and trust with clients
- **Reproducibility > clever hacks** → Scalable, maintainable solutions
- **RAG-first, zero-hallucination** → Reliable answers for business decisions

---

<a name="русская-версия"></a>
<details>
<summary><b>🇷🇺 Русская версия</b></summary>

## Обзор

Я проектирую и создаю AI-системы, которые превращают бизнес-задачи в измеримые результаты. Моя работа фокусируется на готовых к продакшену решениях, которые обеспечивают конкретный ROI через автоматизацию, интеллектуальный анализ и масштабируемую инфраструктуру.

**Основная экспертиза:**
- **Бизнес AI-системы** — Готовые к продакшену агенты, LLM-приложения и ML-пайплайны
- **Медицинский ИИ** — Анализ медицинских изображений, ассистенты радиологов, обработка DICOM
- **Голосовой и аудио ИИ** — ASR, TTS и системы преобразования речи в текст с подходом privacy-first
- **Системная архитектура** — Масштабируемая, поддерживаемая инфраструктура от концепции до развертывания

## Ключевые метрики

| Метрика | Значение |
|---------|----------|
| **Время доставки MVP** | 24 часа |
| **Охват анализа звонков** | 100% (против традиционных 1-5%) |
| **Экономия затрат (анализ звонков)** | $51,000/год |
| **Сокращение времени обработки (ГТД)** | 8 часов → 15 минут |
| **Точность извлечения данных** | 95%+ |
| **Поддерживаемые языки** | 5 (русский, английский, тайский, китайский, испанский) |

## Ключевые проекты

### Медицинский ИИ

**[Scanovich.ai - MRI Radiology Assistant](https://github.com/FUYOH666/Scanovich.ai-MRI_radiology_assistant)**

Локальный AI-ассистент для радиологов в МРТ-центрах. Автоматизирует генерацию медицинских отчетов, снижает диагностические ошибки через AI-ассистированную сегментацию и обеспечивает конфиденциальность данных пациентов через локальное развертывание.

**Tech:** Python, MedSAM2, DICOM, Medical AI  
**Status:** MVP ready, seeking medical partners & investors

### Бизнес-аналитика и автоматизация

**[MindTech-Platform](https://github.com/FUYOH666/MindTech-Platform)**

Объективная оценка контрагентов через AI-анализ бизнес-коммуникаций. Обеспечивает защиту от мошенников, обнаружение мошенничества и беспристрастную оценку талантов для HR-отделов.

**Tech:** Python, FastAPI, vLLM, LLM, ASR, RAG  
**Status:** Open-core model available

**📰 Связанная статья:** [Как ИИ помогает выявить мошенников и скрытых лидеров в команде](https://vc.ru/workdays/2314109-kak-ii-pomogaet-vyyavit-moshennikov-i-skrytykh-liderov-v-komande)

#### Система анализа звонков *(Приватный репозиторий)*

**Проблема:** Колл-центры сталкиваются с проблемой контроля качества — ручной анализ звонков дорог и охватывает только 1-5% разговоров.

**Решение:** AI-система, которая автоматически анализирует 100% звонков, извлекает бизнес-сущности, сравнивает со скриптами продаж и генерирует практические инсайты.

**Результаты:**
- $51,000/год экономии на затратах ручного анализа
- 100% охват звонков против традиционной выборки 1-5%
- Инсайты в реальном времени для немедленного улучшения качества

**Tech:** Python, FastAPI, FasterWhisper (GPU), vLLM, PostgreSQL  
**Status:** Production-ready

**📰 Связанная статья:** [Автоматизация анализа звонков в call-центрах с помощью ИИ](https://vc.ru/ai/2303058-avtomatizatsiya-analiza-zvonkov-v-call-tsentrah-s-pomoshchyu-ii)

#### Автоматизация таможенных деклараций (ГТД) *(Приватный репозиторий)*

**Проблема:** Таможенные брокеры тратят 6-8 часов на ручное заполнение таможенных деклараций, подверженное ошибкам и задержкам.

**Решение:** AI-система, которая автоматически извлекает данные из инвойсов, упаковочных листов и контрактов, определяет коды ТН ВЭД с помощью RAG и генерирует валидный XML ГТД согласно официальной XSD схеме.

**Результаты:**
- 8 часов → 15 минут сокращение времени обработки
- 95%+ точность в извлечении данных и классификации
- Валидированный по XSD XML обеспечивающий соответствие требованиям

**Tech:** Python, OCR (Chandra), vLLM, RAG (Qdrant), XSD validation  
**Status:** Production-ready

**📰 Связанные статьи:**
- [AI-помощник для автоматизации таможенных деклараций в ЕАЭС](https://vc.ru/ai/2300507-ai-pomoshchnik-dlya-avtomatizatsii-tamozhennykh-deklaratsiy-v-eaes)
- [Как ИИ помогает с кодами ТН ВЭД и таможенными декларациями](https://vc.ru/ai/2609452-kak-ii-pomogaet-s-kodami-tn-ved-i-tamozhennymi-deklaratsiyami)

### Голосовой и аудио ИИ

**[VoiceToText](https://github.com/FUYOH666/VoiceToText)**

Бесплатная альтернатива платным сервисам диктовки (экономия $10-20/месяц). Полностью офлайн и приватно — данные не покидают ваше устройство. Оптимизировано для Apple Silicon (M1/M2) с 8GB RAM.

**Tech:** Python, Whisper, MLX, Privacy-first  
**Status:** Production-ready

**[ai-agent-tts](https://github.com/FUYOH666/ai-agent-tts)**

Низколатентные голосовые AI-агенты для взаимодействия с клиентами в реальном времени. Стриминговая ASR/TTS для естественных разговоров. Готовая к продакшену микросервисная архитектура.

**Tech:** FastAPI, LangGraph, vLLM, F5-TTS, Streaming ASR  
**Status:** Production-ready

### AI-агенты для продаж *(Приватные репозитории)*

**AI Sales Agent for WhatsApp** — Готовый к продакшену AI-агент продаж с RAG-базой знаний, поддержкой 5 языков (русский, английский, тайский, китайский, испанский), обработкой голосовых сообщений и интеллектуальным управлением диалогом.

**AI Sales Agent for Telegram** — Аналогично WhatsApp-агенту, оптимизирован для Telegram с интеграцией MCP-инструментов, профильной конфигурацией и расширенными функциями безопасности.

**Vibe Residence AI Agent** — LLM-First агент продаж недвижимости с долговременной памятью и персонализацией.

**Результаты:**
- Доступность 24/7 без дополнительных затрат на персонал
- Последовательное качество на всех языках
- Масштабируемость до тысяч одновременных разговоров

**Tech:** Python, vLLM (Qwen3-30B), RAG (Qdrant), WhatsApp/Telegram APIs, FasterWhisper  
**Status:** Production-ready, deployed in commercial projects

**📰 Связанная статья:** ["Бот за 5 минут" против взрослого AI-агента: как бизнесу не перепутать игрушку с инфраструктурой](https://vc.ru/money/2644261-vzroslyj-ai-agent-protiv-bota-za-5-minut)

### Системные инструменты и инфраструктура

**[Cleaner-OS](https://github.com/FUYOH666/Cleaner-OS)** — Универсальный CLI инструмент для очистки и аудита системы. Освобождает гигабайты дискового пространства от ML-кэшей (Hugging Face, PyTorch, TensorFlow), выявляет неиспользуемые зависимости и уязвимости безопасности.

**[linux-defender](https://github.com/FUYOH666/linux-defender)** — Унифицированное управление безопасностью для Linux-серверов. Обнаружение вторжений, интеграция с ClamAV, Telegram-уведомления.

**[voip-calls-downloader](https://github.com/FUYOH666/voip-calls-downloader)** — Автоматическая загрузка записей звонков из CloudPBX (Ростелеком, Связьтранзит). Экономит часы ручной работы для менеджеров колл-центров.

### Бизнес-приложения

**[SiamStay](https://github.com/FUYOH666/SiamStay)** — Платформа управления арендой вилл для рынка Таиланда. Автоматическая регистрация TM30 (требование иммиграции), система бронирования и интеграция платежей.

## Коммерческие продукты и услуги

### AI-агенты для продаж
Готовые к продакшену многоязычные агенты продаж для WhatsApp и Telegram с RAG-базами знаний. Поддержка 5 языков, обработка голосовых сообщений, поддержание контекста разговора.

### Системы анализа звонков
AI-анализ звонков, который автоматически обрабатывает 100% звонков, извлекает бизнес-сущности, сравнивает со скриптами продаж и генерирует практические инсайты для улучшения качества.

### Автоматизация таможенных операций
AI-система для автоматизации подготовки таможенных деклараций (ГТД). Автоматически извлекает данные из документов, определяет коды ТН ВЭД с помощью RAG и генерирует валидированные по XSD XML-декларации.

### Голосовая AI-платформа
Низколатентные голосовые AI-агенты со стриминговой ASR/TTS для взаимодействия с клиентами в реальном времени. Готовая к продакшену микросервисная архитектура, разработанная для высоконагруженных развертываний.

*Это приватные репозитории. Свяжитесь со мной для коммерческих запросов.*

## Статьи и публикации

Мои статьи демонстрируют глубокое понимание бизнес-проблем и практических AI-решений:

**Автоматизация бизнеса:**
- [Автоматизация анализа звонков в call-центрах с помощью ИИ](https://vc.ru/ai/2303058-avtomatizatsiya-analiza-zvonkov-v-call-tsentrah-s-pomoshchyu-ii) → Система анализа звонков | $51,000/год экономии, 100% охват
- [AI-помощник для автоматизации таможенных деклараций в ЕАЭС](https://vc.ru/ai/2300507-ai-pomoshchnik-dlya-avtomatizatsii-tamozhennykh-deklaratsiy-v-eaes) → Автоматизация таможенных деклараций | 8 часов → 15 минут
- [Как ИИ помогает с кодами ТН ВЭД и таможенными декларациями](https://vc.ru/ai/2609452-kak-ii-pomogaet-s-kodami-tn-ved-i-tamozhennymi-deklaratsiyami) → Автоматизация таможенных деклараций | Технический deep-dive
- ["Бот за 5 минут" против взрослого AI-агента](https://vc.ru/money/2644261-vzroslyj-ai-agent-protiv-bota-za-5-minut) → AI-агенты для продаж | Production-ready vs. demo решения
- [Как ИИ помогает выявить мошенников и скрытых лидеров](https://vc.ru/workdays/2314109-kak-ii-pomogaet-vyyavit-moshennikov-i-skrytykh-liderov-v-komande) → MindTech-Platform | Приложения бизнес-аналитики

**Голос и аудио:**
- [Бесплатная альтернатива диктовкам для MacBook Air M1 8GB](https://vc.ru/apple/2316030-besplatnaya-alternativa-diktovkam-dlya-macbook-air-m1-8gb) → VoiceToText | Бесплатная альтернатива, экономия $10-20/месяц
- [Как избежать подписки на SuperWhisper](https://vc.ru/apple/2314173-kak-izbezhat-podpiski-na-superwhisper-i-ispolzovat-besplatnye-alternativy) → VoiceToText | Экономически эффективные решения
- [Голосовой ИИ-помощник: быстрое решение для бизнеса](https://vc.ru/ai/2308203-golosovoj-ii-pomoschnik-bystroe-resheniye-dlya-biznesa) → Голосовая AI-платформа | Бизнес-приложения

**Системные инструменты:**
- [Создание инструмента для очистки системы](https://vc.ru/dev/2317100-sozdanie-instrumenta-dlya-ochistki-sistemy) → Cleaner-OS | Управление ML-кэшами
- [Домашний сервер и безопасность: проект Defender](https://vc.ru/ai/2339520-domashnij-server-i-bezopasnost-proekt-defender) → linux-defender | Автоматизация безопасности
- [Автоматизация загрузки записей звонков](https://vc.ru/dev/2319312-avtomatizatsiya-zagruzki-zapisei-zvonkov) → voip-calls-downloader | Автоматизация рабочих процессов

**Здоровье и продуктивность:**
- [Telegram-бот для здоровья на данных WHOOP](https://vc.ru/ai/2597655-telegram-bot-dlya-zdorovya-na-dannykh-whoop) → whoop-telegram-bot-ai | Интеграция данных о здоровье

## Консультации и услуги

Предлагаю платные бизнес-консультации и быструю разработку MVP. Готов делиться знаниями, энергией и ресурсами, чтобы помочь людям решать реальные бизнес-проблемы.

**Услуги:**
- **Разработка MVP за 24 часа** — От концепции до рабочего прототипа за 24 часа
- **Консультации по бизнес-ИИ** — Обзоры архитектуры, проектирование решений, анализ ROI
- **Техническое сотрудничество** — Сложные AI/ML проекты, системная архитектура
- **Менторство** — Помощь разработчикам в росте в AI/ML и системном дизайне
- **Возможности соосновательства** — Особенно в медицинском ИИ, бизнес-аналитике или инфраструктуре

**Контакты:**
- **Telegram:** [@ScanovichAI](https://t.me/ScanovichAI) *(Предпочтительно)*
- **Email:** [iamfuyoh@gmail.com](mailto:iamfuyoh@gmail.com)
- **Портфолио:** [scanovich.ai](https://scanovich.ai)

## Технологический стек

Технологии выбираются на основе бизнес-требований, а не трендов. Каждый инструмент служит конкретной цели в предоставлении измеримой ценности.

**Языки и фреймворки:** Python 3.12+ (Основной), TypeScript/Node.js, Shell/Bash

**AI/ML:** vLLM, GPT-OSS, LangChain, LangGraph, MedSAM2, обработка DICOM, Whisper, FasterWhisper, TTS модели, PyTorch, TensorFlow, MLX

**Инфраструктура:** FastAPI, PostgreSQL, Redis, Docker, Kubernetes, Linux, macOS, Cloud платформы

**Архитектурные паттерны:** Микросервисы, Event-driven архитектура, RAG (Retrieval-Augmented Generation), On-premise & hybrid развертывания

## Инженерная философия

Мои инженерные принципы напрямую переводятся в бизнес-ценность:

- **Один источник истины** → Предсказуемость для бизнес-стейкхолдеров
- **Никаких скрытых фоллбеков** → Прозрачность и доверие с клиентами
- **Воспроизводимость > умные хаки** → Масштабируемые, поддерживаемые решения
- **RAG-first, zero-hallucination** → Надежные ответы для бизнес-решений

</details>

---

<div align="center">

**Building the future of AI-powered decision-making systems**

</div>
