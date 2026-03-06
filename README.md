# 📱 Catálogo Interativo Mobile

Aplicativo mobile desenvolvido com **React Native (Expo)** como entrega da disciplina de **Mobile Development** da UNIFECAF.

O app apresenta um catálogo de produtos dividido por categorias masculinas e femininas, consumindo dados em tempo real da API [DummyJSON](https://dummyjson.com).

---

## 🚀 Funcionalidades

- **Tela de Login** com validação de e-mail e senha
- **Listagem de Produtos** separada por abas (Masculino / Feminino)
- **Subcategorias** navegáveis dentro de cada aba
- **Tela de Detalhes** com nome, imagem, descrição, preço, desconto, avaliação, estoque e marca
- **Logout** funcional com retorno à tela de login

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Finalidade |
|---|---|---|
| React Native | SDK 52 | Framework mobile |
| Expo | Latest | Ambiente de desenvolvimento |
| Axios | ^1.4.0 | Requisições HTTP |
| React Navigation | ^6.0.0 | Navegação entre telas |
| DummyJSON API | — | Fonte de dados dos produtos |

---

## 📦 Como Executar

### Pré-requisitos

- Node.js instalado
- Expo Go instalado no celular ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) / [iOS](https://apps.apple.com/app/expo-go/id982107779))

### Opção 1 — Expo Snack (recomendado)

Acesse diretamente pelo navegador:  
👉 [https://snack.expo.dev](https://snack.expo.dev)

Cole o conteúdo do arquivo `App.js` e escaneie o QR Code com o Expo Go.

### Opção 2 — Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/meu-catalogo.git
cd meu-catalogo

# Instale as dependências
npm install --legacy-peer-deps

# Inicie o projeto
npx expo start --tunnel
```

Escaneie o QR Code com o **Expo Go** no celular.

---

## 📂 Estrutura do Projeto

```
meu-catalogo/
├── src/
│   ├── screens/
│   │   ├── LoginScreen.js       # Tela de login
│   │   ├── ProductListScreen.js # Listagem com abas
│   │   └── ProductDetailScreen.js # Detalhes do produto
│   ├── components/              # Componentes reutilizáveis
│   ├── services/
│   │   └── api.js               # Instância do Axios
│   └── store/                   # Configuração Redux (opcional)
├── App.js                       # Navegação principal
├── package.json
└── README.md
```

---

## 🌐 API Utilizada

**DummyJSON** — https://dummyjson.com

| Endpoint | Descrição |
|---|---|
| `/products/category/mens-shirts` | Camisas masculinas |
| `/products/category/mens-shoes` | Sapatos masculinos |
| `/products/category/mens-watches` | Relógios masculinos |
| `/products/category/womens-bags` | Bolsas femininas |
| `/products/category/womens-dresses` | Vestidos femininos |
| `/products/category/womens-shoes` | Sapatos femininos |
| `/products/{id}` | Detalhes de um produto |

---

## 📸 Screenshots

| Login | Produtos Masculinos |
|---|---|
| ![Login](./screenshots/login.png) | ![Masculino](./screenshots/masculino.png) |

| Produtos Femininos | Detalhes |
|---|---|
| ![Feminino](./screenshots/feminino.png) | ![Detalhes](./screenshots/detalhes.png) |

---

## 👨‍💻 Autor

**Fabio Augusto Geraldini Santos**  
RA: 102190  
Curso: Análise e Desenvolvimento de Sistemas  
Instituição: UNIFECAF  
Disciplina: Mobile Development  
Fevereiro de 2026
