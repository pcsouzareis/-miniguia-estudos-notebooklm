# 🐘 Tutor de PostgreSQL com NotebookLM

Este repositório documenta o uso do **NotebookLM como tutor de estudos para PostgreSQL**.

A proposta é transformar uma coleção de materiais em PDF em uma experiência de aprendizado guiada. Em vez de apenas entregar respostas, o NotebookLM deve atuar como um **tutor particular**, ajudando a:

- Explicar conceitos;
- Propor exercícios;
- Revisar tentativas;
- Identificar erros;
- Estimular o raciocínio;
- Indicar as fontes utilizadas em cada explicação.

O NotebookLM permite adicionar PDFs como fontes, selecionar quais materiais serão considerados nas respostas e personalizar o comportamento do chat. Isso torna a ferramenta especialmente útil para estudar conteúdos técnicos utilizando a própria bibliografia como base.

---

## 🎯 Objetivo

Desenvolver conhecimentos práticos e teóricos em **PostgreSQL**, incluindo:

- Criação e consulta de bancos de dados;
- Modelagem de tabelas;
- Tipos de dados;
- Chaves e relacionamentos;
- Comandos SQL;
- Filtros e ordenação;
- JOINs;
- Agrupamentos e agregações;
- Subconsultas;
- Criação de funções;
- Programação com PL/pgSQL;
- Resolução de exercícios;
- Prática com perguntas baseadas no material de estudo.

O objetivo principal é desenvolver autonomia para **escrever, interpretar, testar e corrigir consultas PostgreSQL**.

---

## 📚 Fontes utilizadas

O notebook reúne mais de **50 arquivos PDF** relacionados ao PostgreSQL.

Entre os materiais utilizados estão:

```text
PostgreSQL-Prático.pdf
Perguntas_e_reposta_postgres.pdf
PostgreSQL_Criar_Funções.pdf
PostgreSQL_PLpgSQL_Parte1.pdf
```

Além desses arquivos, existem outros **46+ PDFs complementares** abordando assuntos como:

- PostgreSQL;
- SQL;
- Consultas;
- Funções;
- Procedures;
- PL/pgSQL;
- Administração de banco de dados.

> [!TIP]
> Recomenda-se selecionar apenas os PDFs relacionados ao assunto estudado no momento.
>
> Por exemplo:
>
> - Ao estudar **funções**, priorize os materiais sobre funções e PL/pgSQL.
> - Ao estudar **SQL básico**, priorize os materiais introdutórios.
> - Ao estudar **consultas avançadas**, selecione os materiais relacionados a JOINs, agregações e subconsultas.
>
> Isso ajuda o NotebookLM a trabalhar com um contexto mais específico durante cada sessão de estudo.

---

## 🤖 Prompt personalizado

Na configuração do chat do NotebookLM, utilize o seguinte prompt:

```text
Atue como meu tutor particular de PostgreSQL, utilizando exclusivamente os PDFs disponíveis neste notebook como fonte principal.

Seu objetivo é me ajudar a aprender de forma ativa, prática e progressiva, e não apenas entregar respostas prontas.

Siga estas regras:

1. Explique os conceitos em português do Brasil, com linguagem clara e adequada para alguém em transição para a área de tecnologia.

2. Antes de resolver exercícios ou responder perguntas técnicas, incentive-me a tentar. Faça uma pergunta por vez e aguarde minha resposta quando for apropriado.

3. Ao explicar comandos SQL, apresente:
   - o objetivo do comando;
   - a sintaxe;
   - um exemplo prático;
   - uma explicação linha por linha;
   - erros comuns e como evitá-los.

4. Ao trabalhar com consultas SQL, comece com exemplos simples e avance gradualmente para:
   - filtros;
   - JOINs;
   - GROUP BY;
   - funções de agregação;
   - subconsultas;
   - funções;
   - PL/pgSQL.

5. Quando eu errar, corrija de forma respeitosa. Mostre exatamente em qual parte está o erro, explique o motivo e peça para que eu tente corrigir antes de apresentar uma versão completa.

6. Sempre que possível, relacione a explicação a situações reais, como:
   - cadastro de clientes;
   - vendas;
   - produtos;
   - veículos;
   - estoque;
   - relatórios empresariais.

7. Crie exercícios práticos progressivos utilizando tabelas fictícias.

Não entregue a resposta imediatamente.

Primeiro peça minha tentativa e depois revise meu raciocínio.

8. Ao responder, cite os PDFs ou trechos de fonte utilizados pelo NotebookLM.

Caso a informação não esteja nos materiais, diga claramente que ela não foi encontrada nas fontes selecionadas.

9. Ao final de cada explicação, faça uma única pergunta aberta para verificar se entendi e estimular minha prática.

10. Dê prioridade aos seguintes temas:
    - SQL básico e avançado;
    - criação de tabelas e relacionamentos;
    - SELECT;
    - WHERE;
    - ORDER BY;
    - GROUP BY;
    - HAVING;
    - JOINs;
    - funções de agregação;
    - criação de funções;
    - PL/pgSQL;
    - resolução de questões sobre PostgreSQL.

Mantenha um tom profissional, paciente, motivador e direto.

Ajude-me a construir autonomia para escrever, interpretar, testar e corrigir consultas PostgreSQL.
```

---

## 🚀 Como usar

### 1. Criar o notebook

Crie um novo notebook no **NotebookLM**.

### 2. Adicionar as fontes

Faça upload dos PDFs utilizados nos estudos de PostgreSQL.

### 3. Configurar o tutor

Abra as configurações do chat e selecione a opção de personalização.

### 4. Adicionar o prompt

Copie o prompt apresentado neste README e utilize-o como instrução personalizada.

### 5. Selecionar as fontes

Antes de iniciar uma sessão de estudo, mantenha selecionados principalmente os PDFs relacionados ao assunto que será estudado.

### 6. Iniciar os estudos

Faça perguntas específicas ao tutor.

Exemplos:

```text
Explique JOIN utilizando um exemplo de clientes e pedidos.
```

```text
Crie um exercício sobre GROUP BY e espere minha tentativa.
```

```text
Crie um exercício de função em PL/pgSQL e não mostre a resposta até eu tentar.
```

```text
Explique a diferença entre INNER JOIN e LEFT JOIN utilizando exemplos.
```

---

## 🧠 Método de estudo

A ideia é utilizar o NotebookLM seguindo este ciclo:

```text
Material de estudo
       ↓
Explicação
       ↓
Exemplo
       ↓
Exercício
       ↓
Minha tentativa
       ↓
Correção
       ↓
Nova tentativa
       ↓
Próximo nível
```

O objetivo é evitar um aprendizado baseado apenas em leitura e transformar o conteúdo dos PDFs em **prática ativa de PostgreSQL**.

---

## 📈 Progressão sugerida

Uma possível sequência de estudos é:

```text
PostgreSQL
│
├── Fundamentos
│   ├── Bancos de dados
│   ├── Tabelas
│   ├── Tipos de dados
│   └── Chaves e relacionamentos
│
├── SQL Básico
│   ├── SELECT
│   ├── WHERE
│   ├── ORDER BY
│   ├── INSERT
│   ├── UPDATE
│   └── DELETE
│
├── SQL Intermediário
│   ├── JOIN
│   ├── GROUP BY
│   ├── HAVING
│   └── Funções de agregação
│
├── SQL Avançado
│   ├── Subconsultas
│   ├── CTE
│   ├── Views
│   └── Window Functions
│
└── PL/pgSQL
    ├── Funções
    ├── Variáveis
    ├── IF / ELSE
    ├── LOOP
    ├── FOR
    ├── Exceptions
    └── Procedures
```

---

## 🧪 Primeira atividade

Uma boa forma de começar é pedir ao tutor:

> **"Avalie meu nível de SQL com cinco perguntas progressivas, uma por vez, e só avance depois da minha resposta."**

A partir das respostas, o tutor poderá identificar quais assuntos precisam de maior atenção antes de avançar para conteúdos mais complexos.

---

## 📖 Documentação

Para mais informações sobre como utilizar fontes no NotebookLM, consulte a documentação oficial:

[Google NotebookLM — Gerenciamento de fontes](https://support.google.com/notebooklm/answer/16179559?hl=pt-BR)

---

## 💡 Objetivo final

Este projeto não tem como objetivo utilizar IA apenas para **obter respostas de SQL**.

A proposta é utilizar IA como ferramenta de aprendizado para desenvolver a capacidade de:

> **entender o problema → pensar na solução → escrever o SQL → testar → identificar erros → corrigir → evoluir**

Dessa forma, o NotebookLM funciona como um **tutor complementar aos materiais de estudo**, enquanto a resolução dos problemas continua sendo parte fundamental do processo de aprendizagem.

---

## 🛠️ Tecnologias

- PostgreSQL
- SQL
- PL/pgSQL
- NotebookLM
- Inteligência Artificial
- PDFs como base de conhecimento

---

## 📌 Status do projeto

🚧 **Em desenvolvimento e aprendizado contínuo.**

Novos materiais, exercícios e estratégias de estudo poderão ser adicionados ao repositório conforme a evolução dos estudos.
