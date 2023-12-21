# COROUSEL EM BOOTSTRAP
🌹UTILIZANDO O FRAMEWORK BOOTSTRAP PARA EXIBIR IMAGENS EM CARROSSEL

[![GitHub Repo stars](https://img.shields.io/badge/VILHALVA-GITHUB-03A9F4?logo=github)](https://github.com/VILHALVA)
[![GitHub Repo stars](https://img.shields.io/badge/MEUS-CURSOS-03A9F4?logo=github)](https://github.com/VILHALVA?tab=repositories&q=CURSO&type=public&language=&sort=) <br>

<img src="https://cdn.icon-icons.com/icons2/1364/PNG/512/carousel_89253.png" align="center" width="280"> <br>

## DESCRIÇÃO:
Este código HTML faz parte de uma página web que utiliza o framework Bootstrap para criar um componente de carrossel (carousel). Vamos analisar cada parte do código:

1. **Meta tags e Título:**
   - Inclui as meta tags para o conjunto de caracteres e visualização responsiva.
   - Define o título da página como "CFB Cursos - Curso de Bootstrap".

2. **Vinculação de Estilos e Scripts:**
   - Vincula o arquivo CSS do Bootstrap e adiciona alguns estilos customizados dentro da tag `<style>`.
   - Vincula o arquivo JavaScript do Bootstrap, que é necessário para o funcionamento de certos componentes, como o carrossel.

3. **Elementos HTML:**
   - `<h1>` e `<h3>`: Títulos para a página e uma breve descrição do que é um carrossel Bootstrap.
   - `<div id="banner" class="carousel slide" data-bs-ride="carousel">`: A div principal que contém o carrossel. `data-bs-ride="carousel"` indica que este é um carrossel e pode ser automaticamente percorrido.
   - `<div id="indicadores" class="carousel-indicators">`: Botões indicadores para cada slide do carrossel.
   - `<div id="imagens" class="carousel-inner">`: Contém os itens (imagens) a serem exibidos no carrossel.
   - `<button type="button" class="carousel-control-prev" data-bs-target="#banner" data-bs-slide="prev">` e `<button type="button" class="carousel-control-next" data-bs-target="#banner" data-bs-slide="next">`: Botões de controle para navegar pelos slides.

4. **Slides do Carrossel:**
   - Cada `<div class="carousel-item">` representa um slide do carrossel e contém uma imagem correspondente.

5. **Estilos CSS Customizados:**
   - Algumas regras de estilo adicionais são fornecidas diretamente no arquivo HTML usando a tag `<style>`. Isso inclui margens para os títulos, uma cor de fundo para o segundo título (`<h3>`), e uma altura fixa para as imagens.

6. **Scripts JavaScript Bootstrap:**
   - Vincula o arquivo JavaScript do Bootstrap, que é essencial para o funcionamento de componentes interativos, como o carrossel.

O carrossel exibirá as imagens (`b1.jpg`, `b2.jpg`, etc.) em sequência, com botões de controle e indicadores para navegação. O Bootstrap simplifica a criação de componentes responsivos e interativos, facilitando o desenvolvimento de páginas web modernas.