# 📄 Gerador de Currículo Estático

> Gerador de currículo em arquivo único (HTML/CSS/JS) com layout A4 otimizado para impressão (PDF) e editor de imagem integrado com recorte e zoom.

[Para acessar a Live Demo, clique aqui.](https://heliocarrara.github.io/static-cv-generator/)

## 🚀 Visão Geral

Este projeto é uma ferramenta leve e sem dependências para gerar um currículo profissional. Consiste em um único arquivo HTML contendo todo o CSS e JavaScript necessários. Foi projetado para ser facilmente editável via ferramentas de IA e formatado perfeitamente para impressão em A4.

## ✨ Funcionalidades

- **Arquitetura de Arquivo Único:** Sem instalação, sem `npm install`. Apenas HTML/CSS/JS puro.
- **Otimizado para Impressão:** Regras de CSS `@media print` personalizadas garantem que o layout caiba perfeitamente em uma página A4 sem margens.
- **Editor de Imagem Integrado:** Modal embutido para carregar, recortar e aplicar zoom na sua foto de perfil diretamente no navegador.
- **Estrutura Amigável para IA:** O código está organizado para ser facilmente compreendido e modificado por LLMs (ChatGPT, Gemini, etc.).

## 📦 Como Usar

### 1. Pegue o Código
Copie todo o conteúdo do arquivo `index.html` deste repositório.

### 2. Personalize com IA (Gemini/ChatGPT)
Você não precisa saber programar para editar isso. Abra um chat com o **Gemini** ou **ChatGPT** e use um prompt como este:

> "Tenho um arquivo HTML de currículo. Por favor, substitua os dados de exemplo pelos meus dados reais abaixo no código. Mantenha o layout, CSS e scripts exatamente como estão, apenas atualize o conteúdo do texto.
>
> **Meus Dados:**
> [Cole o texto do seu currículo aqui]"

### 3. Rodar e Visualizar
Para visualizar seu currículo sem precisar configurar um servidor local:
1. Acesse: [https://www.lncc.br/~borges/php/testar.html](https://www.lncc.br/~borges/php/testar.html)
2. Remova o texto que tiver na caixa abaixo.
   
   <img width="617" height="401" alt="image" src="https://github.com/user-attachments/assets/83f85519-1a83-4bcf-9c51-35c35941f10d" />

4. Cole o seu código HTML modificado na área de texto e clique em "Testar sua Página".
   
   <img width="657" height="402" alt="image" src="https://github.com/user-attachments/assets/b516260b-8eda-4d9d-ae01-35403b3fed87" />

6. A página renderizará seu currículo imediatamente.
   <img width="1891" height="937" alt="image" src="https://github.com/user-attachments/assets/2548630d-a948-4de3-8893-6667f29e1506" />


### 4. Foto de Perfil
Com a página carregada:
- Clique no **espaço da foto de perfil**.
- Carregue sua imagem.
- Use o editor integrado para **dar zoom e ajustar** até ficar perfeito.
- Clique em "Salvar".

### 5. Exportar para PDF
Para salvar o arquivo final:
1. Pressione `Ctrl + P` (ou Cmd + P).
2. Selecione **"Salvar como PDF"**.
3. **Configurações Importantes:**
   - Margens: **Nenhuma** (ou Mínima).
   - Opções: Marque **"Gráficos de plano de fundo"**.

---
---

# 📄 Static CV Generator

> Single-file resume generator (HTML/CSS/JS) with a print-optimized A4 layout (PDF) and an integrated image editor with crop and zoom.

## 🚀 Overview

This project is a lightweight, dependency-free tool to generate a professional resume. It consists of a single HTML file containing all the necessary CSS and JavaScript. It was designed to be easily editable via AI tools and perfectly formatted for A4 printing.

## ✨ Features

- **Single File Architecture:** No build steps, no `npm install`. Just pure HTML/CSS/JS.
- **Print-Optimized:** Custom `@media print` CSS rules ensure the layout fits perfectly on an A4 page without margins.
- **Integrated Image Editor:** Built-in modal to upload, crop, and zoom your profile picture directly in the browser.
- **AI-Friendly Structure:** The code is organized to be easily understood and modified by LLMs (ChatGPT, Gemini, etc.).

## 📦 How to Use

### 1. Get the Code
Copy the full content of the `index.html` file from this repository.

### 2. Customize with AI (Gemini/ChatGPT)
You don't need to know coding to edit this. Open a chat with **Gemini** or **ChatGPT** and use a prompt like this:

> "I have an HTML file for a resume. Please replace the current placeholder data with my real information below. Keep the layout, CSS, and scripts exactly as they are, just update the text content.
>
> **My Data:**
> [Paste your resume text here]"

### 3. Run & Preview
To view your resume without setting up a local server:
1. Go to: [https://www.lncc.br/~borges/php/testar.html](https://www.lncc.br/~borges/php/testar.html)
2. Paste your modified HTML code into the text area.
3. The page will render your resume immediately.

### 4. Upload Photo
Once the page is rendered:
- Click on the **profile photo placeholder**.
- Upload your image.
- Use the built-in editor to **zoom and pan** until it fits perfectly.
- Click "Salvar" (Save).

### 5. Export to PDF
To save the final file:
1. Press `Ctrl + P` (or Cmd + P).
2. Select **"Save as PDF"**.
3. **Important Settings:**
   - Margins: **None** (or Minimum).
   - Options: Check **"Background Graphics"**.

## 🛠️ Tech Stack

- **HTML5:** Semantic structure.
- **CSS3:** Variables, Grid, Flexbox, and Media Queries for print.
- **JavaScript (Vanilla):** DOM manipulation and Canvas API for image processing.

## 📄 License

This project is licensed under the MIT License.

---

Made with 💙 by [Helio Carrara](https://www.linkedin.com/in/heliocarrara)
