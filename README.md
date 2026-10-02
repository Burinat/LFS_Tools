# LFS Tools

> Eines tècniques ràpides per a audiovisual, projecció, vídeo, àudio i il·luminació.

[![HTML](https://img.shields.io/badge/HTML-standalone-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![Mobile friendly](https://img.shields.io/badge/disseny-mobile--friendly-4ED9B5)](#)
[![License](https://img.shields.io/badge/ús-personal%20i%20professional-82ADFF)](#)

## ✨ Què és?

**LFS Tools** és una col·lecció d'eines web lleugeres pensades per resoldre càlculs habituals de producció tècnica. Funciona directament al navegador, sense instal·lació, servidor ni dependències de framework.

Cada calculadora és un fitxer HTML autònom i està dissenyada perquè sigui còmoda tant en ordinador com en pantalles petites.

## 🧰 Eines incloses

### 🎥 Vídeo i projecció

| Eina | Descripció |
|---|---|
| 📐 **Calculadora de projecció** | Calcula amplada, distància o relació de tir. Inclou formats 16:9 i 16:10, alçada i diagonal resultants. |
| 🖥️ **Blending avançat** | Calcula la resolució efectiva d'un canvas amb diversos projectors, l'orientació i el blend en píxels. |
| 💡 **Lúmens per entorn** | Relaciona lúmens, superfície i lux per treballar en cinema, corporatiu o exterior. |
| 🏛️ **Lúmens per façana** | Calcula cobertura, geometria projectada, blending i lux en projecció arquitectònica. |
| 🔌 **Capacitat de connector** | Estima el bitrate de vídeo i comprova compatibilitat amb HDMI, DisplayPort i SDI. |

### 🎚️ Àudio

| Eina | Descripció |
|---|---|
| ⏱️ **Delay per BPM** | Converteix BPM a mil·lisegons per a negra, corxera, semicorxera, punt, treset i compàs. |

### 💡 Il·luminació

| Eina | Descripció |
|---|---|
| 🎛️ **Adreces DMX · DIP switches** | Converteix una adreça DMX en interruptors binaris, mostra el rang de canals ocupats i avisa si se supera l'univers DMX. |

## 🚀 Ús local

1. Descarrega o clona aquest repositori.
2. Mantén tots els fitxers HTML dins de la mateixa carpeta.
3. Obre `index.html` amb qualsevol navegador modern.
4. Selecciona l'eina que necessitis des del menú principal.

> ℹ️ No cal instal·lar res: totes les calculadores s'executen localment al navegador.

## 🌐 Publicar amb GitHub Pages

1. Puja tots els fitxers descomprimits al repositori, amb `index.html` a l'arrel.
2. Ves a **Settings → Pages**.
3. A **Build and deployment**, selecciona **Deploy from a branch**.
4. Escull la branca `main` i la carpeta `/(root)`.
5. Desa els canvis i espera que GitHub indiqui l'adreça pública del lloc.

## 📁 Estructura prevista

```text
lfs-tools/
├── index.html
├── projection_calculator.html
├── projection_blend_basic.html
├── projection_blend_advanced.html
├── lumens_calculator.html
├── projection_luminosity.html
├── connector_capacity_calculator.html
├── audio_delay_calculator.html
├── dmx_dip_switch_calculator.html
└── README.md
```

## 📱 Disseny

- 🌙 Interfície fosca d'alt contrast.
- 📲 Adaptada a mòbil, tauleta i escriptori.
- 🎚️ Sliders sincronitzats amb camps numèrics quan correspon.
- ⚡ Resultats recalculats a l'instant.
- 🧭 Navegació senzilla entre la portada i cada eina.

## ⚠️ Nota tècnica

Aquestes eines són ajudes de planificació i estimació. Abans d'una instal·lació real, valida sempre els resultats amb les especificacions del fabricant, les condicions del recinte, les òptiques disponibles, la configuració de senyal i les mesures reals de camp.
