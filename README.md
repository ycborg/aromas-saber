# Instituto Aromas & Saber — Portal Institucional

Portal responsivo de uma academia de gastronomia, feito com **HTML5, CSS3 e Bootstrap 5** (sem frameworks JavaScript nem back-end; o único JS é o bundle oficial do Bootstrap, usado pela navbar, dropdown e modais).

## Estrutura

```
portal-aromas-saber/
├── index.html      Página inicial (navbar, hero, cursos, indicadores, tabela, carrossel de notícias, contato, modais, rodapé)
├── areas.html      Página "Áreas de Ensino" (destino do menu suspenso)
├── css/style.css   Estilos personalizados (paleta, tipografia e ajustes responsivos)
└── img/
    ├── logo.svg               Monograma da instituição
    └── noticia-avental.webp   Foto do avental usada no carrossel de notícias
```

## Requisitos atendidos

| Requisito | Onde |
|---|---|
| RF01 Navbar + dropdown "Áreas de Ensino" | `<header>` das duas páginas (`navbar-expand-lg` + `collapse`) |
| RF02 Hero | `#inicio` |
| RF03 Seis cursos em cards | `#cursos` (`row-cols-1 / md-2 / lg-3`) |
| RF04 Indicadores | Seção de números (`col-6 col-lg-3`) |
| RF05 Tabela | `#consulta` (`.table-responsive`) |
| RF06 Formulário | `#contato` |
| RF07 Modais de detalhes | Botões "Ver detalhes" de cada card |
| RF08 Rodapé | `<footer>` das duas páginas |

## Como abrir

Abra `index.html` no navegador (é necessária conexão com a internet para carregar Bootstrap, fontes e imagens via CDN).
