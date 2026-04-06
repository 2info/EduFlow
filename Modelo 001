# EduFlow
Interface primordial do aplicativo utilizando o V0: https://v0.app/chat/sistema-de-fluxo-escolar-iUyXbEoVjui?ref=U4CR5N

Documentação Técnica: Sistema de Gerenciamento de Fluxo Escolar

1. Visão Geral do Projeto

O Sistema de Gerenciamento de Fluxo Escolar é uma aplicação web desenvolvida para atender às necessidades operacionais de uma instituição de ensino. O software tem como foco o controle em tempo real da movimentação de alunos (entradas, saídas de sala e saídas da instituição), além de promover uma comunicação eficiente entre os diversos setores da escola, como professores, portaria, coordenação e direção.

2. Objetivos

2.1 Objetivo Geral

Desenvolver um software funcional e organizado que possibilite o controle do fluxo diário de alunos dentro da escola, garantindo visibilidade imediata das movimentações para todos os servidores autorizados.

2.2 Objetivos Específicos

Permitir o registro de saída de alunos da sala de aula.

Permitir o registro de entrada e saída do aluno da instituição de ensino.

Informar automaticamente os outros setores da escola sobre essas movimentações através de notificações.

Manter um histórico diário detalhado de eventos.

Diferenciar funcionalidades e permissões de acordo com o cargo do usuário logado.

3. Arquitetura e Tecnologias Utilizadas

O projeto adota uma arquitetura de serviços dividida entre Frontend e Backend:

Frontend: Desenvolvido em Next.js 16 (React, HTML, CSS, JavaScript). Responsável pelas interfaces de usuário, rotas, painéis interativos e consumo da API.

Backend: Desenvolvido em Python com FastAPI. Responsável pela lógica de negócios, endpoints da API, autenticação e gerenciamento do banco de dados.

Banco de Dados: Utiliza armazenamento em memória para fins de demonstração (podendo ser expandido para SQL/NoSQL no ambiente de produção).

4. Estrutura do Projeto

O sistema está organizado nos seguintes diretórios/serviços:

Backend (/backend/main.py)

API completa que provê as rotas da aplicação (ex: /api/*).

Sistema de autenticação.

CRUD (Criação, Leitura, Atualização e Exclusão) de alunos, movimentações e notificações.

Validação e sistema de permissões baseados em cargo (Role-based Access Control).

Frontend (/frontend/)

Mapeado para a rota raiz (/).

Componentização do layout escolar com estilização CSS apropriada.

Páginas estruturadas para o Dashboard e demais ferramentas administrativas.

5. Módulos e Funcionalidades Principais

Página de Login: Sistema de autenticação para controle de acesso dos funcionários.

Dashboard: Painel principal com estatísticas em tempo real, indicando quantitativos de alunos fora da sala ou fora da escola.

Alunos: Módulo para listagem, cadastro de novos alunos e atalho para registro de movimentações.

Movimentações: Tela dedicada ao registro e acompanhamento em tempo real do fluxo (ida ao banheiro, coordenação, saída antecipada, etc).

Histórico: Visualização completa e consolidada de todas as movimentações, com filtros de busca e opção de exportação de dados para o formato CSV.

Notificações: Central de alertas automáticos. Dispara avisos para a coordenação/direção quando um evento importante ocorre (ex: saída de aluno da escola).

Usuários: Módulo exclusivo para a Direção realizar o cadastro e gerenciamento dos funcionários da escola.

6. Perfis de Usuário e Permissões (RBAC)

O acesso e as funcionalidades são liberados de acordo com a função exercida pelo colaborador:

Cargo / Perfil

Nível de Permissão

Funcionalidades Liberadas

Professor

Básico

Registrar saída e retorno do aluno da sala de aula.

Porteiro

Básico

Registrar entrada e saída do aluno das dependências da escola.

Coordenador

Intermediário

Todas as permissões acima + visualizar Histórico + cadastrar e editar Alunos.

Direção

Administrador

Acesso total a todos os módulos + gerenciamento de Usuários (funcionários).

7. Credenciais de Demonstração (Ambiente de Teste)

Para fins de validação do sistema, os seguintes usuários de teste estão pré-configurados:

Direção: - Login: admin

Senha: admin123

Professor: - Login: professor1

Senha: prof123

Porteiro: - Login: porteiro1

Senha: port123

Coordenador: - Login: coord1

Senha: coord123

Documentação gerada com base no escopo e código-fonte do ambiente v0.
