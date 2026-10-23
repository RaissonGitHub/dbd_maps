# Dead by Daylight — Mapas em formato numpad

Coleção de imagens de mapas de **Dead by Daylight** convertidas do formato
**relógio** (12 posições + `MID`) para o formato **numpad**:

```text
7 8 9
4 5 6
1 2 3
```

As imagens de mapa usadas aqui **não são deste repositório**: elas vêm do
projeto [dbd-map-overlay](https://github.com/LucaFontanot/dbd-map-overlay), de
[LucaFontanot](https://github.com/LucaFontanot) e seus contribuidores, e dos
artistas que cederam os mapas. Veja a seção [Créditos](#créditos).

---

## Origem das imagens

| | |
|---|---|
| Repositório de origem | https://github.com/LucaFontanot/dbd-map-overlay |
| Pasta usada | `maps/<Criador>/<Realm>/<Mapa>.<ext>` |
| O que este repositório faz | adiciona uma camada de zonas numpad sobre cada mapa e monta um PSD editável |
| O que este repositório **não** faz | não redistribui os mapas como se fossem originais nem altera os créditos dos autores |

Todo o mérito pelas imagens de mapa é dos autores listados em
[Créditos](#créditos). Este projeto é apenas uma camada de conversão por cima
delas.

---

## O que tem aqui

```text
dbd_maps/
├── EagerFace/
│   ├── Autohaven Wreckers/
│   │   ├── Blood Lodge 3x3 Tactical Map.png     ← imagem numpad
│   │   ├── Blood Lodge (original).jpg           ← original full-res do dbd-map-overlay
│   │   ├── Blood Lodge (shaped).png             ← overlay numpad 
│   │   └── Blood Lodge.psd                      ← as três em camadas
│   └── ...
└── Hens333/
    └── ...
```

Para cada mapa existem quatro arquivos:

| Arquivo | Conteúdo |
|---|---|
| `<Mapa>.<ext>` | imagem numpad
| `<Mapa> (original).<ext>` | cópia do mapa original
| `<Mapa> (shaped).png` | overlay numpad transparente
| `<Mapa>.psd` | PSD com as camadas das imagens

### Mapa de conversão relógio → numpad

| Relógio | Numpad |
|---|---|
| 12 (topo) | **8** |
| 1, 2 | **9** |
| 3 (direita) | **6** |
| 4, 5 | **3** |
| 6 (base) | **2** |
| 7, 8 | **1** |
| 9 (esquerda) | **4** |
| 10, 11 | **7** |
| MID (centro) | **5** |

---

## Créditos

### Autores das imagens de mapa

- **3D futuristic maps** — [DbD League](https://discord.com/invite/dbdleague)
- **3D maps** — [SamoelColt](https://steamcommunity.com/sharedfiles/filedetails/?id=2899093390)
- **2D basic maps** — [Hens333](https://discord.com/invite/hens333)
  - agradecimento especial a **Mistic** pelo novo mapa do Trickster
- **2D iconographic maps** — [EagerFace](https://dbdmaps.com/)
- **2D detailed maps** — [KaiserAleex](https://www.twitch.tv/kaiseraleex)
- **2D detailed maps** — [StanleyWav](https://www.twitch.tv/stanleywav)

Créditos originais: [CREDITS.md do dbd-map-overlay](https://github.com/LucaFontanot/dbd-map-overlay/blob/main/CREDITS.md).

### Licença

O código do [dbd-map-overlay](https://github.com/LucaFontanot/dbd-map-overlay)
está sob a **Apache License 2.0**. As imagens dos mapas pertencem aos seus
respectivos autores — se for reutilizá-las, mantenha os créditos acima e siga as
condições de cada autor.
