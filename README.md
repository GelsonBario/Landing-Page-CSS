# Landing Page "A Magia do CSS"

![Status do Projeto](https://img.shields.io/badge/status-concluído-green)
![Licença](https://img.shields.io/badge/licença-MIT-blue)

Uma landing page moderna e responsiva sobre o poder do CSS, criada para demonstrar diversas técnicas de estilização, layout e animação.

![Demonstração do Projeto](./screenshot.png)
*(Dica: Tire um print da sua página finalizada, salve como screenshot.png na pasta do projeto e esta imagem aparecerá aqui!)*

---

## 📜 Índice

* [Sobre o Projeto](#-sobre-o-projeto)
* [✨ Funcionalidades](#-funcionalidades)
* [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
* [🏁 Como Começar](#-como-começar)
* [🎨 Como Usar e Customizar](#-como-usar-e-customizar)
* [📝 Licença](#-licença)
* [👨‍💻 Autor](#-autor)

---

## 📖 Sobre o Projeto

Este projeto é uma landing page de página única (one-page) desenvolvida com *HTML5* e *CSS3* puro, com um toque de JavaScript para interatividade. O objetivo é servir como um portfólio prático e um recurso de aprendizado, mostrando como criar uma interface web atraente e moderna do zero.

A página aborda o próprio CSS como tema, destacando seus recursos mais poderosos de forma visual e interativa.

---

## ✨ Funcionalidades

* *🎨 Design Moderno:* Interface limpa com tema escuro (dark mode) e cores vibrantes.
* *📱 Totalmente Responsivo:* Layout adaptável para desktops, tablets e celulares.
* *✨ Animações de Entrada:* Elementos surgem na tela de forma suave conforme o usuário rola a página.
* *📜 Scroll Suave:* Navegação fluida ao clicar nos links do menu.
* *NAVIGATION Navegação Fixa Inteligente:* O menu superior é transparente no topo e se torna sólido ao rolar.
* *💧 Efeitos de "Glassmorphism":* Cards com efeito de vidro fosco.
* *🌌 Fundo Animado:* Gradiente sutil e animado na seção principal (hero).
* *💡 Tipografia Fluida:* Títulos que se ajustam perfeitamente a qualquer tamanho de tela usando clamp().

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias:

* *HTML5:* Para a estrutura semântica do conteúdo.
* *CSS3:* Para toda a estilização, layout (Flexbox), animações e responsividade.
* *JavaScript:* Uma pequena função para adicionar o efeito de scroll na barra de navegação.
* *Google Fonts:* Para a fonte customizada ('Poppins').

---

## 🏁 Como Começar

Para obter uma cópia local e executá-la, siga estes passos simples.

1.  *Clone o repositório*
    sh
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    
2.  *Navegue até a pasta do projeto*
    sh
    cd nome-do-repositorio
    
3.  **Abra o arquivo index.html** no seu navegador de preferência. E pronto!

---

## 🎨 Como Usar e Customizar

Este projeto foi feito para ser facilmente customizável. Veja como você pode adaptá-lo:

1.  *Alterar as Cores:*
    Abra o arquivo style.css. No topo, dentro do seletor :root, você encontrará as variáveis de cor. Mude os valores hexadecimais para criar sua própria paleta!
    css
    :root {
        --cor-primaria: #0d0d2b;
        --cor-secundaria: #8a2be2;
        --cor-destaque: #00c6ff;
        --cor-texto: #f0f0f0;
    }
    

2.  *Alterar a Fonte:*
    O projeto usa a fonte 'Poppins' do Google Fonts. Para alterar:
    * Vá para o [Google Fonts](https://fonts.google.com/) e escolha uma nova fonte.
    * Copie o novo link <link> fornecido por eles e substitua o link existente no <head> do index.html.
    * No style.css, atualize a propriedade font-family no seletor body com o nome da sua nova fonte.

3.  *Alterar o Conteúdo:*
    Todo o conteúdo de texto (títulos, parágrafos, itens dos cards) pode ser editado diretamente no arquivo index.html. As seções são comentadas para facilitar a identificação.

4.  *Alterar o Gradiente Animado:*
    No style.css, na classe .hero, você pode alterar as cores do background: linear-gradient(...). A velocidade da animação pode ser ajustada na propriedade animation da mesma classe.

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

## 👨‍💻 Autor

Feito por Gelson Bario.

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gelsonbario/)
[![github](https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GelsonBario/)
