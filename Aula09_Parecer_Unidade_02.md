# Parecer Individual – Unidade II: Programação Assistida por IA

**Aluno:** Luiz Fernando Nobre  
**Disciplina:** Engenharia de Prompt e Aplicações com IA  

---

## Descrição das Atividades Desenvolvidas

Durante a Unidade II, realizei quatro entregas práticas, organizadas em duas etapas principais, com grau crescente de dificuldade.

Na **primeira etapa (Aula 06/04)**, optei por um mini-projeto de nível iniciante: uma **Calculadora Simples**. Nela, implementei as quatro operações fundamentais com uso de `try/except` para garantir robustez — tratando divisão por zero e entradas não numéricas. O projeto seguiu exatamente o que foi proposto no material da aula.

Na **segunda etapa (Aula 14/04 – Sprint de Automação)**, executei três missões encadeadas:

- **Missão 1:** Script de automação de arquivos com `os` e `shutil`. Organiza uma pasta bagunçada em subpastas por extensão (PDF, JPG, MP3 etc.), movendo os arquivos corretamente. Todos os critérios de aceite foram atendidos.
- **Missão 2:** Consumo da API pública ViaCEP, com sistema resiliente usando múltiplos blocos `except` para tratar timeout, falhas de conexão, erros HTTP e JSON inválido.
- **Missão 3:** Monitoramento autônomo simulando leituras a cada 2 segundos, com disparo de alertas no console quando o valor ultrapassa um limiar crítico. O loop é infinito, mas pode ser interrompido por `KeyboardInterrupt`.

---

## Conexão com os Conceitos da Unidade

Todo o conteúdo teórico foi colocado em prática durante as missões. O **workflow Humano-IA** (humano define o problema → IA gera e refatora código) foi vivido na pele: usei a IA como copiloto ativo, sugerindo estruturas, completando funções e melhorando legibilidade. O ciclo colaborativo apresentado nos slides — Instrução → Processamento → Revisão → Ajuste — foi seguido à risca.

Sobre **ferramentas**:
- **GitHub Copilot** sugestões inline e refatoração no VS Code.
- **Google Colab (Jupyter)** ambiente principal de execução.
- **DeepSeek (IA assistente)** segunda camada de verificação e explicação de trechos mais obscuros.

Quanto à **ética e limites da automação**, a unidade deixou claro que IA acelera a escrita e acerta na sintaxe, mas erra feio em contexto de negócio, segurança e decisões estruturais. Isso apareceu claramente na Missão 2: precisei intervir manualmente para definir quais erros tratar e qual formato de saída serviria ao usuário final — a IA, sozinha, não tinha noção de "utilidade real"
