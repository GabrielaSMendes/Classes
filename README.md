# Classes
Lista 2 da matéria de Programação avançada onde contém 8 exercícios 

1. Crie uma classe CalculadoraArea. Implemente três métodos sobrecarregados chamados calcular. O primeiro deve calcular a área de um quadrado (recebe um double), o segundo a de um retângulo (recebe dois double) e o terceiro a de um círculo (recebe um double raio).

2. Crie uma classe Produto com atributos nome, preco e quantidadeEstoque. Implemente um Construtor Mestre que valide se o preço é positivo. Se for negativo, defina-o como zero. Use this() para criar um segundo construtor que aceite apenas o nome, definindo preço e quantidade como valores padrão.

3. Na classe ContaCorrente, crie um método sacar(double valor). Sobregue-o com sacar(double valor, double taxaAdicional). A segunda versão deve calcular o valor total (valor + taxa) e delegar a execução para a primeira versão.

4. Implemente uma classe Logger. Crie métodos log(String mensagem), log(String mensagem, int nivelSeveridade) e log(String mensagem, String modulo). Garanta que todos mantenham um comportamento consistente, conforme as boas práticas de legibilidade.

5. Baseado no exemplo do Smartphone, crie uma classe Livro com titulo, autor e numPaginas. Crie um construtor completo. Crie um construtor que aceite apenas titulo e autor, usando this() para definir numPaginas como 100 por padrão.

6. Implemente a classe Disciplina conforme o exercício da aula. O método lancarNota(double nota) deve garantir que a nota esteja entre 0 e 10. A versão sobrecarregada lancarNota(double nota, double peso) deve realizar o cálculo e chamar a versão simples.
   
7. Observe o código do BankAccount na página 16. Refatore o método deposit(double amount, int agencyCode) para que ele não duplique a lógica de incremento do saldo, utilizando o conceito de delegação visto em aula.

8. Crie uma classe Pedido e construa o Construtor 1 sem parâmetros (define a data como "hoje" e status como "Pendente").
O Construtor 2 recebe a data e usa this() para definir o status padrão. Garanta que o this() seja sempre a primeira instrução do construtor.
