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

- Termux
- Python 3
- termux-api

---

## Instalação

No Termux, execute:

```bash
pkg update -y
pkg install python termux-api -y
pip install requests beautifulsoup4 lxml
termux-setup-storage

-----
-----

1 Entre na pasta do projeto:

cd criar-imagem-termux

2 Execute o script:

python criarimg.py

3 Digite o que deseja criar no prompt:

criar próxima imagem:
>> dragão realista voando céu

4 Para sair do script, digite:

sair

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

Observações

As imagens são salvas em /sdcard/Pictures/IA/

O script abre automaticamente a galeria do seu Android ao finalizar cada imagem

Banner e contador animado aparecem no terminal durante a busca e download


⚠️ Se você não tiver requests instalado, rode este comando:

Provavelmente quando você estará isso vai dar erro mas não importa estará o que tá lá embaixo
                 👇
pip install requests --no-cache-dir 
                👇
pip install requests --no-cache-dir &


                 




