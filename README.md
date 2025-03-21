# 📌 Projeto de Hackathon - Gerenciamento de Vacinação Familiar

## 📋 Visão Geral
Este projeto foi desenvolvido durante o **Hackathon 1000Devs 2025** e tem como objetivo criar um software para **gerenciamento da vacinação de uma família**. A plataforma permite a visualização do calendário vacinal por idade recomendada e o registro de vacinas aplicadas a cada integrante da família.

🌐 **Acesse o site do projeto:** [Vacinas](https://vacinas.adeweb.com.br/index.html)

## 🎯 Objetivos do Projeto
- Facilitar o controle e registro das vacinas aplicadas aos integrantes de uma família.
- Disponibilizar um calendário vacinal baseado na idade recomendada para aplicação.
- Garantir acesso a informações detalhadas sobre imunizações e histórico vacinal.
- Permitir a consulta e gerenciamento dos registros via APIs Restful.
- Utilizar um banco de dados para persistência das informações.

## 🏗️ Tecnologias Utilizadas
- **Backend**: Java com Spark Web Framework
- **Banco de Dados**: MySQL
- **Autenticação**: JWT
- **Ferramentas Adicionais**: Thunder Client para testes de API

## 📌 Funcionalidades Principais
✅ Cadastro de pacientes e seus respectivos registros vacinais.
✅ Visualização de vacinas recomendadas por faixa etária.
✅ Registro de aplicações de vacinas com informações como lote, local de aplicação e profissional responsável.
✅ APIs para inserção, atualização, exclusão e consulta de pacientes e imunizações.
✅ Geração de estatísticas sobre imunizações pendentes e vacinas aplicadas.

## 🔧 Como Executar o Projeto
### 1️⃣ Clonar o repositório:
```bash
  git clone https://github.com/seu-usuario/hackathon-vacinas.git
  cd hackathon-vacinas
```

### 2️⃣ Instalar dependências:
```bash
  mvn clean install  # Para projetos Java com Maven
```

### 3️⃣ Configurar banco de dados:
Criar um banco MySQL e configurar as credenciais no arquivo `application.properties`.

### 4️⃣ Executar o projeto:
```bash
  mvn spring-boot:run  # Se for um projeto Spring Boot
```

## 📈 Roadmap Futuro
🚀 Implementação de uma interface web para melhor experiência do usuário.
🚀 Integração com APIs de órgãos de saúde para validação de informações.
🚀 Implementação de notificações automáticas para vacinas em atraso.
🚀 Melhorias no sistema de estatísticas e relatórios.

## 🛠️ Equipe do Projeto
- **Adevalter**
- **Marcos Vinicius**
- **Arthur Ramalho**
- **Fashion**
- **João Vitor**
- **Bianca Costa**
- **Khauan Luiz**

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir **Issues** e **Pull Requests**.

## 📜 Licença
Este projeto está sob a licença MIT - veja o arquivo **LICENSE** para mais detalhes.

---
💡 **"Tecnologia a serviço da saúde e prevenção"** 🚀
