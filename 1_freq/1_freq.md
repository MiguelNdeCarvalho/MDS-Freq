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
  - **Ex:** fiabilidade, tempo de resposta requisitos de storage, dispositivos de I/O, etc.
- Requisitos ssobre o processo de Software
  - **Ex:** uso de um IDE específico, de uma linguagem ou de um método de desenvolvimento
- Podem ser mais críticos que os funcionais
- Podem afetar o sistema de forma global

Tipos:

- Requisitos do produt
  - Requisitos que especificam qual o comportamento do sistema
- Requisitos organizacionais
  - Requisitos que resultam das politicas e procedimentos da organização/empresa
- Requisitos externos
  - Requisitos relacionados com factores externos ao sistema

## Processos Engenharia de Requisitos

- Variam dependendo de:
  - Domínio de aplicação;
  - Pessoas envolvidas;
  - Entidade que desenvolve os requisitos;

### Identificacao dos Requisitos

- Descoberta de requisitos;
- Trabalho conjunto da equipa técnica com os clientes por forma a descobrir:
  - o domínio da aplicação;
  - os serviços que devem ser fornecidos;
  - restrições de operação/utilização;
- Pode envolver todos os stakeholders:
  - Utilizadores finais;
  - Gestores;
  - Engenheiros envolvidos na manutenção

#### Problemas na Identificacao dos Requisitos

- Stakeholders não sabem o que realmente querem;
- Stakeholders expressam os requisitos nos seus termos próprios;
- Diferentes stakeholders podem ter requisitos com conflitos;

#### Processo de identificacao e analise de requisitos

1. Descoberta dos Requisitos
  - Interagir com todos os stakeholders por forma a descobrir os requisitos
  - Requisitos de domínio são também identificados
  - Fazer a distinção entre requisitos de utilizador e de sistema

2. Clarificação e organização dos requisitos
  - Agrupar requisitos relacionados
  - Organizá-los em conjuntos coerentes

3. Priotarizaçãp e negociação do requisitos
  - Atribuir prioridades
  - Resolver conflitos entre requisitos

4. Especificação de requisitos
  - Escrita dos requisitos

### Cenarios

- User story estruturada;
- Devem incluir:
  - Descrição da situação inicial (ou ponto de partida);
  - Descrição do fluxo normal de eventos;
  - Descrição do que pode correr mal;
  - Informação sobre outras atividades concorrentes;
  - Descrição do estado do sistema quando o cenário termina.

### Especificacao de requisitos

- Processo de escrever os requisitos
  - requisitos de sistema e de utilizador
  - documento de requisitos
- Os requisitos devem ser de fácil compreensão
- Os requisitos devem ser detalhados
- Os requisitos devem ser o mais completo possiveis

#### Formas de escrever os requisitos

- Em linguagem natural.
- De forma estruturada
- Com anotações gráficas
- Com especificações metemáticas

#### Requisitos e desenho do sistema

- Preferencialmente 
  - Especificam o que o sistema deve fazer;
  - Descreve como é feito.

- Na prática, requisitos e desenho são inseparáveis
  - A arquitetura do sistema pode ser desenhada para estruturar os requisitos

#### Especificação em língua natural

- Requisitos são escritos em língua natural, complementados com diagramas e tabelas;

- A linguagem natural é:
  - Expressiva
  - Intuitiva

#### Escrita dos requisitos – Guião

- “Criar” um formato standard para todos os requisitos;
- Usar linguagem de forma consistente:
  - Usar “deve” para requisitos obrigatórios
  - Usar “pode” para requisitos desejáveis
- Usar text highlight para identificar aspetos importantes do requisito
- Evitar termos técnicos;
- Explicar o porque do requisito

#### Problemas da Linguagem Natural

- Falta de clareza
- Confusão de requisitos, os requisitos funcionais e nao funcionais misturam-se entre si;
- Junção dos requisitos

#### Especificações estruturadas

- Abordagem para escrever requisitos:
  - Liberdade limitada para descrever os requisitos;
  - Escritos seguindo um padrao espeicfico.

- Funciona bem para alguns tipos de sistema

#### Espeicificações baseadas em formulários

- Definição da funcionalidade ou entidade;
- Descrição dos inputs e qual a sua origem;
- Descrição dos outputs e qual o seu destino;
- Informação sobre a dados/informação e outras entidades necessárias;
- Descrição das ações a serem tomadas;
- Pré e pós condições (se existirem);
- Efeitos secundários (se existirem);

#### Especificação tabular

- Usada para complementar a língua natural;
- Útil

#### Use Cases

- Tipo de cenários:
  - Fazem parte do UML

- Identificam:
  - Atores;
  - Numa interação com o sistema

- Modelo gráfico de alto nível:
  - Complementado com uma descrição tabular

- Diagrama de sequências (UML):
 Podem ser usados para detalhar os use cases;

#### Documentos de requisitos

- Documento oficial que indicia à equipa de desenvolvimento o que é esperado do sistema;
- Deve incluir a definição dos requisitos de utilizador bem como os requisitos do sistema;
- Deve dizer o que o sistema deve fazer

Formato: 
- Não existe um formato único
- Informação no documento de requisitos depende do tipo de sistema a ser desenvolvido e da
abordagem de desenvolvimento
- Sistemas desenvolvidos de forma incremental, tipicamente, têm um documento de requisitos
menos detalhado

- Existem alguns standards para o documento de requisitos
  - IEEE
  - Usados apenas a projetos grandes

#### Validação dos requisitos

- Demonstrar que os requisitos definem o sistema que se pretende implementar;

- Como validar
  - Validade dos requisitos;
  - Consistência;
  - Completude;
  - Realismo;
  - Verificabilidade;

#### Gestão dos requisitos

- Processo de gerir as alterações dos requisitos durante todo o processo
  - Aparecimento de novos requisitos;
  - Gerir dependências entre requisitos;

- Estabelecer um processo formal
  - efetuar alterações nos requisitos
  - estabelecer ligações entre requisitos