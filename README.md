Sorricid - Sistema de Gestão para Clínica Odontológica 🦷
Sistema web completo para gestão de clínica odontológica, incluindo agendamento de consultas, cadastro de afiliados e gerenciamento de candidatos a vagas de emprego.
📋 Sobre
O Sorricid é uma plataforma web desenvolvida para facilitar a gestão de uma clínica odontológica. O sistema permite que pacientes agendem consultas online, cadastrem-se como afiliados para receber benefícios, e candidatos possam se inscrever para vagas disponíveis. A aplicação oferece painéis administrativos para gerenciar todas essas informações de forma centralizada.
✨ Funcionalidades

Agendamento de Consultas: Formulário completo para pacientes agendarem procedimentos odontológicos
Gestão de Pacientes: Listagem, edição e exclusão de agendamentos
Programa de Afiliados: Cadastro de parceiros interessados em divulgar a clínica
Recrutamento: Sistema para candidatos se inscreverem em vagas disponíveis
Portfólio de Serviços: Página detalhada com todos os procedimentos oferecidos
Galeria de Imagens: Slider automático na página inicial
Sistema de Promoções: Cards destacando ofertas especiais
Validação de CPF: Formatação automática do campo CPF

🚀 Tecnologias
Frontend

HTML5
CSS3
JavaScript (Vanilla)

Backend

PHP 8.2
MySQL/MariaDB

Banco de Dados

MariaDB 10.4.32
3 tabelas principais: pacientes, afiliados, candidato

📦 Instalação
Pré-requisitos

PHP 8.0 ou superior
MySQL/MariaDB
Apache ou servidor web compatível
phpMyAdmin (opcional, para gerenciar o banco)

Passos

Clone o repositório

bashgit clone https://github.com/seu-usuario/sorricid.git
cd sorricid

Configure o servidor web

Coloque os arquivos na pasta do seu servidor (ex: htdocs para XAMPP)
Certifique-se de que o Apache e MySQL estão rodando


Importe o banco de dados

bash# Acesse o phpMyAdmin ou execute via terminal:
mysql -u root -p < venus.sql

Configure a conexão com o banco

As credenciais padrão nos arquivos PHP são:

Host: localhost
Database: venus
User: root
Password: (vazia)


Se necessário, altere nos arquivos PHP (marcaConsulta.php, cadastrarAfiliado.php, etc.)



🔧 Estrutura do Banco de Dados
Tabela: pacientes

Armazena agendamentos de consultas
Campos: id, nome, email, mensagem, cpf, data, profissional, procedimento

Tabela: afiliados

Gerencia o programa de parceiros
Campos: id, nome, email, endereco, numero, bairro, cidade, estado

Tabela: candidato

Gerencia candidatos a vagas
Campos: id, nome, email, escolaridade, funcao, linkedin

💻 Uso

Acesse a aplicação

Abra http://localhost/sorricid/index.html no navegador


Navegação Principal

Início: Página principal com promoções
Nossos Serviços: Catálogo de procedimentos
Agendar: Formulário de agendamento
Sobre Nós: Informações da clínica
Contato: Redes sociais e informações de contato


Áreas Administrativas

/listarPacientes.php - Gerenciar consultas
/listarAfiliados.php - Gerenciar afiliados
/listarcandidatos.php - Gerenciar candidatos



🎨 Páginas Disponíveis

index.html - Página inicial
agendar.html - Formulário de agendamento
NossosServico.html - Serviços oferecidos
sobre.html - Sobre a clínica
contato.html - Informações de contato
candidato.html - Inscrição para vagas
filiado.html - Cadastro de afiliados

📞 Informações da Clínica

Endereço: R. Dr. Jorge de Lima, 113 - Trapiche da Barra, São Paulo - SP, 53410-180
Email: S.sorricid@gmail.com
Telefone: (11) 95736-5641

👥 Desenvolvedores

Henrique Rodrigues
João Castro

📄 Licença
Copyright © 2025 - Todos os Direitos Reservados.
