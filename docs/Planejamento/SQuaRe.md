# **Desempenho — ISO/IEC 25010**

## Introdução

A norma internacional ISO/IEC 25010 define:

1. Um **modelo de qualidade em uso** com cinco características (algumas subdivididas), relacionadas ao **resultado da interação** entre usuário e sistema em um contexto específico.
2. Um **modelo de qualidade de produto** com oito características, que avaliam propriedades **estáticas do software** e **dinâmicas do sistema**.

Esse modelo é aplicável tanto a **sistemas humano-computador** quanto a **produtos de software isolados**.


## Eficiência de Desempenho

A **eficiência de desempenho** mede como o sistema utiliza recursos sob determinadas condições. Ela pode ser analisada de duas formas:

- **Interna**: analisa o comportamento do sistema durante testes ou operações simuladas.
- **Externa**: mede atributos como tempo de resposta e uso real de recursos durante operações reais.


## Subcaracterísticas do Desempenho

- **Utilização de Recursos**: uso de memória, CPU e outros recursos.
- **Capacidade**: quantidade máxima de usuários ou dados suportados.
- **Comportamento Temporal**: tempo para realizar operações e responder ao usuário.
- **Adaptação**: habilidade do sistema em manter eficiência mesmo com variações de carga ou contexto.


## Métricas Associadas

| Nome                        | Tipo                       | Descrição                                                                                  | Foco      |
|-----------------------------|----------------------------|--------------------------------------------------------------------------------------------|-----------|
| **Tempo de resposta**       | Comportamento temporal     | Período entre o comando e a primeira resposta. Ex: B - A                                   | Interno/Externo |
| **Utilização de memória**   | Utilização de recursos     | Espaço de memória necessário para executar uma tarefa. Ex: B / A                           | Interno/Externo |
| **Nº máximo de acessos**    | Capacidade                 | Quantidade máxima de usuários simultâneos. Ex: B em um intervalo de tempo A               | Interno/Externo |



## Aspectos Relevantes

| Subcaracterística     | Contextos de Aplicação                                                                 |
|-----------------------|-----------------------------------------------------------------------------------------|
| **Comportamento Temporal** | Jogos, videochamadas, sistemas de controle em tempo real (baixa latência).         |
| **Utilização de Recursos** | IoT, dispositivos móveis, servidores de alta disponibilidade.                      |
| **Capacidade**             | Plataformas em larga escala como e-commerces, redes sociais e soluções de Big Data.|


## Aplicação Prática

Foi realizada a avaliação da usabilidade de um aplicativo móvel de uma instituição financeira brasileira fictícia, o **Banco BAN**, com base nas normas **ISO/IEC 25010** e **ISO/IEC 25040**. A equipe mapeou funcionalidades prioritárias e propôs melhorias com base nas métricas e princípios estudados.

> Segundo a Febraban (2018), 50% dos investimentos em TI no setor bancário brasileiro em 2017 foram destinados a software, demonstrando a relevância da qualidade nesses sistemas.


## Reflexões dos Integrantes

### Mayara Alves

**Aprendizado**:
- Métricas associadas ao desempenho.
- Complexidade envolvida na avaliação de qualidade.
- Diretrizes da ISO para software.

**Dificuldades**:
- Conteúdo massivo.
- Acesso difícil e técnico à norma.

### Felipe Pedroza

**Aprendizado**:
- Importância das ISOs para padronizar processos.

**Dificuldades**:
- Encontrar artigos aplicáveis como base prática.

### Vinícius Mendes

**Aprendizado**:
- Como aplicar métricas na prática.
- Quais variáveis são relevantes na mensuração.

**Dificuldades**:
- Interpretar objetivos das normas.
- Aplicar medições em cenários reais.

### Philipe Barbosa

**Aprendizado**:
- Diversas características da qualidade de software.
- Impacto do desempenho na experiência do usuário.

**Dificuldades**:
- Linguagem técnica ou conteúdo simplificado demais.


## Percentual de Contribuição

| Nome                       | Matrícula    | Percentual | Atividade Desenvolvida                          |
|----------------------------|--------------|------------|-------------------------------------------------|
| Felipe Lopes Pedroza       | 231026330    | 20%        | Métricas Associadas / Aspectos Relevantes       |
| João Gabriel Carvalho      | 221022328    | 20%        | Exemplo de Aplicação Prática                    |
| Mayara Alves de Oliveira   | 200025058    | 20%        | Característica de Qualidade escolhida           |
| Philipe Barbosa de Morais  | 211062830    | 20%        | Subcaracterísticas                              |
| Vinícius Mendes Martins    | 211063265    | 20%        | Métricas Associadas / Aspectos Relevantes       |


> **Nota**: Esse conteúdo foi baseado na apresentação desenvolvida pelo Grupo sobre a característica de **Desempenho** segundo a norma **ISO/IEC 25010**. [📄 Acesse os slides](../assets/Grupo04_Desempenho.pdf)

## 📑 Histórico de Versão

| Versão | Data       | Descrição                                 | Autor                                   |
|--------|------------|-------------------------------------------|------------------------------------------|
| `1.0`  | 13/05/2025 | Criação da página do SQuaRe | [Mayara A. Oliveira](https://github.com/Mayara-tech) |
| `2.0`  | 13/05/2025 | Criação do SQuaRe |[Felipe Pedroza](https://github.com/darkymeubem), [Fillipe Souto](https://github.com/fillipeb50), [Philipe Barbosa](https://github.com/PhMoraiis), [Mayara Alves](https://github.com/Mayara-tech), [Vinicius Mendes ](https://github.com/yabamiah)|

