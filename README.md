# Projeto de API utilizando FastAPI para Gerenciamento de Centro de Treinamento, Atleta e Categoria

## Visão Geral

Este projeto consiste no desenvolvimento de uma API utilizando o framework FastAPI em Python para gerenciar um centro de treinamento esportivo. A API permitirá o cadastro, consulta, atualização e exclusão de informações relacionadas a atletas, categorias esportivas e dados do centro de treinamento.

## Funcionalidades da API

1. **Atleta**:
   - Listar todos os atletas cadastrados.
   - Criar um novo atleta.
   - Visualizar detalhes de um atleta específico.
   - Atualizar informações de um atleta existente.
   - Excluir um atleta.

2. **Categoria**:
   - Listar todas as categorias esportivas cadastradas.
   - Criar uma nova categoria esportiva.
   - Visualizar detalhes de uma categoria específica.
   - Atualizar informações de uma categoria existente.
   - Excluir uma categoria.

3. **Centro de Treinamento**:
   - Visualizar informações sobre o centro de treinamento.
   - Atualizar informações do centro de treinamento, como endereço, horários de funcionamento, etc.

## Tecnologias Utilizadas

- **FastAPI**: Framework web rápido para construir APIs em Python.
- **Python**: Linguagem de programação principal.
- **Pydantic**: Utilizado para validação de dados.
- **SQLAlchemy**: Biblioteca para interação com banco de dados SQL.
- **SQLite**: Banco de dados escolhido para armazenar as informações.


## Fluxo de Desenvolvimento

1. **Configuração do Ambiente**: Instalação do FastAPI e outras dependências necessárias.
2. **Definição dos Modelos**: Criar os modelos de dados para atleta, categoria e centro de treinamento.
3. **Configuração do Banco de Dados**: Configurar a conexão com o banco de dados.
4. **Implementação das Rotas**: Definir as rotas da API para cada uma das funcionalidades.
5. **Validação de Dados**: Implementar a validação de dados utilizando Pydantic.
6. **Testes Unitários**: Escrever testes unitários para garantir o funcionamento correto da API.

## Conclusão

Este projeto oferece uma oportunidade para aplicar os conceitos aprendidos sobre desenvolvimento de APIs utilizando o FastAPI em um contexto prático e relevante. Ao final do desenvolvimento, teremos uma API robusta e bem documentada, pronta para ser utilizada no gerenciamento de um centro de treinamento esportivo.
