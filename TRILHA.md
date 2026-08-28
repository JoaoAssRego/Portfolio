# Trilha de Aprendizado de Desenvolvimento Web + Plano de Portfólio para o Mercado Brasileiro

## TL;DR
- **Faça o portfólio final em React + TypeScript, hospedado na Vercel — não fullstack.** O mercado júnior brasileiro (Nubank, Globo, PagBank, Mercado Livre, iFood, Stone, C6) pede React + TypeScript com muito mais frequência do que backend próprio; um portfólio fullstack adiciona complexidade que os recrutadores não olham primeiro e ainda sofre com hospedagem gratuita que "hiberna". Demonstre habilidade fullstack em UM projeto separado dedicado.
- **A trilha correta é HTML → CSS → JavaScript (a fase mais longa) → Git/terminal/npm → React → TypeScript → Node/Express + banco → testes/deploy**, algo em torno de 8 a 9 meses no ritmo de 5–10h/semana. JavaScript sólido e um projeto real bem publicado valem mais que muitos clones de tutorial.
- **Comece a construir o portfólio cedo:** uma v1 estática logo após CSS (para já ter link no currículo), uma v2 reescrita em React + TypeScript, e uma v3 polida com testes, acessibilidade e performance no fim. Priorize sempre 2–3 projetos com deploy ao vivo, README bom e código limpo em vez de quantidade.

## Key Findings
1. **React domina o frontend júnior no Brasil**, e TypeScript deixou de ser diferencial e virou requisito básico na maioria das vagas de 2025–2026. A adoção de TypeScript no ecossistema JavaScript saltou de 12% em 2016 para 87% em 2023 (pesquisa State of JS 2023).
2. **Cada empresa tem sua stack:** o Nubank é o maior usuário de Clojure do mundo no backend (após comprar a Cognitect, criadora da linguagem, em julho de 2020, passou a rodar milhares de microsserviços em Clojure) e usa React no frontend; a Globo usa React/Next.js e valoriza acessibilidade e performance por ser mídia; PagBank/PagSeguro mistura React, Angular legado, Node e Java/Kotlin; Itaú e XP têm forte presença de Angular; Mercado Livre (com o design system Andes) e Magalu são pesados em React.
3. **Inglês (leitura/escrita técnica, e conversação no Nubank e multinacionais) é um filtro real.**
4. **Recrutadores valorizam projeto publicado (deploy ao vivo), README claro, responsividade e código limpo**; penalizam clones de tutorial idênticos, to-do lists genéricas e portfólios sem deploy.
5. **Para deploy gratuito, Vercel/Netlify/Cloudflare Pages/GitHub Pages cobrem sites estáticos e React**; backend gratuito (Render/Railway) tem limitações sérias (hibernação, fim do free tier) que desaconselham hospedar o próprio portfólio como fullstack.

## Details

### 1. Recomendação de formato do portfólio (comece por aqui)

**Recomendação: o site de portfólio final deve ser uma aplicação React + TypeScript, publicada na Vercel. Não faça o portfólio em si como fullstack.** A habilidade fullstack deve ser provada em um projeto SEPARADO.

Justificativa baseada no que a pesquisa de mercado mostra:

- **O que o mercado júnior mais pede é frontend em React com TypeScript.** As vagas de estágio/júnior nas empresas-alvo (Nubank, Globo, PagBank, Mercado Livre, iFood, Stone, C6 Bank) listam React e TypeScript com muito mais frequência do que exigem que o candidato tenha construído e hospedado um backend próprio. Fazer o portfólio em React + TS já demonstra exatamente a competência mais procurada.
- **Um portfólio fullstack esconde o que o recrutador quer ver.** Recrutadores e tech leads gastam pouquíssimo tempo em cada portfólio; eles querem ver a interface, a responsividade, o cuidado visual e o código no GitHub. Um backend próprio no site de portfólio adiciona superfície de bug e manutenção sem aumentar o que é avaliado primeiro.
- **Hospedagem gratuita de backend prejudica a experiência do recrutador.** O plano gratuito do Render, por exemplo, coloca o serviço para "dormir" após 15 minutos sem tráfego e leva até um minuto para "acordar" na próxima requisição; o Railway encerrou seu plano gratuito permanente em 1º de agosto de 2023. Um recrutador que abre seu site e espera o backend "acordar" tem péssima primeira impressão. Um site estático/React na Vercel carrega instantaneamente.
- **O perfil dele (básico, 5–10h/semana) favorece foco.** Aprender React + TS bem já é um investimento grande. Empilhar backend + banco no mesmo artefato dilui a qualidade. Melhor ter um portfólio React impecável + um projeto fullstack dedicado (que ele mostra no README e em vídeo, mesmo que o backend só rode localmente ou em free tier).

**Formato concreto recomendado:**
- **Portfólio principal:** React + TypeScript (pode usar Vite ou Next.js), responsivo, acessível, rápido, na Vercel.
- **Projeto fullstack de vitrine (separado):** uma aplicação React + Node/Express + banco (por exemplo PostgreSQL) que resolva um problema real, para provar que ele entende o ciclo completo. Esse é o projeto que "conta a história" de fullstack.

### 2. Requisitos reais de mercado (2025–2026)

**Tecnologias frontend mais recorrentes:** React aparece como a principal biblioteca de frontend nas vagas júnior brasileiras; Next.js aparece com frequência em empresas de conteúdo/produto (Globo, Magalu); Angular ainda é forte em bancos tradicionais (Itaú, XP, parte do PagBank/Inter); Vue é minoritário.

**TypeScript:** virou praticamente padrão em vagas frontend/fullstack júnior. A maioria das descrições de vaga de React em 2025–2026 já pede TypeScript como requisito ou forte diferencial. A pesquisa State of JS 2023 mostrou que 87% dos respondentes já haviam usado TypeScript (contra 12% em 2016) — uma adoção que se reflete diretamente nas exigências das vagas.

**Backend por empresa:**
- **Nubank:** Clojure é a linguagem de backend principal — o Nubank é reconhecido como o maior usuário de Clojure do mundo e, após adquirir a Cognitect (criadora da linguagem) em julho de 2020, passou a operar milhares de microsserviços em Clojure em produção; também usa Kotlin/Scala, com frontend em React. Cultura forte de programação funcional e engenharia.
- **Globo (Globo.com, Globoplay):** React, Next.js, Node.js no frontend/BFF; Java e Go em serviços; valoriza acessibilidade e performance por ser mídia de massa.
- **PagBank/PagSeguro:** React e Angular no frontend, Node.js e Java/Kotlin no backend, mobile em Kotlin/Swift.
- **Itaú:** forte em Java no backend e Angular no frontend; também Python e React.
- **Mercado Livre:** React no frontend (com o design system oficial Andes, documentado em ui.mercadolibre.com), Java e Node no backend; processo com testes de lógica/HackerRank.
- **iFood:** React e Node no frontend/BFF, Kotlin e Go no backend.
- **Stone:** React + TypeScript, Node e Go.
- **Banco Inter:** Angular, React, Flutter, Java.
- **XP Inc:** React, Angular, .NET/C#.
- **Magalu (Luizalabs):** React/Next.js, Node e Python.
- **C6 Bank:** React + TypeScript, Node, Kotlin.

**Testes:** Jest e Testing Library são os mais citados; Cypress/Playwright aparecem como diferencial em vagas mais maduras.

**Ferramentas de engenharia:** Git é obrigatório em praticamente todas as vagas; noções de CI/CD e Docker aparecem como diferencial em júnior e como requisito em pleno.

**Inglês:** exigido em graus variados — leitura técnica no mínimo; Nubank e multinacionais (Mercado Livre) valorizam conversação. É um filtro real.

**Diferenciais citados:** acessibilidade (forte na Globo), performance web (Core Web Vitals), design systems, GraphQL (aparece em algumas empresas de produto).

### 3. Processos seletivos das empresas-alvo

Padrão geral: (1) triagem de currículo/inscrição, (2) conversa com recrutamento (RH/tech recruiter), (3) desafio técnico (take-home) e/ou teste online, (4) entrevista técnica (pode ter pair programming/live coding), (5) entrevista cultural/de valores.

- **Nubank:** processo estruturado com desafio técnico, entrevista técnica (frequentemente pair programming) e entrevista de "business case"/cultura forte; inglês relevante.
- **Mercado Livre:** costuma ter teste online de lógica/HackerRank + entrevistas técnicas e culturais.
- **Globo, PagBank, iFood:** triagem, desafio técnico/entrevista técnica e fit cultural, tipicamente via Gupy ou LinkedIn.

O que avaliam em júnior: fundamentos (HTML semântico, CSS/layout, JS/lógica), capacidade de aprender, clareza ao explicar decisões, Git/organização de código e fit cultural — mais do que decorar frameworks.

### 4. O que recrutadores e tech leads brasileiros valorizam no portfólio

**Valorizam (positivo):**
- **Poucos projetos, mas bem-feitos** (2–3) em vez de muitos incompletos.
- **Deploy ao vivo** com link funcionando — projeto que "não roda" ou só existe em screenshot conta pouco.
- **README bem escrito:** o que é, por que foi feito, tecnologias, como rodar, link do deploy, prints/GIF.
- **Responsividade** (funciona bem no celular) e **código limpo/organizado** no GitHub, com commits com mensagens claras.
- **Projetos que resolvem um problema real** ou têm um toque pessoal, mostrando raciocínio de produto.
- **Acessibilidade e performance** como diferenciais que impressionam.

**Penalizam (clichê/negativo):**
- **Clones de tutorial idênticos** (o mesmo "clone da Netflix", "clone do Spotify" que todo mundo entrega) sem nada autoral.
- **To-do list genérica** e calculadora básica como projeto "principal".
- **Portfólio sem deploy**, só com código.
- **README vazio** ou ausente, repositórios bagunçados, commits do tipo "update".

### 5. Ferramentas gratuitas de deploy (2025–2026)

- **Vercel (plano Hobby, gratuito):** ideal para React/Next.js e sites estáticos; deploy automático a partir do Git; a documentação oficial de limites da Vercel especifica 100 GB de transferência de dados (Fast Data Transfer) por mês, restrito a uso pessoal/não-comercial. **Melhor escolha para o portfólio React.**
- **Netlify (gratuito/Starter):** ótimo para estático e SPA; a página de preços oficial lista 100 GB de banda e 300 minutos de build por mês por membro; funções serverless limitadas.
- **Cloudflare Pages (gratuito):** banda não medida (ilimitada na prática) para estático; limite de builds/mês; excelente performance de CDN.
- **GitHub Pages (gratuito):** só sites estáticos (HTML/CSS/JS); limites "soft" de repositório e banda; perfeito para a v1 estática do portfólio.
- **Render (gratuito):** oferece web services gratuitos que, segundo a documentação oficial, entram em hibernação após 15 minutos sem tráfego e podem levar até um minuto para "acordar" na próxima requisição; serve para demos, não para produção que precise responder na hora.
- **Railway:** encerrou seu plano gratuito permanente em 1º de agosto de 2023, substituindo-o por um plano Hobby de US$ 5/mês baseado em uso.

**Recomendação por formato:** portfólio estático → GitHub Pages ou Cloudflare Pages; portfólio React → Vercel; projeto fullstack de vitrine → frontend na Vercel + backend/banco no Render (ciente da hibernação) ou rodando localmente com vídeo/GIF no README.

### 6. Recursos de estudo gratuitos e de qualidade

- **Curso em Vídeo (Gustavo Guanabara):** melhor porta de entrada em português para HTML, CSS e JavaScript básico. Gratuito no YouTube.
- **FreeCodeCamp (tem versão em português):** exercícios práticos de Responsive Web Design e JavaScript; combina bem com o estilo "instrução → você escreve o código".
- **MDN Web Docs (em português):** referência oficial para HTML, CSS e JS — usar para consultar, não como curso linear.
- **JavaScript.info:** o material mais completo e profundo de JavaScript moderno; tem tradução em português.
- **Origamid:** excelente para CSS, layout, design e frontend; parte gratuita e parte paga, em português.
- **Rocketseat:** forte em React e Node em português, com comunidade no Discord; freemium.
- **The Odin Project (inglês):** trilha fullstack JS gratuita e muito completa (bom para quem topa inglês).
- **roadmap.sh:** mapas visuais de frontend e backend para se orientar sobre o que estudar em cada etapa.
- **Scrimba:** aulas interativas de React (inglês).

### 7. A trilha de aprendizado (fases, no ritmo de 5–10h/semana)

Duração total estimada: ~8 a 9 meses. As semanas assumem o ritmo do usuário; quem fizer 10h/semana avança mais rápido.

**Fase 0 — Ambiente e mentalidade (1 semana).**
Conceitos: instalar e configurar o editor de código (VS Code) e extensões básicas, entender o navegador e as ferramentas de desenvolvedor (inspecionar elemento, console, aba de rede), como abrir arquivos localmente, e como pesquisar dúvidas de forma eficiente (documentação, não só vídeo).
Erros comuns: pular direto para vídeos sem configurar ambiente; copiar-colar sem entender.
Mini-desafio (instruções): configure seu ambiente e escreva um documento pessoal de anotações (em Markdown) descrevendo seu objetivo, quantas horas por semana vai estudar e um cronograma. Critério de aceitação: o documento existe, está versionado (você o revisitará), e você consegue abrir o inspetor de qualquer site e localizar um elemento.

**Fase 1 — HTML (2 semanas).**
Conceitos, nesta ordem: estrutura de um documento HTML; tags de texto e títulos; listas; links e imagens; tabelas; formulários e seus campos; e o mais importante — **HTML semântico** (cabeçalho, navegação, principal, seção, artigo, rodapé) e atributos de acessibilidade (texto alternativo, rótulos de formulário).
Erros comuns: usar divisões genéricas para tudo em vez de tags semânticas; esquecer texto alternativo em imagens; formulários sem rótulos associados.
Mini-desafios (instruções):
1. Construa a página "sobre mim" só com HTML, sem estilo: deve conter cabeçalho com seu nome, uma navegação com âncoras internas, uma seção de biografia, uma lista de habilidades, uma seção de contato com formulário (nome, e-mail, mensagem) e um rodapé. Critérios de aceitação: usa ao menos cinco tags semânticas diferentes; todas as imagens têm texto alternativo; todos os campos do formulário têm rótulo; o HTML passa em um validador oficial sem erros.
2. Recrie a estrutura (só HTML, sem CSS) de uma notícia de um portal como a Globo.com: título, subtítulo, autor, data, parágrafos, imagem com legenda. Critério: hierarquia de títulos correta e uso de tags de figura/legenda.

**Fase 2 — CSS (4 semanas).**
Conceitos, nesta ordem: seletores e especificidade; modelo de caixa (box model); unidades (pixels, em/rem, porcentagem, viewport); cores e tipografia; posicionamento; **Flexbox**; **CSS Grid**; **responsividade com media queries e abordagem mobile-first**; variáveis CSS; transições e animações simples; e noções de organização (nomeação de classes).
Erros comuns: abusar de posicionamento absoluto; não pensar mobile-first; especificidade descontrolada; esquecer estados de foco (importante para acessibilidade).
Mini-desafios (instruções):
1. Estilize a página "sobre mim" da Fase 1 e torne-a totalmente responsiva. Critérios de aceitação: fica boa em telas de 320px a 1440px; o menu funciona no celular; usa Flexbox e Grid em pelo menos um trecho cada; contraste de cores adequado; elementos interativos têm estado de foco visível.
2. Reproduza um layout de cartões (tipo galeria de produtos) que se reorganiza de 1 coluna no celular para 3–4 no desktop, usando Grid. Critério: sem quebrar em nenhum tamanho intermediário.
**➡️ MARCO: aqui nasce a v1 do portfólio.** Ao final da Fase 2, transforme a página "sobre mim" na primeira versão do seu portfólio (estática, HTML/CSS), publique no GitHub Pages e coloque o link no currículo e no LinkedIn. Ela vai evoluir depois.

**Fase 3 — Git, terminal e GitHub (1–2 semanas, pode rodar em paralelo com o fim da Fase 2).**
Conceitos: navegação básica no terminal; o que é versionamento; inicializar repositório, preparar e confirmar alterações (add/commit), histórico, branches, mesclagem, resolução de conflito simples; conectar ao GitHub, enviar/atualizar (push/pull), pull requests; escrever boas mensagens de commit; escrever um bom README; e o que é um arquivo de itens ignorados.
Erros comuns: subir arquivos que não deveriam (pastas de dependências, segredos); mensagens de commit sem sentido; commitar tudo de uma vez.
Mini-desafio (instruções): versione seu portfólio v1 no GitHub com histórico limpo (pelo menos 10 commits com mensagens descritivas), um README explicando o projeto, e configure o deploy pelo GitHub Pages. Critério de aceitação: o repositório está público, o README tem descrição, tecnologias e link do deploy, e não há arquivos indevidos versionados.

**Fase 4 — JavaScript (8–10 semanas — a fase mais importante e mais longa).**
Conceitos, nesta ordem: variáveis e tipos; operadores; condicionais; laços; funções (incluindo funções de seta) e escopo; arrays e seus métodos principais (percorrer, mapear, filtrar, reduzir); objetos; strings; manipulação do DOM (selecionar, criar, alterar, remover elementos); eventos; formulários e validação; tratamento de erros; **assíncrono** (callbacks, promessas, async/await); consumo de APIs (fetch) e JSON; armazenamento local; módulos (import/export). Ao final, noções de imutabilidade e boas práticas.
Erros comuns: confundir igualdade solta e estrita; problemas de escopo e "this"; não entender assincronismo (tentar usar dado antes de a promessa resolver); manipular o DOM de forma desorganizada; não tratar erros de requisição.
Mini-desafios (instruções, em dificuldade crescente):
1. **Lógica pura:** resolva um conjunto de exercícios de arrays e objetos (ex.: dada uma lista de despesas, calcule total, média e a maior). Critério: sem usar bibliotecas, funções pequenas e testáveis.
2. **DOM + eventos:** construa um controlador de tema claro/escuro e um menu que abre/fecha, aplicados ao seu portfólio. Critério: estado persiste ao recarregar (armazenamento local); acessível pelo teclado.
3. **Consumo de API:** construa uma página que busca dados de uma API pública gratuita (por exemplo, previsão do tempo, cotações ou uma API de filmes) e exibe resultados com busca e estados de carregando/erro. Critérios de aceitação: trata erro de rede; mostra indicador de carregamento; funciona no celular; não trava se a API demorar.
4. **Projeto integrador:** um app de uma página que resolva um problema real seu (ex.: organizador de estudos com filtros). Critério: código em módulos, sem framework, publicado.
Evite entregar como "projeto principal" apenas to-do list ou calculadora — use-as no máximo como exercício intermediário.

**Fase 5 — Ferramentas modernas de frontend (1–2 semanas).**
Conceitos: o que é Node.js e npm/pnpm; instalar e gerenciar dependências; scripts de projeto; o que é um empacotador/servidor de desenvolvimento moderno (Vite); módulos ES; o que é transpilação; formatadores e linters (Prettier, ESLint) e por que padronizam o código.
Erros comuns: não entender a diferença entre dependências de desenvolvimento e de produção; versionar a pasta de dependências; brigar com o linter em vez de configurá-lo.
Mini-desafio (instruções): recrie um dos projetos JS da Fase 4 dentro de um projeto Vite, com scripts de desenvolvimento e build, Prettier e ESLint configurados. Critério: o build gera artefatos de produção e o deploy funciona na Vercel ou Netlify.

**Fase 6 — React (6–8 semanas).**
Conceitos, nesta ordem: pensar em componentes; JSX (conceito, não sintaxe decorada); props; estado com useState; renderização condicional e listas (e a importância das chaves); eventos em React; efeitos colaterais com useEffect e consumo de API; formulários controlados; elevação de estado e compartilhamento entre componentes; contexto para estado global simples; roteamento (React Router ou o roteamento do Next.js); e componentização/reuso. Ao final, noções de performance (evitar re-renderizações desnecessárias).
Erros comuns: mutar estado diretamente; usar índice como chave de lista; efeitos com dependências erradas (laços infinitos); espalhar estado que deveria ser derivado; componentes gigantes.
Mini-desafios (instruções):
1. Reconstrua o consumidor de API da Fase 4 em React, com componentes separados, estados de carregando/erro e busca. Critério: componentes reutilizáveis; sem mutação de estado.
2. Construa um app de múltiplas páginas com roteamento (ex.: lista → detalhe) consumindo uma API. Critério: navegação por rotas, URL reflete a página, tratamento de rota inexistente.
**➡️ MARCO: aqui nasce a v2 do portfólio.** Reescreva seu portfólio em React (componentes de cabeçalho, projetos, sobre, contato), consumindo talvez seus dados do GitHub via API. Publique na Vercel e atualize o link no currículo.

**Fase 7 — TypeScript (3–4 semanas).**
Conceitos: por que tipar; tipos primitivos; tipos de objetos e interfaces; tipos de união e literais; funções tipadas; genéricos (noção); tipar props e estado em React; tipar respostas de API. Foco em usar TS em React, que é o cenário das vagas.
Erros comuns: abusar do tipo "qualquer" (any) e anular o benefício; brigar com o compilador em vez de entender o erro; tipos excessivamente complexos cedo demais.
Mini-desafio (instruções): migre o portfólio v2 e o app de API para TypeScript, tipando props, estado e os dados vindos da API. Critério: nenhum "any" implícito; o projeto compila sem erros de tipo; o deploy segue funcionando.

**Fase 8 — Backend com Node/Express + banco de dados (5–6 semanas).**
Conceitos: o que é um servidor HTTP; rotas e métodos; middlewares; construir uma API REST com Express; validação de entrada; variáveis de ambiente e segredos; conexão com banco (PostgreSQL) e noções de modelagem; um ORM/query builder (por exemplo Prisma) em nível básico; autenticação simples (noção de token); CORS; e boas práticas de estrutura de pastas. Noção de NestJS como evolução (opcional, só conceito).
Erros comuns: expor segredos no repositório; não validar entrada; não tratar erros; misturar tudo em um arquivo só.
Mini-desafio (instruções): construa a API do seu **projeto fullstack de vitrine** — algo com utilidade real (ex.: um catálogo, um gestor de finanças pessoais, um agregador). A API deve ter operações de criar, listar, atualizar e remover, validação e persistência em banco. Depois conecte o frontend React + TS a essa API. Critérios de aceitação: dados persistem no banco; entradas inválidas são rejeitadas com mensagem clara; segredos ficam em variáveis de ambiente (fora do repositório); há README com instruções de execução e, idealmente, um vídeo/GIF demonstrando.

**Fase 9 — Testes, acessibilidade, performance e deploy/CI (3–4 semanas).**
Conceitos: por que testar; testes unitários com Jest; testar componentes com Testing Library (testar comportamento, não implementação); noção de teste end-to-end (Cypress/Playwright); auditoria de acessibilidade e de performance (Lighthouse/Core Web Vitals); noções de CI (rodar testes automaticamente a cada push via GitHub Actions); e noção de Docker (só conceito para júnior).
Erros comuns: testar detalhes de implementação; buscar 100% de cobertura sem valor; ignorar acessibilidade e performance.
Mini-desafios (instruções):
1. Adicione testes a pelo menos dois componentes do portfólio e a uma função de lógica, testando comportamento. Critério: testes passam localmente e em CI a cada push.
2. Rode uma auditoria de acessibilidade e performance no portfólio e corrija os problemas. Critério de aceitação: pontuações altas de acessibilidade e performance; navegação completa por teclado; contraste adequado; imagens otimizadas.
**➡️ MARCO: v3 do portfólio (versão final para recrutadores)** — React + TS, testada, acessível, rápida, com 2–3 projetos de destaque (incluindo o fullstack de vitrine), README impecável e deploy na Vercel.

### 8. Como o portfólio evolui ao longo da trilha (resumo dos marcos)
- **v1 (após CSS):** estática, HTML/CSS, no GitHub Pages — já dá para colocar no currículo.
- **v2 (após React):** reescrita em React, na Vercel.
- **v2.5 (após TypeScript):** migrada para TS.
- **v3 (após testes/deploy):** versão final polida, acessível, testada, com o projeto fullstack de vitrine linkado.

## Recommendations
1. **Comece hoje pela Fase 0–1 usando Curso em Vídeo + FreeCodeCamp em português**, e publique a v1 estática do portfólio já ao fim de CSS — ter um link ao vivo cedo é psicologicamente e estrategicamente importante.
2. **Trate JavaScript como o coração da trilha.** Não corra para o React antes de estar confortável com arrays, DOM, assíncrono e consumo de API. Recrutadores testam fundamentos, não decoreba de framework.
3. **Alvo de tecnologias por prioridade de mercado:** React + TypeScript primeiro (o que mais aparece nas vagas), depois Node/Express + banco para provar fullstack, depois testes (Jest + Testing Library). Deixe Docker/CI como diferencial, não bloqueio.
4. **Portfólio: qualidade sobre quantidade.** Tenha 2–3 projetos autorais (nada de clone de Netflix ou to-do list como carro-chefe), todos com deploy ao vivo, README completo e commits limpos.
5. **Invista em inglês em paralelo** (leitura técnica desde já; conversação se mirar Nubank/Mercado Livre) — é filtro real.
6. **Se o tempo apertar, priorize nesta ordem:** (a) fundamentos de JS sólidos; (b) um projeto React + TS bem-feito e publicado; (c) README e deploy impecáveis; (d) Git organizado; (e) só então backend/testes. É melhor entregar menos coisas excelentes do que muitas medianas.
7. **Benchmarks que mudam o plano:** se você conseguir uma entrevista antes de terminar a trilha, priorize revisar fundamentos de JS e o(s) projeto(s) que já tem; se a vaga-alvo pedir Angular (Itaú/XP) em vez de React, ajuste a Fase 6 para Angular; se mirar só frontend, pode encurtar a Fase 8 (backend) e reforçar testes/acessibilidade/performance.

## Caveats
- Requisitos de vaga mudam rápido e variam por time dentro da mesma empresa; use as descrições de vaga atuais (LinkedIn, Gupy, páginas de carreira) como fonte definitiva na hora de aplicar.
- As stacks citadas por empresa refletem o padrão observado publicamente, mas equipes específicas podem usar outras tecnologias (ex.: um time do PagBank em Angular, outro em React). O detalhamento por empresa não pôde ser confirmado com uma vaga individual citada para cada uma neste levantamento — trate como orientação de tendência, não como requisito literal de uma vaga específica.
- Limites de planos gratuitos de hospedagem mudam com frequência; os números citados (Vercel 100 GB/mês, Netlify 100 GB + 300 min de build/mês, Render hibernação após 15 min) refletem a documentação oficial recente, mas confirme antes de decidir.
- As durações em semanas são estimativas para 5–10h/semana e dependem de ritmo, base prévia e consistência.