# Monitor do Dólar

Uma aplicação web em tempo real para acompanhar a cotação do dólar (USD/BRL) com atualizações automáticas a cada 30 segundos.

## Funcionalidades

- Exibição do valor atual do dólar
- Atualização automática a cada 30 segundos
- Indicador visual de alta/baixa
- Valores máximo e mínimo do dia
- Tema claro/escuro
- Design responsivo
- Interface limpa e moderna

## Tecnologias Utilizadas

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS
- Axios
- React Icons

## Pré-requisitos

- Node.js 18.0.0 ou superior
- npm ou yarn

## Instalação

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITÓRIO]
cd dolar-monitor
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## Deploy

Este projeto está configurado para deploy na Vercel. Para fazer o deploy:

1. Crie uma conta na [Vercel](https://vercel.com)
2. Conecte seu repositório
3. Clique em "Deploy"

## API Utilizada

Este projeto utiliza a API pública da [AwesomeAPI](https://docs.awesomeapi.com.br/api-de-moedas) para obter as cotações do dólar em tempo real.

## Licença

MIT 