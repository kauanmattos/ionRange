# Componente Ion-Range com Angular

Este projeto demonstra o uso do componente `ion-range` do Ionic Framework em um aplicativo Angular.

## Visão Geral

O componente `ion-range` é um controle deslizante que permite aos usuários selecionar um valor dentro de um intervalo. Este projeto mostra como usar o `ion-range` para exibir e atualizar um valor numérico em um aplicativo Ionic Angular.

## Funcionalidades

* Exibe um controle deslizante `ion-range` com um intervalo de 0 a 10.
* Atualiza uma variável `valorRange` com o valor selecionado no controle deslizante.
* Exibe o valor de `valorRange` em um rótulo `ion-label`.
* Inclui ícones de adição e remoção no início e no final do controle deslizante.

## Como Usar

1. Clone este repositório.
2. Instale as dependências usando `npm install`.
3. Execute o aplicativo usando `ionic serve`.

## Estrutura do Código

* `home.page.html`: Contém o template HTML para o componente, incluindo o `ion-range` e o `ion-label`.
* `home.page.ts`: Contém a lógica do componente, incluindo a variável `valorRange` e o método `onIonChange`.
* `home.page.scss`: Contém os estilos CSS para o componente.

## Personalização

* Você pode personalizar o intervalo do controle deslizante alterando os atributos `min` e `max` no elemento `ion-range` em `home.page.html`.
* Você pode personalizar a aparência do controle deslizante usando CSS em `home.page.scss`.
* Você pode adicionar mais funcionalidades ao componente modificando o método `onIonChange` em `home.page.ts`.

## Dependências

* Angular
* Ionic Framework
