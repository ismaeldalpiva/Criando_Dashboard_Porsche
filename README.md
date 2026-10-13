# Dashboard de Vendas da Porsche com Agentes de IA

Este repositório apresenta o desenvolvimento de uma dashboard de vendas interativa da Porsche, criada a partir de uma planilha bruta utilizando inteligência artificial (ChatGPT com Canvas) e publicada via **GitHub Pages**.

## 🚀 Visão Geral do Projeto
O objetivo do desafio foi transformar dados brutos de vendas em uma aplicação web funcional de arquivo único (`index.html`), incorporando design sofisticado, indicadores de desempenho (KPIs) e filtros dinâmicos.

## 📊 Perguntas de Negócio e KPIs
A dashboard foi estruturada para responder diretamente a importantes questões comerciais:
1. **Principais modelos vendidos por cidade:** Identificação dos veículos com maior saída em cada localidade.
2. **Modelo mais vendido por estado:** Visão regional consolidada.
3. **Ano-modelo de maior volume:** Análise de preferência temporal de fabricação.
4. **Insights de popularidade e formas de pagamento:** Comportamento de compra por região.

### Indicadores de Topo (KPIs)
- **Receita Total**
- **Modelo Líder**
- **Ano-Modelo com Maior Volume**
- **Total de Vendas**

## 🛠️ Tratamento dos Dados
Antes de alimentar a inteligência artificial, a base de dados passou por etapas críticas de saneamento:
- Exclusão de colunas não sanitizadas ou com fórmulas quebradas.
- Conversão e colagem como valores estáticos para evitar erros de leitura.
- `SalesPriceSanitized` formatada para o padrão contábil.
- `VehicleMileageSanitized` formatada para números.
- `DeliveryStatusSanitized` convertida para valores fixos.

## 🤖 Prompt Utilizado e Refinamentos
### Prompt Base
> "Utilizando o recurso do Canvas, renderize uma dashboard em HTML ao lado com foco em UI/UX elegante inspirado no site oficial da Porsche Brasil (https://www.porsche.com/brazil/pt/), utilizando paleta sofisticada (tons de cinza, off-white, preto e detalhes em vermelho). 
> 
> **Filtros:** Modelo da Porsche, Ano do Modelo, Cidade e Método de Pagamento.
> **Perguntas de Negócio:** Modelos vendidos por cidade, ano-modelo mais comercializado por período e insights de carros populares por cidade."

### Iterações Pós-Visualização
Após a primeira renderização, foram aplicados ajustes finos para otimizar a experiência de uso:
- Remoção dos filtros de data específica ("venda a partir de" e "venda até").
- Substituição do KPI de "preço médio" por "receita total".
- Inclusão do filtro de **Estado**.
- Adição da pergunta de negócio focada em vendas por estado.

## 🎨 Identidade Visual (UI/UX)
Inspirada diretamente no ecossistema digital da Porsche Brasil:
- Tipografia minimalista e hierarquia visual refinada.
- Layout responsivo adaptado para computadores e dispositivos móveis.
- Dados totalmente embutidos no HTML, garantindo independência operacional sem conexões externas complexas.

## 🌐 Acesso ao Projeto
Você pode acessar a versão interativa hospedada online:
- [Acesse a Dashboard no GitHub Pages](SEU_LINK_AQUI)

---
*Projeto desenvolvido como parte de um desafio prático de portfólio de engenharia de dados e IA.*