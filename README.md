# Criar Imagem (Termux)

Script em Python para Android (Termux) que:

- Busca imagens automaticamente na internet (DuckDuckGo / Bing)
- Baixa e salva imagens em `/sdcard/Pictures/IA`
- Abre automaticamente na galeria do Android
- Interface limpa no terminal com banner e contador animado
- Permite criar várias imagens consecutivas sem reiniciar o script

---


Comando único Para qualquer pessoa baixar e executar tudo de uma vez no Termux
           👇

git clone git@github.com:snaidermadilus-debug/criar-imagem-termux.git && \
cd criar-imagem-termux && \
pkg update -y && pkg install python termux-api -y && \
pip install requests --no-cache-dir && \
termux-setup-storage && \
python criarimg.py

## Requisitos

----------

Comando único (one-liner

Para qualquer pessoa baixar e executar tudo de uma vez no Termux:

---

  git clone git@github.com:snaidermadilus-debug/criar-imagem-termux.git && \
  cd criar-imagem-termux && \
  pkg update -y && pkg install python termux-api -y && \
  pip install requests --no-cache-dir && \
  termux-setup-storage && \
  python criarimg.py

---
                 




