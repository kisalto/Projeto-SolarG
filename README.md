# **Projeto SolarG**

## **Sumário**
- [Descrição Geral](#descrição-geral)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Funcionamento](#funcionamento)
- [Configuração](#configuração)
- [Execução](#execução)

---

## **Descrição Geral**
Este projeto é um sistema de CRM front-end para uma empresa de venda de painéis solares, desenvolvido como trabalho de faculdade. Ele oferece páginas para login, cadastro e gestão de agenda, contatos, processos, receitas, despesas e financeiro.

---

## **Tecnologias Utilizadas**
- **HTML**: estrutura das páginas
- **CSS**: estilos visuais e layout
- **JavaScript**: lógica de interface e navegação
- **Arquivos estáticos**: organização do front-end sem backend próprio

---

## **Estrutura do Repositório**
- `README.md`: documentação do projeto
- `colors.txt`: referência de cores do projeto
- `imagens/`: imagens usadas pela interface
- `js/`:
  - `Agenda.js`: lógica da página de agenda
  - `contatos.js`: lógica da página de contatos
  - `index.js`: scripts gerais de navegação e comportamento
  - `login.js`: lógica da página de login
  - `processos.js`: lógica da página de processos
  - `sidebar.js`: controle da sidebar
- `Pages/`:
  - `agenda.html`: página de agenda
  - `contatos.html`: página de contatos
  - `despesas.html`: página de despesas
  - `financeiro.html`: página de financeiro
  - `Index.html`: página inicial
  - `login.html`: página de login
  - `processos.html`: página de processos
  - `receitas.html`: página de receitas
  - `sign_up.html`: página de cadastro
- `styles/`:
  - `agenda.css`: estilos para agenda
  - `contatos.css`: estilos para contatos
  - `financeiro.css`: estilos para financeiro
  - `index.css`: estilos para página inicial
  - `login.css`: estilos para login e cadastro
  - `new.css`: estilos adicionais
  - `processos.css`: estilos para processos
  - `sidebar.css`: estilos da barra lateral

---

## **Funcionamento**
1. O usuário acessa a interface pelo arquivo `Pages/Index.html` ou pelas páginas de login e cadastro.
2. A navegação entre páginas é feita via links e scripts front-end.
3. Cada página HTML carrega seu CSS específico em `styles/`.
4. Os scripts em `js/` controlam interação, exibição e comportamento da interface.
5. O projeto funciona como um front-end estático e pode ser hospedado em qualquer servidor estático.

---

## **Configuração**
### 1. Pré-requisitos
```
Um navegador moderno
```

### 2. Execução local
Basta abrir os arquivos HTML diretamente no navegador ou usar um servidor local simples.

### 3. Servidor local opcional
Se preferir usar um servidor local, execute um servidor estático na pasta do projeto, por exemplo:
```
python3 -m http.server 8000
```

---

## **Execução**
### Abrir no navegador
- Abra `Pages/Index.html` no navegador.
- Navegue pelas páginas disponíveis no menu.

### Usando servidor local
```
cd /path/to/Projeto-SolarG
python3 -m http.server 8000
```
Abra `http://localhost:8000/Pages/Index.html`
