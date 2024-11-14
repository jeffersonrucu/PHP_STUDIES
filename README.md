# Roadmap de Estudos - PHP Backend

Este roadmap foi criado para guiar o aprendizado e o desenvolvimento de habilidades essenciais para alcançar um nível sênior em desenvolvimento backend com PHP. Ele cobre desde fundamentos básicos até tópicos avançados, práticas de segurança, arquitetura de software e ferramentas de DevOps.

## Sumário

- [Fundamentos da Internet](#fundamentos-da-internet)
- [Fundamentos de PHP](#fundamentos-de-php)
- [Programação Orientada a Objetos (OOP) em PHP](#programação-orientada-a-objetos-oop-em-php)
- [Manipulação de Strings e Arrays](#manipulação-de-strings-e-arrays)
- [Erros e Exceções](#erros-e-exceções)
- [Interação com Banco de Dados (SQL e ORM)](#interação-com-banco-de-dados-sql-e-orm)
- [Manipulação de Arquivos e Sistema de Arquivos](#manipulação-de-arquivos-e-sistema-de-arquivos)
- [Segurança em PHP](#segurança-em-php)
- [Sessões e Cookies](#sessões-e-cookies)
- [Web Services e APIs](#web-services-e-apis)
- [Frameworks PHP](#frameworks-php)
- [Controle de Versão com Git](#controle-de-versão-com-git)
- [Testes e Qualidade de Código](#testes-e-qualidade-de-código)
- [Comunicação Assíncrona e Tempo Real](#comunicação-assíncrona-e-tempo-real)
- [Desempenho e Otimização](#desempenho-e-otimização)
- [Arquitetura de Software](#arquitetura-de-software)
- [NoSQL e Bancos de Dados Não Relacionais](#nosql-e-bancos-de-dados-não-relacionais)
- [DevOps e Containers](#devops-e-containers)
- [Escalabilidade e Otimização de Performance](#escalabilidade-e-otimização-de-performance)
- [Mensageria e Filas](#mensageria-e-filas)

---

## Fundamentos da Internet
- [ ] Como a Internet funciona.
- [ ] Protocolo HTTP e suas especificações (métodos, cabeçalhos, status).
- [ ] Como os navegadores funcionam.
- [ ] DNS e resolução de domínios.
- [ ] Conceitos de domínio e hospedagem.

## Fundamentos de PHP
- [x] Sintaxe básica e estrutura da linguagem.
- [ ] Variáveis e tipos de dados.
- [ ] Operadores e expressões.
- [ ] Estruturas de controle (condicionais, loops).
- [ ] Funções e escopo de variáveis.
- [ ] Manipulação de arquivos e importação de scripts externos.
- [ ] Gerenciamento de memória em PHP e coleta de lixo.

## Programação Orientada a Objetos (OOP) em PHP
- [ ] Classes, objetos, propriedades e métodos.
- [ ] Construtores e destrutores.
- [ ] Princípios: herança, polimorfismo, encapsulamento e abstração.
- [ ] Interfaces e traits.
- [ ] Namespaces e autoloading (PSR-4).
- [ ] Design Patterns (ex.: Singleton, Factory, Observer, Strategy, Adapter).

## Manipulação de Strings e Arrays
- [ ] Funções para manipulação de strings e expressões regulares (Regex).
- [ ] Arrays, incluindo multidimensionais e métodos de ordenação.
- [ ] Manipulação avançada de arrays.

## Erros e Exceções
- [ ] Tipos de erros e hierarquia.
- [ ] Tratamento de exceções e boas práticas de manipulação de erros.
- [ ] Exceções personalizadas.

## Interação com Banco de Dados (SQL e ORM)
- [ ] Conexão com bancos de dados relacionais (ex.: MySQL).
- [ ] Consultas preparadas e segurança contra injeção SQL.
- [ ] Transações e controle de concorrência.
- [ ] ORM (Doctrine, Eloquent) e suas vantagens e limitações.
- [ ] Otimização de consultas e índices (B-Trees, índices compostos).

## Manipulação de Arquivos e Sistema de Arquivos
- [ ] Criação, leitura, atualização e exclusão de arquivos.
- [ ] Hierarquia de diretórios e manipulação de sistema de arquivos.
- [ ] Permissões de arquivos e práticas de segurança.

## Segurança em PHP
- [ ] Validação e sanitização de dados.
- [ ] Proteção contra XSS, CSRF, SQL Injection e outras vulnerabilidades comuns.
- [ ] Criptografia e hashing de dados (bcrypt, scrypt).
- [ ] Gerenciamento seguro de sessões e autenticação.
- [ ] Conhecimento sobre OWASP Top 10 e práticas recomendadas.

## Sessões e Cookies
- [ ] Gerenciamento de sessões e configurações de segurança.
- [ ] Criação, leitura e exclusão de cookies.
- [ ] Segurança de sessões e controle de expiramento.

## Web Services e APIs
- [ ] Estrutura e princípios de APIs RESTful.
- [ ] Autenticação e autorização (OAuth, JWT).
- [ ] Princípios de design de APIs (ex.: HATEOAS).
- [ ] Formatos de dados para integração (JSON, XML).
- [ ] GraphQL e construção de APIs flexíveis.

## Frameworks PHP
- [ ] Conhecimento de frameworks como Laravel, Symfony.
- [ ] Arquitetura MVC e injeção de dependências.
- [ ] Middlewares e roteamento.
- [ ] Componentes comuns de frameworks (ORM, filas, eventos).

## Controle de Versão com Git
- [ ] Fundamentos do Git: commit, branch, merge.
- [ ] Fluxos de trabalho: Git Flow, GitHub Flow.
- [ ] Rebase interativo e limpeza de histórico de commits.
- [ ] Resolução de conflitos e Stash.
- [ ] Tags e versionamento semântico.

## Testes e Qualidade de Código
- [ ] Testes unitários, de integração e aceitação com PHPUnit.
- [ ] Cobertura de código e ferramentas de análise estática (PHPStan, PHPCS).
- [ ] TDD (Test-Driven Development) e suas práticas.
- [ ] Documentação de código e APIs (Swagger/OpenAPI).

## Comunicação Assíncrona e Tempo Real
- [ ] WebSockets e SSE para comunicação em tempo real.
- [ ] Filas de mensagens (ex.: RabbitMQ, Kafka) e processamento em background.
- [ ] Gerenciamento de jobs e workers.

## Desempenho e Otimização
- [ ] Cache (Redis, Memcached) para otimização de desempenho.
- [ ] Profiling e benchmarking para análise de performance.
- [ ] Otimização de consultas e código.

## Arquitetura de Software
- [ ] Padrões de design (ex.: Singleton, Factory, Observer).
- [ ] Domain-Driven Design (DDD) e conceitos de agregados, entidades e repositórios.
- [ ] Arquitetura de microsserviços vs. monolítica.
- [ ] Padrões arquiteturais: CQRS, Event Sourcing, SOA.

## NoSQL e Bancos de Dados Não Relacionais
- [ ] Conceitos e tipos de NoSQL (chave-valor, documento, coluna larga, grafos).
- [ ] Exemplos: MongoDB (documento), Redis (chave-valor).
- [ ] Sharding, replicação e consistência eventual.
- [ ] Comparação entre bancos de dados ACID e NoSQL.

## DevOps e Containers
- [ ] Conceitos de CI/CD e automação de deploys.
- [ ] Containers com Docker e orquestração com Kubernetes.
- [ ] Monitoramento e logging (ELK Stack, Prometheus, Grafana).
- [ ] Configuração e automação de ambientes de desenvolvimento, staging e produção.

## Escalabilidade e Otimização de Performance
- [ ] Estratégias de balanceamento de carga e failover.
- [ ] Caching avançado: técnicas de cache distribuído e cache em bancos de dados.
- [ ] Consistência de dados e replicação em sistemas distribuídos.
- [ ] Análise e otimização de desempenho para alta disponibilidade.

## Mensageria e Filas
- [ ] Filas de mensagens e processamento assíncrono (RabbitMQ, Kafka).
- [ ] Design de sistemas com filas para escalabilidade e resiliência.
- [ ] Conceitos de backpressure e controle de carga em filas.
