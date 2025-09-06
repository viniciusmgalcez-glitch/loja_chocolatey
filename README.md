🍫 Loja de Pacotes Chocolatey com Flask
Bem-vindo ao repositório do projeto, uma interface web para gerenciar e visualizar pacotes do Chocolatey, o gerenciador de pacotes para Windows.

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

Feito com ❤️ por viniciusmgalcez-glitch.
