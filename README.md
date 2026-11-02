# Simulador de Investimentos
## 📌 Sobre o projeto
Este projeto consiste no desenvolvimento de uma ferramenta no **Microsoft Excel** para simular investimentos em Fundos de Investimento.

A planilha permite estimar a evolução de um investimento ao longo do tempo, considerando o valor dos aportes mensais, a taxa de rendimento, o patrimônio acumulado e os dividendos mensais estimados.

Também é possível visualizar cenários de investimento em diferentes períodos e distribuir os aportes entre categorias de FIIs de acordo com o perfil do investidor.

## 🎯 Objetivos

- Simular o crescimento do patrimônio a partir de aportes mensais.
- Estimar os dividendos mensais com base no patrimônio acumulado e no rendimento da carteira.
- Comparar projeções para diferentes prazos de investimento.
- Distribuir os aportes entre tipos de Fundos Imobiliários.
- Praticar o uso de fórmulas e recursos financeiros do Excel.

## 🧰 Ferramentas e recursos utilizados

- **Microsoft Excel:** desenvolvimento da planilha e organização dos dados.
- **Função VF:** cálculo do valor futuro dos aportes periódicos.
- **Função PROCV:** consulta dos percentuais de alocação definidos para cada perfil de investidor.
- **Intervalos nomeados:** facilitação da leitura e manutenção das fórmulas.
- **Tabela de apoio:** armazenamento dos percentuais de distribuição por perfil e tipo de FII.

## ⚙️ Funcionalidades

### 1. Configurações

A planilha permite informar o salário e o rendimento da carteira. Com base no salário, apresenta também uma sugestão de investimento correspondente a 30%.

### 2. Simulação do investimento mensal

O usuário pode definir:

- Valor que pretende investir por mês.
- Prazo do investimento em anos.
- Taxa de rendimento mensal estimada.

Com esses dados, a planilha calcula o patrimônio acumulado e estima os dividendos mensais.

### 3. Projeção de cenários

A ferramenta apresenta simulações para os seguintes períodos:

- 2 anos;
- 5 anos;
- 10 anos;
- 20 anos;
- 30 anos.

Para cada cenário, são calculados o patrimônio projetado e os dividendos mensais estimados.

### 4. Distribuição por perfil de investidor

A planilha permite selecionar um perfil de investidor:

- **Conservador**
- **Moderado**
- **Agressivo**

A partir do perfil escolhido, a função PROCV consulta a tabela de apoio e recupera os percentuais sugeridos para cada categoria de FII.

As categorias consideradas são:

- Papel;
- Tijolo;
- Híbridos;
- Fundos de Fundos (FOFs);
- Desenvolvimento;
- Hotelarias.

O valor mensal destinado a cada categoria é calculado com base no percentual correspondente.

## 🗂️ Estrutura do arquivo

O arquivo Excel contém duas abas principais:

| Aba | Descrição |
|---|---|
| `simulador de patrimônio` | Reúne as configurações, os dados do aporte mensal, as projeções de patrimônio e dividendos e a distribuição por perfil. |
| `tabela de apoio` | Armazena os percentuais de alocação para cada combinação de perfil de investidor e tipo de FII. |

## 🚀 Como utilizar

1. Faça o download do arquivo dentro de `file`.
2. Abra o arquivo Excel.
3. Na aba **simulador de patrimônio**, informe os dados de configuração e o valor do aporte mensal.
4. Defina o prazo e a taxa de rendimento mensal utilizada na simulação.
5. Consulte os resultados de patrimônio e dividendos estimados.
6. Compare os cenários de 2, 5, 10, 20 e 30 anos.
7. Selecione o perfil de investidor para visualizar a distribuição sugerida do aporte entre as categorias de FIIs.

Os valores e percentuais podem ser ajustados para testar diferentes hipóteses. As projeções dependem das premissas informadas na planilha.

## 📚 Aprendizados

O desenvolvimento deste projeto permite praticar:

- Organização e estruturação de planilhas;
- Aplicação de funções financeiras no Excel;
- Uso de funções de busca e referência;
- Criação e utilização de intervalos nomeados;
- Construção de tabelas de apoio;
- Simulação de cenários e projeções financeiras;
- Documentação de projetos para publicação no GitHub.

## ⚠️ Aviso

Este projeto tem finalidade **educacional**. As projeções são simulações matemáticas baseadas nas taxas e nos valores informados pelo usuário. Elas não representam garantia de rentabilidade, previsão de resultados reais ou recomendação de investimento.

---

**Tecnologia:** Microsoft Excel  
**Tema:** Educação financeira e simulação de investimentos em Fundos Imobiliários (FIIs)
'''