# Planilha Médica Interativa
Este projeto é uma aplicação web simples e interativa para gerenciamento de registros médicos de pacientes, atuando como um sistema de fechamento mensal. Ele permite visualizar, filtrar, adicionar, editar e remover informações de pacientes, além de gerar relatórios consolidados.

## 🌟 Funcionalidades
Tabela Interativa de Pacientes: Visualize registros de pacientes com colunas para ID, Paciente, Data, Procedimento, Valor, Status e Ações.

Filtragem Dinâmica: Filtre os dados da planilha por mês, status (em aberto/fechado) e pesquise por nome do paciente em tempo real.

Adicionar Novo Paciente: Adicione facilmente novos registros à planilha.

Editar e Remover Registros: Edite as informações de um paciente existente (nome, procedimento, valor) e remova registros da lista.

Geração de Relatórios por Paciente: Gere relatórios detalhados para cada paciente, mostrando o total de procedimentos, valor total e status geral (fechado/pendente).

Visualização Detalhada: Acesse uma visualização modal com todos os procedimentos de um paciente específico.

Exportação de Relatórios: Funcionalidade simulada para exportar relatórios para o Google Docs.

## 💻 Tecnologias Utilizadas
HTML5: Estrutura da página web.

Tailwind CSS: Framework CSS para estilização rápida e responsiva, importado via CDN.

JavaScript Puro (Vanilla JS): Responsável por toda a lógica interativa da aplicação, incluindo manipulação do DOM, filtros, geração de dados e relatórios.

## 🚀 Como Usar
Para executar este projeto, siga os passos abaixo:

Salve o Código: Copie todo o código HTML fornecido e salve-o em um arquivo com a extensão .html (ex: index.html).

Abra no Navegador: Abra o arquivo index.html em qualquer navegador web moderno.

A aplicação será carregada diretamente no seu navegador, sem a necessidade de um servidor web ou configurações adicionais.

## 📖 Uso da Aplicação
Visualizar Dados: A tabela principal exibe os dados dos pacientes.

Filtrar: Use os menus suspensos "Mês" e "Status", e a caixa de busca "Nome do paciente" para filtrar os registros na tabela.

Adicionar Paciente: Clique no botão "Novo Paciente" para adicionar um novo registro pré-preenchido.

Editar Paciente: Clique no ícone de lápis ao lado de um registro para editar o nome, procedimento e valor do paciente através de prompts.

Remover Paciente: Clique no ícone de lixeira para remover um registro (requer confirmação).

Gerar Relatórios: Clique no botão "Gerar Relatórios" para exibir uma seção com cartões de resumo para cada paciente, mostrando um total de procedimentos e valores.

Detalhes do Relatório: Nos cartões de relatório, clique em "Detalhes" para ver a lista completa de procedimentos de um paciente, ou em "Relatório" para um resumo financeiro e por procedimento.

Exportar para Google Docs: Tanto o botão principal "Exportar para Google Docs" quanto o botão dentro do modal de relatório de paciente simulam a exportação dos dados.

## 💡 Possíveis Melhorias Futuras
Persistência de Dados: Atualmente, os dados são armazenados apenas na memória (let patients = [...]). Para persistência, seria necessário integrar um backend (Node.js, Python, PHP, etc.) com um banco de dados (MongoDB, PostgreSQL, MySQL).

Formulários de Edição Robustos: Substituir os prompt() para edição por modais com formulários mais amigáveis e validação de entrada.

Integração Real com Google Docs API: Implementar a exportação real de dados para documentos no Google Docs.

Seletores de Data: Adicionar um seletor de data (<input type="date">) para facilitar a inserção e edição de datas.

Geração de PDF/CSV: Opções para exportar relatórios em outros formatos, como PDF ou CSV.

Autenticação de Usuários: Para um ambiente de produção, seria essencial adicionar um sistema de autenticação.