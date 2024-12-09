Bem-vindo ao repositório do projeto de desenvolvimento de pacotes PL/SQL para gerenciamento das entidades Aluno, Disciplina e Professor em um ambiente Oracle.

Pacote PKG_ALUNO
1. Procedure de exclusão de aluno
Esta procedure recebe o ID de um aluno e exclui o registro correspondente na tabela de alunos, além de remover todas as matrículas associadas.
2. Cursor de listagem de alunos maiores de 18 anos
Este cursor lista o nome e a data de nascimento dos alunos com idade superior a 18 anos.
3. Cursor com filtro por curso
Este cursor é parametrizado e exibe os nomes dos alunos matriculados em um curso específico.

Pacote PKG_DISCIPLINA
1. Procedure de cadastro de disciplina
Esta procedure cadastra uma nova disciplina recebendo como parâmetros o nome, a descrição e a carga horária.
2. Cursor para total de alunos por disciplina
Este cursor exibe o número total de alunos matriculados em cada disciplina com mais de 10 alunos.
3. Cursor com média de idade por disciplina
Este cursor calcula a média de idade dos alunos matriculados na disciplina especificada.
4. Procedure para listar alunos de uma disciplina
Esta procedure exibe os nomes dos alunos matriculados em uma disciplina específica.

Pacote PKG_PROFESSOR
1. Cursor para total de turmas por professor
Este cursor lista os nomes dos professores e o total de turmas que cada um leciona, exibindo apenas aqueles responsáveis por mais de uma turma.
2. Function para total de turmas de um professor
Esta function retorna o total de turmas em que um professor atua como responsável.
3. Function para professor de uma disciplina
Esta function retorna o nome do professor que ministra uma disciplina específica.
