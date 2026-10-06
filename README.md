# 🌿 EnferHub — SaaS de Prontuário & SAE Inteligente

> **A plataforma de prontuário eletrônico e Processo de Enfermagem desenhada sob medida para estudantes e profissionais de enfermagem.**

---

## 🎯 1. Visão do Produto & Proposta de Valor

Diferente dos prontuários hospitalares legados (construídos com foco médico ou puramente faturista), o **EnferHub** nasce para preencher a lacuna da prática clínica da enfermagem.

Com a atualização da **Resolução COFEN nº 736/2024** (que regulamenta o Processo de Enfermagem em todo o território nacional) e a crescente autonomia dos enfermeiros com **consultórios particulares e atendimento home care** (Resolução COFEN nº 568/2018), a demanda por uma ferramenta especializada nunca foi tão alta.

### 👥 Públicos-Alvo e Dores Resolvidas

| Público | Principais Dores | Como o EnferHub Resolve |
| :--- | :--- | :--- |
| **Estudantes de Enfermagem** | Dificuldade em estruturar evoluções nos estágios; insegurança ao correlacionar sinais e sintomas com diagnósticos (NANDA/CIPE); cálculos de medicamentos e gotejamento de soro. | **Modo Acadêmico Guiado:** Formulários passo a passo, sugestão inteligente de diagnósticos, checklists de exame físico céfalo-caudal e calculadoras clínicas integradas. |
| **Enfermeiros Autônomos (Consultórios & Home Care)** | Falta de prontuário acessível; planilhas e anotações em papel desorganizadas; risco de processos ético-legais por falta de documentação padronizada; prontuários médicos caros e incompatíveis com a SAE. | **Prontuário Ágil & Legal:** Foco em consulta de enfermagem, avaliação de feridas (estomaterapia), puerpério/amamentação, prontuário com assinatura digital, geração de relatórios em PDF com carimbo COREN. |
| **Docentes e Faculdades** | Dificuldade de acompanhar as anotações clínicas de dezenas de alunos em campo de estágio. | **Plano Institucional:** Ambiente de simulação onde o professor pode revisar, comentar e avaliar a evolução clínica feita pelo aluno. |

---

## 💎 2. Design System: Identidade Visual Clean & Healthcare

O design do EnferHub foi projetado para transmitir **precisão, tranquilidade, clareza e credibilidade**.

- **Cor Primária:** Verde Esmeralda Clínico (`#059669` / `#10B981`) — remete à saúde, renovação, cura e à tradicional cor da faixa de graduação da Enfermagem.
- **Cor de Fundo & Superfícies:** Cinza Gelo Neutro (`#F8FAFC`) e Branco Puro (`#FFFFFF`) — eliminam fadiga visual em plantões noturnos ou longas jornadas.
- **Tipografia:** `Inter` / `Plus Jakarta Sans` — sem serifa, legibilidade altíssima para termos clínicos e números de dosagens.
- **Micro-interações & Alertas:**
  - 🟢 **Verde Suave:** Parâmetros normais / conduta realizada
  - 🟡 **Âmbar:** Pendências de checagem / risco moderado
  - 🔴 **Rosa Claro/Vermelho Clínico:** Alergias destacadas / alto risco (Braden ≤ 12, dor intensa EVA > 7)

### 🎨 Logotipo & Favicon Criados:
- `assets/favicon.svg`: Símbolo moderno combinando a **Cruz da Saúde** com a **Chama da Lâmpada de Florence Nightingale**.
- `assets/logo.svg`: Logotipo horizontal completo com tipografia e posicionamento da marca.

---

## 🛠️ 3. As 5 Etapas do Processo de Enfermagem (COFEN 736/2024)

O EnferHub foi arquitetado diretamente em conformidade com as cinco etapas oficiais:

1. **Avaliação de Enfermagem:** Anamnese guiada e Exame Físico céfalo-caudal rápido (Neurológico, Respiratório, Cardiovascular, Abdome, Tegumentar, Dispositivos).
2. **Diagnóstico de Enfermagem:** Mapeamento de problemas e riscos (com base em NANDA-I e CIPE).
3. **Planejamento de Enfermagem:** Estabelecimento de metas e resultados esperados (NOC).
4. **Implementação de Enfermagem:** Prescrição dos cuidados (NIC) e checagem de horários.
5. **Evolução de Enfermagem:** Registro diário/por plantão com compilação inteligente para exportação ou impressão.

---

## 🚀 4. Modelo de Monetização SaaS

1. **Plano Gratuito / Freemium Acadêmico:**
   - Até 3 pacientes ativos simultâneos.
   - Acesso às calculadoras clínicas e guias de estágio.
   - Excelente porta de entrada para viralização entre turmas de graduação e cursos técnicos.

2. **Plano Estudante Pro (R$ 19,90 / mês):**
   - Pacientes ilimitados em modo estudo/estágio.
   - Biblioteca completa de diagnósticos e termos técnicos de enfermagem.
   - Exportação de relatórios clínicos para entrega aos preceptores.

3. **Plano Profissional Autônomo (R$ 49,90 / mês):**
   - Prontuário eletrônico completo para consultórios e atendimentos domiciliares.
   - Registro fotográfico de evolução de feridas (com régua milimetrada digital).
   - Assinatura digital com carimbo COREN e conformidade com LGPD.
   - Recibos e controle financeiro simplificado por atendimento.

4. **Plano Instituições / Faculdades (B2B):**
   - Licenciamento por número de alunos para uso em laboratórios de simulação e estágios.

---

## 💻 5. Como Testar o Protótipo Atual

O protótipo interativo já está pronto no repositório:

1. Abra o arquivo [index.html](file:///c:/Users/joao_/Desktop/Antigravity/enfermagem/index.html) diretamente no seu navegador.
2. Navegue entre:
   - **Painel Geral:** Visão de leitos, métricas de risco e tabela de pacientes.
   - **Prontuário Ativo:** Teste o Exame Físico, a **Calculadora da Escala de Braden** em tempo real e a geração dinâmica da **Evolução de Enfermagem**.
   - **Área do Estudante:** Teste a **Calculadora de Gotejamento de Soro (Macrogotas/Microgotas)**.

