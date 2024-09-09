# Documentação do Projeto SIMPAC

## Introdução

O SIMPAC (Simpósio de Pesquisa e Extensão da Univiçosa) é gerenciado pelo NUPEX (Núcleo de Apoio à Pesquisa e Extensão da Univiçosa), que enfrenta desafios na gestão manual de avaliações e na entrega eficiente dos resultados. Este projeto visa otimizar esses processos, criando uma aplicação que organiza projetos por curso de forma eficiente, resultando em menos trabalho repetitivo e maior agilidade nas entregas.

## Objetivos do Projeto

- Automatizar e agilizar a gestão de avaliações de projetos no SIMPAC.
- Organizar os projetos por curso, facilitando a consulta e análise.
- Reduzir o tempo de entrega dos resultados, eliminando etapas manuais.
- Minimizar erros e retrabalho para os organizadores.

## Tecnologias Utilizadas

- **PHP**: Backend e lógica de negócio.
- **JS (JavaScript)**: Interatividade e funcionalidade do frontend.
- **React**: Framework JavaScript para a construção de interfaces de usuário dinâmicas.
- **Symfony5**: Framework PHP para o gerenciamento de rotas, controllers e lógica da aplicação.
- **Banco de Dados**: MySQL/PostgreSQL (a definir), para armazenar informações relacionadas aos projetos, avaliações e usuários.
- **Figma**: Ferramenta de design utilizada para criar os protótipos da interface.

## Arquitetura do Sistema

O sistema será baseado em uma arquitetura MVC (Model-View-Controller) com Symfony5 gerenciando a parte de backend. O frontend será desenvolvido com React, consumindo APIs criadas pelo Symfony para comunicação com o banco de dados e gerenciamento de dados.

## Principais Componentes

- **Frontend**: Desenvolvido em React para criar uma interface amigável e interativa.
- **Backend**: Symfony5 atuará como o principal framework para lidar com rotas, controllers e lógica de backend.
- **Banco de Dados**: Tabelas para gerenciar usuários, cursos, projetos e avaliações.

## Banco de Dados

Até o momento, algumas tabelas foram criadas, representando as principais entidades do sistema:

- **Tabela de Usuários**: Informações dos organizadores e avaliadores.
- **Tabela de Cursos**: Lista de cursos envolvidos no SIMPAC.
- **Tabela de Projetos**: Dados dos projetos submetidos para avaliação.
- **Tabela de Avaliações**: Registra as avaliações feitas por curso/projeto.

### Tabelas Existentes

- **Usuários**: nome, email, função, senha.
- **Cursos**: nome do curso.
- **Simpósio**: data de início, data de término.
- **Trabalho novo**: protocolo, nome do trabalho, área de atuação, modelo, avaliador.
- **Área de atuação**: área (pesquisa, extensão, ensino).
- **Modelo avaliativo**: modelo (pôster, oral).
- **Avaliador**: nome, e-mail, telefone.

## Protótipos

Os primeiros protótipos da interface foram desenvolvidos no Figma. Eles mostram a estrutura inicial de páginas como:

- Página de Login
- Dashboard de Organizadores
- Formulário para Submissão de Projetos
- Página de Avaliações

## Próximos Passos

- Finalizar o design da interface no Figma.
- Implementar as funcionalidades do frontend utilizando React.
- Desenvolver as rotas de backend e lógica com Symfony5.
- Testar a integração entre o frontend e backend.
- Integrar o banco de dados conforme o exigido pelo sistema.

