# ChatGPT Node.js

Este é um projeto de exemplo que demonstra como criar uma aplicação web simples usando Node.js, Express e a API do ChatGPT da OpenAI. A aplicação permite que os usuários insiram mensagens e recebam respostas geradas pelo ChatGPT.

## Configuração

1. Clone este repositório:

   ```bash
   git clone https://github.com/lkazumi/openai-nodejs.git
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API do OpenAI da seguinte forma:

   ```
   OPENAI_API_KEY=SuaChaveDeAPIAqui
   ```

4. Inicie o servidor:

   ```bash
   npm start
   ```

5. Abra seu navegador e acesse `http://localhost:3000` para interagir com a aplicação.

## Uso

Após seguir as etapas de configuração, você poderá inserir mensagens na interface web e obter respostas geradas pelo ChatGPT. A aplicação utiliza a biblioteca Express para gerenciar as solicitações HTTP e a biblioteca OpenAI para se conectar à API do ChatGPT.

## Contribuição

Este é um projeto de exemplo, mas sinta-se à vontade para fazer melhorias, adicionar recursos adicionais e enviar pull requests. Ficaremos felizes com sua contribuição!

## Avisos

Este projeto utiliza a biblioteca `dotenv` para gerenciar as variáveis de ambiente, e é importante manter suas informações de chave de API privadas. Certifique-se de não compartilhar sua chave de API em repositórios públicos.
