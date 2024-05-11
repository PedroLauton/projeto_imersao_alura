# Assistente Virtual com Google Gemini e Armazenamento de Conversas

Este programa em Python implementa um assistente virtual que utiliza o modelo de linguagem Google Gemini para processar comandos e gerar respostas. Adicionalmente, ele oferece a capacidade de armazenar, recuperar e interagir com conversas anteriores.

## Funcionalidades

- **Iniciar Conversas:** Interaja com o modelo de linguagem Google Gemini através da inserção de comandos e receba respostas elaboradas.
- **Armazenar Conversas:** Guarde as perguntas e respostas geradas durante a interação para consultas posteriores.
- **Recuperar Conversas:** Acesse um histórico de conversas realizadas, selecione uma conversa específica e visualize seu conteúdo, incluindo perguntas, respostas e histórico de interação.

## Instruções de Uso

1. **Instalação de Dependências:** Assegure-se de ter a biblioteca `google-generativeai` instalada em seu ambiente Python. Utilize o comando `pip install google-generativeai` para instalar a biblioteca.

2. **Configuração da Chave de API:** Substitua a string `"SUA_API_KEY"` no código pela sua chave de API do Google Gemini. Essa chave é necessária para autenticar e utilizar o modelo de linguagem.

3. **Execução do Programa:** Inicie o programa executando o script Python. Um menu de opções será exibido, apresentando as seguintes funcionalidades:

   - Iniciar uma nova conversa.
   - Consultar conversas armazenadas.
   - Finalizar o programa.

4. **Interação com o Assistente:** Siga as instruções apresentadas na tela para inserir comandos, armazenar conversas e visualizar conversas anteriores.

## Detalhes Técnicos

- **Armazenamento de Conversas:** As conversas são armazenadas em uma lista denominada `pesquisas_salvas`. Cada elemento da lista representa uma conversa e contém a pergunta, a resposta e o histórico de interações.

- **Modelo de Linguagem Google Gemini:** O programa utiliza o modelo de linguagem Google Gemini para processar os comandos inseridos pelo usuário e gerar as respostas correspondentes.

- **Menu Interativo:** Um menu intuitivo é apresentado ao usuário, facilitando a navegação pelas funcionalidades do programa.

- **Histórico de Interações:** A funcionalidade de consultar conversas armazenadas também exibe o histórico de perguntas e respostas associadas a cada conversa.
