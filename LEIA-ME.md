# Meu site pessoal — guia rápido

## O que tem aqui
- `index.html` — página inicial (foto, artigos recentes, pilares, sobre, newsletter)
- `artigos.html` — lista com todos os artigos
- `artigos/exemplo-de-artigo.html` — modelo de post (copie para criar novos)
- `css/style.css` — visual do site (cores no topo do arquivo)
- `img/` — fotos e imagens

## 1. Personalizar
Substitua tudo que está entre colchetes, como `[SEU NOME]`, `[SEU CARGO]` e `[EMPRESA]`.
Ou mande essas informações para o Claude, que ele preenche para você.

**Sua foto:** coloque `foto-perfil.jpg` (meio corpo, fundo neutro, vertical) dentro de `img/`.
No `index.html`, troque `img/foto-perfil.svg` por `img/foto-perfil.jpg`.
Faça o mesmo com `foto-sobre.jpg`.

## 2. Publicar de graça (Netlify, cerca de 2 minutos)
1. Acesse **app.netlify.com/drop** e crie uma conta gratuita.
2. Arraste a pasta `meu-site` inteira para a página.
3. Pronto: o site fica no ar com um endereço do tipo `nome-aleatorio.netlify.app`.
4. Em *Site settings → Change site name*, escolha um nome melhor, como `seunome.netlify.app`.
5. **Domínio próprio (opcional):** compre `seunome.com.br` no Registro.br (cerca de R$40 por ano) e conecte em *Domain management*.

**Newsletter:** os formulários já funcionam no Netlify. Os e-mails cadastrados aparecem em *Forms* no painel.

## 3. Publicar um novo artigo
1. Copie `artigos/exemplo-de-artigo.html` e renomeie, por exemplo `artigos/lideranca-na-era-da-ia.html` (sem acentos nem espaços).
2. Troque título, data, tema e texto.
3. Adicione um card do artigo no início da lista em `artigos.html`.
4. Atualize os 3 cards de "Artigos recentes" no `index.html`.
5. Arraste a pasta de novo no Netlify, em *Deploys*.

**Mais fácil:** mande o texto do artigo para o Claude. Ele cria a página, atualiza as listas e devolve a pasta pronta para arrastar.
