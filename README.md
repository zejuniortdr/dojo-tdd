## Reflexões para decisões de engenharia

#### 🧩 Design e legibilidade
1. O código está fácil de entender para quem nunca o viu antes?

2. Os nomes de variáveis e funções estão claros e autoexplicativos?

3. Existe duplicação de lógica que poderia ser extraída para funções auxiliares?

4. Estamos usando comentários desnecessários ou o código é suficientemente autoexplicativo?

#### ⚙️ Complexidade e estrutura
5. Quantos caminhos diferentes de execução existem na função (complexidade ciclomática)? Poderíamos reduzir isso?

6. O código está modularizado o suficiente, ou ficou tudo em uma função monolítica?

7. É possível reusar essa função em outro contexto ou ela está acoplada demais?

#### 🚀 Performance e eficiência
8. A lógica percorre as notas de forma eficiente? Há algum cálculo desnecessário ou repetido?

9. Se usássemos um número muito grande, como 999_998, o código continuaria rápido?

10. Estamos usando estruturas de dados adequadas (ex: lista, dicionário, etc.) para representar as notas?

#### 🧪 Testes e cobertura
11. Os testes cobrem todos os casos de borda possíveis (como saque com 0, com valores inválidos, ou com uma única nota)?

12. Há testes redundantes ou que não validam comportamentos relevantes?

13. Estamos testando apenas o resultado, ou também testamos possíveis exceções e comportamentos inválidos?

#### 🧠 Decisões e alternativas
14. Poderíamos ter resolvido o problema de outra forma, talvez com divmod, recursão ou programação funcional?

15. Há alguma melhoria que poderíamos fazer para tornar o código mais extensível (por exemplo, para incluir novas notas)?

16. Essa implementação seria fácil de adaptar para uma versão internacional, com outras moedas e cédulas?
