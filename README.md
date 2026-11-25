# Previa Site

Site da Previa (previa: cardápio em realidade aumentada, sites e plaquinhas NFC para restaurantes).

Site estático em um único `index.html` (CSS e JS dentro dele; GSAP, Lenis e model-viewer por CDN). Sem build.

## Ver no computador

Precisa de um servidor (abrir o arquivo direto não carrega as imagens nem o 3D):

    python -m http.server 5190

Depois abra http://localhost:5190/

## Publicar

    vercel deploy --prod
