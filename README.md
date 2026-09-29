# Showcase — Módulo de Hospedagem para Perfex CRM

## Sobre o projeto

Módulo desenvolvido para o Perfex CRM que adiciona um sistema de controle de domínios e contas de hospedagem por cliente, com alerta de vencimento e renovação rápida — funcionalidade que não existe nativamente no sistema.

Desenvolvido com apoio de inteligência artificial (Claude, da Anthropic), sob minha supervisão, acompanhamento e conhecimento técnico para definição das funcionalidades e aplicação no sistema.

## Tabela resumo

| Repositório | Descrição | Tecnologias Utilizadas |
|---|---|---|
| [perfex-hosting-manager](https://github.com/SEU-USUARIO/perfex-hosting-manager) | Módulo que controla domínios e contas de hospedagem por cliente, com alerta de vencimento e renovação rápida. | PHP (CodeIgniter 3), MySQL, JavaScript, jQuery |

## Funcionalidades

- Cadastro de domínios (registrador, data de registro, vencimento, renovação automática) vinculado a um cliente
- Cadastro de contas de hospedagem (plano, servidor, usuário, valor, vencimento) vinculado a um cliente
- Listagem com indicador visual colorido de vencimento (verde / amarelo / vermelho)
- Renovação rápida de vencimento com um clique (+1 ano)
- Botão de acesso rápido à hospedagem de um cliente, direto no perfil dele
- Alerta automático de vencimento (30, 15, 7 e 1 dia antes), via notificação interna no sistema

## Sobre o Perfex CRM

O [Perfex CRM](https://www.perfexcrm.com/) é um sistema de gestão de relacionamento com clientes (CRM) comercial, construído em PHP (CodeIgniter 3), usado como base para o desenvolvimento deste módulo.

## Metodologia

O módulo foi desenvolvido como uma extensão independente do sistema (seguindo o padrão de módulos do Perfex CRM), sem alterar nenhum arquivo do núcleo da aplicação. O processo envolveu:

- Definição dos requisitos e funcionalidades
- Desenvolvimento assistido por IA (Claude, Anthropic)
- Criação de tabelas próprias no banco de dados
- Testes em ambiente de produção real (hospedagem Hostinger)
- Depuração e correção de erros com base em logs do servidor
- Documentação de instalação e uso
