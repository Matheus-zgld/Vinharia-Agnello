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

## ⚙️ Efeitos Visuais do Projeto

 # 🌐 Geral
   - ::selection
     O que faz: muda a cor de fundo e do texto ao selecionar texto.
     Pseudo-elemento: ::selection
     Efeito: cor de fundo rosa escuro (#84033b) e texto branco durante seleção.

 # 🏠 Página Principal
   - secao5 h1::first-letter
     O que faz: aumenta a primeira letra dos títulos h1 dentro da seção 5.
     Pseudo-elemento: ::first-letter
     Efeito: letra inicial maior (4vw), com pequeno espaçamento à direita.
   
   - #logo:hover
     O que faz: aumenta o tamanho do logo quando o mouse passa por cima.
     Pseudo-classe: :hover
     Efeito: scale(1.1) com transição suave de 0.3s.
   
   - #video iframe:hover
     O que faz: aumenta e adiciona sombra ao vídeo (iframe) ao passar o mouse.
     Pseudo-classe: :hover
     Efeito: scale(1.2), sombra rosada e transição de 0.4s.
   
   - .secaoLista_img:hover
     O que faz: move a imagem 20px para a direita ao passar o mouse.
     Pseudo-classe: :hover
     Efeito: translate(20px) lateral.

 # 🔐 Página de Cadastro/Login
   - .cadastro-container input
   O que faz: define estilo básico dos inputs com borda, padding e transição.
   Transição: aplicada para suavizar efeitos.
   
   - .cadastro-container input:focus
   O que faz: quando o input recebe foco, a borda engrossa e o campo aumenta.
   Pseudo-classe: :focus
   Efeito: border: 2px solid + scale(1.1).

 # Catálogo de Vinhos
   - Exibe todos os vinhos à venda com filtros de tipo, região, uva, entre outros. Cada vinho tem imagem e descrição própria. Facilita a busca e navegação do usuário.
   
 # Galeria da Vinheria
   - Versão visual da casa — explore imagens amplas e estilizadas dos ambientes da vinheria, destacando sua arquitetura, decoração e atmosfera única. Sinta o clima do espaço antes mesmo de visitar.

  # ✍️ Assinaturas
    - .primeira_coluna td:hover .table_img
    O que faz: imagem gira 360° ao passar o mouse sobre a célula.
    Pseudo-classe: :hover
    Efeito: rotate(360deg) com transição.
    
    - .primeira_coluna td:hover p
    O que faz: aumenta o tamanho e muda o peso da fonte do parágrafo.
    Pseudo-classe: :hover
    Efeito: scale(1.1) + font-weight: 300.
    
    - #container_info + @keyframes piscar
    O que faz: animação contínua de pulsar o elemento.
    Tipo: @keyframes
    Efeito: alterna escala de 1.1 → 1 → 1.1 em 2s (loop infinito).

 # Sobre Nós
   - Conta a história dos fundadores da vinheria, destacando o atendimento personalizado e o cuidado com os vinhos. A página cria uma conexão emocional com o usuário e demonstra um pouco da história, trajetória e finalidade do serviço.



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
