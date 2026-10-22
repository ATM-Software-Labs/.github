<p align="center">
  <strong>ATM Software Labs</strong><br/>
  Proyectos personales de Alberto Trujillo Mingorance, técnico de sistemas en Barcelona.<br/>
  <em>Personal projects by Alberto Trujillo Mingorance, a systems technician in Barcelona.</em>
</p>

<p align="center">
  <a href="https://labs.trujillomingorance.com"><b>labs.trujillomingorance.com</b></a> ·
  <a href="https://alberto.trujillomingorance.com">Portfolio</a> ·
  <a href="mailto:alberto@trujillomingorance.com">Email</a>
</p>

---

Aquí está el código de las webs y herramientas que publico en `trujillomingorance.com`. Las mantengo yo solo, en mi tiempo libre, sobre los planes gratuitos de Cloudflare (Pages, Workers, D1 y KV). El acceso interno usa Microsoft Entra ID con SSO, y cada repositorio explica en su README qué hace, cómo se despliega y qué limitaciones tiene.

## Proyectos

| Proyecto | Qué es | Web |
|---|---|---|
| [NutriFit](https://github.com/ATM-Software-Labs/nutrifit) | Seguimiento de calorías y macros con análisis de fotos por IA. PWA y APK | [nutri.trujillomingorance.com](https://nutri.trujillomingorance.com) |
| [Trujillo Guides](https://github.com/ATM-Software-Labs/trujillo-guides) | Guías prácticas de sistemas: Cloudflare, DNS, correo e identidad | [guides.trujillomingorance.com](https://guides.trujillomingorance.com) |
| [Rewrite](https://github.com/ATM-Software-Labs/rewrite-ai) | Editor para reescribir, corregir y traducir textos con IA | [rewrite.trujillomingorance.com](https://rewrite.trujillomingorance.com) |
| [INVEST](https://github.com/ATM-Software-Labs/invest-platform) | Consulta y comparación de acciones, ETF y cripto. No es asesoramiento financiero | [invest.trujillomingorance.com](https://invest.trujillomingorance.com) |
| [ATM Tools](https://github.com/ATM-Software-Labs/atm-tools) | Utilidades que funcionan en el navegador, sin subir nada a un servidor | [tools.trujillomingorance.com](https://tools.trujillomingorance.com) |
| [FocusGuard](https://github.com/ATM-Software-Labs/focusguard-saas) | Panel de filtrado DNS sobre Cloudflare Zero Trust Gateway | [focusguard.trujillomingorance.com](https://focusguard.trujillomingorance.com) |
| [AI Studio](https://github.com/ATM-Software-Labs/trujillo-ai-studio) | Chat con varios modelos, bot de Discord y API compatible con OpenAI en un Worker | [ai.trujillomingorance.com](https://ai.trujillomingorance.com) |
| [ATM Labs](https://github.com/ATM-Software-Labs/atm-labs-hub) | Directorio de los servicios y su estado | [labs.trujillomingorance.com](https://labs.trujillomingorance.com) |
| [Portfolio](https://github.com/ATM-Software-Labs/portfolio) | CV y experiencia | [alberto.trujillomingorance.com](https://alberto.trujillomingorance.com) |
| [domain-root](https://github.com/ATM-Software-Labs/domain-root) | Web del dominio raíz | [trujillomingorance.com](https://trujillomingorance.com) |
| [OpenSentinel](https://github.com/ATM-Software-Labs/open-sentinel) | Aviso de arranque y panel local para un PC con Windows | Se instala en local |

## Cómo está montado

- **Hosting:** Cloudflare Pages y Workers, con D1 y KV para datos.
- **Acceso:** sesión compartida entre subdominios e inicio de sesión interno con Microsoft Entra ID (OIDC con PKCE).
- **Correo:** Cloudflare Email Routing con SPF, DKIM y DMARC.
- **Licencias:** la mayoría de repositorios usan MIT; cada uno indica la suya.

## Contacto

¿Has encontrado un fallo o un problema de seguridad? Abre un issue en el repositorio o escribe a [alberto@trujillomingorance.com](mailto:alberto@trujillomingorance.com).

---

<p align="center"><sub>© 2026 ATM Software Labs</sub></p>
