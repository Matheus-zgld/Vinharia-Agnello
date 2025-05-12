## ✍️ Nome do Projeto

Vinheria Agnello

---

## 📄 Breve Descrição do Caso da Vinheria Agnello

A Vinheria Agnello é uma empresa familiar de São Paulo. Atua há mais de 15 anos com uma única loja física voltada para a venda de vinhos nacionais e estrangeiros. Seu maior diferencial é o atendimento personalizado, com vendedores altamente treinados que sugerem uvas, rótulos, harmonizações e ocasiões para consumo.

Com a chegada da pandemia e a queda das vendas nas lojas, o proprietário Giulio, que se opunha à digitalização, acabou por seguir o conselho da filha Bianca e criou um portal de comércio eletrônico. O objetivo é desenvolver uma solução que preserve o serviço consultivo e acolhedor da experiência na loja, mesmo no espaço digital.

A empresa já possui um ERP de controlo interno, mas a construção do portal requer um projeto derivado da experiência do utilizador e adaptado às necessidades de diferentes perfis de clientes, desde o principiante ao enófilo experiente. O projeto será construído recorrendo a metodologias ágeis, tendo Bianca como Product Owner e um lead developer como Scrum Master, com o objetivo de transferir a identidade da Vinheria para o mundo digital.

---

## ⚙️ Estrutura do Projeto

 # Página Inicial
   - Apresenta a Vinheria Agnello com seu histórico, atendimento especializado e diferenciais. Inclui notícias e vídeo sobre vinhos e acesso rápido ao catálogo. Foco em engajamento e apresentação da marca.

 # Catálogo de Vinhos
   - Exibe todos os vinhos à venda com filtros de tipo, região, uva, entre outros. Cada vinho tem imagem e descrição própria. Facilita a busca e navegação do usuário.
   
 # Galeria da Vinheria
   - Versão visual da casa — explore imagens amplas e estilizadas dos ambientes da vinheria, destacando sua arquitetura, decoração e atmosfera única. Sinta o clima do espaço antes mesmo de visitar.

 # Assinaturas
   - Página que explica os planos de assinatura mensal de vinhos. Cada plano inclui detalhes como quantidade, tipos de vinho, valor e benefícios.

 # Sobre Nós
   - Conta a história dos fundadores da vinheria, destacando o atendimento personalizado e o cuidado com os vinhos. A página cria uma conexão emocional com o usuário e demonstra um pouco da história, trajetória e finalidade do serviço.

 # Login/Cadastro
   - Página de login e cadastro para os clientes, com campos para os usuários se identificarem e/ou criarem uma conta.

---

# 🎨 Efeitos Visuais do Projeto

Esta seção descreve todos os efeitos visuais aplicados no projeto, organizados por página. São utilizados pseudo-elementos, pseudo-classes, transformações, transições e animações para melhorar a experiência do usuário.

## 🌐 Geral (Aplicado em todo o projeto)

### - Seleção de texto

- **Pseudo-elemento:** `::selection`
- **Efeito:** Altera a cor do fundo para `#84033b` (rosa escuro) e a cor do texto para branco ao selecionar qualquer texto na página.

## 🏠 Página Principal

### - Estilização de Títulos

#### Primeira letra destacada
- **Elemento:** `.secao5 h1::first-letter`
- **Efeito:** Aumenta a primeira letra dos títulos `h1` da seção 5, deixando-a com `font-size: 4vw` e um pequeno `margin-right` de `0.1vw`.

### - Interação com o Logo

#### Escala ao passar o mouse
- **Elemento:** `#logo:hover`
- **Efeito:** Aumenta o tamanho do logo com `transform: scale(1.1)` e uma transição suave de `0.3s`.

### - Interação com o Vídeo

#### Zoom e sombra ao passar o mouse
- **Elemento:** `#video iframe:hover`
- **Efeitos:**  
  - Aumenta o vídeo (`scale(1.2)`)  
  - Adiciona uma `box-shadow` rosa  
  - Transição suave de `0.4s`

### - Interação com Imagens de Lista

#### Deslocamento lateral
- **Elemento:** `.secaoLista_img:hover`
- **Efeito:** Move a imagem 20px para a direita com `transform: translate(20px)`

## 🔐 Página de Cadastro/Login

### - Estilização dos Campos de Input

#### Estilo padrão
- **Elemento:** `.cadastro-container input`
- **Efeito:** Campos de texto estilizados com bordas arredondadas, padding, cor de fundo escura, texto branco, e transição suave de `0.2s`.

#### Ao focar no campo
- **Pseudo-classe:** `:focus`
- **Efeito:** Aumenta ligeiramente o tamanho do campo com `scale(1.1)` e destaca a borda com `border: 2px solid #84033b`.

## ✍️ Página de Assinaturas

### - Interação com Tabela de Assinaturas

#### Animação nas imagens
- **Elemento:** `.primeira_coluna td:hover .table_img`
- **Efeito:** Gira a imagem 360 graus ao passar o mouse, com transição de `0.4s`.

#### Ampliação do texto
- **Elemento:** `.primeira_coluna td:hover p`
- **Efeitos:**  
  - Aumenta o tamanho do texto com `scale(1.1)`  
  - Reduz o peso da fonte (`font-weight: 300`)  
  - Transição suave de `0.4s`

### - Animação Contínua

#### Efeito de pulsar
- **Elemento:** `#container_info`
- **Animação:** `@keyframes piscar`
- **Efeito:** O elemento pulsa continuamente, alternando entre `scale(1.1)` e `scale(1)` a cada 2 segundos em um loop infinito.

## 📖 Página de Catálogo
### - Interação com os cartões do catálogo de vinhos
- **Elemento:** `section .container .produto:hover`
- **Efeitos:** aumenta o tamanhos dos cartões e adiciona bordas `transform: scale(1.03,1.03);  border: #84033b solid 3px;  transition: transform 0.3s;`
### - Animação no título
- **Elemento:** `section .tituloPrincipal h1`
- **Animação:** `@keyframes aparecer`
---

## 👤 Nome dos Integrantes
 - André Mateus Yoshimori
 - Eduardo Francisco Mauro Gonçalves
 - Ever Callisaya Amaru
 - Gabriel Luchetta dos Santos
 - Matheus Henrique Ferreira Camargo da Silva

---

## 👾 Link para o site publicado no Github Pages

https://matheus-zgld.github.io/Vinheria-Agnello/
