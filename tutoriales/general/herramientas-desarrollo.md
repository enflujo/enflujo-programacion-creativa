# Herramientas de desarrollo <img  src="https://emojis.slackmojis.com/emojis/images/1660663279/60857/tim-the-tool-man-taylor.png?1660663279" width="30"/>

Esta es una lista básica de herramientas para tener un taller local de desarrollo. Sobre esta base pueden instalar otras herramientas y extensiones según el gusto de cada uno.

## Terminal (emulador de consola) <img  src="https://emojis.slackmojis.com/emojis/images/1646429960/55230/party-terminal.gif?1646429960" width="30"/>



###  <img  src="https://emojis.slackmojis.com/emojis/images/1643514177/1419/windows.gif?1643514177" width="16"/> Windows

Windows trae por defecto dos programas que nos permiten darle comandos a la terminal: [Símbolo del sistema de Windows](https://es.wikipedia.org/wiki/S%C3%ADmbolo_del_sistema_de_Windows) (cmd.exe o Command Prompt) y [PowerShell](https://es.wikipedia.org/wiki/PowerShell). Aquí no usamos ninguno de los dos porque son feos.

Además, para poder usar los mismos comandos entre sistemas Linux, macOS y Windows y así entendernos en lenguajes similares en los tutoriales, entre nosotrxs y con nuestros computadores, recomendamos instalar un emulador de terminal que reconoce comandos para sistemas operativos basados en Unix (como macOS y Linux) y los traduce al sistema operativo de Windows por nosotrxs. 

Recomendamos descargar y usar [cmder](https://cmder.app/).

## Gestor de aplicaciones

Con estos instalamos aplicaciones de manera global en el computador.

###  <img  src="https://emojis.slackmojis.com/emojis/images/1643514177/1419/windows.gif?1643514177" width="16"/> Windows

Instalar [Chocolatey](https://chocolatey.org/install). Comando para ejecutarlo `choco`.

### <img  src="https://emojis.slackmojis.com/emojis/images/1643514416/3931/macos.gif?1643514416" width="16"/> Mac

Instalar [Homebrew](https://brew.sh/). Comando para ejecutarlo es `brew`.

###  <img  src="https://emojis.slackmojis.com/emojis/images/1643514745/7530/hackerman.jpg?1643514745" width="16"/> Linux

Ya viene con APT _(Advanced Package Tool)_. Comando para ejecutarlo es: `apt-get`.

## Aplicaciones globales

Con el gestor instalado para su sistema operativo, instalar:

- NodeJS
- Git
- Yarn

### Windows

```bash
choco install nodejs git yarn
```

### Mac

```bash
brew install node git yarn
```

### Linux

```bash
sudo apt-get update
sudo apt-get dist-upgrade
sudo apt-get install nodejs git yarn
```

## Editor de código

Recomiendo [VSCode](https://code.visualstudio.com/)

## Algunas extensiones recomendadas para VSCode

- GitHub Pull Requests and Issues
- GitLens - Git supercharged
- Glitch
- Gitmoji
- indent-raindow
- Settings Sync
- Prettier
- Better Comments
- Github Markdown Preview + sus Extensions Packs.
- Android iOS Emulator
- Color Picker

## Sobre Git y Github

[Git](https://git-scm.com/) es un software de control de versiones para desarrolladores, es decir, permite manejar distintas versiones de un solo archivo o proyecto e ir y venir entre versiones cómodamente, como si pudiéramos pasear entre dimensiones paralelas de un mismo mundo, probar cosas distintas en cada una y volver atrás, si hace falta. 

[Github](https://github.com/) es una plataforma web para alojar archivos de código que facilita la colaboración entre varias personas que usan Git. Al igual que este, permite controlar los cambios y las versiones de los archivos y, además, sirve para la gestión y la organización de los proyectos. A veces puede ser confuso y tal vez frustrante pero es muy útil. 

Conceptos clave para trabajar con Git y GitHub en repositorios (proyectos) compartidos:

1. Fork: copiar el código de otra persona en el propio repositorio para modificarlo.
2. Pull Request: enviar los cambios realizados a la persona dueña del repositorio original (del fork -> al repo original) para que los apruebe. 
3. Merge (fusionar): Integrar los cambios hechos por otros al repositorio original, una vez aprobados.
4. Branch(es) (rama(s)): bifurcaciones dentro de un mismo repositorio que permiten tener distintas versiones de los archivos. La rama principal en Git y GitHub solía llamarse Master pero en las últimas versiones se llama Main por polémicas sobre el lenguaje, las jerarquías, el racismo y la esclavitud (a las ramas que no eran Master se les llamaba 'slaves'). 
5. Pull: Actualizar localmente su código con los cambios de un repositorio.
6. Push: Similar a "pull" pero en el sentido contrario. Mandar cambios locales al repositorio.

[Más sobre el trabajo con Git y GitHub](../git-github/guia-breve.md).
