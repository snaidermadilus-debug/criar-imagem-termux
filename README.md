# Criar Imagem Termux

Script Python para criar imagens automaticamente no Termux e abrir na galeria do Android.

---

## Como usar

### 1️⃣ Instalar dependências no Termux:

```bash
pkg update -y && pkg upgrade -y
pkg install python termux-api -y
pip install requests beautifulsoup4 lxml
termux-setup-storage
