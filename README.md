# Pag_Inicial-Insta_Dev - Clone Educacional

<div align="center">
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Concluído-green)
![Responsivo](https://img.shields.io/badge/Responsivo-Sim-success)
![Educacional](https://img.shields.io/badge/Finalidade-Educacional-blue)

</div>

---

## ⚠️ SISTEMA DE DISCLAIMER OBRIGATÓRIO

<div align="center" style="background: linear-gradient(135deg, #fff3cd 0%, #ffeaa7 100%); border: 3px solid #f39c12; border-radius: 15px; padding: 25px; margin: 25px 0; box-shadow: 0 8px 25px rgba(0,0,0,0.1);">

### 🚨 **SISTEMA DE ISENÇÃO DE RESPONSABILIDADE IMPLEMENTADO**

**IMPORTANTE:** Este projeto agora conta com um **sistema completo de disclaimer obrigatório** que garante conformidade legal e transparência total.

- ✅ **Página de Disclaimer Dedicada** - Acesso obrigatório antes da página principal
- ✅ **Confirmação Explícita do Usuário** - Checkbox de concordância obrigatória
- ✅ **Armazenamento Local** - Aceitação salva no navegador do usuário
- ✅ **Redirecionamento Automático** - Fluxo controlado de acesso
- ✅ **Informações Completas** - Detalhes técnicos e legais transparentes
- ✅ **Design Profissional** - Interface moderna e acessível

**Fluxo de Acesso:**
1. Usuário acessa o site → Redirecionado automaticamente para `disclaimer.html`
2. Deve ler e marcar confirmação explícita de entendimento
3. Só então pode acessar a demonstração do projeto
4. Link permanente para revisitar o disclaimer disponível

</div>

---

## 📋 Sobre o Projeto

Clone da página inicial do Instagram desenvolvido em **Janeiro de 2025** como parte do programa **Dev em Dobro**. Projeto **100% educacional** para portfólio e demonstração de habilidades em Front-End.

## 🎯 Funcionalidades

### Interface
- ✅ Layout idêntico à página original do Instagram
- ✅ Design responsivo (mobile e desktop)
- ✅ Animações suaves e transições
- ✅ Formulário de login estilizado
- ✅ Seção de download de apps

### Sistema de Disclaimer (NOVO)
- ✅ Página dedicada de aviso legal
- ✅ Confirmação obrigatória do usuário
- ✅ Armazenamento local da aceitação
- ✅ Redirecionamento automático controlado
- ✅ Link permanente para revisitar o disclaimer
- ✅ Informações técnicas e legais completas

### Técnico
- ✅ Código limpo e organizado
- ✅ Animações com JavaScript puro
- ✅ CSS moderno com variáveis e flexbox
- ✅ Estrutura semântica HTML5

## 📁 Estrutura do Projeto Atualizada

```
Pag_Inicial-Insta_Dev/
├── disclaimer.html          ← NOVA: Página de disclaimer obrigatório
├── index.html              ← Página principal (acesso controlado)
├── README.md               ← Documentação atualizada
└── src/
    ├── css/
    │   └── style.css       ← Estilos principais + footer disclaimer
    ├── js/
    │   └── script.js       ← Animação das imagens
    └── img/
        ├── celular.png
        ├── insta1.png
        ├── insta2.png
        ├── insta-logo.png
        ├── google.png
        ├── ios.png
        └── ... (outras imagens)
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica da página
- **CSS3** - Estilos, responsividade e animações
- **JavaScript** - Lógica de animação e controle do disclaimer
- **Font Awesome** - Ícones para a página de disclaimer
- **Git/GitHub** - Controle de versão e deploy
- **GitHub Pages** - Hospedagem gratuita

## ⚖️ Sistema de Disclaimer (Detalhamento)

### Características do Sistema:
1. **Página Dedicada** (`disclaimer.html`)
   - Design profissional com gradientes e animações
   - Informações técnicas completas do projeto
   - Lista detalhada de limitações e propósitos
   - Checkbox de confirmação obrigatória
   - Botões de ação com estados visuais

2. **Controle de Acesso** (`index.html`)
   - Redirecionamento automático para o disclaimer
   - Verificação de aceitação prévia no localStorage
   - Prevenção de navegação para trás
   - Link permanente para revisitar o disclaimer

3. **Armazenamento Local**
   - Salva timestamp da aceitação
   - Persistência entre sessões
   - Reset via função específica

### Código Principal do Sistema:

**Controle de Acesso (index.html):**
```javascript
// Verifica aceitação do disclaimer
if (localStorage.getItem('disclaimerAccepted') !== 'true') {
    window.location.href = 'disclaimer.html';
}
```

**Confirmação no Disclaimer:**
```javascript
function acceptDisclaimer() {
    if (!document.getElementById('legalConsent').checked) {
        alert('Confirmação obrigatória!');
        return;
    }
    localStorage.setItem('disclaimerAccepted', 'true');
    window.location.href = 'index.html';
}
```

## 📱 Demonstração

### Desktop:
- Layout dividido com celular à esquerda
- Formulário de login à direita
- Imagens alternam automaticamente a cada 5 segundos
- Footer com link para o disclaimer

### Mobile:
- Apenas o formulário é exibido
- Layout otimizado para telas pequenas
- Footer adaptado para mobile

### Fluxo de Acesso:
1. **Primeiro Acesso**: `disclaimer.html` → Confirmação → `index.html`
2. **Acessos Seguintes**: Verificação → `index.html` (se já aceitou)
3. **Revisitar**: Link no footer para retornar ao disclaimer

## 🚫 O que este projeto NÃO possui (Declarado Explicitamente):

- ❌ Backend ou banco de dados
- ❌ Sistema de login real ou funcional
- ❌ Conexão com APIs do Instagram/Meta
- ❌ Coleta, armazenamento ou processamento de dados de usuários
- ❌ Afiliação, endosso ou autorização da Meta Platforms, Inc.
- ❌ Fins comerciais ou monetização

## ✅ Conformidade Legal

Este projeto está em total conformidade com:

- **Termos do GitHub** para fins educacionais
- **Direitos Autorais** - Reconhecimento explícito da propriedade intelectual da Meta
- **LGPD/GDPR** - Nenhum dado pessoal coletado
- **Boas Práticas** - Transparência total com os usuários
- **Finalidade Educacional** - Apenas para estudo e portfólio

## 🚀 Como Usar

1. **Acesso Online:**
   - O site redirecionará automaticamente para o disclaimer
   - Leia atentamente e marque a confirmação
   - Acesse a demonstração do projeto

2. **Execução Local:**
   ```bash
   # Clone o repositório
   git clone [url-do-repositorio]
   
   # Abra o disclaimer.html no navegador
   # Siga o fluxo normal de aceitação
   ```

3. **Para Desenvolvedores:**
   - Estude a estrutura do disclaimer.html para implementações similares
   - Analise o sistema de controle de acesso com localStorage
   - Adapte o design para outros projetos educacionais

## 📝 Código Principal da Animação

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

## 👩‍💻 Autoria

**Rayssa Vieira** - Desenvolvedora Front-End  
**Programa:** Dev em Dobro  
**Período:** Janeiro de 2025  
**Finalidade:** Exercício educacional de Front-End para portfólio

### Habilidades Demonstradas:
- Desenvolvimento Front-End com HTML5, CSS3 e JavaScript
- Implementação de sistemas de controle de acesso
- Design responsivo e animações CSS/JS
- Conformidade legal e transparência com usuários
- Versionamento com Git/GitHub

---

<div align="center">
  
### ⭐ Se este projeto ajudou você, considere dar uma estrela no repositório!

**Nota:** Este projeto é mantido estritamente para fins educacionais. Todo o código é original e desenvolvido como exercício de aprendizado.

</div>

## 📄 Licença de Uso

Este projeto está disponível para estudo e referência. O design da interface do Instagram é propriedade intelectual da Meta Platforms, Inc. Esta implementação é uma reprodução educacional sem fins comerciais.

---

**Última Atualização:** Janeiro 2025  
**Status do Projeto:** Concluído ✓  
**Sistema de Disclaimer:** Implementado e Funcional ✓
