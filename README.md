# Projeto: Fokus - Gerenciamento de Tarefas com Pomodoro e TypeScript

O **Fokus** é um site de gerenciamento de tarefas baseado na técnica Pomodoro, desenvolvido com TypeScript. Este projeto faz parte do meu aprendizado no curso de TypeScript pela Alura, e utiliza conceitos avançados de manipulação de estado, eventos personalizados e atualização dinâmica de interface. O objetivo é ajudar os usuários a gerenciar melhor suas tarefas e tempo, com feedback visual claro para o progresso de cada tarefa.

## Tecnologias Utilizadas
- **TypeScript**
- **HTML5**
- **JavaScript (ES6+)**

## Funcionalidades

### 1. Interfaces e Tipagem
- Definimos interfaces para estruturar e tipar conjuntos de propriedades, garantindo que cada objeto siga um padrão claro.
- Utilizamos tipos básicos como `string` e `boolean`, além de arrays tipados.

### 2. Imutabilidade e Programação Funcional
- Evitamos mutações diretas no estado da aplicação, aplicando a imutabilidade através do uso de funções puras e conceitos de programação funcional.

### 3. Manipulação de Arrays e Operador Spread
- Criamos e manipulamos arrays tipados, utilizando o operador spread (`...`) para clonagem e atualização de propriedades de objetos sem modificar o original.

### 4. Manipulação de Elementos do DOM
- Selecionamos, criamos e manipulamos elementos HTML dinamicamente através de métodos como `querySelector`, `createElement` e `appendChild`.

### 5. Uso de Templates Literais para SVG
- Utilizamos templates literais para criar e injetar elementos SVG diretamente no JavaScript, facilitando a manipulação e interação dinâmica.

### 6. Atualização da Interface com Base no Estado
- A interface é atualizada dinamicamente com base no estado da aplicação, utilizando a função `atualizarUI`. A lista de tarefas é re-renderizada sempre que o estado muda.

### 7. Manipulação de Classes e Atributos
- Utilizamos métodos como `classList.add` e `setAttribute` para adicionar, verificar e manipular classes e atributos nos elementos HTML, garantindo um feedback visual claro para o usuário.

### 8. Eventos Personalizados e Interações na UI
- Capturamos eventos de clique, como o botão de adicionar tarefas, e eventos personalizados, como `TarefaFinalizada`, para modificar o estado da aplicação e refletir mudanças na UI.

### 9. Feedback Visual para Tarefas Concluídas
- Tarefas concluídas recebem uma marcação visual diferenciada, utilizando classes CSS para alterar a aparência, tornando a interface mais intuitiva.

