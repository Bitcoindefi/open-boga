# Contribuir a Agente Smith

Gracias por querer sumar. Este es un proyecto MIT hecho desde la práctica jurídica
real argentina, y crece mejor con gente que litiga todos los días.

## Qué aporte sirve más

1. **Fichas de jurisdicción** (`jurisdicciones/`): tu provincia — código procesal,
   régimen de plazos (hábiles judiciales/administrativos, feria, plazo de gracia),
   fuentes oficiales y particularidades del fuero. Usá `jujuy.md` o `salta.md` como
   plantilla.
2. **Skills** (`skills/`): mejoras al router de áreas, nuevos ejes normativos,
   correcciones de método en plazos/diagnóstico/bucles.
3. **MCP SAIJ** (`componentes/mcp-saij/`): mejoras de búsqueda y cobertura.
4. **Documentación**: ejemplos de uso, correcciones, traducciones.

## Reglas de la casa (no negociables)

- **Jamás datos de casos reales.** Ni nombres, ni DNI, ni carátulas reales, ni
  hechos identificables — ni siquiera "anonimizados". El `.gitignore` es
  denegar-por-defecto justamente por esto; no lo debilites.
- **Fuente primaria o marca de verificación.** Toda afirmación normativa o
  jurisprudencial nueva debe estar verificada en fuente primaria (SAIJ, InfoLeg,
  boletines oficiales) con su cita, o marcada `🔲 verificación pendiente`. Nunca
  se inventa una cita: es la regla número uno del alma del agente (`soul.md`).
- **Alerta normativa.** Si tocás una zona de reforma reciente o vigencia discutida,
  marcá `⚠️` con la fecha de tu verificación.
- **Español.** El proyecto se escribe en español rioplatense neutro; los términos
  procesales, en el uso de la jurisdicción que corresponda.
- **MIT.** Todo aporte queda bajo la licencia del repo.

## Flujo

1. Fork → rama con nombre descriptivo (`ficha-cordoba`, `fix-plazos-feria`).
2. PR con: qué agrega, qué fuentes primarias usaste y qué queda `🔲`.
3. Los PR que agregan afirmaciones jurídicas sin fuente se devuelven con cariño.

## Código de conducta

Sé profesional y constructivo. Acá se discuten normas y métodos, no personas.
El proyecto asiste a quienes defienden a los más vulnerables: ese es el estándar
de seriedad que se espera de cada aporte.
