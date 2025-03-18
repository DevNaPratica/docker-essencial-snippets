# Docker Essencial - Snippets e Modelos

Bem-vindo ao repositório **Docker Essencial - Snippets e Modelos**! 
Aqui você encontrará exemplos práticos e arquivos de configuração para auxiliar no aprendizado e uso eficiente do Docker, seguindo os conteúdos do ebook **Docker Essencial: Fundamentos e Práticas para Todos os Níveis**.

## O que você encontrará neste repositório?

- **Comandos básicos do Docker** 
- **Scripts para facilitar a execução de containers** 
- **Exemplos de `docker-compose.yml` para aplicações reais** 
- **Snippets reutilizáveis para acelerar sua produtividade** 
- **Exercícios práticos para fixação do conhecimento** 

## 📂 Estrutura do Repositório

```
├── 01-verificacao-instalacao/
│   ├── hello-world.sh
├── 02-gerenciamento-containers/
│   ├── listar-containers.sh
│   ├── iniciar-container.sh
│   ├── parar-container.sh
│   ├── remover-container.sh
├── 03-servidor-nginx/
│   ├── rodar-nginx.sh
│   ├── rodar-nginx-mapeando-porta.sh
│   ├── rodar-nginx-em-background.sh
├── 04-manutencao/
│   ├── remover-container-forcado.sh
│   ├── limpar-imagens-nao-utilizadas.sh
├── docker-compose-exemplos/
│   ├── nginx-compose.yml
│   ├── postgres-compose.yml
│   ├── nodejs-compose.yml
└── README.md
```

## Como Utilizar

### 1. Verificação da Instalação do Docker
Para testar se o Docker está instalado corretamente, execute:
```sh
bash 01-verificacao-instalacao/hello-world.sh
```
Se o Docker estiver funcionando, você verá uma mensagem de boas-vindas.

### 2. Gerenciamento de Containers
- **Listar containers ativos:**
  ```sh
  bash 02-gerenciamento-containers/listar-containers.sh
  ```
- **Parar um container:**
  ```sh
  bash 02-gerenciamento-containers/parar-container.sh <container_id>
  ```
- **Remover um container:**
  ```sh
  bash 02-gerenciamento-containers/remover-container.sh <container_id>
  ```

### 3. Executando o Servidor Nginx
- **Rodar o Nginx na porta padrão:**
  ```sh
  bash 03-servidor-nginx/rodar-nginx.sh
  ```
- **Rodar Nginx mapeando uma porta personalizada:**
  ```sh
  bash 03-servidor-nginx/rodar-nginx-mapeando-porta.sh
  ```

### 4. Exemplos de `docker-compose.yml`
#### Subindo um servidor Nginx com `docker-compose`
```sh
cd docker-compose-exemplos/
docker-compose -f nginx-compose.yml up -d
```
#### Subindo PostgreSQL com `docker-compose`
```sh
cd docker-compose-exemplos/
docker-compose -f postgres-compose.yml up -d
```

## Contribuição
Contribuições são bem-vindas! Se você quiser adicionar novos exemplos ou corrigir algo, fique à vontade para abrir um Pull Request.

## Compartilhe e Aprenda Junto
Gostou do repositório? 🌟 Então dê um **star** e compartilhe com seus amigos e colegas que estão aprendendo Docker!

**Acompanhe o ebook e pratique com esses exemplos!**

---

📌 **Autor:** Dev Na Prática  
📧 **Contato:** devnapraticasuporte@gmail.com  
📢 **Siga-me para mais conteúdos sobre Docker e DevOps!** (@devnapratica no instagram)

