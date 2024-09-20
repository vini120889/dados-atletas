# Sistema de Informações de Atletas

Este repositório contém um código JavaScript que exibe informações detalhadas de um atleta, incluindo seu nome, idade, peso, notas, categoria, IMC (Índice de Massa Corporal) e a média válida de suas notas.

## Funcionalidades

- Exibição de informações do atleta: Nome, idade, peso e categoria.
- Cálculo do IMC: Baseado no peso e altura do atleta.
- Exibição das notas: Lista das notas obtidas pelo atleta.
- Cálculo da média válida: Desconsiderando a maior e a menor nota do conjunto de notas.

## Estrutura do Código

O código faz uso de uma classe `Atleta` (não incluída no exemplo) com vários métodos para obter as informações do atleta:

- `obtemNomeAtleta()`: Retorna o nome do atleta.
- `obtemIdadeAtleta()`: Retorna a idade do atleta.
- `obtemPesoAtleta()`: Retorna o peso do atleta.
- `obtemNotasAtleta()`: Retorna as notas do atleta.
- `obtemCategoria()`: Retorna a categoria do atleta com base na idade.
- `obtemIMC()`: Calcula e retorna o IMC (Índice de Massa Corporal) do atleta.
- `obtemMediaValida()`: Calcula e retorna a média válida das notas do atleta, descartando a maior e a menor nota.

### Exemplo de Saída

Quando o código é executado, a saída no console será semelhante à seguinte:

Nome: Cesar Abascal<br>
Idade: 30<br>
Peso: 75<br>
Notas: 10, 9.34, 8.42, 10, 7.88<br>
Categoria: Adulto<br>
IMC: 27.68166089965398<br>
Média: 9,25333333<br>

### Como Executar

1. Clone o repositório:<br>
   git clone: https://github.com/seu-usuario/nome-do-repositorio.git
   
2. Implemente a classe Atleta: O código assume que você já possui uma classe Atleta que implemente os métodos mencionados.

3. Execute o código no ambiente JavaScript: Você pode rodar o código diretamente em um navegador usando a ferramenta de desenvolvedor ou em um ambiente Node.js.

4. Veja os resultados no console: Os resultados das informações do atleta serão exibidos no console.
