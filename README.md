# 🌌 SkyAPI – Documentação

Documentação oficial das rotas disponíveis na **SkyAPI**.

---

## 🔐 Autenticação

Todas as requisições exigem uma chave de API enviada via query parameter:

---

# 📡 Rotas Disponíveis

## 🏝️ 1. Dados da Ilha

Retorna todas as informações relacionadas à ilha do jogador.

### Endpoint

### Parâmetros

| Parâmetro | Tipo   | Obrigatório | Descrição |
|------------|--------|-------------|------------|
| `id`       | string | Sim         | ID único da ilha (armazenado em `island_redirect` no perfil do jogador) |
| `key`      | string | Sim         | Chave de autenticação da API |

### Exemplo de Requisição

---

## 👤 2. Dados do Perfil do Jogador

Retorna informações gerais do perfil do jogador.

### Endpoint
### Parâmetros

| Parâmetro | Tipo   | Obrigatório | Descrição |
|------------|--------|-------------|------------|
| `key`      | string | Sim         | Chave de autenticação da API |

### Exemplo de Requisição

---

## 🎒 3. Inventários do Perfil

Retorna os dados de inventário vinculados ao perfil do jogador.

### Endpoint
### Parâmetros

| Parâmetro | Tipo   | Obrigatório | Descrição |
|------------|--------|-------------|------------|
| `key`      | string | Sim         | Chave de autenticação da API |

### Exemplo de Requisição

---

# 📌 Observações

- Todas as rotas utilizam o método `GET`.
- Todas as respostas são retornadas em formato `JSON`.
- Caso a chave seja inválida ou ausente, a requisição será negada.
- Certifique-se de proteger sua chave de API.

---

# 🛠️ Base URL

---

# 📄 Licença

Uso interno ou conforme termos definidos pelo desenvolvedor.
