# Desafio Backend - Plataforma de Negociação de Veículos
Um cliente de uma concessionária de veículos entrou em contato para criar um sistema com o objetivo de coletar diversas informações sobre veículos. Basicamente, seria um sistema que conteria anúncios de compra e venda de veículos, além da comparação de preços e histórico da Tabela FIPE.
Em resumo, a plataforma deve permitir a negociação de veículos, contendo o máximo de informações possíveis para compra e venda, e pesquisa de preços e histórico da Tabela FIPE. O primeiro passo do projeto será construir uma estrutura inicial com as seguintes funcionalidades:

## Requisitos do Projeto
1. **CRUDs**: CRUD para informações do veículo e para informações relacionadas à Tabela FIPE.
2. **Controle de Acesso (ACL)**: Somente usuários autorizados (administradores) poderão cadastrar informações do veículo e da Tabela FIPE. Deve ser implementado um sistema de permissões granular, permitindo diferentes níveis de acesso.
3. **Listagem dos veículos**: lista todos os veículos disponíveis para venda.
4. **Comparação de preços**: Compar o veículo selecionado com a Tabela FIPE, incluindo um campo com o cálculo de diferença de preço.
5. **Autenticação via JWT**: Implementar uma solução segura para acesso à API.
6. **Aplicar conceitos de Domain-Driven Design (DDD)**: Estruturar o sistema em módulos de domínio, como "Veículos", "Tabela FIPE" e "Usuários", aplicando agregados, entidades e repositórios.
7. **Utilização de DTOs (Data Transfer Objects)**: Criar DTOs para retorno e entrada de dados, garantindo uma melhor separação de responsabilidades.
8. **Queries personalizadas**: Criar consultas otimizadas para listagem de veículos, permitindo filtros por preço, ano e comparação com a tabela FIPE.
9. **Pesquisa de mercado e benchmarks**: Antes da implementação, analisar soluções similares do mercado (ex.: OLX, Webmotors) e documentar as melhores práticas adotadas.


## Ferramentas e Tecnologias Utilizadas
- Linguagem: PHP
- Framework: Symfony
- Servidor Web: Nginx
- Banco de Dados: MySQL
- Arquitetura e comunicação: API RESTful
- Containerização: Docker
- Segurança: JWT para autenticação
- ORM: Doctrine
- Documentação: Postman, API Dog e Insomnia
- Controle de versão: Git

## Entrega do Desafio envolve
1. **Código-fonte do projeto** hospedado em um repositório Git privado.
2. **Documentação da API**, explicando os endpoints com clareza, fluxos de autenticação e exemplos de uso.
3. **Instruções de instalação** e execução do ambiente utilizando Docker.
4. **Qualidade do código**: Programação orientada a objetos (OOP) é obrigatória; padrões de projeto e SOLID são desejáveis.
5. **Segurança**: Implementação correta de autenticação e controle de acesso. (JWT e Voters: https://symfony.com/doc/current/security/voters.html).
6. **Desempenho**: Eficiência das queries e arquitetura adotada.
7. **Uso adequado do Git**: Avaliação de Gitflow e commits semânticos.
