# 💳 Simulador de Taxas Cielo - SolarMIX

Este é um **Simulador de Taxas Cielo** desenvolvido para a SolarMIX Energias Renováveis. A aplicação permite simular de forma rápida e prática as taxas aplicadas por bandeiras de cartões em transações de débito, crédito à vista e crédito parcelado.

## 🚀 Funcionalidades

- Simulação de taxas com base nas principais bandeiras: Visa, Mastercard, Elo, Amex, Hipercard e Diners.
- Cálculo de taxa percentual, valor da taxa e valor líquido da venda.
- Opção de crédito parcelado com seleção dinâmica de número de parcelas.
- Geração de PDF com os resultados da simulação.
- Compartilhamento da simulação via WhatsApp.
- Interface responsiva e amigável para desktop e mobile.

## 🧮 Tecnologias Utilizadas

- **HTML5 & CSS3** — Layout responsivo com foco em usabilidade e visual moderno.
- **JavaScript Puro** — Lógica de simulação de taxas e manipulação de DOM.
- **jsPDF** — Geração de arquivo PDF diretamente no navegador.
- **WhatsApp Web API** — Compartilhamento da simulação com um clique.

## 📦 Estrutura

```
📁 cielo_tax_simulator.html
    └── Código completo da aplicação (HTML, CSS, JS)
```

## 🖥️ Como usar

1. Abra o arquivo `cielo_tax_simulator.html` em qualquer navegador moderno.
2. Preencha:
   - O valor da venda.
   - A bandeira do cartão.
   - O tipo de transação (débito, crédito à vista ou parcelado).
   - Número de parcelas (quando aplicável).
3. Clique em **"Simular Taxas"**.
4. Visualize o resultado detalhado e utilize as opções de exportação:
   - Gerar PDF.
   - Compartilhar no WhatsApp.

## 🧠 Observações Técnicas

- O sistema utiliza formatação brasileira (ex: `R$ 1.000,00`).
- As taxas utilizadas estão baseadas em valores de mercado e podem ser ajustadas no objeto `taxasCielo` no código-fonte JavaScript.
- O app é completamente estático e não requer backend ou servidor.

## 📄 Licença

Este projeto é de uso interno da **SolarMIX Energias Renováveis**. Modificações e redistribuição requerem autorização prévia.

---

Desenvolvido com 💡 por Paulo Gomes


🔗 Acesse o simulador: [https://paulo-gomes0681.github.io/simulador-cielo/]
