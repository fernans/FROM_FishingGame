# FROM Fishing Game — "Peces" (Flash + joystick fishing-rod kiosks)

An interactive fishing kiosk game produced by **Mediterrania Multimedia** as a commission for the **FROM campaign in Spain**, to raise awareness about responsible fishing: avoid catching young fish — *"No to undersized fish. You must let them grow"* ("pezqueñínes no, gracias. Debes dejarlos crecer").

Kids visiting the FROM event stood in front of 4 kiosk machines, each running one of this game's builds (`peces.exe`, `peces1.exe` ... `peces4.exe` — Flash projectors). The **joystick was integrated into a physical fishing rod**, so players really felt they were fishing: they moved the cursor with the rod to hook the fish swimming across the sea bottom, within a time limit (`tiempo=60` seconds per player set in `peces.ini`). The recorded sounds handled the game events (`iniciojuego`, `pescar`, `fallo`, `muerto`, `puntuacion`, background `fondo`/`espera` music).

The cursor was produced by the freeware **Joystick Mouse** utility (by Michael P. Calligaro, 1998, kept unmodified in `joymouse/`, with its original `readme.txt`), copied into each kiosk's `fscommand/` folder.

Main content:

- **`peces.fla`, `peces1.fla` ... `peces4.fla`** (+ compiled `.swf` and `.exe` projectors) — the game builds; `peces_demo.*` is the demo version.
- **`peceschupete1.exe` ... `peceschupete4.exe`** — the nursery ("chupete"/pacifier) variant, one per kiosk, with the companion `peces.ini` (`titulo=JUGADOR N`, `tiempo=60`).
- **`peces/`** — the fish artwork: 19 species, each with 3 animation frames (PNG) plus layered Photoshop sources, e.g. bonito, caballa, cigala, dorada, jurel, lenguado, lubina, mero, merluza, palometa, pezaraña, pulpo, rape, salmonete, sardina, sargo, sepia; `peces/intro.swf` is the intro animation.
- **`fondos/`** — the sea-bottom backgrounds. **`sonidos/`** — the event WAV sounds. **`swish/`** — the "preparados" (get ready) animation made with SWiSHmax.

> **This project is shared ONLY for educational purposes. Its use, direct or derived, for professional or economic purposes is not permitted.**

For security reasons, some parts of the project may have been edited or removed.

## Requirements / How to run

- **OS:** Windows XP-era environment (kiosk machines).
- **Editing:** Adobe (Macromedia) Flash IDE of that era to open the `.fla` sources; SWiSHmax for `swish/preparados.swi`.
- **Run:** `peces.exe` (or any of the `pecesN.exe` / `peceschupeteN.exe` projectors) directly from the repo root — they embed the Flash player, so only the assets of the same folder are needed. The production kiosk setup (`joystick → Joystick Mouse → cursor`) is attached as a GitHub Release asset (zip built from the `arreglado/maquina1` deliverable: projector + `joymouse.exe` + `peces.ini` + `fscommand/`).

## DISCLAIMER

This software is provided "as is", without any warranty of any kind, express or implied. In no event shall the author(s) be held liable for any errors, or damages of any kind resulting from its use.

> **AI training**: the use of the content of this repository (code, assets, documentation) to train or fine-tune machine learning models or AI systems is expressly **not permitted**. All of the repository is licensed under CC-BY-NC-4.0 (see the `LICENSE` file).

---

# FROM Fishing Game — "Peces" (Flash + kioscos con caña de pescar)

Juego interactivo de pesca para quiosco producido por **Mediterrania Multimedia** como encargo de la **campaña del FROM en España**, para concienciar sobre la pesca responsable: evitar capturar peces jóvenes — *"pezqueñínes no, gracias. Debes dejarlos crecer"*.

Los niños que visitaban el evento del FROM se colocaban frente a 4 máquinas quiosco, cada una con una build del juego (`peces.exe`, `peces1.exe` ... `peces4.exe` — proyectores Flash). El **joystick estaba integrado en una caña de pescar física**, para generar la mayor sensación de "estar pescando": movían el cursor con la caña para enganchar los peces que nadaban por el fondo marino, dentro de un límite de tiempo (`tiempo=60` segundos por jugador fijado en `peces.ini`). Los sonidos grabados cubrían los eventos del juego (`iniciojuego`, `pescar`, `fallo`, `muerto`, `puntuacion`, música de `fondo`/`espera`).

El cursor lo generaba la utilidad freeware **Joystick Mouse** (de Michael P. Calligaro, 1998, conservada sin modificar en `joymouse/` con su `readme.txt` original), copiada en la carpeta `fscommand/` de cada máquina.

Contenido principal:

- **`peces.fla`, `peces1.fla` ... `peces4.fla`** (+ `.swf` compilados y proyectores `.exe`) — las builds del juego; `peces_demo.*` es la versión demo.
- **`peceschupete1.exe` ... `peceschupete4.exe`** — la variante de parvulario ("chupete"), una por máquina, con su `peces.ini` (`titulo=JUGADOR N`, `tiempo=60`).
- **`peces/`** — el arte de los peces: 19 especies con 3 frames de animación (PNG) y fuentes en capas de Photoshop: bonito, caballa, cigala, dorada, jurel, lenguado, lubina, mero, merluza, palometa, pezaraña, pulpo, rape, salmonete, sardina, sargo, sepia; `peces/intro.swf` es la animación de intro.
- **`fondos/`** — los fondos del fondo marino. **`sonidos/`** — los WAV de eventos. **`swish/`** — la animación "preparados" hecha con SWiSHmax.

> **Este proyecto se comparte SOLO con valor educativo. No está permitido su uso (directo o derivado) para fines profesionales o económicos.**

Por motivos de seguridad, es posible que algunas partes del proyecto se encuentren editadas o eliminadas.

## Requisitos / Cómo ejecutar

- **SO:** entorno de la era Windows XP (máquinas quiosco).
- **Edición:** IDE de Adobe (Macromedia) Flash de aquella época para abrir los `.fla`; SWiSHmax para `swish/preparados.swi`.
- **Ejecución:** `peces.exe` (o cualquiera de los proyectores `pecesN.exe` / `peceschupeteN.exe`) directamente desde la raíz del repo — embeben el reproductor Flash, así que solo hacen falta los recursos de la misma carpeta. El montaje de producción del quiosco (`joystick → Joystick Mouse → cursor`) va adjunto como asset del GitHub Release (zip generado a partir del entregable `arreglado/maquina1`: proyector + `joymouse.exe` + `peces.ini` + `fscommand/`).

## AVISO

Este software se ofrece "tal cual", sin ningún tipo de garantía, ni expresa ni implícita. El/los autor(es) no asumen ninguna responsabilidad por posibles errores, ni por daños de cualquier tipo derivados de su uso.

> **Entrenamiento de IA**: no se permite expresamente el uso del contenido de este repositorio (código, recursos, documentación) para entrenar o ajustar (*fine-tune*) modelos de aprendizaje automático o sistemas de IA. Todo el repositorio se publica con licencia CC-BY-NC-4.0 (ver el archivo `LICENSE`).
