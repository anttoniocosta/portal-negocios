# Arquitetura do Sistema

## Visão Geral
Arquitetura em três camadas:

1. Frontend (Next.js / React)
2. Backend (API Node.js)
3. Banco de Dados (PostgreSQL, Redis, Storage)

## Componentes
- Autenticação JWT
- API REST
- WebSocket para chat
- Storage de arquivos
- Cache Redis

## Infraestrutura
- Frontend: Vercel
- Backend: Railway ou AWS
- Banco: PostgreSQL
- Storage: S3 ou Cloudflare R2

## Boas práticas
- Clean Architecture
- Repository Pattern
- DTOs
- Testes automatizados