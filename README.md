# SISTEMA DE COMPRA DE INGRESSOS (E-TICKET DASHBOARD)


Este projeto consiste em uma aplicação interativa para simular a compra e 
validação de ingressos para diferentes setores de um evento (Pista, Cadeira 
Superior e Cadeira Inferior). O script atualiza dinamicamente a quantidade 
de ingressos disponíveis exibida na tela, valida se há saldo suficiente 
para a quantidade solicitada e emite alertas de sucesso ou erro.

------------------------------------------------------------------------
1. FUNCIONALIDADES PRINCIPAIS
------------------------------------------------------------------------
* Seleção de Setor: Identifica o tipo de ingresso selecionado pelo usuário 
  (Pista, Superior ou Inferior) a partir de um campo de seleção.
* Validação de Disponibilidade: Verifica se a quantidade desejada é menor 
  ou igual ao número de ingressos ainda disponíveis para o setor escolhido.
* Atualização Dinâmica do DOM: Subtrai a quantidade comprada do painel 
  em tempo real, mantendo os dados da interface sempre sincronizados.
* Feedback ao Usuário: Exibe notificações visuais (alert) confirmando a 
  compra ou avisando sobre a indisponibilidade de ingressos.

------------------------------------------------------------------------
2. ESTRUTURA DO CÓDIGO JAVASCRIPT
------------------------------------------------------------------------
* `comprar()`: Função principal disparada pelo clique do botão de compra. 
  Ela captura o tipo de ingresso e a quantidade, direcionando a lógica 
  para a função de validação específica do setor.
* `comprarPista(qtd)`: Gerencia o estoque e a compra de ingressos do tipo Pista.
* `comprarSuperior(qtd)`: Gerencia o estoque e a compra de ingressos do tipo Superior.
* `comprarInferior(qtd)`: Gerencia o estoque e a compra de ingressos do tipo Inferior.

------------------------------------------------------------------------
3. TECNOLOGIAS UTILIZADAS
------------------------------------------------------------------------
* 🟡 JavaScript (ES6+) - Lógica de validação e manipulação de texto no DOM.
* 🌐 HTML5 - Estruturação dos campos de entrada, seleção e exibição de saldos.
* 🎨 CSS3 - Estilização visual e layout do painel de vendas.

------------------------------------------------------------------------
4. REFERÊNCIA DO PROJETO
------------------------------------------------------------------------
Este projeto foi desenvolvido com base no seguinte treinamento:
* Instituição: Alura
* Curso: Lógica de programação: Praticando com desafios

========================================================================
Criado para fins educacionais e consolidação de lógica aplicada ao DOM.
========================================================================
