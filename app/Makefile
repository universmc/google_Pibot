# Define variables
NODE_ENV = development
NODE_PORT = 5144
NODE_APP = index.js

COMMANDE1_MSG="✨ Menu ✨"

work_MSG="✨ Lancement de workplan.json✨"
CTRL_MSG="✨ Lancement du contrôleur NES✨"
COMMANDE1_MSG="✨ Lancement de groq server✨"

groq:
	@echo "${bot_MSG}"
	@./telegram/groq.js

bot:
	@echo "${bot_MSG}"
	@./models.sh


ctrl:
	@echo "${CTRL_MSG}"
	@node ctrl.js

wp:
	@echo "${work_MSG}"
	@node workplan.js
map:
	@echo "${bot_MSG}"
	@npm run map

# Makefile pour mapper les boutons du contrôleur NES
.PHONY: bouton_a bouton_b bouton_start bouton_select map bot

bouton_a:
	@echo "🌴 Compiling project Bouton 🅰️  .. 🌴 🌴 .."

bouton_b:
	@echo "✨ DevOps bouton 🅱️  ✨"

bouton_start:
	@echo "🔷 Starting the server...🔷 "
	@./menu.sh

bouton_select:
	@echo "💾 Pausing process or displaying status...💾 "
menu:
	@echo "Welcom To cycliq Economical system."
	@echo""
	@echo"╔═════════════════════════════════════╗     ╔═════════════════════════════════════════════════════════════════════╗"
	@echo"╠═══════════ ✨ Pi Console ═══════════╣     ║  [💫] [💬] [📚] [🌌] [✨] [⚡️] [💰] [🌴] [📱] [📡]              [🛰]║"
	@echo"║                                     ║     ╠═════════════════════════════════════════════════════════════════════╣"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"║                                     ║     ║                                                                     ║"
	@echo"╠═════════════════════════════════════╣     ╠═════════════════════════════════════════════════════════════════════╣"
	@echo"║(∏)                                  ║     ║[💻.📱]:/<                                                        /%>║"
	@echo"╚═════════════════════════════════════╝     ╚═════════════════════════════════════════════════════════════════════╝"	
	@echo""

MAGIC_TARGETS := codex build rep file script clean

dev:

all: $(MAGIC_TARGETS)

update:
	@echo "✨ Mise en état du dossier sur github✨"
	@git add .
	@git commit -m "test"
	@git push
	@echo "✨ Mise à jour terminée✨"

init: gantt phase1 phase2 phase3 phase4 phase5 phase6 phase7 phase8
# Magic COMPILER groq quantum
gantt:
	@echo "initialisation de l'instance"
	@git clone auto

gant1:
	@echo "phase de conception"
	@node mission.js

gant2:
	@echo "phase de configuration"
	@node configuration.js

gant3:
	@echo "phase d'entrainnement du model IA"
	@node models.js

gant4:
	@echo "phase de gestion et iteration du frontend"
	@git clone src.js
	
gant5:
	@echo "phase de gestion et iteration du backend"
	@node srv.js


gant6:
	@echo "phase de test et debugage"
	@node data.js

gant7:
	@echo "phase de validation documentation"
	@node models/modelcss.js

gant8:
	@echo "phase d'affiliation et contribution"
	@node models/modelcss.js

server:
	@node srv/Telegram/server.js
	@echo "Unleashing quantum Magic Mafile with every script we shape" 
# Ouvrez-vous aux dimensions cachées
clean-r:
	@echo "Returning the quantum realm to pristine state"
	@rm -rf data/* build/* src/* data/*

clean-R:
	@echo "Unweaving the fabric, a celestial fate"@rm -rf output/ build/ src/ data/

clean: clean-r clean-R