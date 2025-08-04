# HomeAssistant stuff

This repo contains various HomeAssistant scripts, automations etc.

- **MeshCore_Public-TestResponder.yml** (Automation)
  Met dank aan AWolden: https://github.com/awolden/meshcore-ha.
  1. Installeer via HACS deze plugin in HomeAssistant: meshcore-ha
  2. Voeg een node toe aan HomeAssistant via deze plugin
  3. Maak een automation aan met de code in het MeshCore_Public-TestResponder.yml bestand
     
  Wanneer dan in het MeshCore public channel een bericht gestuurd wordt met de tekst: test, antwoordt de node die aan HomeAssistant is gekoppeld met een bericht.
