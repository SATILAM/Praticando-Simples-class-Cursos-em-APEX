# Exemplo Simples class Cursos.

O código acima define uma classe pública chamada "Cursos".

Possui quatro variáveis de instância do tipo String: "ingles", "linguagemProgramacao", "apex" e "adminSalesforce". 

Essas variáveis representam diferentes cursos ou habilidades relacionadas a inglês, linguagens de programação, 
Apex (uma linguagem de programação usada no desenvolvimento do Salesforce) e administração do Salesforce.

A classe também tem um método construtor que aceita quatro parâmetros, cada um dos quais é do tipo String.

O construtor atribui os valores de parâmetro às variáveis de instância usando a palavra-chave "this".

...........................##..............................................

Foi utilizado o método System.debug() para imprimir na tela as informações dos Cursos.

...........................##..............................................

DEVELOPER CONSOLE - ANONYMOUS - SALESFORCE:

Cursos meusCursos = new Cursos('Inglês', 'Linguagem de Programação', 'Apex', 'Administrador Salesforce');

System.debug('Segundas, Quartas e Sextas-feiras: ' + meusCursos.ingles);

System.debug('Terças, Quartas e Quintas-feiras: ' + meusCursos.linguagemProgramacao);

System.debug('Terças e Quintas-feiras: ' + meusCursos.apex);

System.debug('Segundas e Sextas-feiras: ' + meusCursos.adminSalesforce);

https://satilam.github.io/Praticando-Simples-class-Cursos-em-APEX/
