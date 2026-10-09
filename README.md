# Dra. Thatiane Bertolacini — Landing Page

Landing page institucional para a Dra. Thatiane Bertolacini, especialista em Ortodontia e Ortopedia Funcional dos Maxilares, com atendimento em **Cambuí-MG**, **Toledo-MG** e **Atibaia-SP**.

🔗 **Site no ar:** https://tbertolacini.com.br

## Sobre o projeto

Site institucional de página única (landing page) desenvolvido para divulgação do consultório, com foco em apresentar a especialista, os diferenciais do tratamento com alinhadores invisíveis e os três endereços de atendimento.

## Stack

- HTML5 + CSS3 (custom properties / design tokens, sem framework)
- JavaScript vanilla (menu mobile)
- Totalmente estático — um único arquivo `index.html`, sem build step, sem dependências de backend
- Hospedado via GitHub Pages, com domínio próprio (`tbertolacini.com.br`) registrado no Registro.br

## Destaques técnicos

- Design system próprio com tokens de cor (paleta navy + champagne) e tipografia pareada (Lora para títulos, Plus Jakarta Sans para texto)
- Layout responsivo (grid/flexbox), com breakpoints dedicados para mobile, tablet e desktop
- Mídia (imagens e vídeo) embutida como `data:` URI — página 100% autocontida, sem requisições externas além das fontes do Google Fonts
- Seção de localização com mapas reais das três cidades de atendimento

## Deploy

O repositório já está configurado para GitHub Pages com domínio customizado:

1. Nas configurações do repositório → **Pages**, selecionar a branch `main` (pasta `/root`) como fonte
2. O arquivo `CNAME` já aponta para `tbertolacini.com.br`
3. No painel de DNS do domínio (Registro.br), configurar:
   - **Registros A** (domínio raiz) apontando para os IPs do GitHub Pages:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - **CNAME** do subdomínio `www` apontando para `mfajunior.github.io`
4. Aguardar a propagação de DNS e habilitar "Enforce HTTPS" nas configurações de Pages

## Autor

Desenvolvido por [Milton Faria Andrade Júnior](https://github.com/mfajunior).
