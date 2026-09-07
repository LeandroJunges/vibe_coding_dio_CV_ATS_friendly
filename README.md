#PROMPT para o lovable: 
# ATS CV Optimizer — Gerador e Otimizador de Currículos

## 1. Visão do produto

Crie uma aplicação web moderna, futurista e extremamente intuitiva chamada **ATS CV Optimizer**.

A aplicação será uma ferramenta de análise e otimização de currículos para processos seletivos.

O objetivo é permitir que o usuário:

1. Informe os dados de uma vaga.
2. Envie seu currículo atual.
3. Analise automaticamente o currículo em relação à vaga.
4. Calcule um índice de aderência entre o currículo e a vaga.
5. Identifique requisitos da vaga que já estão presentes no currículo.
6. Identifique palavras-chave importantes ausentes ou pouco evidenciadas.
7. Identifique pontos que podem melhorar a compatibilidade com sistemas ATS.
8. Gere uma versão otimizada do currículo.
9. Permita visualizar o currículo otimizado.
10. Permita exportar o novo currículo em PDF.

### Importante

A aplicação **não deve inventar experiências, conhecimentos, certificações, cargos ou habilidades que o usuário não possui**.

A otimização deve trabalhar somente com informações existentes no currículo e informações fornecidas pelo usuário.

O objetivo é melhorar:

* estrutura;
* clareza;
* organização;
* palavras-chave;
* descrição das experiências;
* destaque das competências;
* compatibilidade com ATS;
* legibilidade;
* correspondência com os requisitos da vaga.

---

# 2. Conceito visual

A aplicação deve transmitir uma sensação de:

* Inteligência Artificial;
* tecnologia;
* inovação;
* precisão;
* análise;
* futuro;
* carreira;
* software premium.

Utilizar uma identidade visual **futurista, sofisticada e tecnológica**, evitando aparência genérica de dashboard administrativo.

### Paleta sugerida

Utilizar principalmente:

* fundo escuro;
* azul elétrico;
* ciano;
* roxo neon;
* violeta;
* pequenos detalhes em verde para indicar sucesso;
* branco/cinza claro para textos.

Utilizar gradientes modernos, por exemplo:

* azul → roxo;
* ciano → azul;
* roxo → magenta.

Os efeitos neon devem ser utilizados com moderação.

### Estilo

Inspirar-se visualmente em:

* interfaces de produtos de IA;
* dashboards modernos;
* ferramentas SaaS premium;
* interfaces cyberpunk minimalistas;
* glassmorphism;
* cards com bordas sutis;
* gradientes;
* microanimações.

Evitar:

* excesso de elementos;
* visual infantil;
* excesso de neon;
* excesso de sombras;
* aparência de template administrativo;
* interfaces visualmente poluídas.

A interface deve parecer um produto SaaS moderno que poderia ser comercializado.

---

# 3. Público-alvo

A aplicação será destinada a pessoas que estão procurando emprego e desejam adaptar seu currículo para uma determinada vaga.

O usuário não precisa possuir conhecimento técnico.

A experiência deve ser extremamente simples.

---

# 4. Autenticação

## Não criar login.

A aplicação deve funcionar sem:

* cadastro;
* login;
* senha;
* autenticação;
* criação de conta.

O usuário entra na aplicação e pode imediatamente analisar seu currículo.

Não criar telas de:

* Login;
* Register;
* Forgot Password;
* Profile;
* Account.

---

# 5. Fluxo principal

O fluxo principal deverá ser:

```text
Landing Page
      ↓
Informar vaga
      ↓
Enviar currículo
      ↓
Analisar CV
      ↓
Resultado da análise
      ↓
Ver pontos fortes e gaps
      ↓
Otimizar currículo
      ↓
Visualizar novo CV
      ↓
Exportar PDF
```

---

# 6. Landing Page

Criar uma landing page simples e impactante.

## Hero

Headline:

> Seu currículo está preparado para a vaga?

Subheadline:

> Analise seu currículo contra uma vaga específica, descubra sua aderência e gere uma versão otimizada para ATS — sem inventar experiências.

CTA principal:

> Analisar meu currículo

CTA secundário:

> Como funciona?

### Elemento visual

Criar uma representação visual futurista mostrando:

```text
CURRÍCULO
     +
VAGA
     ↓
AI ANALYSIS
     ↓
87% MATCH
     ↓
ATS OPTIMIZED CV
```

Utilizar animações sutis.

---

# 7. Área de entrada

Criar uma tela chamada:

## "Vamos analisar seu currículo"

A tela deve possuir três entradas principais.

---

## 7.1 Vaga

Campo:

### "Título da vaga"

Exemplo:

```text
Desenvolvedor Full Stack Pleno
```

---

## 7.2 URL da vaga

Campo:

### "URL da vaga"

Placeholder:

```text
https://empresa.com/vagas/desenvolvedor-fullstack
```

Adicionar uma explicação:

> Cole o link da vaga para utilizar as informações publicadas pela empresa.

---

## 7.3 Descrição da vaga

Campo textarea:

### "Descrição da vaga"

Placeholder:

```text
Cole aqui a descrição completa da vaga...
```

Permitir que o usuário utilize somente a descrição caso não queira informar uma URL.

---

# 8. Upload do currículo

Criar uma área de upload extremamente destacada.

Título:

> Seu currículo

Descrição:

> Envie seu currículo atual para compararmos com os requisitos da vaga.

Aceitar:

* PDF;
* DOCX.

Área de drag & drop:

```text
┌─────────────────────────────────────┐
│                                     │
│          ↑                          │
│                                     │
│     Arraste seu currículo           │
│           ou                        │
│      Escolha um arquivo             │
│                                     │
│       PDF ou DOCX                   │
│                                     │
└─────────────────────────────────────┘
```

Depois do upload mostrar:

```text
✓ Curriculo_Leandro.pdf

2.4 MB
```

Permitir remover e substituir o arquivo.

---

# 9. Botão de análise

Botão principal:

> Analisar currículo

Ao clicar:

* validar os campos;
* verificar se existe currículo;
* verificar se existe informação suficiente sobre a vaga;
* iniciar análise.

Durante a análise mostrar uma experiência visual futurista.

Exemplo:

```text
ANALISANDO SEU CURRÍCULO

✓ Extraindo informações do currículo
✓ Identificando competências
◉ Comparando requisitos da vaga
○ Analisando palavras-chave
○ Calculando aderência
○ Identificando oportunidades
```

Utilizar animações suaves.

---

# 10. Resultado da análise

Criar uma página de resultado chamada:

# "Seu currículo foi analisado"

No topo mostrar um grande indicador:

```text
87%
ADERÊNCIA À VAGA
```

O indicador deve ser visualmente impactante.

Utilizar um gráfico circular/progress ring.

Mostrar também:

```text
Compatibilidade geral

████████████████░░░ 87%
```

---

# 11. Métricas da análise

Criar cards com indicadores.

### Experiência

```text
92%
```

### Competências técnicas

```text
88%
```

### Palavras-chave

```text
76%
```

### Formação

```text
100%
```

### Estrutura ATS

```text
91%
```

Os valores devem ser dinâmicos.

---

# 12. Análise detalhada

Criar uma seção:

## "Como seu currículo se compara à vaga"

Dividir em três categorias.

### Você já possui

Mostrar requisitos encontrados no currículo.

Exemplo:

```text
✓ Node.js
✓ TypeScript
✓ React
✓ PostgreSQL
✓ REST APIs
✓ Git
```

Cada item deve possuir uma pequena indicação explicando onde essa competência foi identificada.

---

# 13. Oportunidades de melhoria

Seção:

## "Você possui, mas pode destacar melhor"

Aqui devem aparecer competências ou requisitos que aparentemente estão presentes no currículo, mas estão mal descritos ou pouco destacados.

Exemplo:

```text
TypeScript

Encontramos experiência com TypeScript,
mas ela aparece pouco nas descrições das experiências profissionais.

Sugestão:
Evidenciar o uso de TypeScript nas experiências
onde essa tecnologia foi utilizada.
```

Adicionar botão:

> Aplicar melhoria

---

# 14. Gaps

Seção:

## "Requisitos não identificados"

Mostrar requisitos importantes da vaga que não foram encontrados no currículo.

Exemplo:

```text
Docker

Não encontramos evidências claras de experiência
com Docker no currículo.
```

Importante:

Não sugerir que o usuário adicione uma competência que ele não possui.

Mostrar:

> Se você possui essa experiência, podemos ajudar a destacá-la no currículo.

---

# 15. Palavras-chave

Criar uma seção:

## "Palavras-chave da vaga"

Utilizar tags.

Exemplo:

```text
Node.js
TypeScript
React
AWS
Docker
PostgreSQL
REST API
Microservices
CI/CD
Git
```

Separar visualmente:

### Encontradas

Tags verdes.

### Encontradas, mas pouco evidenciadas

Tags amarelas.

### Não identificadas

Tags vermelhas.

---

# 16. Análise ATS

Criar um card especial:

# "ATS Score"

Mostrar:

```text
91 / 100
```

Avaliar aspectos como:

* estrutura;
* títulos das seções;
* legibilidade;
* palavras-chave;
* experiência profissional;
* competências;
* formatação;
* excesso de elementos gráficos;
* compatibilidade com parsing;
* consistência das informações.

Mostrar recomendações.

Exemplo:

```text
✓ Estrutura clara
✓ Experiências bem identificadas
✓ Seções facilmente interpretáveis
⚠ Algumas experiências poderiam utilizar palavras-chave mais específicas
⚠ Algumas descrições possuem pouco contexto técnico
```

---

# 17. Botão de otimização

Depois da análise apresentar um CTA principal:

> Otimizar meu currículo

Texto auxiliar:

> Vamos melhorar a estrutura e destacar suas experiências relevantes para esta vaga sem adicionar informações que você não possui.

---

# 18. Tela de otimização

Mostrar uma comparação:

```text
CURRÍCULO ATUAL                 CURRÍCULO OTIMIZADO

Desenvolvimento de sistemas     Desenvolvimento de aplicações
                                Full Stack utilizando Node.js,
                                TypeScript e React...
```

Permitir visualizar:

### Antes

Currículo original.

### Depois

Currículo otimizado.

---

# 19. Sugestões de alterações

Para cada alteração mostrar:

```text
Experiência profissional

ANTES

Desenvolvimento de sistemas web.

↓

DEPOIS

Desenvolvimento de aplicações web utilizando
Node.js, TypeScript e React, atuando na criação
e manutenção de APIs REST e integração com
bancos de dados relacionais.
```

Mostrar a justificativa:

> A versão otimizada torna explícitas competências já presentes no currículo e melhora a correspondência com os requisitos da vaga.

Adicionar opção:

```text
✓ Aceitar alteração
↩ Manter original
```

Também permitir:

> Aceitar todas as sugestões

---

# 20. Editor do currículo

Criar um editor moderno de currículo.

Layout:

```text
┌─────────────────────┬─────────────────────────────┐
│                     │                             │
│   SEÇÕES            │       PREVIEW DO CV         │
│                     │                             │
│   Perfil             │   João da Silva             │
│   Experiência        │   Full Stack Developer      │
│   Formação           │                             │
│   Skills             │   Experiência               │
│   Projetos           │   ─────────────             │
│   Certificações      │                             │
│                     │   Empresa X                 │
│                     │   Desenvolvedor...          │
│                     │                             │
└─────────────────────┴─────────────────────────────┘
```

Permitir editar:

* nome;
* título profissional;
* resumo;
* experiências;
* formação;
* habilidades;
* idiomas;
* certificações;
* projetos;
* links profissionais.

---

# 21. Design do currículo exportado

O currículo gerado deve ser:

* profissional;
* minimalista;
* altamente legível;
* compatível com ATS;
* sem elementos que dificultem parsing;
* sem excesso de gráficos;
* sem barras de progresso de habilidades;
* sem ícones essenciais para transmitir informações;
* sem informações escondidas;
* com hierarquia clara.

Priorizar:

```text
Nome
Cargo
Contato
Resumo profissional
Experiência
Formação
Competências
Projetos
Certificações
Idiomas
```

O usuário deve poder escolher entre algumas variações de layout profissional, desde que todas mantenham compatibilidade com ATS.

---

# 22. Exportação

Criar botão:

> Exportar currículo

Opções:

```text
PDF
DOCX
```

O PDF deve preservar o layout apresentado no preview.

Nome sugerido:

```text
Curriculo_Otimizado_NomeSobrenome.pdf
```

---

# 23. Resultado final

Depois da exportação mostrar:

# "Seu currículo está pronto 🚀"

Mostrar:

```text
ATS Score

91 → 96

Aderência à vaga

87% → 94%
```

Mostrar resumo:

```text
✓ 12 palavras-chave relevantes destacadas
✓ 5 experiências melhor descritas
✓ 3 seções reorganizadas
✓ Estrutura otimizada para ATS
```

Botões:

> Baixar currículo

> Editar novamente

> Analisar outra vaga

---

# 24. Histórico da sessão

Como não haverá login, não criar histórico persistente de usuário.

Entretanto, enquanto a página estiver aberta, permitir manter os dados da análise atual em memória/localStorage para evitar perda acidental durante a edição.

Criar opção:

> Começar nova análise

Antes de apagar os dados, solicitar confirmação.

---

# 25. Responsividade

A aplicação deve ser totalmente responsiva.

Desktop:

* dashboard completo;
* editor lado a lado;
* preview do CV.

Tablet:

* layout adaptado.

Mobile:

* navegação vertical;
* cards empilhados;
* preview em largura completa;
* editor otimizado para tela pequena.

---

# 26. Componentes visuais

Criar componentes reutilizáveis para:

* Button;
* Input;
* Textarea;
* FileUploader;
* ProgressRing;
* ScoreCard;
* KeywordTag;
* AnalysisCard;
* RecommendationCard;
* ResumePreview;
* ResumeEditor;
* ComparisonView;
* LoadingAnalysis;
* Modal;
* Toast;
* EmptyState.

---

# 27. Estados da aplicação

Implementar claramente os estados:

```text
INITIAL
↓
JOB_INPUT
↓
CV_UPLOAD
↓
ANALYZING
↓
ANALYSIS_RESULT
↓
OPTIMIZING
↓
EDITOR
↓
EXPORTING
↓
COMPLETED
```

Também tratar:

```text
ERROR
EMPTY
INVALID_FILE
INVALID_JOB
NETWORK_ERROR
```

---

# 28. Experiência de usuário

A experiência deve passar a sensação de que o usuário está utilizando uma ferramenta de IA avançada.

Durante a análise, utilizar mensagens como:

```text
Extraindo seu perfil profissional...
```

```text
Identificando competências...
```

```text
Comparando seu perfil com os requisitos...
```

```text
Encontrando oportunidades de melhoria...
```

```text
Calculando compatibilidade ATS...
```

```text
Preparando recomendações...
```

As mensagens devem ser apresentadas com microanimações.

---

# 29. Segurança e privacidade

Como o usuário enviará um currículo, tratar os documentos como dados potencialmente sensíveis.

Não exibir dados do currículo em logs públicos.

Não armazenar permanentemente os documentos sem consentimento explícito.

Adicionar uma pequena mensagem próxima ao upload:

> Seus dados são utilizados apenas para realizar esta análise.

Caso o backend seja implementado posteriormente, preparar a arquitetura para permitir exclusão dos arquivos após o processamento.

---

# 30. Arquitetura

Separar claramente:

### Frontend

Responsável por:

* interface;
* upload;
* formulário;
* visualização;
* editor;
* resultados;
* preview;
* exportação.

### Backend/API

Preparar a aplicação para futuramente consumir endpoints como:

```text
POST /api/job/analyze
POST /api/resume/analyze
POST /api/resume/optimize
POST /api/resume/export
```

Não é necessário implementar autenticação.

---

# 31. Estrutura de dados

Criar modelos conceituais semelhantes a:

```typescript
Job {
  title: string
  url?: string
  description: string
}

Resume {
  fileName: string
  fileType: string
  content: string
}

AnalysisResult {
  overallScore: number
  atsScore: number
  experienceScore: number
  skillsScore: number
  keywordScore: number
  educationScore: number

  matchedKeywords: string[]
  weakKeywords: string[]
  missingKeywords: string[]

  strengths: string[]
  recommendations: Recommendation[]
  gaps: Gap[]
}
```

---

# 32. Regras importantes da IA

A lógica de análise deve seguir estas regras:

### Regra 1 — Nunca inventar

Não criar:

* experiências;
* tecnologias;
* certificações;
* cargos;
* resultados;
* empresas;
* formação;
* idiomas.

### Regra 2 — Evidência

Toda recomendação deve estar relacionada a alguma informação encontrada no currículo ou na vaga.

### Regra 3 — Otimização

A IA pode:

* reorganizar informações;
* melhorar redação;
* destacar competências existentes;
* utilizar palavras-chave existentes na vaga quando houver evidência no currículo;
* melhorar descrições;
* eliminar redundâncias;
* melhorar títulos e estrutura.

### Regra 4 — Transparência

Quando uma competência da vaga não for encontrada, mostrar claramente:

> Não identificamos essa competência no currículo enviado.

Não assumir que o candidato possui a competência.

---

# 33. Dashboard de resultado

Criar um dashboard visualmente impressionante.

Exemplo:

```text
┌──────────────────────────────────────────────────┐
│                                                  │
│             MATCH SCORE                          │
│                                                  │
│                 87%                              │
│                                                  │
│       Boa compatibilidade com a vaga             │
│                                                  │
└──────────────────────────────────────────────────┘

┌────────────┐ ┌────────────┐ ┌────────────┐
│ ATS        │ │ Skills     │ │ Experience │
│ 91         │ │ 88         │ │ 92         │
└────────────┘ └────────────┘ └────────────┘


PALAVRAS-CHAVE

✓ Node.js
✓ React
✓ TypeScript
✓ PostgreSQL

⚠ Docker
⚠ AWS

✕ Kubernetes
```

---

# 34. Copy da aplicação

Utilizar linguagem simples, direta e moderna.

Evitar linguagem excessivamente técnica.

Exemplos:

Em vez de:

> "Processamento semântico do documento curricular"

Utilizar:

> "Analisamos seu currículo para entender suas experiências e competências."

Em vez de:

> "Score de similaridade semântica"

Utilizar:

> "Aderência à vaga"

---

# 35. Sensação desejada

O usuário deve terminar a experiência pensando:

> "Agora eu sei exatamente o quanto meu currículo combina com essa vaga e o que posso melhorar."

A aplicação deve parecer:

**AI + Career + SaaS + Futuro**

e não apenas um simples gerador de currículo.

---

# 36. Prioridade de implementação

Implementar primeiro o fluxo principal:

```text
Landing
→ Dados da vaga
→ Upload CV
→ Loading
→ Análise
→ Score
→ Palavras-chave
→ Recomendações
→ Otimização
→ Preview
→ Exportação
```

Depois adicionar funcionalidades secundárias.

Priorizar uma experiência funcional e visualmente refinada em vez de adicionar muitas funcionalidades incompletas.

---

# 37. Critério de sucesso

Ao abrir a aplicação, o usuário deve conseguir entender em poucos segundos:

1. O que a ferramenta faz.
2. Que precisa informar uma vaga.
3. Que precisa enviar seu currículo.
4. Que receberá um score de aderência.
5. Que poderá gerar uma versão otimizada do currículo.

A aplicação deve ser **premium, futurista, simples de usar e visualmente surpreendente**, mantendo foco total no objetivo principal: **ajudar o candidato a apresentar melhor suas experiências reais para uma vaga específica e aumentar a compatibilidade do currículo com sistemas ATS.**

