# Geosynk - Landing Page

Landing page moderna para a Geosynk, plataforma de IA especializada em gestão de áreas contaminadas.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica moderna
- **Tailwind CSS**: Framework CSS utility-first via CDN
- **JavaScript Vanilla**: Animações e interações
- **CSS3**: Animações customizadas e efeitos visuais

## Características

### Design
- Layout moderno e responsivo
- Esquema de cores profissional (verde/turquesa)
- Animações suaves ao scroll
- Efeitos de hover interativos
- Gradientes e elementos visuais modernos

### Seções
1. **Hero Section**: Chamada principal com CTA
2. **Problema**: Desafios do gerenciamento ambiental
3. **Solução**: Como a Geosynk resolve
4. **Funcionalidades**: 4 features principais em cards
5. **Benefícios**: Para engenheiros e empresas
6. **Casos de Uso**: 5 setores diferentes
7. **Roadmap**: Timeline de evolução
8. **CTA/Demo**: Formulário de contato
9. **Footer**: Links e informações

### Funcionalidades
- Scroll suave entre seções
- Animações ao entrar no viewport
- Navbar com sombra ao scroll
- Efeito parallax no hero
- Formulário funcional
- Totalmente responsivo

## Como Usar

### Opção 1: Abrir Diretamente no Navegador
1. Navegue até a pasta `geosynk-landing`
2. Clique duas vezes no arquivo `index.html`

### Opção 2: Servidor Local (Recomendado)
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (npx)
npx serve

# Com PHP
php -S localhost:8000
```

Depois acesse: `http://localhost:8000`

## Estrutura de Arquivos

```
geosynk-landing/
├── index.html      # Estrutura HTML principal
├── styles.css      # Estilos customizados e animações
├── script.js       # Interações e animações JavaScript
└── README.md       # Este arquivo
```

## Paleta de Cores

- **Primary**: #0A4D3C (Verde escuro)
- **Secondary**: #18A380 (Verde médio)
- **Accent**: #2DD4BF (Turquesa)
- **Dark**: #0F172A (Preto azulado)
- **Light**: #F8FAFC (Branco suave)

## Personalização

### Cores
Edite a configuração do Tailwind no `<head>` do `index.html`:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#0A4D3C',    // Sua cor primária
                secondary: '#18A380',   // Sua cor secundária
                accent: '#2DD4BF',      // Cor de destaque
            }
        }
    }
}
```

### Conteúdo
Todo o conteúdo está em português no `index.html` e pode ser facilmente editado.

### Formulário
O formulário atualmente mostra um alerta. Para integrar com backend:
1. Edite a função de submit em `script.js`
2. Adicione sua API endpoint
3. Configure o método de envio (fetch, axios, etc)

## Compatibilidade

- Chrome (última versão)
- Firefox (última versão)
- Safari (última versão)
- Edge (última versão)
- Responsivo para mobile, tablet e desktop

## Próximos Passos

Para produção, considere:
1. Hospedar o Tailwind CSS localmente
2. Otimizar imagens (quando adicionar)
3. Minificar CSS e JS
4. Adicionar analytics (Google Analytics, etc)
5. Configurar SEO (meta tags, Open Graph)
6. Integrar formulário com backend real
7. Adicionar testes A/B

## Licença

Projeto proprietário da Geosynk.

---

**Desenvolvido com tecnologias modernas para máxima performance e experiência do usuário.**