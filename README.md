# NeoCAll
# 📌 neo call 

## 👤 Dev do Projeto

| Nome do Aluno        | RA       | Turma   |
|-----------------------|----------|---------|
| Igor Oliveira Marcondes | R080CD5 | DS4R48  |

## Status do Projeto 📊

## 📌 Status do Projeto

| Projeto          | Status        |
|------------------|---------------|
| Sistema NeoCall | 🟡 Em andamento |

# Requisitos Levantados 📝

[Requisitos](./RequisitosSist.md) 

---

# Casos de Uso
[Diagrama](./caso%20de%20uso.png)

---

# 🎯 Desafio do Projeto

[Desafio](./DesafiodoprojetoSist.md)

---

# 📋 Backlog do Produto

[Sprints](./BacklogdoProduto.md)


 ## 📅 Cronograma de Evolucão do Projeto
 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/6dd3da98-a29e-466c-aa5d-81014fdf8639" />
 
 Tabela das Sprints - Sistema NeoCAll Inteligente (Baseado no Diagrama)
Sprint	Período (2025)	Objetivos	Entregas	Documentação
Sprint 1 — Infraestrutura e Segurança	10/02 – 23/02	Configuração do ambiente, banco de dados, arquitetura modular e segurança inicial (login e verificação de conta)	Ambiente dev configurado, SQL Server, arquitetura com papéis Cliente, Admin, Colaborador e IA, criptografia e login com verificação de conta	
Sprint 2 — Cadastro e Autenticação	24/02 – 09/03	Cadastro de usuários e autenticação com níveis de acesso diferenciados para Cliente, Admin e Colaborador	CRUD de usuários, login/logout com níveis de acesso, testes iniciais	
Sprint 3 — Gestão de Chamados (Cliente/Admin)	10/03 – 23/03	Funcionalidades para Cliente abrir, editar e encerrar chamados; Admin encerrar chamados e gerar relatórios	Formulário de abertura e edição de chamados, funcionalidades de encerramento e geração de relatórios para Admin	
Sprint 4 — Sugestões Inteligentes via IA	24/03 – 06/04	Treinamento da IA para sugerir soluções frequentes; implementação da interação Colaborador-IA	Modelo treinado, sistema de sugestões frequentes para Colaboradores, testes do fluxo de soluções	
Sprint 5 — Finalizações e Segurança Avançada	07/04 – 20/04	Refinamento da segurança, ajustes na arquitetura e modularidade, testes finais e documentação	Melhorias em segurança, ajustes na arquitetura, testes finais, documentação completa	
Entrega Final	24/05	Entrega da versão 1.0 com todas funcionalidades integradas	Sistema completo, documentação e apresentação final


  ---
  
## 🛠️ Tecnologias Utilizadas
- *Linguagem:* C#  
- *Frameworks:* ASP.NET Core, Entity Framework  
- *Banco de Dados:* SQL Server  
- *Ferramentas de Apoio:* Figma (prototipagem) e Astah (modelagem de diagramas)

---
## 🖥️ Como Utilizar

O *NeoCall Inteligente* permite:  
- *Usuário:* criar conta, abrir chamados, acompanhar e encerrar chamados.  
- *Técnico:* visualizar, classificar, atualizar e fechar chamados.  
- *Administrador:* gerenciar usuários, permissões e acompanhar métricas.  

---

## 🚀 Como Executar Localmente

```bash
# clone o repositório
git clone https://github.com/seu-repo.git
cd helpdesk-inteligente

# restaure pacotes e crie o banco
dotnet restore
dotnet ef database update

# rode o projeto
dotnet run


  
