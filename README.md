# 📦orkBox - Sistema de Gestão Patrimonial

## Objetivo do Projeto🎯

O WorkBox é uma plataforma completa para gestão patrimonial, estoque e conformidade fiscal. Facilita o controle dos bens físicos, estoque e de documentos fiscais.

## Funcionalidades Principais

- Autenticação segura e controle hierárquico de usuários
- Cadastro único e detalhado de bens patrimoniais com status e depreciação
- Integração com SEFAZ e leitura automática das notas fiscais (XML NF-e, NFC-e)
- Relatórios e dashboards personalizáveis para análise de desempenho
- Auditoria de logs e conformidade com LGPD
- Interface responsiva para desktop e mobile


## Como Rodar o Projeto💾

### Pré-requisitos
- Node.js (recomendável versões mais recentes)
- Banco de dados PostgreSQL

### Passos para executar localmente

1. Clone o repositório:
2. Instale as dependências:
3. Configure o banco de dados:
- Crie as tabelas executando os scripts SQL
- Configure variáveis de ambiente no arquivo `.env` com as credenciais do banco
4. Execute as migrações e populadores (se houver):
- npm run migrate
- npm run seed
5. Inicie o servidor de desenvolvimento:
- npm run dev
6. Acesse a aplicação via navegador:
- http://localhost:3000

### Agora o Projeto já está rodando🌐
