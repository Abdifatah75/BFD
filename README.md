[README.md](https://github.com/user-attachments/files/22733834/README.md)

# Bensheimer Fahrdienst – Weekly Payroll App (Streamlit)

This is a simple **no-code-like** web app to record Uber income/expenses **per week** and export an Excel report just like your template.

## Features
- Data entry form (Einnahme/Ausgabe, Unterkategorie, Betrag, Zahlungsart, Date)
- Auto-calculates **Week number** (ISO week), **Month**, **Year**
- Weekly report: 
  - Umsatz ohne Tipp, Tipp, Umsatz mit Tipp
  - Anteil Fahrer 40% ohne Tipp, Anteil Fahrer mit Tipp
  - Barzahlung, Tanken, Sozial Abgabe, Ausgaben gesamt
  - Verdienen (Privatfahrten, Uber Überweisung, Uber Bar)
  - Ich bekomme noch
- Export Excel matching your **WEEKLY template**

## One‑click Deploy (Streamlit Community Cloud – FREE)
1. Create a **GitHub repo** and upload these files (all from this folder).
2. Go to https://share.streamlit.io
3. Sign in with GitHub → **New app** → select your repo → main branch → **app.py**.
4. Click **Deploy**. That’s it 👍

> **Note**: Streamlit Cloud does **not persist files** on restarts.
> Use **Download Backup** (CSV) and **Upload Restore** inside the app to save/restore your data.
> If you want persistent storage (Google Sheets), we can add this later.

## Local run
```bash
pip install -r requirements.txt
streamlit run app.py
```
