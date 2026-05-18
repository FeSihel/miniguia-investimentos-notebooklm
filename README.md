# 📈 Miniguia de Estudos: Introdução a Investimentos com NotebookLM

Bem-vindo ao repositório do meu projeto prático desenvolvido para o desafio de projeto da **DIO (Digital Innovation One)**! Este projeto demonstra a aplicação prática da Inteligência Artificial (utilizando o Google NotebookLM) como uma ferramenta de aprendizagem ativa, integrando pensamento crítico, curadoria de fontes oficiais e engenharia de prompts.

---

## 🚀 Caderno Temático no NotebookLM

O ambiente interativo e contextualizado deste projeto pode ser acessado diretamente através do link público abaixo:

🔗 **[Acessar Caderno de Estudos no NotebookLM](https://notebooklm.google.com/notebook/b50b9e9d-0a1b-4148-9720-148cedc88a73)**

---

## 🎯 Contexto e Objetivos

### Contexto
O ecossistema financeiro e o mercado de capitais frequentemente parecem complexos para novos investidores devido à densidade de jargões técnicos e à diversidade de ativos disponíveis. Para construir um entendimento sólido e mitigar riscos de tomada de decisão, este projeto utilizou o **NotebookLM** para estruturar um ecossistema de aprendizado fechado (*grounding*), focado em conceitos de educação financeira, funcionamento da Bolsa de Valores e dinâmica dos títulos públicos.

### Objetivos de Estudo
* **Compreender as dimensões fundamentais:** Dominar as engrenagens do "Tripé dos Investimentos" (Retorno, Risco e Liquidez) com base em diretrizes oficiais de regulação.
* **Mapear a mecânica de negociação:** Diferenciar o comportamento estrutural e os riscos de liquidez entre ativos de Renda Fixa e Renda Variável (Ações e Fundos Imobiliários).
* **Desenvolver Engenharia de Prompts:** Testar os limites do modelo de IA para gerar análises comparativas profundas, mitigando alucinações por meio de contextos estritamente delimitados.

---

## 📚 Curadoria de Fontes Selecionadas

Para alimentar o NotebookLM com informações de alta qualidade e confiabilidade técnica, foram selecionadas e submetidas as seguintes fontes abertas:

1. **[PDF] CVM Educacional - Módulo 06: Introdução aos Investimentos:** Documento oficial e institucional da Comissão de Valores Mobiliários (CVM) que serviu de base principal para a estruturação do tripé financeiro, classificação de riscos e conceito de *suitability*.
2. **[Link] Wikipédia - Bolsa de Valores:** Base de dados de consulta pública detalhando o histórico, infraestrutura de mercado e o ambiente de liquidação de títulos de capitais.
3. **[Link] Blog Sicredi - Guia de Investimento na Bolsa:** Artigo prático e mercadológico focado na jornada do investidor iniciante, detalhando o papel das corretoras e a execução de ordens de compra e venda.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

A documentação do processo de comunicação com a IA demonstra o raciocínio analítico aplicado para extrair o melhor resultado das fontes fornecidas.

### O Teste de Validação Avançada (A Pergunta Estratégica)
Para validar se o NotebookLM estava operando sob restrição estrita das fontes (*grounding*) ou se utilizava conhecimento genérico da internet, elaborei o seguinte prompt de engenharia reversa:

> **Prompt:** *"Com base estritamente nos documentos fornecidos, explique como o pilar da Liquidez se comporta de forma diferente quando um investidor decide sair de uma Ação negociada na Bolsa de Valores versus quando ele decide resgatar um título do Tesouro Direto antes do vencimento."*

### O Resultado Obtido e Análise Crítica (Troubleshooting)
O modelo realizou o cruzamento de dados com precisão cirúrgica, dividindo a lógica estrutural em dois grandes blocos:

1. **Responsabilidade e Mecanismo de Recompra:**
   * **Ações na Bolsa:** As empresas emissoras não têm obrigação de resgatar ou recomprar o título do investidor. A liquidez depende inteiramente do mercado secundário — ou seja, de encontrar outro investidor interessado no pregão.
   * **Tesouro Direto:** O emissor (o Tesouro Nacional/Governo) garante a recompra diária dos títulos públicos, eliminando o risco de falta de contraparte para o resgate antecipado.
2. **Formação de Preço e Volatilidade:**
   * **Ações na Bolsa:** A liquidez é ditada estritamente pelo volume de ofertas de compra e venda. Em cenários de baixa liquidez, o investidor é forçado a aceitar preços desalinhados com o valor "justo" se precisar de saída imediata.
   * **Tesouro Direto:** Embora a liquidez seja garantida pelo governo, o resgate antecipado ocorre pelo valor de mercado do dia, aplicando o conceito de **Marcação a Mercado**. Variações nas taxas de juros da economia podem impor prejuízos financeiros ao investidor se ele sair antes do prazo de vencimento pactuado.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Assunto

#### O Tripé dos Investimentos (Matriz CVM)
De acordo com o material oficial da CVM, antes de aceitar qualquer oferta de investimento, o investidor deve analisar de forma planejada o equilíbrio de três variáveis interdependentes:
* **Retorno:** A expectativa de ganho real da aplicação. Pode apresentar regras rígidas no momento da contratação (Renda Fixa) ou flutuar conforme o desempenho corporativo e macroeconômico (Renda Variável).
* **Risco:** A medida de incerteza em finanças. Consiste na probabilidade de o retorno real diferir do esperado. Desdobra-se em *Risco de Mercado* (oscilações de preços e taxas) e *Risco de Crédito* (inadimplência ou "calote" do emissor).
* **Liquidez:** A facilidade e a rapidez com que um ativo financeiro pode ser convertido em dinheiro em caixa, sem que ocorra perda significativa de seu valor justo.

---

### 2. 🔤 Glossário de Conceitos Aprendidos

* **Renda Fixa Pré-fixada:** Ativo financeiro cuja taxa de juros e rendimento exato em reais são conhecidos e fixados no exato momento da aplicação.
* **Renda Fixa Pós-fixada:** Modalidade onde a rentabilidade final é atrelada ao desempenho de um indexador econômico de referência (como a Taxa Selic ou o CDI), conhecendo-se apenas o critério de rendimento na compra.
* **Ações:** Títulos patrimoniais que representam a menor fração do capital social de uma sociedade anônima. Confere ao detentor a condição de coproprietário da empresa, participando de seus lucros (dividendos) e riscos.
* **Debêntures:** Títulos de dívida de médio e longo prazo emitidos por empresas de capital aberto para captação de recursos de médio e longo prazo. Funcionam como um contrato de empréstimo onde o investidor é o credor da companhia.
* **Fundos Imobiliários (FII):** Condomínios fechados de recursos que captam capital para aplicar em ativos do setor imobiliário (sejam físicos, como shoppings e galpões logísticos, ou papéis de crédito do setor). Suas cotas são livremente negociadas no ambiente da Bolsa.
* **Suitability:** Regulamentação que exige a análise e verificação do perfil do cliente (conservador, moderado ou arrojado) antes da recomendação de qualquer produto financeiro, garantindo a adequação aos objetivos e tolerância a riscos.

---

### 3. 🔄 Prompts Reutilizáveis para Revisão Ativa

Insira estes prompts no chat do seu NotebookLM para conduzir sessões de revisão dinâmica:

```text
Prompt 1 - Simulação de Flashcards (Autoavaliação):
"Com base exclusivamente no Módulo 06 da CVM, formule 3 questões de múltipla escolha focadas na distinção entre Risco de Mercado e Risco de Crédito. Apresente uma questão por vez e aguarde minha resposta antes de fornecer o gabarito e a devida justificativa teórica."
Prompt 2 - Abstração Didática (Analogias Concretas):
"Aja como um professor de finanças focado em acessibilidade e didática. Explique a dinâmica da 'Marcação a Mercado' em títulos pós-fixados e pré-fixados utilizando uma analogia simples com o mercado de compra e venda de veículos usados."
Prompt 3 - Análise de Cenário e Mitigação de Riscos:
"Considerando os textos anexados sobre o funcionamento da Bolsa de Valores e os cuidados apontados pela CVM, elabore um checklist de 4 pontos fundamentais que um investidor iniciante deve checar antes de realizar a compra de sua primeira ação ordinária."

🛠️ Tecnologias Utilizadas
Google NotebookLM (Mecanismo de IA e Engenharia de Contexto)
GitHub (Versionamento e Portfólio Digital)
Markdown (Estruturação e Formatação de Conteúdo)

Desenvolvido com foco técnico e pensamento crítico por Felipe Sihel Lipszyc para a comunidade DIO.
