# Desafio3_Dio_PowerBI

### Desafio de Configuração de Banco de Dados e Transformação de Dados com o Microsoft Azure e Power BI

Este projeto teve como objetivo configurar um banco de dados na nuvem utilizando o Microsoft Azure, populá-lo com dados e realizar a transformação desses dados utilizando o Power BI. Durante o processo, foram adquiridos diversos aprendizados e habilidades.

### Requisito do Projeto 11: Realização da Junção dos Colaboradores e Seus Respectivos Gerentes

Para atender ao requisito de número 11, que consistia em "Realizar a junção dos colaboradores e respectivos nomes dos gerentes", desenvolvi o seguinte código SQL para obter o resultado desejado:

```sql
SELECT e.Fname AS Employee_FirstName, e.Lname AS Employee_LastName, 
       m.Fname AS Manager_FirstName, m.Lname AS Manager_LastName
FROM employee e
LEFT JOIN employee m ON e.Ssn = m.Super_ssn;
```

Este código SQL permitiu obter uma lista de todos os colaboradores e seus respectivos nomes de gerentes, quando aplicável, com base na estrutura da tabela "employee".

## Criação de um Pequeno Relatório de Visualizações de Dados

Além da transformação dos dados, criei um pequeno relatório no Power BI para visualizar as informações de forma mais clara e compreensível. O relatório incluiu gráficos e tabelas que destacam os principais insights obtidos a partir dos dados.

## Aprendizados e Conquistas

Durante a execução deste projeto, pude adquirir os seguintes conhecimentos e competências:

- **Configuração de Banco de Dados na Nuvem:** Aprendi como configurar e implantar com sucesso um banco de dados na nuvem usando a plataforma Microsoft Azure. Isso inclui a criação de instâncias de banco de dados, definição de permissões e garantia de alta disponibilidade.

- **Transformação de Dados com o Power BI:** Obtive experiência na importação de dados brutos no Power BI e na aplicação de transformações necessárias para torná-los adequados para análise. Isso envolveu limpeza, agregação e formatação de dados.

- **Consultas SQL Complexas:** Desenvolvi habilidades avançadas em consultas SQL, incluindo a capacidade de realizar junções de tabelas, criar consultas subordinadas e escrever consultas otimizadas para recuperar informações específicas.

- **Criação de Relatórios Interativos:** Utilizei o Power BI para criar relatórios interativos e visualizações de dados que permitem aos usuários explorar e extrair insights valiosos dos dados.

- **Modelagem de Dados Avançada:** Compreendi os princípios da modelagem de dados, incluindo a criação de relacionamentos entre tabelas, a definição de medidas e a elaboração de modelos dimensionais.

- **Segurança de Dados na Nuvem:** Aprendi sobre boas práticas de segurança de dados na nuvem, incluindo o gerenciamento de credenciais, o controle de acesso e a criptografia de dados sensíveis.

- **Trabalho em Ambientes em Nuvem:** Ganhei familiaridade com a operação eficaz de ferramentas de análise de dados em ambientes em nuvem, permitindo uma colaboração mais eficiente e escalabilidade dos projetos.

Estes conhecimentos adquiridos durante o projeto permitiu me capacitar e abordar desafios complexos de gerenciamento e análise de dados, demonstrando compromisso com a melhoria contínua e a capacidade de enfrentar tarefas de dados de forma eficaz.


