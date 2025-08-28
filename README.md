# 📊 ENEM 2023 Data Analysis

Este projeto realiza uma análise exploratória dos **microdados do ENEM 2023**, utilizando **Python**, **SQL (SQLite)** e visualizações gráficas.  
O objetivo é extrair **insights relevantes sobre desempenho, perfil socioeconômico e características dos participantes**.

---

## Dataset

O arquivo `MICRODADOS_ENEM_2023.csv` contém informações detalhadas sobre candidatos que participaram do exame.  
Esses dados são disponibilizados oficialmente pelo **INEP**.

### Principais colunas utilizadas:
- `NU_INSCRICAO` → identificador do candidato  
- `TP_SEXO` → sexo do participante  
- `TP_FAIXA_ETARIA` → faixa etária  
- `TP_COR_RACA` → cor/raça declarada  
- `TP_ESCOLA` → tipo de escola (pública/privada)  
- `TP_DEPENDENCIA_ADM_ESC` → dependência administrativa da escola  
- `SG_UF_PROVA` → estado de realização da prova  
- `NU_NOTA_CN` → nota Ciências da Natureza  
- `NU_NOTA_CH` → nota Ciências Humanas  
- `NU_NOTA_LC` → nota Linguagens e Códigos  
- `NU_NOTA_MT` → nota Matemática  
- `NU_NOTA_REDACAO` → nota Redação  
- `Q001`–`Q025` → questionário socioeconômico (ex.: escolaridade dos pais, renda, bens)  

---

## Perguntas de Análise

Durante a análise exploratória, foram respondidas perguntas como:

1. Qual a média geral das notas dos participantes?  
2. Como as notas variam por sexo, idade, raça e tipo de escola?  
3. Quais estados apresentaram as maiores médias de nota?  
4. Qual a distribuição da renda familiar (Q006) por cor/raça?  
5. Qual a relação entre escolaridade dos pais e desempenho dos filhos?  
6. Qual a taxa de conclusão do Ensino Médio por estado?  
7. Como está distribuído o percentual de treineiros (IN_TREINEIRO)?  
8. Quais diferenças aparecem nas médias por dependência administrativa da escola?  
9. Existe correlação entre renda, acesso à internet (Q025) e desempenho?  
10. Quais perfis socioeconômicos se destacam entre os melhores desempenhos?

---

## Tecnologias Utilizadas
- **Python**  
- **Jupyter Notebook**  
- **SQLite (via sqlite3)**  
- **Pandas**  
- **Matplotlib / Seaborn**  

---

## ▶️ Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/gubrandaods7/enem-2023-analysis.git
cd enem-2023-analysis
```
2. Baixe os microdados oficiais do ENEM 2023 no portal do INEP.
3. Extraia o arquivo MICRODADOS_ENEM_2023.csv para a pasta do projeto.
4. Abra o Jupyter Notebook e execute as análises.

---

## Autor

**Gustavo Brandão**

📧 E-mail: gubrandaods@gmail.com  
🐙 GitHub: [github.com/gubrandaods7](https://github.com/gubrandaods7)  
🔗 LinkedIn: [linkedin.com/in/gustavo-brandao-0b7635197](https://www.linkedin.com/in/gustavo-brandao-0b7635197)
