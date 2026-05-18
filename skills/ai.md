# AI-native разработка и AI Engineering

## LLM и агенты (на проде)

- **Multi-agent systems** — построение Avi, multi-agent buyer assistant в Avito (миллионы пользователей, 0.3% error rate, p75 8s).
- **LLM Inference** — продакшн-инфра под нагрузку classifieds (50M+ MAU).
- **RAG** — retrieval-augmented generation как часть AI-инфры Avito.
- **Evals** — система оценки качества LLM-ответов.
- **Agent SDK** — внутренний SDK для продуктовых команд.
- **LLM Gateway** — единая точка доступа к моделям для всех потребителей внутри компании.

## AI-инструменты в работе

- Claude Code как основной AI-партнёр разработки.
- AI-native подход: агенты пишут код, контроль через DoD, бизнес-кейсы и спецификации.

## Промптинг и контекст-менеджмент

_TBD — добавить инсайты из практики LLM Platform._

## Построение AI-продуктов

- Multi-agent системам нужно то же, что и обычному backend: state management, retries, observability. Плюс LLM non-determinism сверху.
- Перенос распределённого backend-опыта (Kubernetes, high-load) на LLM-инфраструктуру.
