## 📚 **Tech Challenge IV - Sistema de Blogging**

Este projeto, disponível no repositório [TECHCHALLENGEIV](https://github.com/ldmarcos/TECHCHALLENGEIV), consiste em uma **API RESTful** e um **aplicativo mobile**, desenvolvidos para gerenciar postagens, usuários (docentes e alunos) e oferecer uma experiência integrada e eficiente.

---

## 🛠️ **Tecnologias Utilizadas**

### **Backend (API)** 🖥️
- **Node.js** com **Express.js**
- **Sequelize** (ORM)
- **PostgreSQL** para persistência de dados
- **JWT** para autenticação
- **Mocha** e **Chai** para testes

### **Frontend (Mobile)** 📱
- **React Native** com **Expo**
- **Axios** para consumo da API
- **React Navigation** para navegação
- **Yup** para validação de formulários
- **Pell Rich Text Editor** para edição avançada de conteúdo

---

## 📂 **Estrutura do Projeto**

```plaintext
TECHCHALLENGEIV/
├── API/                # Back-end
│   ├── src/            # Código-fonte principal
│   │   ├── config/     # Configurações (DB, JWT)
│   │   ├── controllers/# Lógica de rotas
│   │   ├── middleware/ # Autenticação e validações
│   │   ├── models/     # Modelos do banco de dados
│   │   ├── routes/     # Rotas RESTful
│   │   └── test/       # Testes automatizados
├── mobile/             # Front-end mobile
│   ├── app/            # Navegação e telas
│   │   ├── navigation/ # Gerenciamento de rotas
│   │   ├── screens/    # Telas de postagens e usuários
│   │   └── context/    # Estado global
│   ├── assets/         # Imagens, ícones e fontes
│   ├── components/     # Componentes reutilizáveis
```

---

## 🚀 **Configuração**

### **1️⃣ Backend (API)**
1. Clone o repositório e navegue até a pasta `API`:
   ```bash
   git clone https://github.com/ldmarcos/TECHCHALLENGEIV.git
   cd TECHCHALLENGEIV/API
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure as variáveis de ambiente em um arquivo `.env`:
   ```plaintext
   DB_HOST=localhost
   DB_USER=seu-usuario
   DB_PASS=sua-senha
   DB_NAME=techchallenge
   JWT_SECRET=seu-segredo
   ```

4. Execute as migrações do banco:
   ```bash
   npx sequelize-cli db:migrate
   ```

5. Inicie o servidor:
   ```bash
   npm start
   ```

---

### **2️⃣ Frontend (Mobile)**
1. Navegue até a pasta `mobile`:
   ```bash
   cd ../mobile
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Configure as variáveis de ambiente em um arquivo `.env`:
   ```plaintext
   BASE_URL=http://localhost:3000
   ```

4. Inicie o aplicativo com o Expo:
   ```bash
   npx expo start
   ```

5. Escaneie o QR Code com o aplicativo **Expo Go** para rodar o app no celular.

---

## 🌟 **Funcionalidades**

### **API** 🖥️
- **CRUD de Postagens**: Criar, listar, atualizar e deletar.
- **Autenticação**: Login seguro com JWT.
- **Gestão de Usuários**:
  - Docentes: Cadastro e gerenciamento.
  - Alunos: Listagem e administração.

### **Mobile** 📱
- **Navegação intuitiva**: Telas de login, home, postagens e perfil.
- **Busca eficiente**: Filtragem por palavras-chave.
- **Criação/Edição de conteúdo**: Suporte a formatação avançada de texto.
- **Responsividade**: Compatível com diferentes dispositivos móveis.

---

## 📋 **Requisitos**

- **Node.js >= 14.x**
- **PostgreSQL >= 12**
- **Expo CLI**:
  ```bash
  npm install -g expo-cli
  ```

---

## ✅ **Testes**

### **API:**
- Execute os testes automatizados:
  ```bash
  npm test
  ```

### **Mobile:**
- Realize testes manuais no Expo para garantir a funcionalidade.

---

## 📌 **Dicas**
- Certifique-se de que a **API** está funcionando antes de rodar o aplicativo mobile.
- Configure corretamente o `.env` para o ambiente de produção.

✨ **Desenvolvido com dedicação para o Tech Challenge IV!** ✨

---

Caso precise de ajustes ou queira incluir algo mais, é só avisar!
