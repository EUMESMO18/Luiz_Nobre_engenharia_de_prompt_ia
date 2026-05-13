# Desafio Unidade 3 - Cadastro de Usuários

Para a realização deste desafio, selecionei o projeto de **Cadastro de Usuários**. A solução será desenvolvida utilizando a plataforma **WIX**, 
focando em uma interface funcional e fluxos de dados eficientes.

<img width="1896" height="964" alt="Captura de tela 2026-05-12 205758" src="https://github.com/user-attachments/assets/f36a23fa-e759-4dc9-b581-25082a22fbdb" />
<img width="1906" height="966" alt="Captura de tela 2026-05-12 205934" src="https://github.com/user-attachments/assets/348df13f-6152-4964-902b-bb7879dbc099" />

# Justificativa Técnica da Escolha da Plataforma
## Por que escolhemos o Wix?

Para este desafio, a escolha do **Wix** não foi por acaso. A gente precisava de uma plataforma que unisse agilidade com um visual profissional, e o Wix entrega exatamente isso através de alguns pontos principais:

*   **Fácil de usar, fácil de navegar:** A interface é muito intuitiva. Isso ajudou a gente a não perder tempo batendo cabeça com ferramentas complexas e focar no que realmente importa: a estrutura do projeto e como o usuário vai interagir com ele.
*   **Praticidade com o "Arrastar e Soltar":** O sistema de *Drag and Drop*, Ele dá uma liberdade enorme para montar o layout do jeito que a gente imaginou, permitindo criar um design moderno sem precisar ficar preso a códigos manuais travados.
*   **Foco na Experiência (UX):** Como a plataforma resolve a parte bruta da interface de um jeito rápido, sobrou mais tempo para a gente pensar na jornada do usuário e garantir que o cadastro seja simples e direto, sem enrolação.

# - Ánalise Critica;
## - Vantagens (Potencialidades)
1. **Prototipagem rápida sem código.**
O Wix permitiu montar o formulário de cadastro em poucos minutos, sem escrever uma linha de código. Para MVPs e projetos de prazo curto como este, isso é uma vantagem real — a equipe consegue validar a ideia antes de investir em desenvolvimento tradicional.

2. **Interface visual intuitiva (Drag and Drop).**
A curva de aprendizado é praticamente nula. Qualquer membro do grupo conseguiu contribuir com o projeto sem depender de um perfil técnico específico, o que facilita a colaboração e a divisão de responsabilidades.

3. **Banco de dados integrado (Wix CMS).**
O Wix oferece um banco de dados nativo que armazena automaticamente os dados do cadastro, sem necessidade de integrar ferramentas externas. Isso reduz a complexidade da arquitetura para casos de uso simples como o nosso.

## - Limitações
1. **Dificuldade em customizações complexas.**
O Wix impõe limites no que pode ser feito fora dos seus componentes nativos. Qualquer lógica de negócio mais sofisticada — como validações avançadas, regras de acesso por perfil ou integração com sistemas externos — exige o uso do Velo (JavaScript proprietário da plataforma), o que contradiz a proposta no-code.

2. **Dependência de plataforma externa (Vendor Lock-in).**
Todo o projeto fica hospedado e vinculado à infraestrutura do Wix. Se a plataforma mudar seus preços, descontinuar funcionalidades ou sair do ar, não há controle sobre os dados ou a continuidade do serviço — um risco real de lock-in tecnológico.

3. **Menor controle sobre performance e segurança.**
Como a plataforma gerencia toda a infraestrutura, não é possível configurar aspectos críticos como políticas de senha, criptografia dos dados cadastrados ou tempo de resposta do servidor. Para um sistema de cadastro real, isso seria uma limitação de segurança relevante.




# Colaboração do Grupo

| Integrante | Responsabilidades |
|---|---|
| **Luiz Fernando Nobre** | Criação do layout da página de cadastro no Wix, configuração do formulário e campos de entrada, testes de usabilidade e captura dos prints para documentação |
| **Samuel Natalicio da Silva** | Estruturação do repositório no GitHub, redação do README (justificativa técnica e análise crítica)
