# Biblioteca Digital UniFECAF

Primeira versão do site da Biblioteca Digital UniFECAF, desenvolvida como trabalho da disciplina **Design Web**. O projeto transforma um protótipo de baixa fidelidade em uma interface web moderna, responsiva e alinhada à identidade visual da instituição, usando **apenas HTML e CSS**.

## Links

- Site publicado: https://gdelgado-coder.github.io/biblioteca-unifecaf/
- Repositório: https://github.com/gdelgado-coder/biblioteca-unifecaf/

## Sobre o projeto

O site ajuda o aluno a conhecer a biblioteca, ver os livros disponíveis, saber onde ficam as unidades e como entrar em contato. A proposta visual é simples e levemente gamificada, com nível, barra de XP e selos nos livros, sempre sem atrapalhar a leitura.

## Seções da página

1. **Menu:** navegação fixa no topo, com links para as seções.
2. **Banner principal:** título e chamada em fundo liso, com o símbolo da UniFECAF translúcido.
3. **Sobre a nossa biblioteca:** apresentação e galeria de imagens.
4. **Nossos livros:** seis cards com capa, descrição e botão "Saiba mais", que leva à página oficial da biblioteca.
5. **As unidades:** três blocos com imagem e texto.
6. **Contatos:** WhatsApp, endereço e horários, retirados do site oficial da UniFECAF.
7. **Rodapé.**

## Tecnologias

- HTML5 (tags semânticas)
- CSS3 (variáveis, Grid, Flexbox e media queries)
- Fontes do Google Fonts: Poppins (títulos) e Nunito Sans (texto)

Não foram usados JavaScript, frameworks, construtores de sites ou templates prontos.

## Estrutura de arquivos

```
biblioteca-unifecaf/
├── index.html
├── README.md
├── css/
│   └── style.css
└── assets/
    └── imagens/
```

## Identidade visual

| Cor | Hex | Uso |
|---|---|---|
| Azul institucional escuro | `#004878` | Fundos principais |
| Azul-noite | `#00304F` | Banner e unidades |
| Azul do logo | `#0060A8` | Detalhes e hover |
| Azul Cerulean | `#2E4FB8` | Ilustrações |
| Verde | `#95DE68` | Botões e destaques |
| Verde claro | `#E9F6E0` | Seção de contatos |

As cores foram baseadas no logo e na identidade da UniFECAF (fonte: Brandfetch).

## Responsividade

O layout se adapta a computadores, tablets e smartphones:

- Livros em 3 colunas no desktop, 2 no tablet e 1 no celular.
- Unidades e contatos empilham no celular.
- Imagens fluidas, sem distorção.
- Menu compacto em uma linha no celular.

## Acessibilidade

- Idioma definido (`lang="pt-BR"`) e HTML semântico
- Texto alternativo em todas as imagens
- Link para pular direto ao conteúdo
- Foco visível na navegação por teclado
- Contraste de cores verificado (WCAG AA)
- Respeito à preferência de movimento reduzido

## Como visualizar

1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` no navegador.

Não é preciso instalar nada.

## Créditos

- Logo e identidade visual: UniFECAF
- Contatos e informações da biblioteca: [site oficial da UniFECAF](https://www.unifecaf.com.br/biblioteca)
- Ilustrações: criadas para este projeto
- Textos dos livros e das unidades: fictícios, criados para fins acadêmicos

## Autor

[Seu nome] · RA [seu RA]
Disciplina: Design Web · UniFECAF

> Projeto acadêmico, sem fins comerciais.
