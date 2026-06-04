Saaligatoren Supabase-Version mit verschlüsseltem Gewicht

Dateien:
- Formularseite.html
- Adminseite.html
- saaligatoren_logo.PNG

Ablauf:
1. Formularseite speichert das Gewicht verschlüsselt in weight_encrypted.
2. Das Klargewicht wird nicht mehr in Supabase gespeichert.
3. Adminseite fragt den privaten Schlüssel ab und entschlüsselt nur lokal im Browser.
4. Das Gewicht wird nicht angezeigt.

Wichtig:
- Den privaten Schlüssel sicher speichern.
- Ohne privaten Schlüssel ist keine Berechnung möglich.
- Alte Klartext-Testdaten bitte löschen.
