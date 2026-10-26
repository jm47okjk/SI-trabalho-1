# Lisboa de perto

Um guia turístico digital para descobrir Lisboa. O site apresenta a cidade,
destaca alguns dos seus monumentos e bairros e dá a conhecer sabores
tradicionais, através de três páginas simples de navegar.

## Pré-visualização: <small>*O projeto encontra-se publicado e funcional na Vercel*</small>
🔗 [Visitar Lisboa de Perto](https://lisboa-de-perto.vercel.app)


![Pré-visualização da página inicial do guia Lisboa de perto](./Pré-visualização%20Inícial.png)


## Conteúdos

### Início

Em [`index.html`](./index.html), encontra-se uma introdução a Lisboa, alguns
factos sobre a cidade e atalhos para as restantes secções do guia.

### Locais a visitar

Em [`locais.html`](./locais.html), são apresentados três lugares emblemáticos:

- **Torre de Belém** — monumento manuelino junto ao Tejo;
- **Castelo de São Jorge** — castelo histórico com vista sobre a cidade;
- **Alfama** — bairro antigo conhecido pelas ruas estreitas e pelo Fado.

### Gastronomia

Em [`gastronomia.html`](./gastronomia.html), o visitante encontra informações
sobre pastel de nata, bacalhau à Brás e sardinhas assadas. A página inclui
também uma tabela com sugestões por zona e um vídeo de uma receita.

## Organização do projeto

```text
.
├── index.html
├── locais.html
├── gastronomia.html
├── css/
│   ├── style.css
│   ├── locais.css
│   └── gastronomia.css
├── Pré-visualização Inícial.png
└── README.md
```

Cada página HTML carrega a sua própria folha de estilos dentro da pasta
[`css/`](./css/). Assim, cada secção pode ter uma identidade visual distinta,
mantendo elementos comuns como a navegação, a tipografia e o comportamento em
ecrãs pequenos.

## Design e funcionalidades

- Layout adaptável a computadores, tablets e telemóveis.
- Navegação entre as três páginas do guia.
- Cartões, imagens, ligações informativas e conteúdos próprios de cada secção.
- Animações suaves e efeitos ao passar o rato sobre elementos interativos.
- Respeito pela preferência do dispositivo por movimento reduzido.
- Descrição alternativa nas imagens para facilitar a sua compreensão por
  tecnologias de apoio.
- Apresentação em tema claro.

## Como executar

O projeto é estático: não necessita de instalação, dependências ou servidor.

1. Descarrega o projeto ou clona este repositório.
2. Abre a pasta do projeto.
3. Abre `index.html` no navegador.
4. Usa a navegação no topo para visitar as páginas de locais e gastronomia.

Também é possível abrir a pasta no Visual Studio Code e iniciar um servidor
local, por exemplo com a extensão Live Server.

## Recursos externos

As fotografias, os tipos de letra e o vídeo são carregados de serviços externos.
É necessária uma ligação à Internet para os visualizar. Se o vídeo incorporado
não funcionar, a página de gastronomia disponibiliza uma ligação para o abrir
diretamente no YouTube.

## Tecnologias

- HTML5
- CSS3
