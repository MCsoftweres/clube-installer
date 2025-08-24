
# Sistema de Clube com Reconhecimento Facial

Este projeto é um sistema de autenticação para clubes que utiliza reconhecimento facial via webcam, além de autenticação por senha. Ele inclui uma interface web simples e um instalador automático para Windows.

## 🚀 Funcionalidades
- Cadastro de usuários com nome e rosto
- Login com verificação facial
- Interface web com Flask
- Instalador automático para Windows
- Página de download hospedável no GitHub Pages

## 📦 Instalação

### Requisitos
- Python 3 instalado
- Webcam funcional

### Passos
1. Baixe os arquivos `clube_system.zip` e `installer.bat`
2. Coloque ambos na mesma pasta
3. Execute `installer.bat` com dois cliques
4. O sistema será instalado e iniciado automaticamente em `localhost:4000`

## 🌐 Hospedagem no GitHub Pages

1. Crie um repositório público no GitHub
2. Envie os arquivos do pacote `clube_site_package.zip`
3. Vá em **Settings > Pages** e selecione a branch `main` e pasta `/root`
4. Acesse sua página em `https://seu-usuario.github.io/nome-do-repositorio/`

## 📁 Estrutura do Projeto
```
clube_system/
├── app.py
├── templates/
│   ├── login.html
│   ├── register.html
│   └── home.html
├── known_faces/
└── run.sh

clube_site/
├── index.html
├── installer.bat
└── clube_system.zip
```

## 👨‍💻 Autor
Pedro - Projeto de autenticação com reconhecimento facial
