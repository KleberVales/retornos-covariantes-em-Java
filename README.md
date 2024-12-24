# retornos-covariantes-em-Java

### Descrição do Exercício
O objetivo é criar uma hierarquia de classes que use retornos covariantes para sobrescrever métodos em subclasses. Em Java, um método de uma subclasse pode sobrescrever um método da superclasse, retornando um tipo que é uma subclasse do tipo original retornado.\
Você receberá um código parcialmente implementado no editor, onde o método principal (main) recebe o nome de um estado (por exemplo, WestBengal, AndhraPradesh, etc.) e imprime o nome da flor nacional daquele estado usando as classes e métodos que você deve implementar.

### Detalhes
1. Retorno Covariante:
   * Permite que métodos sobrescritos retornem um subtipo do tipo original definido na superclasse.
2. Classes:
   * Você deve implementar as classes e métodos descritos no diagrama fornecido (detalhes no enunciado original do exercício).
3. Entrada:
   * O código fornecido para você já lê uma string representando o nome de uma subclasse de State (ex.: WestBengal, AndhraPradesh, etc.).
4. Saída:
   * A saída é gerada pelo código oculto, que cria um objeto da classe correspondente à string de entrada e chama o método apropriado para imprimir o nome da flor nacional.
  
### Formato de Entrada
- Uma string representando o nome de um estado (WestBengal, AndhraPradesh, etc.).

### Formato de Saída
- O nome da flor nacional daquele estado (ex.: Lily).

### Exemplo de Entrada e Saída
- Entrada:
  
```
AndhraPradesh

```
- Saída:
  
```
Lily

```
