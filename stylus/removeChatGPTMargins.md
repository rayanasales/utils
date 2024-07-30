# Stylus: Remove ChatGPT Margins

## Google Chrome Setup

Você pode mudar a fonte usando uma extensão do Chrome que permite injetar CSS personalizado nas páginas que você visita. Uma dessas extensões é a "Stylus", que permite criar estilos personalizados para os sites.

1. **Instalar a extensão Stylus**:
   - Vá até a Chrome Web Store e procure por "Stylus". Instale a extensão no seu navegador.
   - Link para extensão: https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne?pli=1
2. **Criar um novo estilo**:
   - Clique no ícone da extensão Stylus na barra de ferramentas do Chrome.
   - Escolha "Manage" e depois "Write new style".
   - Nomeie seu novo estilo (por exemplo, "Override Chrome Defaults").
3. **Adicionar CSS personalizado**

## CSS para forçar estilo

```css
.mx-auto {
  max-width: unset !important;
}
.flex-grow {
  max-width: unset !important;
}
.text-message {
  max-width: unset !important;
}
```

## Gerenciando impacto: Style settings

### Custom included sites

`*https://chatgpt.com/*`</br>

### Custom excluded sites

`*https://leetcode.com/*` </br>
`*https://calendar.google.com/*` </br>
`*https://mail.google.com/*` </br>
