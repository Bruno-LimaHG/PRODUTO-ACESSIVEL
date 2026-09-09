# Produto Acessível e Animado 🛒

Este repositório contém a atividade da **Semana 20**, focada no desenvolvimento de uma página de produto que integra boas práticas de **acessibilidade digital** e **animações interativas**.

## 🎯 Objetivo
Criar uma interface visualmente atraente utilizando animações e interações, garantindo que o conteúdo seja acessível para pessoas com deficiência através do uso de tecnologias assistivas, como leitores de tela e navegação por teclado.

## 🛠️ Tecnologias Utilizadas
- **HTML5**: Estrutura semântica rigorosa (uso de tags como `<main>`, `<h1>`, `<p>`, `<button>`).
- **CSS3**: Estilização, *Hover*, *Focus Visible* e *Transitions* suaves.
- **JavaScript (Vanilla)**: Manipulação da DOM para mensagens interativas.
- **GSAP (GreenSock)**: Biblioteca JavaScript utilizada para a animação de entrada (surgimento da página de produto).

## ♿ Recursos de Acessibilidade Aplicados
- **HTML Semântico:** As tags corretas para os elementos corretos.
- **`aria-label`:** Utilizado no botão de compra para descrever sua função, substituindo apenas um ícone visual por um texto legível por leitores de tela.
- **`aria-live="polite"`:** Utilizado na caixa de mensagens interativas para informar automaticamente aos leitores de tela quando um produto é adicionado ao carrinho, sem interromper o fluxo do usuário.
- **Texto Alternativo (`alt`):** Imagem do produto descrita adequadamente para deficientes visuais.
- **Navegação por teclado:** Todos os botões e áreas interativas podem ser acessados usando a tecla `Tab`.
- **Foco Visível (`:focus-visible`):** Adição de borda evidente ao navegar pelo teclado, garantindo que o usuário saiba exatamente onde está na página.

## 🚀 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/Bruno-LimaHG/produto-acessivel.git
   ```
2. Abra a pasta do projeto no seu editor de código (como o VS Code).
3. Utilize a extensão **Live Server** para abrir o arquivo `index.html` no seu navegador.
4. Experimente usar a página apenas com o teclado (tecla `Tab`) e perceba o contorno de foco nos botões!

## 🔎 Ferramentas de Teste
Este projeto passou por auditorias de acessibilidade para detecção de barreiras:
- **Lighthouse** (Ferramenta nativa do Google Chrome)
- Testes manuais guiados sem uso de mouse.
