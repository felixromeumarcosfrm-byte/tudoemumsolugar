 [README.md](https://github.com/user-attachments/files/26304659/README.md)
# 🛍️ FRM Boutique Tudo em um só lugar — Ecossistema Digital

## 📌 Descrição

Este projeto é uma loja virtual completa desenvolvida em **HTML, CSS e JavaScript puro**, chamada **FRM Boutique**.
O sistema simula um e-commerce moderno com funcionalidades essenciais como vitrine de produtos, carrinho de compras, autenticação de usuário e painel administrativo.

---

## 🚀 Funcionalidades principais

### 🔐 Autenticação de usuário

* Tela inicial para identificação do cliente
* Saudação personalizada após login
* Dados guardados no **localStorage**

---

### 🛒 Vitrine de produtos

* Exibição dinâmica de produtos (grid responsivo)
* Categorias automáticas (Smartphones, Moda, Perfumes, etc.)
* Filtro por categorias
* Imagens e preços formatados em Kwanza (Kz)

---

### 🧺 Carrinho de compras

* Adicionar/remover produtos
* Contador de itens
* Cálculo automático do total
* Persistência de dados no navegador

---

### 📦 Finalização de pedido

* Integração com **WhatsApp**
* Geração automática da mensagem de compra
* Histórico de pedidos salvo localmente

---

### 📜 Histórico de compras

* Registro de pedidos realizados
* Exibição de data, total e quantidade de itens

---

### ⚙️ Painel administrativo

* Acesso protegido por senha (`admin123`)
* Adicionar novos produtos
* Excluir produtos existentes
* Atualização dinâmica da loja

---

## 🗂️ Estrutura de dados

### Produtos

```js
{
  id: number,
  name: string,
  price: number,
  cat: string,
  img: string
}
```

### Carrinho

* Lista de produtos adicionados
* Armazenado em `localStorage`

### Histórico

* Registro de pedidos realizados
* Inclui: cliente, data, total e quantidade

---

## 💾 Armazenamento

O sistema utiliza **localStorage** para:

* Produtos (`frm_db`)
* Carrinho (`frm_cart`)
* Histórico (`frm_history`)
* Usuário (`frm_user`)

---

## 🎨 Design

* Interface moderna com tema escuro
* Destaques em dourado (luxo)
* Responsivo (funciona em telemóvel e desktop)
* Animações suaves e interativas

---

## 📱 Categorias disponíveis

* Smartphones
* Moda
* Calçados
* Perfumes
* Acessórios
* Desporto

---

## ⚠️ Limitações

* Não possui backend (não é um sistema real de pagamento)
* Dados podem ser perdidos ao limpar o navegador
* Segurança básica (senha fixa no código)

---

## 🔥 Melhorias recomendadas

* Integrar com banco de dados real (Firebase ou Node.js)
* Implementar sistema de pagamento automático
* Criar login com autenticação segura
* Adicionar sistema de entrega e rastreamento

---

## 📌 Conclusão

Este projeto é uma base sólida para um e-commerce moderno, ideal para:

* Testes de negócio
* Portfólio
* Início de uma loja online real

---

## 👤 Autor

**Félix Romeu Marcos**
Diretor Geral — FRM Boutique
