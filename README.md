Estudo de Caso
Gerência Acadêmica de uma Universidade:
Um estudo para desenvolvimento de modelagem conceitual e lógica. 

1. Apresentação  

Um Estudo de CASO traduz uma importante fonte de conhecimento a partir da aplicação das teorias apresentadas em um determinando enquadramento, nesse caso, em BANCO de DADOS. 

Observe que no relato de um estudo de caso, contém: 

i. Introdução; 

ii. Fundamentação Teórica; 

iii. Trabalhos Relacionados; 

iv. A Descrição do Caso; 

v. A Discussão dos Resultados; 

vi. Considerações; 

vii. Bibliografia ou Referência Bibliográfica. 

 

O caso que aqui apresentamos como modelo de orientação encontra-se abaixo no item 3 cujo título é: Gerência Acadêmica de uma Universidade. No estudo que propomos, o aluno deverá focar neste estudo de caso apenas na modelagem de um Diagrama Entidade Relacionamento (DER) em duas etapas. Modelo conceitual e modelo Lógico. 

 

2. Objetivos 

Ler o referido Caso de Estudo e produzir um documento, anexando-o no Canvas sob o título: “Estudo de Caso #01 Gerência Acadêmica de uma Universidade: Um estudo para desenvolvimento de modelagem conceitual e lógica”). 

 

Esse documento deverá conter: 

i. um relato de no máximo 10 linhas sobre o tema objeto do Estudo de Caso (Enfoque somente na Modelagem Conceitual e Lógica de uma farmácia), 

ii. um Diagrama Entidade Relacionamento (DER) conceitual e um Diagrama Entidade Relacionamento (DER) lógico (utilize o software BrModelo ou algum outro que achar melhor), 

iii. relatar as dificuldades conceituais encontradas, e 

iv. suas considerações e reflexões sobre a modelagem. 

 

3. Estudo de Caso 

Gerência Acadêmica de uma Universidade 

Resumo: Decidiu-se automatizar alguns procedimentos da Gerência Acadêmica (GA) da Universidade UNIESTUDANTE. Com a finalidade de auxiliar esta tarefa, foi solicitado o desenvolvimento de um banco de dados. 

Introdução: A Gerência Acadêmica mantém um controle centralizado de alunos, cursos, disciplinas, turmas, professores, departamento e histórico escolar de alunos.  

Nesta universidade existe apenas um departamento que por sua vez gerencia várias disciplinas e controla vários cursos. Neste departamento trabalham inúmeros professores.   

Os professores deste departamento podem lecionar 1 ou mais disciplinas, as disciplinas são cursadas por vários alunos e da mesma forma os alunos podem cursar várias disciplinas em seu curso, pois vários alunos podem ser matriculados em um curso. No caso do curso, ele pode gerar uma turma que só existirá se pelo menos existir um aluno, mas este curso pode existir e não conter aluno algum. Dessa forma, o curso está inativo, mas ele possui 1 ou mais disciplinas. Os alunos terão um histórico escolar e este histórico é composto por várias disciplinas. 

Algumas disciplinas possuem uma particularidade, elas só podem ser cursadas caso uma outra como pré-requisito já tenha sido cursada. 

Alguns atributos são sugeridos para cada entidade: 

Aluno: RA (Registro Acadêmico), CPF, filiação, sexo, nome, nome do meio, sobrenome, emails, endereços, telefones, status, data de nascimento.  
Professor: CPF, código do professor, data de nascimento, Titulação, Status, nome, nome do meio, sobrenome; 
Curso: nome do curso; 
Departamento: nome do departamento; 
Turma: Código da turma, quantidade de alunos, período, data de início, data de fim; 
Histórico: nota, frequência; 
Disciplina: código, nome, número de alunos, carga horária, ementa. 
Os atributos acima são sugestões, caso haja necessidade de mais atributos, o aluno é livre para adicioná-los. 

 

Desenvolvimento: Crie o modelo conceitual desta base de dados relacional. A sugestão é que seja criada com a ferramenta livre BrModelo.  

 

4. Referências  

ELMASRI, Ramez E.; NAVATHE, Shamkant. Sistema de Banco de Dados. 6 ª edição. Pearson/Pretice Hall, 2018.   
DATE C J. Introdução a Sistemas de Banco de Dados. 1ª Edição. GEN LTC, 2004.  
VICCI, Claudia. Banco de Dados. Edição: 1°. Pearson, 2015. 
PUGA, Sandra; FRANÇA, Edson; GOYA, Milton. Banco de dados: Implementação em SQL, PL/SQL e Oracle 11g. Edição: 1°. Pearson, 2013.  
MEDEIROS, Luciano Frontino de, Banco de Dados: princípios e prática. Edição: 1°, 2013.  
LEAL, Gislaine Camila Lapasini. Linguagem, programação e banco de dados: guia prático de aprendizagem. 1° Edição. Editora Intersaberes, 2015.  
LIGHTSTONE, Sam. Projeto e modelagem de banco de dados. Edição: 1. GEN LTC, 2013. 
Ramakrishnan, Raghu. et al. Sistemas de Gerenciamento de Bancos de Dados. Edição: 3. Editora: AMGH, 2007. 