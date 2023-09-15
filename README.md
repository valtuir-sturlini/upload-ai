# upload.ai

A aplicação é uma plataforma web que permite aos usuários carregar vídeos, realizar transcrições desses vídeos e gerar títulos e descrições para vídeos do YouTube com base nas transcrições. A aplicação utiliza a API GPT-3.5-turbo 16k para gerar os textos e permite ajustar a "temperatura" para controlar a criatividade da IA. Os usuários também têm a opção de adicionar novos prompts.

## Tecnologias e bibliotecas utilizadas

### API

- [Fastify](https://www.npmjs.com/package/fastify) v4.23.1
- [Prisma](https://www.npmjs.com/package/prisma) v5.3.0
- [OpenAI](https://www.npmjs.com/package/openai) v4.6.0
- [Axios](https://www.npmjs.com/package/axios) v1.5.0
- [Dotenv](https://www.npmjs.com/package/dotenv) v16.3.1
- [TypeScript](https://www.npmjs.com/package/typescript) v5.2.2

### Web

- [Radix UI](https://www.npmjs.com/package/@radix-ui) (Múltiplos pacotes agrupados sob o @radix-ui)
- [FFmpeg](https://www.npmjs.com/package/@ffmpeg/ffmpeg) v0.12.6
- [Tailwind CSS](https://www.npmjs.com/package/tailwindcss) v3.3.3
- [React](https://www.npmjs.com/package/react) v18.2.0
- [React DOM](https://www.npmjs.com/package/react-dom) v18.2.0
- [PostCSS](https://www.npmjs.com/package/postcss) v8.4.29
- [Lucide React](https://www.npmjs.com/package/lucide-react) v0.276.0
- [TypeScript](https://www.npmjs.com/package/typescript) v5.2.2
- [Vite](https://www.npmjs.com/package/vite) v4.4.9

## Instruções de Instalação e Uso

### Executando o BackEnd

No BackEnd insira a database e uma chave OpenAI no arquivo .env vazio <br>
DATABASE_URL= <br>
OPENAI_KEY=

    Navegue até o diretório do Backend no terminal:
    $ cd upload-ai-api

    Instale as dependências necessárias:
    $ npm install

    Agora você pode iniciar o servidor do Backend executando:
    $ npm run dev

### Executando o FrontEnd

    Navegue até o diretório do Frontend no terminal:
    $ cd upload-ai-web

    Instale as dependências necessárias:
    $ npm install

    Agora, você pode iniciar a aplicação do Frontend:
    $ npm start

O terminal irá exibir o endereço local onde a aplicação está sendo executada.
