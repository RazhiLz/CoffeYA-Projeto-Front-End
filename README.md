# README - Projeto de Site de Café

## 📝 Sobre o Projeto

Este projeto foi uma experiência interessante e simples que eu decidi fazer para melhorar minhas habilidades em front-end, especificamente com HTML e CSS. O objetivo principal era criar uma página visualmente agradável e funcional para um site de café, sem o uso de frameworks ou bibliotecas externas, apenas com HTML e CSS puros. ☕️

A ideia surgiu porque eu queria focar no design e na estruturação do layout, e também testar a criação de uma página completa sem depender de outras ferramentas. Eu sabia que seria uma tarefa simples, mas um ótimo exercício para me desafiar e aperfeiçoar minhas habilidades no desenvolvimento front-end. 💻

---

## ⚙️ Estrutura do Projeto

A estrutura do site foi organizada de forma simples, mas funcional, para proporcionar uma boa experiência ao usuário. Aqui está uma explicação detalhada de como organizei os elementos principais e como utilizei o CSS para tornar tudo visualmente atraente.

### 1. **Estrutura HTML**

O HTML foi o alicerce do meu projeto. Eu criei as seções principais para o layout do site:

- **`<header>`**: Contém a navegação principal com links para as páginas, como "Home", "Menu" e "Sobre".
- **`<section>`**: Utilizado para agrupar as seções principais do site como "Home", "Sobre", "Menu", "Avaliações" e "Localização".
- **`<footer>`**: Contém informações de rodapé como links sociais e informações adicionais de contato.

```html
<header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#about">Sobre</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
</header>
```
## 2. Estilos CSS

Usei o CSS para estilizar o layout e dar uma identidade visual ao site. Os estilos principais incluem:

### Cores
Utilizei uma paleta de cores que combina tons de preto e dourado para criar um contraste agradável e uma sensação sofisticada, refletindo a atmosfera de um café.

```css
:root {
    --main-color: #d3ad7f;
    --black: #13131a;
    --bg: #010103;
    --border: 0.1rem solid rgba(255, 255, 255, 0.3);
}
```
### Tipografia
Utilizei a fonte "Roboto", que é clara e legível, dando um toque moderno ao site.

### Layout
Para o layout, usei flexbox e grid para tornar o design responsivo e organizado.

```css
section {
    padding: 3rem 2rem;
    margin: 0 auto;
    max-width: 1200px;
}
```
### Interatividade
Algumas interações foram adicionadas, como transições de cor e aumento de ícones ao passar o mouse, para dar um toque dinâmico ao site.

```css
.btn:hover {
    letter-spacing: 0.2rem;
}

.footer .share img:hover {
    background-color: var(--main-color);
    transform: scale(1.2);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}
```

## 🧑‍💻 Desafios e Aprendizados

Apesar de ser um projeto simples, eu encontrei alguns desafios durante a criação do layout:

- **Responsividade**: Tive que garantir que o design se ajustasse bem em diferentes tamanhos de tela. Utilizei grid e flexbox para lidar com os diferentes tamanhos de dispositivos.
- **Estilização Avançada**: Alguns efeitos visuais e transições exigiram um pouco mais de atenção, mas foram uma ótima oportunidade para aprender mais sobre o poder do CSS.
- **Consistência Visual**: Manter a consistência de cores e fontes em todo o site foi essencial para criar uma identidade visual coesa.

No final, o projeto me ajudou a entender melhor a criação de sites com HTML e CSS de maneira mais eficiente e focada em design.

## 💬 Conclusão

Este foi um projeto simples, mas muito valioso para aprimorar minhas habilidades em front-end. Eu consegui trabalhar tanto a estruturação do HTML quanto a estilização avançada com CSS, criando um site funcional e visualmente agradável para o tema de café. ☕️

Foi uma ótima oportunidade de aprendizado e um bom exemplo de como, com as ferramentas certas, é possível criar algo funcional com apenas HTML e CSS.
