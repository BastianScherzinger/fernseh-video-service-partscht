# 🏗️ Build-Dokumentation: Fernseh-Video-Service Partscht

**Erstellt:** 02.06.2026 03:51  
**Stadt:** Schotten  
**Branche:** Elektriker  
**Projekt-Typ:** 📄 Landing Page  
**Score:** 100/100  
**Einnahmen-Potenzial:** 450–700€  
**Build-Runden:** 5  

---

## Referenz-Projekt
- Kopiert von: `hg-fluegel`
- Typ: landing

## Digitale Ausgangslage
- Website vorhanden: ❌ Keine
- Mobile-optimiert: ❌
- Bilder: ❌
- Social Media: ❌
- Verbesserungspunkte:
  - 🔧 Elektriker — idealer Privatkunde, zahlt gut
  - ❌ Keine Website — maximales Potenzial

## Build-Runden
- **Runde 1:** Architektur, Models, Views, Templates, SEO, Security, Deploy-Config
- **Runde 2:** Code-Review + kritische Fixes
- **Runde 3:** SEO-Vertiefung + Performance
- **Runde 4:** Conversion-Optimierung + Security-Hardening
- **Runde 5:** Finaler Check + Deployment-Verifikation

## Lokale Entwicklung
```bash
cd fernseh_video_service_partscht
pip install -r requirements.txt
cp .env.example .env  # Werte eintragen!
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## Pflicht-ENV-Vars
```
SECRET_KEY=  # bereits gesetzt
DEBUG=False  # bereits gesetzt
CONTACT_EMAIL=info@fernseh-video-service-partscht.de
RESEND_API_KEY=  # resend.com → kostenloses Konto
PGDATABASE=  # Neon.tech DB
PGUSER=
PGPASSWORD=
PGHOST=
```


## Nächste Schritte
1. ENV-Vars im Railway-Dashboard befüllen
2. Echte Firmenbilder hochladen
3. Texte + Öffnungszeiten anpassen
4. Google Search Console einrichten
5. Kunde übergeben 💰

---
*Gebaut von Django Dream Team 🤖 — github.com/django-dream-team*