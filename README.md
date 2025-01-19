# EBAC Django Project

Este é um projeto desenvolvido durante o curso da EBAC, utilizando o framework Django. O objetivo é aprender a criar e gerenciar aplicações web com Python e Django, explorando conceitos de desenvolvimento web, banco de dados e deploy.

## Estrutura do Projeto

### Tecnologias Utilizadas
	•	Python: 3.9+
	•	Django: 4.2.18
	•	Banco de Dados: SQLite (default do Django)
	•	Bibliotecas Instaladas:
	•	requests
	•	beautifulsoup4

Instalação e Configuração
	1.	Clone o Repositório:

git clone <url-do-repositorio>
cd mysite


	2.	Crie e Ative um Ambiente Virtual:

python -m venv env
source env/bin/activate  # No Windows: env\Scripts\activate


	3.	Instale as Dependências:

pip install -r requirements.txt


	4.	Aplique as Migrações:

python manage.py migrate


	5.	Execute o Servidor de Desenvolvimento:

python manage.py runserver


	6.	Acesse no Navegador:
Abra o navegador em http://127.0.0.1:8000/.

Registro do Progresso

Branch: inicial
	•	Objetivo: Configuração inicial do projeto Django.
	•	Comandos Executados:

python manage.py migrate
python manage.py runserver


	•	Status:
	•	Migrações aplicadas com sucesso.
	•	Servidor de desenvolvimento iniciado.
	•	Página inicial do Django exibida em http://127.0.0.1:8000/.

Próximos Passos
	1.	Criar o primeiro aplicativo Django usando o comando:

python manage.py startapp <app_name>


	2.	Configurar modelos, views e templates.
	3.	Implementar funcionalidades específicas do projeto.

Observações
	•	Erros Conhecidos:
	•	apple-touch-icon e favicon.ico: Arquivos de ícones não encontrados. Estes erros não afetam o funcionamento do projeto.
	•	Nota:
Atualize este README em cada branch ou nova funcionalidade para manter um histórico claro do progresso.

