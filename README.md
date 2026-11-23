# Kaprekar DigitalX

> **Consultora de Inteligencia de Conversión & Arquitectura de Decisiones**
> IA Agéntica · GEO/AEO · Human-in-the-Loop · First-Party Data

Web corporativa de Kaprekar DigitalX (Bilbao, País Vasco). Construida como
**single-file HTML** — cero dependencias, cero build: CSS + JS vanilla inline.

## 🌐 Producción
- Dominio: **https://kaprekar.ai**
- Email: **digitalx@kaprekar.ai**

## 📁 Estructura

| Archivo | Función |
|---|---|
| `index.html` | Sitio completo (16 secciones + Test IA + Calculadora ROI) |
| `CNAME` | Dominio custom GitHub Pages (`kaprekar.ai`) |
| `robots.txt` | Crawl rules + sitemap |
| `sitemap.xml` | Índice de URLs para LLMs/crawlers |
| `.nojekyll` | Desactiva Jekyll (entrega estática pura) |

## 🚀 Despliegue (GitHub Pages)

1. **Settings → Pages** → Source: *Deploy from a branch* → `main` / `(root)`
2. DNS en tu registrador (apex `kaprekar.ai`):
   - `A` → `185.199.108.153` · `185.199.109.153` · `185.199.110.153` · `185.199.111.153`
   - `CNAME www` → `familyconnexai.github.io`
3. Espera a que GitHub emita el certificado y activa **Enforce HTTPS**

## 🧩 Features clave

- Dual theme tipográfico (Sora ↔ Cormorant Garamond + Syne) con persistencia y carga diferida
- Marquee bidireccional con hover-pause
- Test de Madurez IA (Gartner Maturity Model) + Calculadora ROI/ROAS interactivas
- JSON-LD ProfessionalService + FAQPage (protocolo Answer-First para LLMs)
- Preloader v3 (6 capas failsafe) · cookie banner GDPR · luz especular · tilt 3D · back-to-top
- Accesibilidad: skip-link, focus-visible, targets 44px, reduced-motion

## ⚠️ Pendientes

- [ ] URLs reales: Aviso Legal / Privacidad / Cookies (footer)
- [ ] URL LinkedIn (footer · Dirección Estratégica)
- [ ] `og:image` 1200×630
- [ ] Analytics sin PII (opcional, tras consentimiento)

---

*6174 — la constante que reorganiza el caos.*