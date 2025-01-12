# Mineração de Dados

**Prof. Dr. Sergio N. Simões**  
**Pós-graduação em Desenvolvimento de Aplicações Inteligentes**  
**Mineração de Dados — Trabalho 01**

**Nome:** Otávio Lube dos Santos  
**Matrícula:** 20231DEVAI0157

# Respostas das Atividades

## Atividade 1

### 1-1) **Análise Exploratória**
**Observações sobre os dados:**
1. **Distribuição de Idades:** A variável "Age" apresenta uma distribuição enviesada à direita, indicando uma maior concentração de clientes em faixas etárias mais jovens.
2. **Renda Anual:** A variável "Income" também possui enviesamento à direita, com valores mais concentrados em faixas menores e poucos clientes em faixas de renda mais alta.
3. **Educação:** A maioria dos clientes possui ensino médio (categoria 1), enquanto apenas uma pequena fração alcançou o nível de graduação.
4. **Status Marital:** Existe equilíbrio entre clientes solteiros e não solteiros.
5. **Sexo:** Há equilíbrio entre homens e mulheres no dataset.

### 1-2) **Análise de Clustering**
**Relatório sobre os clusters:**
- **Cluster 0:** Solteiros, homens, cidades pequenas, empregados ou autônomos.
- **Cluster 1:** Não solteiras, mulheres, cidades pequenas, desempregadas ou funcionárias.
- **Cluster 2:** Não solteiras, mulheres, cidades médias/grandes, empresárias/autônomas.
- **Cluster 3:** Solteiros, homens, cidades médias/grandes, empregados/autônomos.
- **Cluster 4:** Não solteiros, homens.
- **Cluster 5:** Solteiras, mulheres, cidades pequenas.

### 1-3) **Conclusão Multivariada**
- **Pontos principais:**
  1. Pessoas em cidades pequenas têm rendas mais baixas.
  2. Gerentes ou empresários têm rendas mais altas.
  3. Nível educacional superior não influencia diretamente a renda.
  4. Não solteiros têm rendas mais baixas e são geralmente mais jovens.
  5. Homens mais velhos têm rendas mais altas.

Gráficos de dispersão e histogramas (especialmente os resultados de clusters) são úteis para justificar essas conclusões.

### 1-4) **Gráficos que embasam conclusões dos clusters:**
- **Cluster 0:** Histogramas de "Age", "Occupation" e "Settlement size".
- **Cluster 1:** Histogramas de "Sex", "Marital status" e "Occupation".
- **Cluster 2:** Dispersões e histogramas de "Income" por "Education" e "Settlement size".

### 1-5) **Estratégias de Marketing para Cluster 2:**
- Focar em produtos premium ou serviços personalizados.
- Marketing digital com segmentação para grandes centros urbanos.
- Ofertas relacionadas à gestão e empreendedorismo.

### 1-6) **Pesquisa sobre Árvores de Decisão**
Árvores de decisão são úteis para interpretar clusters pois criam divisões claras e hierárquicas entre os dados. A partir disso, cada divisão descreve um conjunto de regras baseadas nos atributos.

---

## Atividade 2

### 2-1) **O que é Clustering e aplicações**
Clustering é a técnica de agrupar dados semelhantes sem rótulos prévios. Aplicações incluem segmentação de clientes, detecção de anomalias e análise de comportamentos.

### 2-2) **Por que é não supervisionado?**
Não há rótulos ou variáveis-alvo. O modelo agrupa com base em semelhanças intrínsecas dos dados.

### 2-3) **Diferença entre Hierárquico e Particional**
- **Hierárquico:** Cria uma estrutura em árvore, útil para conjuntos pequenos.
- **Particional (ex.: K-Means):** Agrupa em número fixo de clusters, adequado para grandes bases.

### 2-4) **Como funciona K-Means?**
- Inicializa centros aleatórios para clusters.
- Atribui pontos ao cluster mais próximo.
- Recalcula os centros até convergir.

**Outros métodos:** DBSCAN, Mean-Shift, e Agglomerative Clustering.

### 2-5) **Métricas de distâncias em Clustering**
- Distância Euclidiana, Manhattan e Cosine são as mais comuns.

### 2-6) **Critérios de Linkage**
- **Single linkage:** Agrupa pelo ponto mais próximo.
- **Complete linkage:** Considera o ponto mais distante.
- **Average linkage:** Calcula a média de distâncias.
