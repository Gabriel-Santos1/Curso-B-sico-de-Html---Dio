# 📚 Guia de HTML Essencial

## ✍️ Tipografia

### Títulos

- `H1`
- `H2`
- `H3`
- `H4`

### Ênfase

- **Negrito**: `<strong>` ou `<b>`
- *Itálico*: `<i>`

### Citação

- `<blockquote>`: Usado para destacar trechos ou citações.

---

## 📃 Listas e Links

### Lista Ordenada

```html
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
```

### Lista Desordenada

```html
<ul>
  <li>Item A</li>
  <li>Item B</li>
</ul>
```

### Links

```html
<a href="URL" title="Descrição">Texto do Link</a>
```

---

## 🖥️ Formulários

### Métodos de Envio

- `GET`: Envia os dados visivelmente na URL.
- `POST`: Envia os dados de forma "encapsulada".

### Autocomplete

- `on`: Ativa preenchimento automático.
- `off`: Desativa preenchimento automático.

### Input

```html
<input type="number" min="0" max="10" step="1">
```

---

## 🏷️ Tags HTML e Marcações

### Marcações de Texto

- `<i>`: Itálico  
- `<u>`: Sublinhado  
- `<b>`: Negrito  
- `<mark>`: Texto destacado  
- `<sup>`: Texto sobrescrito  
- `<sub>`: Texto subscrito  
- `<blockquote>`: Citação/explicação destacada  

### Fieldsets

```html
<fieldset>
  <legend>Informações Pessoais</legend>
  <!-- Campos aqui -->
</fieldset>
```

### Embeds e Mídias

- Tags antigas como `<embed>` foram descontinuadas.
- Prefira `<video>` para vídeos.

### Iframes

- Permite carregar outras páginas dentro da sua.
- Usado em integrações como Google Maps ou YouTube.

---

## 🖼️ Trabalhando com Mídia

### Imagens

```html
<img src="imagem.jpg" title="Descrição da imagem">
```

### Áudio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

### Vídeo

```html
<video controls>
  <source src="video.mp4" type="video/mp4">
  <track src="legenda.vtt" kind="subtitles">
</video>
```

---

## 📊 Tabelas

### Estrutura Básica

```html
<table summary="Tabela de Exemplo">
  <caption>Exemplo de Tabela</caption>
  <thead>
    <tr>
      <th>Coluna A</th>
      <th>Coluna B</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Dado 1</td>
      <td>Dado 2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Rodapé</td>
    </tr>
  </tfoot>
</table>
```

### Propriedades CSS Comuns

- `nth-child(even)`: Seleciona linhas pares.
- `colspan`: Define quantas colunas uma célula ocupa.
- `cellspacing`: Espaço entre células (usado no HTML antigo).
- `cellpadding`: Espaço interno da célula.
