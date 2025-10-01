# Vinheria Agnello – site estático (HTML/CSS)

Projeto acadêmico inspirado no caso fictício **“O Caso da Vinheria Agnello”**, referência das disciplinas do 1º ano de Engenharia de Software
O estudo descreve uma vinheria familiar de São Paulo, cujo diferencial é o atendimento consultivo: orientação sobre uvas, regiões, vinícolas e harmonizações. 

Com o impacto da pandemia e a migração dos clientes para o e-commerce, o proprietário Giulio, incentivado por sua filha Bianca (Product Owner no caso), decide criar um portal online que traduza a experiência calorosa da loja física para o ambiente digital

Este repositório entrega a **primeira versão navegável** do site, com páginas estáticas em **HTML5 + CSS3**, catálogo, formulário de contato e conteúdos institucionais.

O projeto é leve, multipágina e sem dependências de build: basta abrir o `index.html` no navegador. A navegação principal, a identidade e o rodapé são compartilhados entre as páginas.

## Menu de Navegação
- [Descrição](#vinheria-agnello--site-estático-htmlcss)
- [Integrante](#integrante)
- [Site publicado](#site-publicado)
- [Estrutura](#estrutura)
- [Como executar localmente](#como-executar-localmente)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Observações](#observações)
- [Licença](#licença)


## Integrante
- João Antonio Sarracine Faedrich de Souza

## Site publicado
Acesse o site no GitHub Pages:  
👉 [Vinheria Agnello no GitHub Pages] https://sarracinee.github.io/Vinheria-Agnello/

## Estrutura

<img width="232" height="290" alt="image" src="https://github.com/user-attachments/assets/08b55374-dcd4-4505-87b7-88436f1639f7" />


- **`index.html`** – home com meta tags, hero image e embed de vídeo do YouTube. 
- **`style.css`** – estilos globais (reset leve, tipografia, layout de cabeçalho, rodapé, tabelas, formulários e botões). 
- **`about.html`** – página institucional com a história e imagem da fachada.   
- **`catalog.html`** – índice das categorias do catálogo e imagem de apoio. 
- **`carrinho.html`** – estado “carrinho vazio” com CTA para o catálogo. 
- **`contato.html`** – formulário de clientes que, ao enviar, redireciona para a página de confirmação. 
- **`maisprodutos.html`** – tabela de harmonizações “Além do vinho”. 
- **`videos.html`** – placeholder para a área de vídeos.

## Como executar localmente

1. Baixe/clonar este repositório.  
2. Abra o arquivo `index.html` diretamente no navegador **ou** use a extensão “Live Server” do VS Code para recarregamento automático. 
3. Verifique o caminho das imagens em `src/assets/imgs/` (os HTMLs já apontam para essa pasta).

## Tecnologias Utilizadas

- HTML5 semântico.
- CSS customizado modularizado (`nav.css`, `utility.css`, `landing.css`, `global.css`).
- Com espaço para JS em um futuro breve.

## Observações

Este sistema foi criado com fins educacionais, focado em boas práticas de estrutura, semântica HTML e estilização desacoplada. Nenhum dado comercial é real.

---

## Licença

Este projeto está licenciado sob a licença **MIT**. 