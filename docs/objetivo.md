\# 👤 Épico 1: Administrar o Usuário



Documentação das histórias de usuário e critérios de aceite para o módulo de gestão e autenticação de usuários.



\---



\## 📝 1. Criar Conta

> \*\*Descrição:\*\* O cliente cria um usuário para poder acessar as funcionalidades do aplicativo.



\* ✅ \*\*Caminho Feliz:\*\* Usuário criado com sucesso e redirecionado para o sistema.

\* ❌ \*\*Caminho Triste:\*\* Falha na criação da conta pois já existe um usuário cadastrado com o e-mail informado.



\---



\## 🔐 2. Tela de Login

> \*\*Descrição:\*\* O usuário deseja acessar a conta previamente criada no aplicativo.



\* ✅ \*\*Caminho Feliz:\*\* Login validado e realizado com sucesso, concedendo acesso ao aplicativo.

\* ❌ \*\*Caminho Triste:\*\* Falha no acesso, pois o usuário esqueceu a senha ou inseriu credenciais inválidas.



\---



\## 🔄 3. Tela de Recuperação de Senha

> \*\*Descrição:\*\* O usuário perdeu a senha da sua conta e deseja recuperá-la solicitando o envio de um código de recuperação para o seu e-mail.



\* ✅ \*\*Caminho Feliz:\*\* Código enviado para o e-mail com sucesso e o usuário consegue redefinir a sua senha.

\* ❌ \*\*Caminho Triste:\*\* O usuário não tem mais acesso ao e-mail cadastrado, impossibilitando a recuperação e causando a perda da conta.



\---



\## 🌐 4. Autenticação Social (OAuth) e Atualizar Usuário

> \*\*Descrição:\*\* O usuário deseja poder entrar no aplicativo de forma rápida usando sua conta do Google ou do Facebook.



\* ✅ \*\*Caminho Feliz:\*\* Integração concluída com sucesso, permitindo o acesso instantâneo com a conta social escolhida.

\* ❌ \*\*Caminho Triste:\*\* O usuário não lembra a senha da sua própria conta do Facebook ou do Google na hora da autorização, impedindo o login no aplicativo.

