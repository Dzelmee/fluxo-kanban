# movo.

O foco aqui foi visualizar o andamento das tarefas e permitir a movimentação dos registros entre etapas.

É um projeto de portfólio voltado a **tarefas e etapas de trabalho**. Trabalhei tanto na apresentação visual quanto nas operações de cadastro e consulta dos dados.

## O que implementei

- Cadastro, edição e exclusão de registros, com validação no servidor.
- Busca e formulários para trabalhar com os dados.
- Indicadores calculados a partir dos registros existentes.
- Interface responsiva, tema claro/escuro e animações com suporte a redução de movimento.
- Movimentação de tarefas entre etapas do quadro.

## Tecnologias

HTML, CSS, JavaScript com ES Modules e Node.js usando o módulo HTTP nativo. Os dados são mantidos em um arquivo JSON local.

## Executar localmente

```bash
npm test
npm start
```

A aplicação abre em `http://localhost:3000`. É possível alterar a porta pela variável `PORT`.

## O que ainda falta para produção

Este é um projeto demonstrativo, sem autenticação, controle de acesso por usuário ou banco de dados de produção. Os dados são armazenados localmente em JSON; não há suporte garantido a múltiplas instâncias ou concorrência. As imagens externas dependem de conexão com a internet.

## Imagens

Imagens utilizadas do Unsplash, conforme a [licença da plataforma](https://unsplash.com/license).

Referências usadas neste projeto:
- https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=1100&q=85.
