---
title: "Criando sites com Hugo e Netlify"
date: 2020-03-16T11:40:11+02:00
publishdate: 2018-10-07T11:40:11+02:00
image: "/images/blog/8.jpg"
tags: ["hugo", "programação", "golang",]
comments: true
---
<h2><strong> Sites Estáticos Utilizando o Framework Hugo</strong></h2>
Com o objetivo de incentivar mulheres a criar seu próprio site, obter um novo conhecimento para aplicar em seus trabalhos ou poderem fazer disso uma nova forma de obter renda, no dia 15 de fevereiro de 2020, a comunidade Women Who Go de Curitiba, em parceria com Women Techmakers de Curitiba, ofereceu um workshop para criação de sites estáticos utilizando o framework Hugo.
Hugo é um framework open source desenvolvido em Go, simples de usar e muito rápido para gerar páginas estáticas. Em seu site oficial é possível encontrar centenas de temas prontos para todos os gostos e necessidades.

<h2><strong>O que são sites estáticos?</strong></h2>
Quando acessamos um site, é feita uma requisição a um servidor que devolve para o navegador a informação em formato HTML (HyperText Markup Language) que renderiza este texto formatado.
Porém, a grande maioria dos sites são gerados dinamicamente, o que exige processamento do servidor, por vezes um banco de dados e uma linguagem de programação que faz a conversão para HTML.
Os sites estáticos não exigem este processamento pois eles já estão armazenados no servidor no formato HTML, e com isso tem um custo de hospedagem menor (para alguns casos até gratuito) e melhor performance. Além de não ter brechas de segurança.
Estas vantagens fizeram com que grandes blogs e empresas adotassem a ferramenta, como Tableless, 1Password, Let’s Encrypt e outros.
Sites estáticos são muito indicados para blogs, sites pessoais e institucionais.

<h2><strong>Bora ver como é fácil?</strong></h2>
Vamos utilizar neste tutorial:
- Terminal (para quem usa Windows, sugerimos usar o Git Bash);
- Git para versionar o projeto;
- Github como repositório remoto;
- Netlify para publicar o site.

<h2><strong>Instalação</strong></h2>
O Hugo é disponibilizado como um executável pronto para uso via terminal. É possível utiliza-lo nos principais sistemas operacionais. A instalação consiste em baixar o executável em qualquer local do seu sistema, e fazer uma configuração nas variáveis de ambiente para que o terminal reconheça seu comando.
Para facilitar esta instalação / configuração é possível usar gerenciadores de pacotes como:

<h3><strong>Brew no MacOs</strong></h3>
$ brew install hugo

<h3><strong>Apt-get no Linux (Debian e Ubuntu)</strong></h3>
$ sudo apt-get install hugo

<h3><strong>Chocolatey no Windows</strong></h3>
$ choco install hugo -confirm

O Chocolatey não vem instalado no windows, portanto deve ser instalado antes de usar este comando.
Se preferir pode seguir a instalação manual (sem o chocolatey) que descrevo aqui.