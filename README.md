# Site de Comparação de Preços de Gasolina e Álcool

Este site foi desenvolvido utilizando **React** com **TypeScript** e tem como objetivo auxiliar os usuários a decidirem se é mais vantajoso abastecer com gasolina ou álcool, com base nos preços de cada combustível.

## Tecnologias Utilizadas

- **React**: Utilizado para criar a interface do usuário de maneira eficiente, com gerenciamento de estado local para capturar e calcular os preços.
- **TypeScript**: Fornece tipagem estática para garantir maior segurança e previsibilidade durante o desenvolvimento.
- **CSS**: O design simples e funcional foi desenvolvido utilizando um arquivo CSS externo (`App.css`).
- **Imagens**: Uma logo personalizada foi adicionada ao projeto, exibida no topo da página.

## Funcionalidades

1. **Entrada de Dados**:
   - O usuário pode inserir os valores do **preço do álcool** e da **gasolina** em reais.
   - Os valores são manipulados com precisão, utilizando o método `toLocaleString` para formatar a moeda no padrão brasileiro (BRL).

2. **Cálculo Automático**:
   - Ao submeter os valores, o site realiza um cálculo simples: **álcool ÷ gasolina**.
   - Se o resultado for **menor ou igual a 0.7**, o site recomenda o uso do álcool. Caso contrário, sugere abastecer com gasolina.

3. **Exibição dos Resultados**:
   - Após o cálculo, os resultados são exibidos em uma seção com o título e os valores inseridos, indicando claramente qual combustível é mais vantajoso no momento.

## Interface de Usuário

A interface é organizada de maneira simples e intuitiva:
- O usuário é recebido com a logo do site no topo.
- Dois campos de entrada permitem a digitação dos preços dos combustíveis.
- Um botão de "Calcular" dispara o cálculo e exibe os resultados abaixo.

## Exemplo de Uso

O usuário insere o preço do álcool como `4,90` e o da gasolina como `6,00`. Após clicar em "Calcular", o site exibirá o resultado:

