# Cantina do Estudante — Projeto Acadêmico (MEI)

Site institucional e informativo desenvolvido como projeto de faculdade para simular a presença digital de uma cantina operada por um **Microempreendedor Individual (MEI)**. O sistema funciona como uma vitrine digital estática para consulta rápida de preços no balcão, sem funcionalidades de carrinho ou vendas online.

---

## Sobre o Projeto

O objetivo principal desta aplicação é oferecer aos estudantes e frequentadores do campus uma forma rápida, organizada e responsiva de consultar os salgados, lanches e bebidas disponíveis na cantina, além dos horários de funcionamento e dados de contato do empreendimento.

### Funcionalidades
- **Página Inicial (`index.html`):** Apresentação da cantina e seus diferenciais (produção diária, bebidas frescas e atendimento ágil).
- **Cardápio Interativo (`cardapio.html`):**
  - Exibição de **10 opções de salgados/lanches** (coxinha, croissant, pão de queijo, esfiha, entre outros) e **4 opções de bebidas** (refrigerante, água, suco natural e café).
  - **Filtro por categoria** em tempo real via JavaScript (`Todos`, `Salgados e Lanches`, `Bebidas`).
  - **Barra de busca instantânea** para localizar itens pelo nome ou descrição.
  - Interface puramente informativa (cards não clicáveis, focados apenas na visualização de valores).
- **Contato e Localização (`contato.html`):** Endereço no campus, horário de atendimento, canais de contato e dados cadastrais fictícios do MEI.

---

## Tecnologias Utilizadas

* **HTML5:** Estruturação semântica dividida em múltiplas páginas.
* **CSS3:** Estilização moderna com variáveis de layout, Flexbox, CSS Grid e design responsivo.
* **JavaScript (Vanilla):** Manipulação do DOM para filtragem de categorias e pesquisa em tempo real no cardápio.

---

## Estrutura de Arquivos

```text
projeto-cantina/
├── index.html       # Página inicial (Home)
├── cardapio.html    # Tabela de preços, filtros e busca de itens
├── contato.html     # Informações de localização, horários e dados do MEI
├── style.css        # Folha de estilos compartilhada por todas as páginas
├── script.js        # Lógica de filtro e busca do cardápio
└── README.md        # Documentação do projeto
```

---

## Como Executar o Projeto

Por ser um projeto front-end estático, não há necessidade de instalar dependências ou configurar servidores complexos:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/projeto-cantina.git
   ```
2. **Acesse a pasta do projeto:**
   ```bash
   cd projeto-cantina
   ```
3. **Execute no navegador:**
   - Dê um duplo clique no arquivo `index.html` para abri-lo diretamente no seu navegador padrão.
   - *(Opcional)* Caso utilize o **VS Code**, você pode usar a extensão **Live Server** para rodar o projeto em um servidor local.

---

## Contexto Acadêmico

* **Disciplina:** Desenvolvimento Web / Empreendedorismo
* **Modelo de Negócio:** Microempreendedor Individual (MEI)
* **Ano:** 2026