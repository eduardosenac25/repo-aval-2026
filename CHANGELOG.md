# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-25

### Adicionado

- Nova situação "Aprovado com distinção" para médias iguais ou superiores a 9,0.
- Formatação da média com uma casa decimal e separador decimal em vírgula.
- Testes cobrindo notas inválidas e a classificação de distinção.

### Alterado

- Ajuste na lógica de situação para considerar a média 7,0 como "Aprovado".
- Simplificação do cálculo da média sem uso de laço `for`, preservando o comportamento anterior.
- Atualização da documentação de uso e das regras de avaliação no README.

### Corrigido

- Correção do bug em que a média 7,0 era exibida como "Recuperação".
- Validação de notas fora do intervalo de 0 a 10 e de valores não numéricos.

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.
