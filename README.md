# 🎮 LH Games - Codificação Front-End

Este projeto consiste na criação e estilização das páginas **Home** e **Login** para um e-commerce de jogos (*LH Games*), desenvolvido durante o curso de Front-End.

---

## 📸 Demonstração das Páginas

### 🏠 Home Page
- **Header/Navbar**: Logo interativa, links de navegação (`Promoções`, `Console`, `Jogos`) e barra de busca funcional em layout.
- **Banner Carrossel**: Destaques de produtos em rotação automática usando Bootstrap Carousel.
- **Seção "Os Mais Vendidos"**: Grid responsivo com cards de jogos contendo imagem, descrição, preço e botão de compra.

### 🔐 Login e Cadastro
- **Formulário de Login**: Campo para usuário e senha com validação em JavaScript.
- **Formulário de Cadastro**: Transição suave via jQuery (`slideToggle`) entre a tela de login e o formulário de novo cadastro.
- **Navegação**: Botão fixo "Voltar ao topo" com rolagem suave.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica da aplicação.
- **CSS3**: Estilização personalizada, ajustando layout e responsividade.
- **Bootstrap 5.2**: Framework para componentes responsivos (Navbar, Carousel, Cards e formulários).
- **JavaScript (Vanilla)**: Lógica de controle de acesso/login, navegação e alertas.
- **jQuery**: Manipulação do DOM e efeitos de transição entre formulários (`slideToggle`).

---

## 🔑 Credenciais de Teste (Login)

Para testar o login na aplicação, utilize os seguintes dados:

- **Usuário:** `admin`
- **Senha:** `123456`

---

## 📂 Estrutura do Projeto

```text
atividadeCFE/
├── css/
│   └── estilo.css      # Regras de estilo personalizadas
├── img/                # Logotipos, banners e imagens dos jogos
├── js/
│   ├── script.js       # Funções JavaScript (login, cadastro, scroll)
│   └── jquery-script.js# Animações e efeitos com jQuery
├── index.html          # Página principal (Home)
└── login.html          # Página de Login e Cadastro
