# ☀️ Simulador de Economia – Energia por Assinatura Poupp

Simulador online para estimar quanto você pode economizar na conta de luz com a **energia solar por assinatura (Geração Distribuída – GD)** da **Poupp Energia**, para unidades consumidoras atendidas pela **Celesc (Santa Catarina)**.

Sem obra, sem instalação de placas e sem investimento: você continua recebendo energia da Celesc e paga menos pela parcela de energia da fatura.

---

## Como usar

1. Acesse o simulador.
2. Informe o **valor médio da sua conta de luz** (R$/mês).
3. Veja a **economia estimada por mês, em 12 meses e em 5 anos**, e compare as bandeiras tarifárias.
4. Clique em **Enviar pelo WhatsApp** para receber a proposta oficial.

> A Poupp atende contas a partir de **R$ 200/mês**.

---

## Premissas do cálculo

| Parâmetro | Valor | Observação |
|---|---|---|
| Desconto por bandeira | **15% verde · 18% amarela · 21% vermelha 1 · 25% vermelha 2** | Tabela da Poupp, conforme a bandeira do mês |
| Base do desconto | **Parcela de energia** da fatura | Não incide sobre impostos, taxas e iluminação pública |
| Participação da energia na fatura | **61,9%** | Média estimada; varia de conta para conta |
| Conta mínima | **R$ 200/mês** | Critério de atendimento da Poupp |

**Fórmula:**

```
Economia mensal = Valor da conta × 61,9% × desconto da bandeira
Economia anual  = Economia mensal × 12
```

Exemplo (bandeira verde): conta de R$ 1.000 → R$ 1.000 × 0,619 × 0,15 = **R$ 92,85/mês** (≈ R$ 1.114/ano).

---

## ⚠️ Aviso importante

Este simulador apresenta **valores estimados**, apenas para referência.
**A simulação não é a proposta oficial.** A proposta oficial da Poupp Energia é emitida somente após a análise da sua conta de energia.

---

## Fale comigo

**Valdoir Damazio** – Consultor Poupp Energia | Florianópolis/SC

- WhatsApp: [(48) 99808-9975](https://wa.me/5548998089975)
- E-mail: valdoirdamazio@me.com

---

## Tecnologia

Página estática em HTML, CSS e JavaScript, publicada via GitHub Pages.

Para publicar: **Settings → Pages → Branch: `main` / `(root)` → Save**. O arquivo principal deve se chamar `index.html`.
