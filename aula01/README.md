# Gerenciamento do Acesso e Manipulação de Dados
## Como gerenciar o acesso e manipular os daodos?
- **Sistema Gerenciador de Banco de Dados** (SGBD - servidor de banco de dados, como MariaDB, SQLServer, PostregSQL): Um sistema solicita a inserção e gerenciamento do seu dado a um SGBD que organiza e faz o que foi solicitado. Tudo é feito em meio físico (tabela de um banco de dados;

## Características de um BD
- **Dado:** É um registro bruto, sem contexto. Por exemplo, "10" ou "vermelho";
- **Informação:** É o dado contextualizado. "10" se torna "10 alunos faltaram" (contexto educacional);
- Os dados refletem um cenário de um domínio (contexto);
- A ordem dos dados importa

## **Sistema Gerenciador de Banco de Dados (SGBD)**
- Conjunto de softwares que facilita a definição, manipulação, inserção e o compartilhamento ao banco de dados, além de proteção;
- Definição: Em resumo, criação de uma tabela;
- Compartilhamento: Gerencia o compartilhamento de dados entre clientes, além de gerenciar acesso;
- O SGBD transforma um comando SQL de alto nível para um comando de baixo nível, pois ele conversa diretamente com o sistema operacional. Também retorna a resposta em baixo nível, que é convertida para alto nível em outro lugar;

> Para praticar: [SQL Online](https://sqliteonline.com/)

## Atores (usuários) em um Sistema de BD
- **Sistema de BD:** Sistema que recebem interações de diferentes vertentes
- **Administrador (Database Administrator:** Define a autorização para o acesso aos dados
- **Projetista:** Responsável por modelar e desenvolver a estrtura apropriada para o armazenamento de dados
-  **Usuários finais:** Casuais (utilizam o sistema); Parametrizáveis (constante consulta e atualização, observa o que pode ser melhorado ou mudado em um sistema. Ex: trabalhadores de uma agência); Sofisticados (conhecem e/ou implementam um sistema)

## Aspectos na utilização de um SGBD
- Custos provocados por investimentos
- Impacto no tempo da resposta da minha aplicação, por ser um outro software sendo usado

## Características do SGBD
- Natureza autodescritiva
- Isolamento
- Suporte para múltiplas versões
- Restrição de acesso aos dados
- Otimização de acesso aos dados
- Backup e restauração
- Permite múltiplas interfaces
- **Restrições de integridade**
- **Controle de redundância com chaves**
