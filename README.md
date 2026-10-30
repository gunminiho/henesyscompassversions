# Henesys Compass — versiones

Releases de **Henesys Compass**, compañero de escritorio para MapleStory Classic World.
Este repositorio solo aloja los instalables; cada release incluye:

- `HenesysCompass-<versión>-win64.zip` — carpeta portable (descomprimir y ejecutar `HenesysCompass.exe`).
- `update.json` — manifiesto que consulta el actualizador integrado.
- `SHA256SUMS.txt` — suma de verificación del zip.

La app (desde la 0.2.0) comprueba `releases/latest/download/update.json` al abrirse y ofrece instalar la versión nueva
tras verificar su SHA-256. La comprobación no envía ningún dato del usuario.

Henesys Compass observa la pantalla y guía al jugador. No lee memoria del juego, no inyecta código ni automatiza acciones.
No está afiliado a Nexon. MapleStory es propiedad de Nexon.
