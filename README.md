# Portal Acadêmico UFSM

Dashboard acadêmico responsivo desenvolvido com React, Vite e Tailwind CSS.

## Pré-requisitos

- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- Git (para clonar o repositório)

## Como executar o projeto

Clone o repositório e entre na pasta do projeto:

```bash
git clone https://github.com/deividtrindade777/Rebranding-Portal-UFSM.git
cd Rebranding-Portal-UFSM
```

Instale as dependências:

```bash
npm install
```

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

Abra o endereço mostrado no terminal, normalmente `http://localhost:5173`.

### Windows PowerShell: erro de execução de scripts

Se o PowerShell bloquear o comando `npm`, use:

```powershell
npm.cmd run dev
```

Como alternativa permanente para o usuário atual, execute uma vez:

```powershell
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Feche e abra o terminal novamente após alterar essa configuração.

## Build de produção

Para gerar os arquivos prontos para hospedagem:

```bash
npm run build
```

O resultado será criado na pasta `dist/`. Essa pasta não deve ser enviada ao Git; plataformas como Vercel e Netlify executam esse build automaticamente.

## Arquivos que não devem subir ao GitHub

O `.gitignore` mantém arquivos locais fora do repositório, incluindo `node_modules/`, `dist/`, arquivos `.env` e logs.
