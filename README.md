# 📊 Simulador de Investimentos em Fundos Imobiliários (Excel)

## 🧠 Descrição do Projeto

Este projeto foi desenvolvido como parte de um laboratório prático com o objetivo de aplicar conceitos de **Excel financeiro** na criação de uma ferramenta de simulação de investimentos em **Fundos Imobiliários (FIIs)**. A planilha permite ao usuário explorar diferentes cenários com base em:

- Valor inicial investido
- Aportes mensais
- Tempo de investimento
- Rentabilidade esperada

> A proposta é **automatizar cálculos financeiros complexos** para facilitar a tomada de decisão dos investidores.

---

## 🎯 Objetivos de Aprendizagem

- Criar ferramentas de simulação de investimentos no Excel
- Aplicar cálculos como juros compostos e rendimento mensal
- Automatizar o cálculo de dividendos e patrimônio acumulado
- Estruturar documentação técnica com Markdown e GitHub

---

## 🧰 Funcionalidades da Planilha

### ✅ Parâmetros Personalizáveis

- Valor de Investimento Inicial
- Aporte Mensal
- Rentabilidade Mensal (%)
- Prazo de Investimento (meses)

---

### 📈 Cálculo de Patrimônio Acumulado

A planilha utiliza fórmulas para calcular o crescimento do patrimônio com base em **juros compostos**, considerando aportes mensais e reinvestimento de dividendos.

```excel
=VF(taxa_mensal;qtd_anos*12;aporte*-1)
```

---

### 💸 Simulação de Dividendos Mensais

Os dividendos são calculados com base na **rentabilidade mensal**, mostrando ao usuário quanto ele receberia mês a mês:

```excel
=patrimônio_mensal * rentabilidade
```

Além disso, é possível visualizar:

- Total acumulado de dividendos
- Dividendos por mês
- Média mensal de rendimento

---

## 🗂 Estrutura do Projeto

```bash
📁 Simulador-Fundos-Imobiliarios
├── README.md
├── Simulador_Investimentos_Fundos_Imobiliarios_Excel.xlsx
├── 📁 images
│   └── banner_fii.png
```

---

## 📝 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/simulador-fundos-imobiliarios.git
   ```
2. Abra o arquivo `.xlsx` no Excel
3. Edite os campos de entrada com seus dados
4. Visualize o retorno simulado e os dividendos

---

## 🧪 O que Aprendi

✅ Aplicação prática de **funções financeiras do Excel**  
✅ Criação de simulações dinâmicas com **referência absoluta e relativa**  
✅ Organização e documentação técnica usando **Markdown no GitHub**  
✅ Uso de **gráficos automatizados** para visualização clara de resultados

---

## 📎 Recursos Adicionais

- [Documentação do GitHub](https://docs.github.com/)
- [Guia Markdown GitHub](https://guides.github.com/features/mastering-markdown/)
- [GitHub Quick Start](https://github.com/githubtraining/hellogitworld)
- [Formação GitHub Certification (GitBook)](https://open-gitbook.org)
