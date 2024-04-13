# Web Crawler

## Descrição
O **Web Crawler** é uma aplicação que permite extrair dados de páginas da web de forma automatizada. Utilizando a técnica de web scraping, essa ferramenta é capaz de navegar por diferentes URLs, coletar informações específicas e organizá-las para análise posterior.

## Funcionalidades
1. **Upload de Arquivo JSON:**
   - Os usuários podem fazer upload de um arquivo JSON contendo uma lista de URLs a serem analisadas.

2. **Extração de Dados:**
   - O sistema utiliza o Puppeteer, uma ferramenta de automação de navegador, para acessar as páginas e extrair os dados desejados.

3. **Compilação e Download:**
   - Após a extração dos dados de cada URL, o sistema compila as informações em arquivos JSON individuais.
   - Esses arquivos são então compactados em um arquivo ZIP, facilitando o download e compartilhamento dos resultados.

## Tecnologias Utilizadas
- **Node.js:** Ambiente de execução JavaScript do lado do servidor.
- **Express.js:** Framework web para Node.js que simplifica a criação de aplicativos web.
- **Puppeteer:** Biblioteca Node.js que fornece uma API de alto nível para controle programático do Chrome ou Chromium.
- **Multer:** Middleware para manipulação de arquivos de formulário em Node.js.
- **Archiver:** Módulo para criação e manipulação de arquivos ZIP em Node.js.
- **Body-parser:** Middleware que analisa os corpos das requisições HTTP em Node.js.
- **fs (File System):** Módulo nativo do Node.js para interação com o sistema de arquivos.

## Instalação e Execução
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seuusuario/web-crawler.git


2. **Instale as dependências:**
 - Navegue até o diretório da aplicação e execute o seguinte comando para instalar as dependências necessárias:
 - cd web-crawler
 - npm install

3. **Inicie o servidor:**
 - Execute o seguinte comando para iniciar o servidor Node.js:
 - npm start

4. **Acesse a aplicação no navegador:**
 - Abra o seu navegador web e acesse o seguinte endereço:
 - http://localhost:3334

## Como Utilizar a Aplicação

4. **Upload do Arquivo JSON:**
 - Selecione um arquivo JSON contendo uma lista de URLs.
 - Clique no botão "Iniciar" para iniciar o processo de extração de dados.

5. **Acompanhamento do Progresso::**
 - Durante o processamento, uma mensagem de "Carregando..." será exibida.
 - Aguarde até que o download do arquivo ZIP seja iniciado automaticamente.

6. **Download dos Dados:**

 - Após a conclusão, um arquivo ZIP contendo os dados extraídos estará disponível para download.

## Contribuindo 
 - Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests com melhorias.