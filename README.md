# 🛒 Artana Orçamentos - Gerador de Orçamentos Rápidos

Um sistema web leve e responsivo desenvolvido para a equipe de vendas da **Artana Multistore**. O aplicativo permite a criação rápida de orçamentos, cálculo automático de materiais (como Decks, Ripados e Rodapés), adição de itens extras e exportação direta para PDF e WhatsApp.

## ✨ Funcionalidades

- **Cálculo em Tempo Real:** Digite a medida e veja o orçamento sendo montado instantaneamente.
- **Múltiplos Produtos:** Fórmulas integradas para Decks (calculando barrotes, presilhas, etc.), Ripados e Rodapés.
- **Painel de Itens Adicionais:** Adicione produtos extras como Brises, Colas, Selantes ou até mesmo **Itens Personalizados (Manuais)**.
- **Sistema de Descontos Flexível:** Aplique desconto fixo de 10% ou insira descontos manuais em Porcentagem (%) ou Dinheiro (R$).
- **Exportação Profissional:**
  - **PDF:** Gera um documento em PDF pronto para o cliente, com o logotipo da empresa (mantendo a proporção correta).
  - **WhatsApp:** Copia o orçamento formatado (com negritos e quebras de linha) direto para a área de transferência.
- **Prevenção de Perda (Auto-save):** O sistema salva os dados automaticamente no `localStorage`. Se a página for fechada acidentalmente, o orçamento não é perdido.
- **Notificações Modernas (Toasts):** Alertas visuais elegantes e não intrusivos no topo da tela.

## 🚀 Como Usar (Instalação)

O projeto é **100% Client-Side** (roda direto no navegador), não necessitando de servidor, banco de dados ou backend.

1. Faça o clone do repositório:
   ```bash
   git clone [https://github.com/SEU_USUARIO/artana-orcamentos.git](https://github.com/SEU_USUARIO/artana-orcamentos.git)
