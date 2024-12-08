# exercicios-sql
Segunda lista de exercícios da matéria de Gerenciamento de Banco de Dados.

# passo a passo:
Para executar este código utilizamos a versão gratuíta do SQL Worksheet da Oracle.
1. Criar e executar as sequências.
2. Criar as tabelas aluno, professor, curso, disciplina matrícula e turma.
3. Popular cada tabela com os respectivos dados.
4. Executar este código

# o que cada procedure faz: 
# PKG_ALUNO
excluir_aluno - exclui o aluno da tabela aluno com base no id_aluno, e remove todas as matrículas associadas ao aluno na tabela matricula.

listagem de alunos > 18 - retorna o nome e a data de nascimento de todos os alunos com idade superior a 18 anos.

cursor com filtro por curso - retorna os nomes dos alunos matriculados no curso especificado, baseado no id_curso.

# PKG_DISCIPLINA
cadastro de disciplina - recebe o nome, a descrição e a carga horária de uma disciplina e insere essas informações na tabela disciplina.

total de alunos por disciplina - retorna o número total de alunos matriculados em cada disciplina, exibindo apenas aquelas com mais de 10 alunos

cursor com média de idade por disciplina - recebe um id_disciplina e calcula a média de idade dos alunos matriculados na disciplina, retornando o valor arredondado para o inteiro mais próximo.

listar alunos de uma disciplina - recebe o id_disciplina e exibe os nomes dos alunos matriculados nessa disciplina.

# PKG_PROFESSOR 
total de turmas por professor - exibe o nome dos professores e o total de turmas que cada um possui, mostrando apenas os professores com mais de uma turma.

total de turmas de um professor - recebe o id_professor e retorna o número de turmas que o professor leciona.

professor de uma disciplina - recebe o id_disciplina e retorna o nome do professor responsável por essa disciplina.
