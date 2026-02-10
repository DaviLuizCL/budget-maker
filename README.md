# Orcamenteiro

Orcamenteiro é um fazedor de orçamento Open Source, simples e extensível, pensado para ajudar pessoas e pequenas empresas a criar, organizar e exportar orçamentos de forma eficiente.

**Status:** Projeto inicial — backend completo em Django e frontend em React.

## Visão geral

Orcamenteiro permite criar orçamentos detalhados com itens, categorias, impostos e descontos, gerar relatórios e exportar PDFs. O objetivo é oferecer uma solução aberta e colaborativa para gestão de orçamentos.

## Principais funcionalidades (planejadas)
- Criar, editar e apagar orçamentos
- Gerenciar itens e categorias
- Autenticação de usuários e permissões básicas
- Geração de relatórios e exportação para PDF/CSV
- API REST para integração com outros serviços

## Arquitetura e stack
- **Backend:** Django (Django REST Framework para a API)
- **Frontend:** React (SPA consumindo a API REST)
- **Banco de dados:** PostgreSQL (recomendado)

## Instalação (resumo)

Backend (exemplo rápido):

1. Criar e ativar um ambiente virtual Python
2. Instalar dependências: `pip install -r requirements.txt`
3. Rodar migrações: `python manage.py migrate`
4. Iniciar servidor: `python manage.py runserver`

Frontend (exemplo rápido):

1. Entrar na pasta do frontend
2. Instalar dependências: `npm install` ou `yarn`
3. Iniciar: `npm start` ou `yarn start`

## Contribuição

Contribuições são bem-vindas! Abra issues para discutir novas funcionalidades ou correções e envie pull requests seguindo as convenções do projeto.

## Licença

Este projeto é licenciado sob a GNU General Public License v3.0 (GPL-3.0). Veja o arquivo de licença para mais detalhes.

---

Se quiser, eu posso também adicionar um arquivo `LICENSE` com o texto da GPL-3.0 ou criar exemplos iniciais de endpoints Django/React.
