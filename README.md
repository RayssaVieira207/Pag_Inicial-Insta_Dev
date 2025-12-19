#  Pag_Inicial-Insta_Dev - Clone Educacional

<div align="center">
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Concluído-green)

</div>

---

## ⚠️ DISCLAIMER IMPORTANTE

<div align="center" style="background-color: #fff3cd; border: 2px solid #ffeaa7; border-radius: 10px; padding: 20px; margin: 20px 0;">

### 🚨 **AVISO LEGAL**

**IMPORTANTE:** Esta página é uma recriação não oficial para fins de estudo e demonstração de habilidades.

- ❌ **NÃO** é o site oficial do Instagram ou Meta
- ❌ **NÃO** sou afiliado(a) ao Instagram ou Meta de forma alguma
- ✅ Este projeto é **ESTRITAMENTE** para fins educacionais
- ✅ Todo o código foi desenvolvido por mim como exercício
- ✅ **NÃO** possui sistema de login real
- ✅ **NÃO** coleta dados de usuários

</div>

---

## Sobre o Projeto

Clone da página inicial do Instagram desenvolvido em **Janeiro de 2025** como parte do programa **Dev em Dobro**. Projeto **100% educacional** para portfólio.

## Funcionalidades

- ✅ Interface idêntica à original
- ✅ Design responsivo (mobile e desktop)
- ✅ Animação de troca de imagens
- ✅ Formulário de login estilizado
- ✅ Seção de download de apps

## Estrutura do Projeto

```
Pag_Inicial-Insta_Dev/
├── index.html
├── README.md
└── src/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── img/
        ├── celular.png
        ├── insta1.png
        ├── insta2.png
        └── ...
```

## Tecnologias

- **HTML5** - Estrutura da página
- **CSS3** - Estilos e responsividade
- **JavaScript** - Animações simples
- **Git/GitHub** - Controle de versão

## O que o projeto NÃO tem:

- ❌ Backend ou banco de dados
- ❌ Sistema de login real
- ❌ Conexão com APIs
- ❌ Coleta de dados

## Como Usar

1. Baixe os arquivos
2. Abra o `index.html` no navegador
3. Para mobile, use as ferramentas de desenvolvedor

## Demonstração

**Desktop:**
- Layout com celular à esquerda
- Formulário à direita
- Imagens alternam a cada 5 segundos

**Mobile:**
- Apenas o formulário é mostrado
- Layout otimizado para telas pequenas

## Código Principal

**Animação das imagens (script.js):**
```javascript
let img = document.querySelector(".troca-img");

function trocarImagem() {
    if(img.style.opacity == 0) {
        img.style.opacity = 1;
    } else {
        img.style.opacity = 0;
    }
}

setInterval(trocarImagem, 5000);
```

## Considerações Legais

Projeto em conformidade com:
- Termos do GitHub para fins educacionais
- Código 100% original
- Sem dados coletados
- Sem fins comerciais

## Autor

**Rayssa Vieira** - Desenvolvedora Front-End  
Projeto do Dev em Dobro - Janeiro 2025

---

<div align="center">
  
⭐ Se este projeto ajudou você, considere dar uma estrela no repositório!

</div>
