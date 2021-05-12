---
-title: "Aplicaciones escenciales para programadores en Ubuntu 20.04"
_title: "De Windows a Ubuntu 20.04 ¿Qué aplicaciones necesito?"
title: "De Windows a Ubuntu 20.04 ¿Por dónde empezar?"
date: 2021-05-01T18:00
thumb: "ubuntu.png"
description: "Guía de ubuntu para principiantes"
lang: "Spanish"
tags:
  - Ubuntu
  - Spanish
---

## Empezando con Ubuntu

Ubuntu es una de las distribuciones más populares al momento de empezar con Linux 🐧, especialmente por nosotros, los programadores 👨‍💻, si vienes de Windows y estas buscando las aplicaciones alternativas a las que usabas antes, te dejo una lista que puede interesarte:

<!-- ### Lista de aplicaciones -->

1. [Remmina](#remmina)
2. [Flameshot](#flameshot)
3. [Zsh y Ohmizsh](#zsh)
4. [Font Manager](#font-manager)

<a name="remmina"></a>

### 1. Remmina

![Remmina in Ubuntu](/assets/img/_remmina.png "Remmina")

[Remmina](https://remmina.org/) es un cliente de escritorio remoto que nos ayuda a conectarnos a servidores mediante el protocolo **SSH, RDP, VNC** y más. Ya viene instalada por defecto y en la sección de preferencias puedes configurar el tema de la terminal, elejir una carpeta para las capturas de pantalla, administrar los keystroke, qué son snippets para ejecutarlos rapidamente en la terminal y más.

Puedes establecer la configuración de una conexión para que se estableza por defecto para las nuevas si asi lo deseas, agrupar tus conexiones en carpetas, entre otras funciones interesantes que seguro te serán útiles.

<a name="flameshot"></a>

### 2. Flameshot

![Flameshot](https://flameshot.org/media/animatedUsage.gif "Flameshot")

[Flameshot](https://flameshot.org) es escencial incluso si no eres programador, te permite realizar recortes de pantalla, editarlos, copiarlos al portapapeles para enviarlas instantaneamente, guardarlas como imagenes si asi lo deseas, entre otras funciones que puedes encontrar [aquí](https://flameshot.org).
Para instalarla simplemente buscala en la tienda de aplicaciones de ubuntu (Ubuntu Software) y dejate llevar.
Si lo usas con mucha frecuencia quizá te interese que se inicie junto con el sistema operativo, para hacer esto sigue estos pasos:

1. Busca y abre el programa **Startup Applications Preferences** ó **Preferencias de aplicaciones de inicio** si tu SO está en español.
2. Presiona la opción **agregar** y escribe el comando de ejecución de flameshot, para saber cuál es ejecuta en la terminal lo siguiente: `which flameshot` .
3. Copia y pega esto en el formulario y listo. El programa se ejecutará al iniciar el sistema operativo en el proximo reinicio.

<a name="zsh"></a>

### 3. Zsh y oh-my-zsh

![Zsh](/assets/img/_terminal.png "Zsh")

Zsh es una shell alternativa a la que viene por defecto en ubuntu y con ayuda de [oh-my-zsh](https://ohmyz.sh/) puedes agregarle [temas](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes) y [plugins](https://github.com/ohmyzsh/ohmyzsh/wiki/Plugins) que harán que tu desarrollo sea más agradable.

Para instalar **zsh** ejecuta:

```bash
sudo apt install zsh
```

Y para instalar **oh-my-zsh**

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### Plugins

Los siguientes plugins te pueden ayudar a ser más rápido y productivo mientras te mueves por la terminal:

- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
  te brinda sugerencias al momento de escribir los comandos basados en tu historial de uso.
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
  Este paquete proporciona resaltado de sintaxis para el shell zsh, esto ayuda a revisar los comandos antes de ejecutarlos, especialmente para detectar errores de sintaxis. Seleccione la sugerencia con la combinación `ctrl + ➝` .

<a name="font-manager"></a>

### 4. Font Manager

![Font Manager](/assets/img/_font-manager.png "Font Manager")

Cuando personalizamos nuestros editores de código usualmente probamos fuentes nuevas que debemos descargar e instalar, **Font Manager** te brinda una interfaz para agregar nuevas fuentes de manera muy sencilla, solo tienes que descargar manualmente los archivos **.ttf** y agregarlos mediante la aplicación.

Para instalarla solo ejecute:

```bash
sudo apt install font-manager
```

Y después de esto podrá encontrarla dentro de sus aplicaciones.

<!--
## Conclusión

Empezar a usar ubuntu para desarrollar aplicaciones puede ser más agragable con las aplicaciones adecuadas  -->
