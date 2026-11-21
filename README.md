# Mobile Emulator

**Mobile Emulator** é um projeto web que simula uma interface de celular dentro do navegador e permite organizar e executar experiências HTML locais.

- **Proprietário do projeto:** IanPaulo (GitHub: [@ianPaulo900Dev](https://github.com/ianPaulo900Dev))
- **Repositório:** [ianPaulo900Dev/mobile-html](https://github.com/ianPaulo900Dev/mobile-html)
- **Plataforma:** Web (HTML, CSS e JavaScript)
- **Idioma principal:** Português (Brasil)

## Visão geral

O pacote de origem enviado para este projeto contém uma interface de emulador Android, uma loja/catálogo de aplicativos, configurações de modelo e escala do aparelho, importação de aplicativos por ZIP e uma coleção de jogos e ferramentas HTML.

A estrutura também inclui o **PC Simulator**, com aplicações de sistema e jogos HTML próprios.

## Estrutura do pacote de origem

```text
Mobile Emulator/
├── Mobile - v5.html       # Interface principal do emulador
├── style.css              # Estilos da interface
├── script.js              # Lógica do emulador
├── lista.txt              # Catálogo de aplicativos
└── app/
    ├── ...                # Aplicativos e jogos HTML
    └── Pc Simulator/
        ├── index.html
        ├── Htmls/
        └── system/
```

> A estrutura acima descreve o ZIP de origem recebido. Nem todos os arquivos e recursos binários desse pacote foram publicados nesta primeira configuração do repositório.

## Como executar

O emulador usa arquivos locais e caminhos relativos. Para uma execução completa, mantenha juntos o HTML principal, `style.css`, `script.js`, `lista.txt` e a pasta `app/`, preservando os nomes e a hierarquia das pastas.

Em navegadores que bloqueiam a leitura de arquivos locais por `fetch()`, abra o projeto por um servidor HTTP local ou por uma hospedagem estática compatível.

## Recursos identificados no pacote

- Interface de celular com tela inicial e barra de status.
- Catálogo de aplicativos baseado em `lista.txt`.
- Instalação e desinstalação simuladas.
- Configurações de tamanho, escala e orientação.
- Importação de aplicativos HTML em arquivos ZIP.
- Armazenamento local de configurações e aplicativos importados.
- PC Simulator com aplicações de sistema e jogos HTML.

## Observações

- O conteúdo deste repositório deve ser mantido organizado e com os caminhos relativos preservados.
- Antes de distribuir jogos, imagens, áudio ou outros recursos de terceiros, confirme as respectivas permissões e licenças.
- O projeto é independente e não é afiliado ao Google ou ao Android.

---

© IanPaulo. Projeto mantido por [@ianPaulo900Dev](https://github.com/ianPaulo900Dev).

download: 
https://www.mediafire.com/file/x1y0jiqcfgm9ef3/Mobile+Emulator.zip/file
