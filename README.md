# Solo - Agora em Português/BR

Tema traduzido para Português/BR.

Solo é um tema minimalista para [Ghost](https://github.com/TryGhost/Ghost) focado em destacar o trabalho de um escritor ou criador individual. Este tema é altamente personalizável, com algumas configurações simples que permitem aplicar rapidamente seu próprio estilo pessoal ao seu site.

**Demonstração: https://solo.ghost.io**

# Instruções

1. [Baixe este tema](https://github.com/romaodesouza/Solo/archive/main.zip)
2. Faça login no Ghost e vá para a área de configurações `Design` para fazer o upload do arquivo zip

# Desenvolvimento

Os estilos de edição são compilados usando Gulp/PostCSS para preencher a futura especificação CSS. Você precisará ter [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) e [Gulp](https://gulpjs.com) instalados globalmente. Depois disso, a partir do diretório raiz do tema:

```bash
# Instalar
yarn

# Executar a compilação e observar as mudanças
yarn dev
```
Agora você pode editar os arquivos `/assets/css/`, que serão compilados automaticamente para `/assets/built/`.

A tarefa `zip` do Gulp empacota os arquivos do tema em `dist/solo.zip`, que você pode então fazer upload para o seu site.

```bash
yarn zip
```

# Contribuição

Este repositório é sincronizado automaticamente com o monorepo [TryGhost/Themes](https://github.com/TryGhost/Themes). Se você deseja contribuir ou levantar uma questão, vá para o repositório principal [TryGhost/Themes](https://github.com/TryGhost/Themes), onde nossos temas oficiais são desenvolvidos.

## Direitos autorais & Licença

Direitos autorais © 2013-2023 Ghost Foundation - Lançado sob a licença [MIT license](LICENSE).
