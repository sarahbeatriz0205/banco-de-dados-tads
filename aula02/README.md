# Modelagem
- Representação de ideias de maneira concreta para tornar possível a construção de um sistema
- No contexto de BD, significa estruturá-lo (tipos de dados, relacionamentos e suas restrições)

## Categorias de modelos de dados
- **Conceituais:** Representação para usuários especializados e projetistas, sendo utilizado o **modelo entidade-relacionamento**. Mais próxima do mundo das ideias
- **Lógicos:** Nível de implementação. Tradução do diagrama ER para o modelo relacional
- **Físicos:** Comanods SQL de um determinado SGBD

## Conceitos básicos da abordagem relacional
### Esquemas, instâncias e estado
- **Esquema:** Descrição do BD. Dicionário de dados
> Ex: Tabelas de um sistema escolar, com aluno, curso e disciplina

- **Instâncias:** Representações de elementos reais no BD
> Ex: Dados do aluno, curso e disciplina

## Categorias das linguagens
- **Definição de dados**
- **Manipulação**
- **Consulta**

## Procedimentos dos Comandos DML
- **Alto nível (não procedural):** Manipulação de registros por ação imediata (um único comando)
- **Baixo nível (procedural):** Utiliza scripts (qualquer linguagem) para manipulação de registros
- Os comandos DML podem ser embutidos em linguagens de programação ou utilizada em modo interativo

## Modelagem ER (Entidade-Relacionamento)
- Utiliza entidade, relacionamento e atributo (semelhante a um diagrama de classe UML)
- **Entidade:** Conjunto de instâncias
- **Relacionamento:** Associa instâncias de entidades
- **Diagrama de ocorrências:** Serve para que se entenda um determinado estado do BD

### Tipos de relacionamento
- **Auto-relacionamento (unário):** ligação entre instâncias da mesma entidade
- **Binário:** ligação entre instâncias de duas entidades diferentes
- **Ternário:** ligação entre instâncias de três entidades diferentes
- **Cardinalidade (multiplicidade):** limitação da quantidade de associações
