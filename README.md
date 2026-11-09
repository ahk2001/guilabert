# Autoescuela Guilabert — Plataforma Web Institucional

> Landing page e portal institucional de alta conversão para a **Autoescuela Guilabert**, centro de formação vial de referência em Elche (Alicante, Espanha), com mais de 30 anos de história e certificação oficial da DGT.

---

## 🚀 Visão Geral

Projeto estático de alta performance, estruturado com foco em:
- **Design Editorial & Conversão:** Estilo moderno, grid bento, tipografia suíça contemporânea e paleta institucional (Vermelho Guilabert, Preto, Branco e tons neutros).
- **SEO & Otimização Local:** Metadados enriquecidos para busca local em Elche, marcação semântica, Open Graph, `sitemap.xml` e `robots.txt`.
- **Acessibilidade e Usabilidade:** Elementos semânticos, navegação por teclado, contraste otimizado e design 100% responsivo para todos os dispositivos móveis.
- **Segurança & Boas Práticas:** Zero dependências vulneráveis em tempo de execução, links externos com `rel="noopener noreferrer"` e deploy automatizado via GitHub Actions.

---

## 📁 Estrutura do Repositório

```text
guilabert/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Pipeline CI/CD automatizado para GitHub Pages
├── assets/                     # Mídias e imagens otimizadas para web
│   ├── alumnos-aprobados-*.png # Fotos reais de aprovação de alunos
│   ├── aula-teorica-*.png      # Imagens das instalações e salas de aula
│   ├── coche-guilabert*.jpg    # Frota de veículos homologados
│   ├── fachada-guilabert*.png  # Fachada da sede física em Elche
│   ├── favicon.png             # Favicon da marca
│   ├── home.png                # Imagem principal / Open Graph banner
│   └── logo.png                # Logotipo oficial
├── docs/                       # Documentação interna de suporte e pesquisa
│   ├── dossie_autoescola.md    # Dossiê estratégico com dados de mercado e marca
│   └── dados.txt               # Registros e canais de contato verificados
├── .gitignore                  # Regras para prevenção de lixo e dados sensíveis
├── index.html                  # Página principal de alta conversão
├── README.md                   # Documentação do projeto
├── robots.txt                  # Diretrizes para indexadores de busca
└── sitemap.xml                 # Mapa do site para indexação em buscadores
```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação orientada a acessibilidade e SEO.
- **CSS3 Moderno:** Variáveis CSS customizadas, Bento Grid, Flexbox, microinterações e suporte a modo de cor forçado.
- **JavaScript Vanilla:** Scripts leves e reativos para cálculo de orçamentos, FAQ em acordeão, rolagem suave e tracking sem sobrecarga de bibliotecas pesadas.
- **GitHub Actions & Pages:** Infraestrutura de entrega contínua (CI/CD) para deploy seguro e automático em CDN global.

---

## 🌐 Como Executar Localmente

Como o projeto é estático e puro, não necessita de etapas de compilação:

1. Clone o repositório:
   ```bash
   git clone https://github.com/ahk2001/guilabert.git
   cd guilabert
   ```

2. Abra o arquivo `index.html` diretamente em seu navegador preferido ou use um servidor local simples:
   ```bash
   # Utilizando Python 3:
   python -m http.server 8080
   # Ou utilizando o pacote serve via npx:
   npx serve .
   ```

3. Acesse em `http://localhost:8080`.

---

## 🚢 Deploy e Entrega Contínua

O repositório já conta com pipeline integrado via GitHub Actions (`.github/workflows/deploy.yml`):

1. Qualquer commit enviado para a branch `main` aciona o build e deploy para o **GitHub Pages**.
2. Para habilitar no painel do GitHub:
   - Acesse **Settings** > **Pages**
   - Em **Build and deployment > Source**, selecione **GitHub Actions**.

---

## 📞 Contato & Localização

- **Endereço:** Carrer Poeta Miguel Hernández, 27, 03201 Elche (Alicante)
- **WhatsApp Comercial:** +34 656 70 79 43
- **Instagram Oficial:** [@aeguilabert](https://www.instagram.com/aeguilabert/)
