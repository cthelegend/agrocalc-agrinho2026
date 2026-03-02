# AgroCalc 🌱📊  
**Calculadora de Pegada de Carbono na Agricultura Sustentável**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SEU-USUARIO/agrocalc)

**Projeto para o Concurso Agrinho 2026 – Subcategoria 3 (Front-End: HTML, CSS, JavaScript)**  
Tema: *Agro forte, futuro sustentável: equilíbrio entre produção e meio ambiente*

### Visão Geral
O **AgroCalc** é uma calculadora interativa e educativa que estima a **pegada de carbono** (emissões de CO₂ equivalente) de uma propriedade agrícola. Desenvolvido 100% com tecnologias front-end, o site permite inserir dados simples da fazenda e visualizar:

- Emissões atuais vs. cenário sustentável
- Redução possível com práticas como plantio direto, ILPF (Integração Lavoura-Pecuária-Floresta), energia solar e preservação de mata ciliar
- Gráficos animados e certificado de sustentabilidade!

Inspirado em dados reais da Embrapa, Plano ABC+ e fatores IPCC adaptados ao Brasil, o projeto mostra que é possível **produzir mais** (agro forte) com **menos impacto ambiental** (futuro sustentável).

### Capturas de Tela

![Banner Principal](assets/banner-agrocalc.png)  
*Família feliz em fazenda sustentável com painéis solares e plantações verdes*

![Formulário de Inputs](assets/formulario.png)  
*Inputs intuitivos com sliders e selects*

![Resultados com Gráfico](assets/resultados-grafico.png)  
*Gráfico comparativo + certificado*

### Funcionalidades Principais ✨
- Formulário responsivo com validação (área em ha, tipo de cultivo, animais, fertilizantes, manejo)
- Cálculo em tempo real baseado em fatores brasileiros aproximados:
  - Emissões base (ex.: pecuária ~1,4 ton CO₂e/cabeça/ano; fertilizantes N ~0,01 ton/kg)
  - Bônus de sequestro (plantio direto -0,5 a -1 ton/ha; ILPF -1,5 a -3 ton/ha)
- Gráficos dinâmicos com **Chart.js** (barras: atual vs. sustentável)
- Certificado personalizado gerado via HTML/CSS (com vaquinha fofa thumbs up 🐄)
- Design: cores pastel, animações suaves, mascotes
- Totalmente responsivo (mobile-first) e acessível
- Offline após carregamento inicial

### Tecnologias Usadas 🛠️
- **HTML5** + **CSS3** (Flexbox, Grid, animações/transições)
- **JavaScript** (ES6+, manipulação DOM, eventos)
- **Chart.js** (via CDN) para visualização de dados
- Sem frameworks pesados, leve e rápido!
