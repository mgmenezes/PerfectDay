# 📸 Como Adicionar Suas Fotos ao Carrossel

## 🎯 **Passo a Passo:**

### **1. Preparar as Fotos**
- Renomeie suas fotos para nomes simples: `foto1.jpg`, `foto2.jpg`, etc.
- Tamanho recomendado: 800x600 pixels (proporção 4:3)
- Formato: JPG ou PNG
- Otimize as imagens para web (máximo 500KB cada)

### **2. Colocar as Fotos na Pasta**
1. Coloque todas as fotos na pasta `images/` que foi criada
2. Certifique-se de que os nomes estão corretos

### **3. Atualizar o HTML**
No arquivo `index.html`, encontre a seção do carrossel e substitua as URLs das imagens:

**ANTES:**
```html
<img src="https://images.unsplash.com/photo-1516589178581-6cd7833ae3b2?w=800&h=600&fit=crop" alt="Momento especial 1" loading="lazy">
```

**DEPOIS:**
```html
<img src="images/foto1.jpg" alt="Momento especial 1" loading="lazy">
```

### **4. Personalizar as Legendas**
Altere as legendas para combinar com suas fotos:

```html
<div class="slide-caption">Nossa primeira foto juntos ❤️</div>
<div class="slide-caption">Aventuras pelo mundo 🌍</div>
<div class="slide-caption">Momentos especiais em casa 🏠</div>
```

## 📝 **Sugestões de Fotos baseadas no que você compartilhou:**

1. **foto1.jpg** - Vocês com o cachorrinho (primeira foto)
2. **foto2.jpg** - Momento no restaurante/bar (segunda foto)  
3. **foto3.jpg** - Foto romântica de perfil (terceira foto)
4. **foto4.jpg** - No restaurante elegante (quarta foto)
5. **foto5.jpg** - No elevador/espelho (quinta foto)
6. **foto6.jpg** - Ao ar livre sorrindo (sexta foto)
7. **foto7.jpg** - Na praia/local noturno (sétima foto)
8. **foto8.jpg** - Relaxando na praia (última foto)

## ⚡ **Exemplo Completo de Substituição:**

```html
<div class="carousel-slide active">
    <img src="images/foto1.jpg" alt="Nosso amor" loading="lazy">
    <div class="slide-caption">Nosso amor e nosso pequeno companheiro ❤️</div>
</div>
<div class="carousel-slide">
    <img src="images/foto2.jpg" alt="Momentos especiais" loading="lazy">
    <div class="slide-caption">Momentos de alegria e cumplicidade 💕</div>
</div>
```

## 🎨 **Dicas Extras:**

### **Para Otimizar as Fotos:**
- Use ferramentas online como TinyPNG ou Squoosh.app
- Mantenha proporção 4:3 para melhor visualização
- Prefira imagens horizontais

### **Para Hospedar na Vercel:**
1. Após fazer as alterações, faça o upload da pasta `images/` junto com os arquivos
2. A Vercel automaticamente servirá as imagens estáticas

### **Alternativa com Imgur (mais fácil):**
1. Suba suas fotos no Imgur.com
2. Copie o link direto da imagem
3. Use o link no lugar de `images/foto1.jpg`

Exemplo: `src="https://i.imgur.com/SEUCODIGO.jpg"`

---

**💡 Lembre-se:** Após fazer as alterações, teste localmente abrindo o `index.html` no navegador antes de fazer o deploy! 