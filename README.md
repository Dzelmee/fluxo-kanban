# movo. — Quadro de tarefas

O movo. nasceu da ideia de enxergar o andamento do trabalho sem precisar abrir cada tarefa. O quadro mostra as etapas e permite movimentar os registros conforme o trabalho avança.

## O que implementei

- Cadastro, edição, busca e exclusão de tarefas.
- Movimentação dos registros entre etapas do quadro.
- Validação no servidor e indicadores baseados nos dados existentes.
- Interface responsiva, temas claro/escuro e animações que respeitam movimento reduzido.

## Como executar

```bash
npm test
npm start
```

O servidor inicia em `http://localhost:3000`. Para usar outra porta, configure `PORT`.

## Tecnologias e armazenamento

Usei HTML, CSS e JavaScript com ES Modules no front-end. O servidor é feito em Node.js, usando o módulo HTTP nativo. Os registros ficam em um arquivo JSON local.

## Limitações

Esta é uma aplicação de demonstração, não um serviço pronto para produção. Ainda não há autenticação, permissões por usuário nem banco de dados de produção. O armazenamento em JSON também não foi pensado para várias instâncias simultâneas.

## Imagens

Fotografias do [Unsplash](https://unsplash.com/license):
- https://images.unsplash.com/photo-1497366754035-f200968a6e72?auto=format&fit=crop&w=1600&q=85
- https://images.unsplash.com/photo-1521737711867-e3b97375f902?auto=format&fit=crop&w=1100&q=85
