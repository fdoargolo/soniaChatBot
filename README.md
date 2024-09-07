# Sônia ChatBot

# Descrição

Sônia (Sônia – Sistema de Orientação e Navegação para a Inclusão e Apoio). Fornece informações precisas e rápidas sobre os serviços de atendimento à mulher em Pernambuco, com foco em segurança, direitos, e suporte em situações de violência.

# Requisitos

- [Node.js](https://nodejs.org/) (v14 ou superior)
- [npm](https://www.npmjs.com/) (v6 ou superior)

# Instalação

1. **Instale as dependências**:
   Execute o comando abaixo no diretório raiz do projeto para instalar todas as dependências listadas no `package.json`:

   ```bash
   npm install
   ```

2. **Crie o arquivo `.env`**:
   O projeto utiliza variáveis de ambiente para armazenar chaves e outras informações sensíveis. Crie um arquivo `.env` na raiz do projeto e adicione a sua chave de API da seguinte forma:

   ```bash
   API_KEY="Sua chave de API aqui"
   ```

   Certifique-se de substituir `"Sua chave de API aqui"` pela chave correta que você obteve do serviço de API correspondente.

3. **Inicie o servidor**:
   Depois de configurar o arquivo `.env`, você pode iniciar o servidor localmente com o comando:
   ```bash
   npm start
   ```
   Isso iniciará a aplicação em modo de desenvolvimento. Acesse o chatbot no navegador através de `http://localhost:3000`.

# Uso

Uma vez que o servidor esteja rodando, a interface do chatbot estará disponível. Você verá um botão de chat na parte inferior da tela, ao clicar nele, a assistente virtual "Cora" será exibido. A partir daí, você pode digitar suas perguntas e receber respostas automatizadas.

# Exemplos de perguntas que você pode fazer ao bot:

Pergunta: Quais são os telefones de emergência para mulheres em Pernambuco?       
Resposta: Para emergências ligue 190 (Polícia Militar)

## Estrutura do Projeto

- **/public/**: Contém arquivos estáticos como imagens, ícones e estilos, incluindo o front-end e a lógica do chatbot.
- **/server.js**: Configuração do servidor que lida com as requisições do chatbot e conecta com a API.
# soniaChatBot
# soniaChatBot
