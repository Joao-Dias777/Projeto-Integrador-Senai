Projeto Integrador Boletim

Este programa é uma ferramenta útil para professores gerenciarem de forma eficiente o desempenho acadêmico de seus alunos. Siga este manual para garantir o uso correto e eficaz do software.


Instruções de Uso
1. Nome da Turma
    * O programa solicitará que você insira o nome da turma. Digite o nome e pressione Enter.
2. Unidade Curricular
    * Em seguida, insira o nome da unidade curricular e pressione Enter.
3. Nome do Professor
    * Insira o nome do professor e pressione Enter.
4. Dados dos Alunos
    * O programa solicitará que você insira os dados para 5 alunos. Para cada aluno:
        * Digite o nome do aluno e pressione Enter.
        * Insira as notas (4 notas, uma de cada vez, entre 0 e 100). O programa validará a entrada e solicitará a nota novamente se for inválida.
        * Insira o número de faltas (entre 0 e 10). O programa validará a entrada e solicitará o número de faltas novamente se for inválido.
5. Exibição dos Resultados
    * Após inserir os dados de todos os alunos, o programa calculará as médias e as situações dos alunos.
    * Os resultados serão exibidos no console, incluindo:
        * Nome da turma, unidade curricular e professor.
        * Dados de cada aluno: notas, faltas, média final e situação (Aprovado, Recuperação, Reprovado).
        * Média geral da turma, número de alunos acima e abaixo da média, aluno com maior e menor média, melhor aluno junto a sua média.
6. Geração do Boletim em Arquivo
    * O programa salvará os dados no arquivo boletimEscolar.txt.
    * A mensagem "Boletim salvo em boletimEscolar.txt!" será exibida no console.

Cores no Console
* Verde (Aprovado): Alunos com média maior ou igual 70 e faltas menores que 2.
* Amarelo (Recuperação): Alunos com média entre 50 e 69 e faltas menores que 5.
* Vermelho (Reprovado): Alunos com média menores que 50 ou faltas maiores ou igual a 5.

Exemplo de Execução

Nome da turma: 1DT
Unidade Curricular: Lógica de Programação e Algoritmos
Nome do professor: Atila

Nome do aluno 1: João
Nota 1 (0 a 100): 85
Nota 2 (0 a 100): 90
Nota 3 (0 a 100): 75
Nota 4 (0 a 100): 80
Faltas (0 a 10): 1

...

======= Boletim Escolar =======
Professor: Atila
Unidade Curricular: Lógica de Programação e Algoritmos
Turma: 1DT

Aluno: João
Nota 1: 85
Nota 2: 90
Nota 3: 75
Nota 4: 80
Faltas: 1
Média Final: 82.5
Situação: Aprovado

...

Média geral da turma: 70.5
Alunos acima da média geral: 3
Alunos abaixo da média geral: 2
Aluno com maior média: João
Aluno com menor média: Gabriel
Melhor aluno: João com média 82.5

Boletim salvo em boletimEscolar.txt!

Solução de Problemas
* Erro ao inserir notas/faltas: Certifique-se de inserir números inteiros válidos dentro dos intervalos especificados.
* Arquivo não salvo: Verifique as permissões de escrita no diretório e se o nome do arquivo está correto.
