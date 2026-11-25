# El Foso de Sett

Guía interactiva de fans para aprender a jugar **Riftbound**, el juego de cartas de League of Legends, pensada para quien ya juega a Magic: The Gathering. Estética basada en Sett.

## Qué tiene

- **La guía**, en 10 asaltos: cómo se gana, montar el mazo, leer una carta, pagar con runas, el turno, el combate, el punto final, los seis colores, estilos y mazos, y palabras clave.
- **Simuladores:** pagar una carta con runas, avanzar por las fases del turno, resolver un combate y un test sobre el punto final.
- **Durante la partida:** el botón rojo de abajo a la derecha (o la tecla `/`) abre una chuleta con buscador. Tiene reglas, palabras clave y tips, y está pensada para el móvil en mitad de una partida.
  Enlace directo para guardar en el móvil: `…/index.html#partida`.

Es una sola página HTML estática, sin dependencias ni proceso de build. Las fuentes se cargan desde Google Fonts.

## Verla en local

```bash
python3 -m http.server 8000
```

Luego abre <http://localhost:8000>.

## Publicar con GitHub Pages

1. Sube el repo a GitHub.
2. Ve a **Settings → Pages**.
3. En *Source*, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. La web quedará en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Fuentes y avisos

- Guía de fans, **no oficial**. Las reglas están simplificadas para aprender. Para dudas concretas, consulta las [reglas oficiales](https://riftbound.leagueoflegends.com/en-us/news/rules-and-releases/gameplay-guide-core-rules).
- Riftbound, Sett, League of Legends y las imágenes de las cartas (`img/`) son propiedad de Riot Games. Se usan sin fines comerciales, como contenido de fans.
- Los datos de las cartas vienen de [Riftcodex](https://riftcodex.com). Las descripciones de los colores se basan en la [guía oficial de construcción de mazos](https://playriftbound.com/en-us/news/rules-and-releases/deckbuilding-primer/).
