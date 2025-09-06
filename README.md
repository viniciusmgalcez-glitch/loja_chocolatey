<div align="center">
<h1>🍫 Loja de Pacotes Chocolatey com Flask</h1>
<p>Uma vitrine web simples, feita com Flask, para navegar e pesquisar pacotes do Chocolatey.</p>

<p>
<img src="https://img.icons8.com/?size=100&id=13441&format=png&color=000000" alt="Badge Python"/>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Flask-000000%3Fstyle%3Dfor-the-badge%26logo%3Dflask%26logoColor%3Dwhite" alt="Badge Flask"/>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Render-46E3B7%3Fstyle%3Dfor-the-badge%26logo%3Drender%26logoColor%3Dwhite" alt="Badge Render"/>
</p>
</div>

<div align="center">
<img src="https://www.google.com/search?q=https://placehold.co/800x400/2d333b/f0f6fc%3Ftext%3DScreenshot%2Bda%2BAplica%C3%A7%C3%A3o" alt="Screenshot da tela inicial da Loja Chocolatey" style="border-radius: 8px;"/>
</div>

📝 Descrição
Este projeto é uma aplicação web simples, construída com o micro-framework Python Flask, que serve como uma "loja" ou vitrine para pacotes do Chocolatey. O objetivo é facilitar a busca e a visualização de programas que podem ser instalados no Windows via linha de comando. A aplicação foi desenvolvida pensando na implantação na plataforma Render.

✨ Funcionalidades Principais
Listagem de Pacotes: Exibe uma lista de pacotes populares ou pré-definidos do Chocolatey.

Busca de Pacotes: Permite que os usuários pesquisem por pacotes específicos.

Visualização de Detalhes: Mostra informações sobre um pacote, como versão e o comando de instalação.

Design Responsivo: Interface limpa e adaptável para diferentes tamanhos de tela.

🛠️ Tecnologias Utilizadas
Backend:

Python

Flask

Frontend (Renderização no Servidor):

HTML5

CSS3

Jinja2 (Template Engine do Flask)

Deployment:

Render

Gunicorn (ou outro WSGI server)

🚀 Como Executar o Projeto
Siga os passos abaixo para configurar e rodar o projeto em seu ambiente local.

Pré-requisitos
Python (versão 3.8 ou superior)

Git

pip (gerenciador de pacotes do Python)

Instalação
Clone o repositório:

git clone [https://github.com/viniciusmgalcez-glitch/loja_chocolatey.git](https://github.com/viniciusmgalcez-glitch/loja_chocolatey.git)
cd loja_chocolatey

Crie e ative um ambiente virtual:

# Para Windows
python -m venv venv
.\venv\Scripts\activate

# Para macOS/Linux
python3 -m venv venv
source venv/bin/activate

Instale as dependências:

pip install -r requirements.txt

(Opcional) Configure as variáveis de ambiente:

Crie um arquivo .env na raiz do projeto.

Adicione as configurações do Flask.

FLASK_APP=app.py
FLASK_ENV=development

Execução
Inicie o servidor de desenvolvimento do Flask:

flask run

A aplicação estará acessível em http://127.0.0.1:5000.

🤝 Como Contribuir
Contribuições são sempre bem-vindas! Se você deseja ajudar a melhorar este projeto, siga os passos abaixo:

Faça um Fork deste repositório.

Crie uma nova branch para sua feature: git checkout -b minha-feature.

Faça suas alterações e realize o commit: git commit -m "feat: Adiciona nova funcionalidade".

Envie para a sua branch: git push origin minha-feature.

Abra um Pull Request para que possamos avaliar suas mudanças.

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

<div align="center">
Feito com ❤️ por <a href="https://www.google.com/search?q=https://github.com/viniciusmgalcez-glitch">viniciusmgalcez-glitch</a>.
</div>
