# portfolio-react-
Portfólio profissional em React — páginas, componentes reutilizáveis, deploy

 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
index 9debc5bd2c15d2af2d392c75b56fc939636b33f5..21f5901960ea387fbcd86f4a6aafeeed0949f490 100644
--- a/README.md
+++ b/README.md
@@ -1,7 +1,31 @@
-# portfolio-react-
-Portfólio profissional em React — páginas, componentes reutilizáveis, deploy
+# Portfolio Java Profissional
 
- [Contador de Clicks](https://andrensc2009.github.io/portfolio-react/): O usuário tem três botões disponíveis: "Aumentar", "Diminuir" e "Reiniciar", e a contagem é exibida em um elemento de texto na página.
-- [Contador de Palavras](https://andrensc2009.github.io/portfolio-react//): Contador de palavras em tempo real em que você pode digitar no campo de entrada e ver o número de palavras e caracteres atualizados automaticamente na tela.
-- [Encurtador de URL](https://andrensc2009.github.io/portfolio-react//): Encurtador de URL é uma ferramenta que reduz o tamanho de uma URL, tornando-a mais curta e fácil de compartilhar.
-- [Pesquisa de Filmes](https://andrensc2009.github.io/portfolio-react//): A pesquisa de filmes permite aos usuários buscar por filmes específicos por título, proporcionando uma experiência de usuário mais eficiente e personalizada.
+Este projeto é um **site de portfolio profissional** com:
+
+- **Backend em Java (Spring Boot)** com API REST para os dados de projetos.
+- **Frontend interativo** (HTML, CSS e JavaScript) com visual neutro e profissional.
+- Tema com detalhes em **preto, prata e cinza**, tipografia estilo **Caslon**.
+
+## Seções incluídas
+
+- Meus Códigos
+- Jogos em que estou desenvolvendo
+- Projetos que eu estou fazendo
+- Projetos em que participei
+
+## Como executar
+
+```bash
+mvn spring-boot:run
+```
+
+Depois, abra:
+
+- `http://localhost:8080` (interface web)
+- `http://localhost:8080/api/portfolio/items` (API com todos os itens)
+- `http://localhost:8080/api/portfolio/categorias` (API agrupada por categoria)
+
+## Estrutura principal
+
+- `src/main/java/com/portfolio/site` → aplicação Java e backend
+- `src/main/resources/static` → frontend (index, estilos e interação)
 
EOF
)
