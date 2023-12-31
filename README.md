# Teste de Front-End

Este projeto consiste em duas páginas web:

* **Page pacientes:** Exibe uma lista de pacientes e permite que o usuário execute ações como adicionar, editar e excluir pacientes.
* **Modal informações básicas:** Cria um formulário para coletar os dados de um paciente.

## Page pacientes

### Componentes principais

* **Tabela:** Apresenta os dados dos pacientes em formato tabular, incluindo nome, CPF, data de nascimento, e-mail, cidade e ações.
* **Formulário de pesquisa:** Permite que o usuário pesquise pacientes por nome.
* **Botão para adicionar paciente:** Redireciona para uma página de cadastro de novos pacientes.
* **Botões de ações:** Oferece opções para editar e excluir pacientes, utilizando dropdowns.

### Observações importantes

* As funções de excluir, adicionar ou editar pacientes não estão implementadas nesse código.

## Modal informações básicas

### Componentes principais

* **Formulário:** Define um formulário com o método POST e a ação "enviar-dados.php".
* **Fieldset:** Agrupa os campos de dados pessoais.
* **Labels:** Fornecem rótulos para cada campo de entrada.
* **Inputs:** Campos de texto para digitar o nome, apelido, nacionalidade, data de nascimento, CPF, RG e observações adicionais.
* **Selects:** Listas suspensas para selecionar gênero e estado civil.
* **Botão Continuar:** Redireciona o usuário para a página "contato.html" sem enviar os dados do formulário.

### Observações importantes

* Os arquivos utilizam CSS inline.
* O código atual não possui tratamento de erros ou validação de dados.
* Este é um projeto que, em retrospecto, é um pouco ambicioso para uma iniciante, no entanto estou feliz com meu progresso, embora não esteja nem perto do resultado final que eu espero.

## Desenvolvido por

* [Mell Santos de Campos](https://github.com/mellsantos)

