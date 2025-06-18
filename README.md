# PyCofre
Aplicação python de controle financeiro

PYCofre
Sistema de controle financeiro simples feito em Python com interface gráfica usando CustomTkinter, armazenamento de dados em Excel e gráficos gerados com Matplotlib.

Sobre
O PYCofre é um aplicativo desktop que permite cadastrar usuários, registrar entradas e despesas mensais, definir metas financeiras, salvar tudo em arquivos Excel e visualizar gráficos para análise financeira.

Funcionalidades
Cadastro e login de usuários (dados salvos em usuarios.xlsx)

Registro de entradas e despesas por mês

Definição de metas financeiras mensais (salvas em metas.xlsx)

Salvamento e carregamento automático de dados financeiros em arquivo_valores.xlsx

Visualização de gráficos de entradas x despesas e percentual de gastos por mês

Interface intuitiva e moderna com CustomTkinter

Tecnologias
Python 3.x

pandas

openpyxl

matplotlib

customtkinter

Como usar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
Instale as dependências:

bash
Copiar
Editar
pip install pandas openpyxl matplotlib customtkinter
Execute o script principal:

bash
Copiar
Editar
python seu_arquivo.py
Na interface, cadastre um usuário, faça login, adicione entradas e despesas, defina metas e visualize gráficos.

Estrutura de arquivos
usuarios.xlsx: armazena os usuários cadastrados (nome e senha)

arquivo_valores.xlsx: armazena entradas, despesas e saldo mensal

metas.xlsx: armazena metas financeiras definidas por mês

Próximos passos / melhorias
Implementar criptografia de senhas

Validar entrada de dados com mais rigor

Adicionar funcionalidade de exportar relatórios em PDF

Melhorar o design da interface

Licença
MIT License — sinta-se livre para usar e modificar!
