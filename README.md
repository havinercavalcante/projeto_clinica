# API de Gerenciamento de Pacientes e Agenda de Clínica

## Descrição
Esta API RESTful foi desenvolvida para ser consumida por um software de gerenciamento de pacientes e agenda de uma clínica. Ela oferece funcionalidades para gerenciar informações dos pacientes, agendar consultas e manter registros atualizados das atividades da clínica. O projeto utiliza Django e Django Rest Framework para uma implementação eficaz e segura.

## Tecnologias Utilizadas
- Python
- Django
- Django Rest Framework

## Instalação e Configuração
Para configurar e rodar a API localmente, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/api-gerenciamento-clinica.git

2. Navegue até o diretório do projeto:
   ```bash
   cd api-gerenciamento-clinica

3. Crie um ambiente virtual:
   ```bash
   python -m venv venv

4. Ative o ambiente virtual:
   ```bash
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`

5. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   
6. Realize as migrações:
   ```bash
   python manage.py migrate

7. Inicie o servidor:
   ```bash
   python manage.py runserver

