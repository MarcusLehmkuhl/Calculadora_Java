# Calculadora com CI.

Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção

Pipeline de CI:
- dev - Compilação e testes.
- hmg - Análise e cobertura do código.
- prd - Empacotamento.

<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>
