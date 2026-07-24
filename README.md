# Artana Orçamentos 📊

Sistema web leve, rápido e responsivo desenvolvido para o **Departamento de Vendas da Artana Multistore**, focado no cálculo automatizado de materiais (Deck, Rodapés, Ripados e Ripados Externos), geração de orçamentos detalhados em tabela, cópia rápida para o WhatsApp e exportação oficial em PDF.

## 🚀 Funcionalidades

- **Cálculo Automático Instantâneo:** Atualiza os itens, quantidades e valores monetários em tempo real conforme você digita as medidas ou altera os produtos.
- **Campos Opcionais:** Inclusão automática do **Nome do Cliente** e de **Observações** personalizadas no orçamento.
- **Desconto Integrado:** Aplicação rápida de 10% de desconto sobre o valor final.
- **Formatação Monetária Brasileira:** Exibição limpa de valores no padrão oficial (`R$ 1.234,56`).
- **Exportação em PDF:** Gera um documento formatado profissionalmente com cabeçalho da empresa, tabela de itens e valores finais através das bibliotecas *jsPDF* e *AutoTable*.
- **Atalho para WhatsApp:** Copia o orçamento completo formatado diretamente para a área de transferência com um clique.

## 🛠️ Tecnologias Utilizadas

- **HTML5** e **CSS3** (Design limpo, responsivo e baseado em Flexbox).
- **JavaScript (Vanilla)** para a lógica de cálculo e manipulação dinâmica do DOM.
- **jsPDF** & **jsPDF-AutoTable** (CDN) para a geração dos relatórios em PDF.

## 📦 Como Usar

1. Acesse o arquivo `index.html` em qualquer navegador web moderno.
2. *(Opcional)* Preencha o **Nome do Cliente** e as **Observações**.
3. Selecione o **Tipo de Produto** desejado no menu suspenso.
4. Digite a **Quantidade** (m² ou Metro Linear). O cálculo será exibido instantaneamente na tabela abaixo.
5. Utilize os botões para **Aplicar Desconto**, **Copiar para o WhatsApp** ou **Baixar o PDF** do orçamento.
