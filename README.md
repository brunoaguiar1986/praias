🌍 Projeto: Site Flask Hospedado no Render

https://praias.onrender.com/

Este repositório contém um site simples desenvolvido com Flask e hospedado no Render. O objetivo é demonstrar como criar e implantar uma aplicação Flask de forma gratuita.


🚀 Tecnologias Utilizadas

Python 3.10+

Flask (Framework Web)

Gunicorn (Servidor WSGI para produção)

HTML/CSS (Templates para a interface)

Render (Plataforma de hospedagem)


📂 Estrutura do Projeto

/meu_projeto
│── /templates
│   ├── index.html  # Página principal
│── requirements.txt  # Lista de dependências
│── Procfile  # Comando para rodar a aplicação no Render
│── index.py  # Código principal do Flask
│── README.md  # Documentação do projeto


⚙️ Como Rodar Localmente

1️⃣ Clone este repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

2️⃣ Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

3️⃣ Instale as dependências:

pip install -r requirements.txt

4️⃣ Execute o servidor Flask:

python index.py

Acesse o site no navegador: http://127.0.0.1:5000


🌍 Como Implantar no Render

1️⃣ Suba o projeto para o GitHub:

git add .
git commit -m "Primeiro commit"
git push origin main

2️⃣ Acesse o Render e crie um novo "Web Service".

3️⃣ Conecte o repositório do GitHub.

4️⃣ Configure o ambiente:

Build Command: pip install -r requirements.txt

Start Command: gunicorn index:app

Environment: Python 3.10+

5️⃣ Clique em Deploy e aguarde a publicação!


🛠 Solução de Problemas

Caso encontre erros ao implantar, verifique:

Se o requirements.txt contém gunicorn.

Se o nome do arquivo Flask está correto no Procfile.

Os logs no Render para mais detalhes.


📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar! 😃

Feito por Bruno 🚀
