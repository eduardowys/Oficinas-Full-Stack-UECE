# OFICINA 3 - CSS

## Case: A Jornada do Blog Pessoal

Imagine que você decidiu criar um blog pessoal para compartilhar suas aventuras de viagem. Você já estruturou a página com HTML e agora quer dar vida a ela usando CSS. Vamos juntos estilizar essa página, tornando-a atraente e agradável para seus futuros leitores!

### Passos:

1. **Criando o Arquivo HTML:**
   Reutilize o seu arquivo HTML que estamos trabalhando em aula. Adicione a estrutura básica de um documento HTML, incluindo as tags `<html>`, `<head>`, `<title>`, `<link>` e `<body>`.

2. **Criando o Arquivo CSS:**
   Crie um arquivo chamado `styles.css`, adicione estilos básicos para o corpo da página, como a cor de fundo, fonte e margens.

3. **Estilizando Menu de Navegação:**
   No arquivo `styles.css`, adicione estilos para os links do menu de navegação, como cor e comportamento ao passar o mouse.

4. **Estilizando Formulários:**
   No arquivo `styles.css`, adicione estilos para formulários (`<form>`), incluindo campos de entrada (`<input>`, `<label>`), e o botão de envio (`<button>`).

---

### Correção do Erro:

Após seguir todos os passos da oficina, você perceberá que o formulário na sua página não está exibindo o botão de envio corretamente. A cor do botão não estará correta, e a página não se comportará como o esperado. Você vai identificar e corrigir esse erro.

### Passos:
- Identificação do Erro: O que está faltando no código acima? Analise o código e
tente identificar a propriedade ausente que está causando o problema.
- Correção do Erro: Adicione a propriedade correta ao código para garantir que o
botão seja estilizado adequadamente.
#### 1. **Análise do Código:**
   Observe o código CSS do botão de envio (`input[type="submit"]`). Verifique se todas as propriedades estão corretamente aplicadas.

   **Código fornecido inicialmente:**
   ```css
   input[type="submit"] {
       background-color: #007bff;
       color: white;
       padding: 10px 20px;
       border: none;
       cursor: pointer;
       /* Falta uma propriedade importante aqui */
   }
