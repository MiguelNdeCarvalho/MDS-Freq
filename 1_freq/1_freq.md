# 1ª Frequência de MDS

## Tópicos

- [Processos de Software (1º PowerPoint)](#processos-de-software)
  - [Modelos de Processos de Software](#modelos-de-processos-de-software)
    - [Modelo Waterfall (Cascata)](#modelo-waterfall-cascata)
      - [Etapas](#-etapas-waterfall)
      - [Desvantagens](#-desvantagens-waterfall)
      - [Problemas](#-problemas-waterfall)
      - [Utilização](#-utilizacao-waterfall)
    - [Modelo Incremental](#modelo-incremental)
      - [Vantagens](#-vantagens-incremental)
      - [Problemas](#-problemas-incremental)
      - [Integração e Configuração](#-integracao-e-configuracao-incremental)
      - [Tipos de componentes disponiveis](#-tipos-de-componentes-disponiveis-incremental)
    - [Modelo Baseado em reutilizações](#modelo-baseados-em-reutilizacao)
      - [Integração e configuração](#integracao-e-configuracao)
        - [Etapas do processo](#-etapas-do-processo)
        - [Vantagens](#-vantagens)
        - [Desvantagens](#-desvantagens)

## Processos de Software

- Conjunto de atividades usado para desenvolver software.

### Modelos de Processos de Software

- Modelo Waterfall (cascata)
- Modelo Incremental
- Integração e configuração

#### Modelo Waterfall (Cascata)

**[`^        para cima        ^`](#)**

- Baseado em planos.

![waterfall](imgs/waterfall.png)

##### ->Etapas Waterfall

- Análise e especificações de requísitos;
- Desenho do software;
- Implementação e testes unitários;
- Integração e testes de Sistema;
- Operação e manutenção.

##### ->Desvantagens Waterfall

- Dificuldade em incluir alterações depois de dar início ao

##### ->Problemas Waterfall

- Divisão inflexível do projeto em diferentes etapas;
- Dificulta a resposta a alteração de requisitos;
- Os requisitos devem se bem conhecidos;
- Poucos sistemas tem requisitos estáveis.

##### ->Utilizacao Waterfall

- Para sistemas grandes;
- Desenvolvido para equipas grandes.

#### Modelo Incremental

**[`^        para cima        ^`](#)**

![incremental](imgs/incremental.png)

##### ->Vantagens Incremental

- Custos para incluir alterações de requisitos é reduzido;
  - Menos análise e documentação.
- Mais fácil obter feedback do client relativo ao desenvolvimento que está a ser feito
  - Os clientes podem analisar demos do software e perceber o que já se encontra implementado.
- Entrega e deployment mais rápido de software utilizável.

##### ->Problemas Incremental

- Processo não é visível
  - Difícil medir o progresso.
    - Software desenvolvido de forma rápida.
- Estrutura do software degrada-se a cada incremento
  - Incorporar novas funcionalidades torna-se cada vez mais difícil

##### ->Integracao e Configuracao Incremental

- Baseado na utilização do software;
- Elementos reutilizáveis podem ser configuráveis.

##### ->Tipos de componentes disponiveis Incremental

- Web services;
- Coleções de objetos.

#### Modelo baseados em reutilizacao

**[`^        para cima        ^`](#)**

![reutilizacao](imgs/reutilizacao.png)

##### Integracao e configuracao

###### ->Etapas do Processo

- Especificação de requísitos;
- Pesquisa e análise de software;
- Alteração / Adaptação de requísitos;
- Configuraçãp das aplicações do sistema;
- Adaptação e integração de componentes

###### ->Vantagens

- Custos e riscos reduzidos;
  - Menos software é criado de raiz.
- Enregas e deployments do sistema mais rápido.

###### ->Desvantagens

- Compromissos com os requisitos;
- Não existe controle sobre a evolução dos componentes reutilizados.

**[`^        para cima        ^`](#)**

