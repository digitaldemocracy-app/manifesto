🌐 [English](../CONTRIBUTING.md) · Español

> ⚠️ Esta traducción se hizo con ayuda de IA y aún no ha sido revisada por un hablante nativo. Puede contener errores. El texto oficial es la [versión en inglés](../CONTRIBUTING.md). Ayuda: revísala o tradúcela de nuevo.

# Cómo contribuir

Este manifiesto no es de nadie: es un punto de partida. Corrígelo, tradúcelo, mejóralo.

Todo ocurre a la vista de todos, en este repositorio. No hay lista de correo ni canal privado. Los issues y los pull requests son el registro.

## Formas de contribuir

| Quiero… | Haz esto |
|---|---|
| Firmar el manifiesto | Sigue [SIGNATURES.md](SIGNATURES.md) |
| Corregir una errata o un enlace roto | Abre un pull request directamente |
| Sugerir un cambio en la redacción o en las ideas | Abre un issue con la plantilla **Text suggestion** |
| Traducir o revisar una traducción | Abre un issue con la plantilla **Translation or review** y después un pull request |
| Hacer una pregunta o plantear una objeción | Mira antes [FAQ.md](FAQ.md); si no está ahí, abre un issue con la plantilla **Text suggestion** y ponle la etiqueta `question` |

## El texto oficial

- El texto oficial es la versión en inglés, en [README.md](../README.md).
- El texto en portugués, [pt/README.md](../pt/README.md), es el original del autor y la referencia de sentido para todas las traducciones.
- Los cambios sustanciales al texto oficial (todo lo que vaya más allá de erratas, gramática o enlaces) deben empezar como un issue, para que el razonamiento sea público antes de cualquier edición. Deciden el autor y los mantenedores; la discusión queda registrada.
- Todo cambio pasa por un pull request revisado por al menos un mantenedor. La rama `main` está protegida; nadie sube cambios directamente, tampoco los mantenedores.

## Traducciones

1. Consulta [TRANSLATIONS.md](../TRANSLATIONS.md) para ver el estado de tu idioma. Si alguien ya está trabajando en él, súmate a su issue en lugar de abrir uno nuevo.
2. Abre un issue con la plantilla **Translation or review**. Indica el idioma, si eres hablante nativo y si vas a traducir o a revisar.
3. Traduce a partir del texto en inglés. Cuando una frase sea ambigua, usa el original en portugués para decidir el sentido. Mantén los mismos títulos y el mismo número de párrafos; no añadas, quites ni reordenes secciones.
4. Pon el archivo en `<code>/README.md`, en una carpeta con el código ISO 639-1 de dos letras (`es`, `fr`, `zh`, …); los documentos complementarios van en la misma carpeta: `PRINCIPLES.md`, `FAQ.md`, `NEUTRALITY.md`, `CONTRIBUTING.md`, `SIGNATURES.md` y `LICENSE` (la traducción oficial de Creative Commons, cuando exista). Si un idioma necesita una variante regional, usa un guion y el código de región (`pt-PT`, `zh-TW`).
5. Idiomas de escritura de derecha a izquierda (árabe, urdu, persa, hebreo): envuelve todo el texto en `<div dir="rtl">` … `</div>`, con una línea en blanco después de la etiqueta de apertura y antes de la de cierre. Mira [ar/README.md](../ar/README.md).
6. Abre un pull request. Una traducción se marca como **Reviewed** cuando al menos otro hablante nativo la aprueba en el pull request.

Las traducciones a idiomas más allá de los diez de la lista son bienvenidas. Los diez son un punto de partida, no un límite.

## Estilo

- Frases cortas. Palabras sencillas. El manifiesto está hecho para leerse en voz alta y repetirse.
- Mantén el tono: invita, no acusa. Acusamos a la distancia, no a las personas.
- No se apoya ni se ataca a ningún partido, candidato, gobierno o país, en ningún idioma.

## Conducta

Debatir no es pelear. Los argumentos tienen lados, y los lados tienen argumentos. Discrepa de las ideas, no de las personas. Los mantenedores cerrarán las discusiones que se vuelvan personales y podrán bloquear cuentas que insistan.

## Licencia

Al contribuir aceptas que tu aportación se publique bajo la misma licencia que el manifiesto, [Creative Commons Atribución 4.0 Internacional (CC BY 4.0)](LICENSE). Los traductores figuran en el archivo de la traducción y en el historial de git.
