# Análise de Qualidade em Repositórios Java Open-Source  

Este repositório contém a análise da qualidade de código de 1.000 repositórios Java populares do GitHub, correlacionando métricas de qualidade com características do processo de desenvolvimento.  

## 📌 Objetivo  
Investigar a relação entre popularidade, maturidade, atividade e tamanho dos repositórios com métricas de qualidade interna, como **CBO (acoplamento entre objetos), DIT (profundidade da árvore de herança) e LCOM (falta de coesão dos métodos)**, utilizando a ferramenta CK.  

## 🔍 Metodologia  
1. **Coleta de Dados**: Uso das APIs REST/GraphQL do GitHub para obter informações dos repositórios.  
2. **Extração de Métricas**: Aplicação da ferramenta CK para análise de código.  
3. **Análise Estatística**: Uso de medidas centrais (média, mediana e desvio padrão) e testes de correlação (Spearman/Pearson) para validar os resultados.  
4. **Visualização**: Geração de gráficos para interpretação dos dados.  

## 📊 Entregas  
- **Lab02S01**: Lista dos 1.000 repositórios + Script de automação + Amostra inicial de métricas.  
- **Lab02S02**: Coleta completa dos dados + Primeira versão do artigo.  
- **Lab02S03**: Análise estatística e visualização de dados + Relatório final.  

## 📅 Prazo Final  
**29/03** – Desconto de **1 ponto/dia** de atraso.  

🚀 **Este projeto busca entender como a colaboração em código open-source impacta sua qualidade interna!**
