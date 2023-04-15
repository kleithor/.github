# Kleithor

## Services

```mermaid
flowchart TB
  website(Website\nNextJS)
  logger-web(LoggerJS-Web\nReactJS)
  documentation(Documentation\nNextra/NextJS)
  backend(Backend\nExpressJS)
  pg[(Postgres)]
  redis[(Redis)]

  website <--- backend
  logger-web <--- backend
  backend<-->pg
  backend<-->redis
```
