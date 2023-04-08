# Olá, Mundo!
 Primeiro repositório do curso de Git e GitHub

 Repositório criado durante uma aula do **Curso de Git e GitHub** do site de ensino Curso em Vídeo!
 
 ---

Durante o **Curso de Git e GitHub** o ilustre professor Gustavo Guanabara ensina a linguagem Markdown. Adicionei no README para testes.

# Testes da Linguagem Markdown
---
Podemo misturar configurações por exemplo "*" + "__"

Ex: Uma frase de __*exemplo*__ misturando ~~configurações~~ Markdown

---
## Listas

### Listas numeradas:

Precisará ser incluído um número (é indiferente o número) com um ponto, a linguagem Markdown ira numerar de forma crescente automaticamente.

1. Teste
7. Teste 2
   1. Teste 3
   2. teste 4
40. Teste 5

### Lista demarcada:

Neste modelo de lista será necessário incluir um "*" ou "-" na frente do item da lista que deseja incluir, se incluir um item na linha abaixo juntamente com um espaçamento este item se tornará um subitem do item acima adicionado.

* Teste 1
* Teste 2
  * Teste 3
  * Teste 4
* Teste 5

### Lista de tarefas:

Já para criar uma lista de tarefas precisa ser incluído "- [ ]" antes da frase da tarefa, se quiser indicar que a tarefa for concluída será necessário incluir um X dentro dos colchetes.

- [x] Fazer uma Issue de testes
- [ ] Participar da reunião a tarde
- [X] Pagar as contas do mês
- [ ] Criar uma página de loja

---
### Tabelas

Para criar uma tabela na linguagem Markdown precisará incluir o nome da coluna dividido por Pipes, e abaixo disso virá a linha de divisão das colunas para os valores incluídos da seguinte maneira: "---|---|---". Para inserir os valores na tabela também precisa dividi-los entre colunas com um pipe.

Placa de vídeo | Marca | Preço
---|---|---
RX 6750 XT | AMD | $2.699,99
RTX 3060 Ti | Nvidia | $2.799,99
Arc A750 | Intel | $2.399,99

Terminou a tabela

---

### Comandos

Para formatar um texto em comandos (destacar) será necessário incluir uma crase no início e no final do comanto citado.

Para criar uma classe com o metodo main na linguagem java, deve-se utilizar a seguinte frase `public static void main(String[] args){`

Se desejar incluir um código com mais linghas será necessário adicionar incluir três crases:

```
package exercicios;

import java.util.Locale;

public class exercicio1 {
    
    public static void main(String[] args){
        String product1= "Computer";
        String product2= "Office desk";
        
        int age = 30;
        int code = 5290;
        char gender = 'F';
        
        double price1 = 2100.0;
        double price2 = 650.50;
        double measure = 53.234567;
        
        System.out.println("Products: ");
        System.out.printf("%s, which price is $ %.2f%n",product1,price1);
        System.out.printf("%s, which price is $ %.2f%n",product2, price2);
        System.out.println(" ");
        System.out.printf("Record: %d years old, code %d and gender: %c%n", age, code, gender);
        System.out.println(" ");
        System.out.printf("Measue with eight decimal places: %.8f%n", measure);
        System.out.printf("Reuded (three decimal places): %.3f%n",measure);
        Locale.setDefault(Locale.US);
        System.out.printf("US decimal point: %.3f%n", measure);
}
}
```
---

### Emojis

Para incluir emojis em na linguagem Markdown será necessário utilizar dois pontos e escrever o nome do emoji e completar com mais dois pontos.

Hello, world! :wave:
