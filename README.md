# Passo a passo para execução:

### Para executar o front-end

#### 1- Entrar na pasta upload-ai-web

#### 2- Executar o comando para instalar as libs

```pnpm i```

#### 3- Executar o comando para iniciar o projeto

```pnpm run dev```

### Para executar o back-end

#### 1- Entrar na pasta upload-ai-api

#### 2- Executar o comando para instalar as libs

```pnpm i```

#### 3- Executar o comando para iniciar o prisma

```pnpm prisma init --datasource-provider sqlite```

#### 4- Executar o comando para criar as tables

```pnpm prisma migrate dev```

#### 5- Executar o comando para iniciar o back-end

```pnpm run dev```