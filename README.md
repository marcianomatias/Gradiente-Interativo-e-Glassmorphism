
# Gradiente Interativo e Glassmorphism

Um projeto moderno que demonstra a implementação de gradientes interativos e efeito glassmorphism usando HTML, CSS e JavaScript.

## 🚀 Demonstração

O projeto apresenta:
- Gradiente dinâmico que responde ao movimento do mouse
- Efeito vidro (glassmorphism) com transparência e blur
- Controles de cores personalizáveis
- Interface responsiva e moderna

## 💻 Tecnologias Utilizadas

- HTML5
- CSS3 (com suporte a backdrop-filter)
- JavaScript Vanilla

## 🎨 Recursos

### Gradiente Interativo
- Muda dinamicamente com o movimento do mouse
- Seletor de cores personalizável
- Transições suaves

### Efeito Glassmorphism
- Transparência elegante
- Efeito blur no background
- Bordas suaves
- Sombras sutis

## 🛠️ Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/marcianomatias/Gradiente-Interativo-e-Glassmorphism.git
```

2. Abra o arquivo `index.html` em seu navegador

3. Interaja com o gradiente movendo o mouse e use os seletores de cor para personalizar

## 📦 Estrutura do Projeto

```
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## ⚙️ Compatibilidade

Requer navegadores modernos com suporte a:
- CSS backdrop-filter
- CSS gradients
- JavaScript ES6+

## 💡 Exemplos de Código

### HTML
```html
<div class="container">
    <div class="glass-card">
        <div class="gradient-controls">
            <input type="color" class="color1" value="#ff6b6b">
            <input type="color" class="color2" value="#4ecdc4">
        </div>
    </div>
</div>
```

### CSS
```css
.glass-card {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border-radius: 20px;
    padding: 2rem;
}
```

### JavaScript
```javascript
container.addEventListener('mousemove', (e) => {
    const x = e.clientX / window.innerWidth;
    const y = e.clientY / window.innerHeight;
    updateGradient(x, y);
});
```

## 👤 Autor

**Marciano Matias**
- GitHub: [@marcianomatias](https://github.com/marcianomatias)
- LinkedIn: [Marciano Matias](https://www.linkedin.com/in/marcianomatias/)

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

⭐️ Se este projeto te ajudou, considere dar uma estrela!

```

Este README.md fornece uma documentação clara e completa do projeto, incluindo:
- Descrição do projeto
- Recursos e funcionalidades
- Instruções de instalação e uso
- Exemplos de código
- Informações sobre compatibilidade
- Detalhes do autor
- Licença

A formatação em Markdown garante uma boa apresentação no GitHub, com:
- Títulos hierárquicos
- Listas
- Blocos de código
- Emojis para melhor visualização
- Links relevantes
