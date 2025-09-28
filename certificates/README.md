# Certificados - Instrucciones de Uso

## Para agregar tus certificados reales:

1. **Coloca tus archivos PDF en esta carpeta** con los siguientes nombres:
   - `java-fundamentals-coursera.pdf` - Certificado de Fundamentals of Java Programming (Coursera)

2. **Los archivos deben ser PDFs** para que funcione correctamente la descarga.

3. **Nombres de descarga**: Los archivos se descargarán con nombres descriptivos como:
   - "Java_Fundamentals_Certificate.pdf"

## Certificado actual:
- ✅ **Fundamentals of Java Programming** - Coursera (2024)

## Para agregar más certificados:

1. **Editar el HTML**: En `index.html`, busca la sección de certificados y añade:
```html
<div class="certificate-card bg-gradient">
    <div class="certificate-icon">🏆</div>
    <h4 class="certificate-title">Nombre del Certificado</h4>
    <p class="certificate-issuer">Institución</p>
    <p class="certificate-date">Año</p>
    <a href="certificates/archivo.pdf" class="certificate-download" download="Nombre_Descarga.pdf">
        <i class="fa-solid fa-download"></i>
        Download Certificate
    </a>
</div>
```

## Nota importante:
Los enlaces de descarga funcionarán cuando tengas los archivos PDF reales en esta carpeta.