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

### Requisitos Funcionais
* Cadastro de usuário: Usufruidores podem cadastrar no sistema;
* Autenticação de login com diferentes níveis de acesso;
* Abertura de chamados: Usuários podem registrar requisições de suporte;
* Classificação inteligente: A IA analisa os chamados e, com base no histórico de chamados anteriores, sugere soluções às requisições antes de encaminhar ao suporte técnico adequado.

### Requisitos Não-Funcionais
* Banco de dados em SQL Server;
* Segurança do Sistema;
* Modularidade e Sistema integrado.

---


# Casos de Uso
[Casos de Uso]<img width="1536" height="785" alt="UseCase Diagram1" src="https://github.com/user-attachments/assets/71981944-1b43-4011-ad3c-5ea092f76702" />

O diagrama acima representa os principais fluxos do sistema NeoCall Inteligente e os diferentes papéis de usuários:

Cliente: pode autenticar-se via login, abrir chamados, editar chamados, acompanhar o andamento, e encerrar chamados quando resolvidos.

Administrador (Admin): possui permissões para encerrar chamados e gerar relatórios do sistema.

Colaborador: pode receber sugestões de soluções frequentes feitas pela IA e devolver a solução do chamado ao cliente.

---

# 🎯 Desafio do Projeto

Atualmente, empresas e usuários enfrentam dificuldades na abertura e gestão de chamados de suporte técnico. Muitas vezes, problemas de hardware e software não são classificados corretamente, causando:

- Atrasos na resolução dos chamados
- Retrabalho para a equipe de TI
- Acúmulo de chamados pendentes
- Insatisfação dos usuários

O desafio deste projeto é desenvolver um sistema de HelpDesk inteligente, que permita:

- Registrar e acompanhar chamados de forma organizada, com papéis claros para cada tipo de usuário: Cliente, Administrador (Admin), Colaborador e IA.
- Garantir níveis de acesso diferenciados para cada usuário, conforme representado no diagrama:
- Clientes podem fazer login, abrir, editar e encerrar chamados.
- Administradores têm permissões para encerrar chamados e gerar relatórios.
- Colaboradores recebem sugestões de soluções da IA e devolvem respostas aos chamados.
- Integrar uma IA que sugere soluções frequentes automaticamente, agilizando a triagem e reduzindo o tempo de atendimento, conforme mostrado no fluxo entre IA e Colaborador.

---
