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
- [Engenharia de requisitos (2º PowerPoint)](#processos-de-software)
  - [O que s]

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

## Engenharia de Requisitos

**[`^        para cima        ^`](#)**

### Requisitos

#### O que sao requisitos

- Descrições do sistema;
- Restrições do sistema;
- Identificados durante o processo de engenharia de requisitos.

#### Tipos de requisitos

- Requisitos do Utilizador
  - Frases escritas em língua natural;
  - Diagramas de serviços do sistema;
  - Restrições de utilização/operação;
  - Escritos para os clientes;

**Ex**: “O sistema deve gerar relatórios mensais com o custo dos medicamentos receitados por cada
clínica, durante o mês em questão”.

- Requisitos do Sistema
  - Documento estruturado;
  - Descrições detalhadas das funcionalidades do sistema e dos serviços;
  - Restrições de utilização/operação;
  - Define o que deve ser implementado;

**Ex**: “No último dia de cada mês, deve ser feito um gerado um relatório com todos os medicamentos
receitados, o seu custo e a clínica que os receitou.”

#### System stakeholders

- Qualquer pessoa
  - que esteja relacionada com o sistema;
  - que tenha algum interesse no sistema.

-Tipos de stakeholders
  - Utilizadores finais;
  - Gestores do sistema;
  - Donos do sistema;
  - Stakeholders externos;

#### Requisitos funcionais

- Descrevem as funcionalidades do sistema

- Dependem de:
  - Tipo de software;
  - Utilizadores do sistema;
  - Tipo do sistema onde o software vai ser usado.

- Requisitos funcionais de utilizador;
  - Descrições de alto-nível sobre o que o sistema deve fazer.
- Requisitos funcionais do sistema:
  - Descrição detalhada sobre os serviços do sistema

- Devem ser consistentes e “completos”;
- Completos, incluir todas as descrições;
-Consistentes, não existir conflitos ou contradições.

#### Requisitos nao funcionais

- Definem propriedades e restrições ao sistema.
  - **Ex:**