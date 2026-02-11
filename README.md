# Projeto Peso ⚖️

Aplicação Web desenvolvida em **PHP** para gerenciamento ou cálculo de peso (desenvolvida no contexto de Sistemas de Informação). O projeto utiliza **Docker** para garantir um ambiente de desenvolvimento padronizado e fácil execução.

## 🚀 Tecnologias Utilizadas

- **PHP** (Linguagem Principal)
- **Docker** & **Docker Compose** (Containerização)
- **Apache** (Servidor Web)
- **Shell Script** (Automação de setup)
- **HTML/CSS/JS** (Interface)

## 📦 Instalação e Execução

A forma recomendada de executar este projeto é utilizando containers. Certifique-se de ter o **Docker** instalado.

### 1. Rodando com Docker

Abra o terminal na pasta raiz do projeto e execute o comando para subir os containers:

```bash
docker-compose up -d --build
```

### 2. Configuração (Opcional)

Caso seja necessário rodar configurações iniciais manuais (se o Docker não fizer automaticamente), utilize o script fornecido:

```bash
./setup.sh
```

*Após subir os containers, acesse a aplicação no navegador: http://localhost:80 (ou a porta definida no docker-compose)*

---

### 📂 Estrutura do Projeto

- `public/` e `app/`: Diretórios principais do código fonte PHP.
- `Dockerfile`: Definição da imagem do ambiente.
- `docker-compose.yml`: Orquestração dos serviços.
- `000-default.conf` / `.htaccess`: Configurações do servidor Apache.
- `setup.php` / `setup.sh`: Scripts de inicialização e configuração.

---
Desenvolvido por **[Samuel Junqueira](https://github.com/samueljunqueiraa)**
