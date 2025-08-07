# 🔧 Funktionsliste Agentensystem

## Muss-Funktionen
- [ ] Neue Aufgabe speichern (`task_core.add_task(title, deadline, priority)`)
- [ ] Erinnerung setzen (`reminder.set(time, task_id)`)
- [ ] Konversation speichern/abfragen (`memory.store`, `memory.retrieve`)
- [ ] Prompt dynamisch erzeugen (mit Kontext)
- [ ] Output validieren & interpretieren (`output_parser`)

## Nice-to-Have
- [ ] Agent-Handoff zwischen Modulen (z. B. TaskManager → Reminder)
- [ ] Logging aller Agenten-Aktionen
- [ ] Agentenstatus als JSON abrufbar für Frontend

> Diese Datei dient der Planung und Kommunikation zwischen Modulen.
