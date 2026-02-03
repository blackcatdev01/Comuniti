# Comuniti
El experimento donde tú eres el protagonista. ¡Deja tu huella




#!/bin/bash

# --- Configuración de Colores ---
G='\033[0;32m' # Verde
C='\033[0;36m' # Cyan
B='\033[0;34m' # Azul
W='\033[1;37m' # Blanco Brillante
R='\033[0;31m' # Rojo
NC='\033[0m'    # Sin Color

# --- Lógica Simple ---
USER_HOST=$(whoami)
OS=$(uname -s)
DATE=$(date +'%Y-%m-%d %H:%M')

clear

# --- Arte ASCII ---
echo -e "${C}"
echo "  ██████╗ ██████╗ ███╗   ███╗██╗   ██╗███╗   ██╗██╗████████╗██╗"
echo " ██╔════╝██╔═══██╗████╗ ████║██║   ██║████╗  ██║██║╚══██╔══╝██║"
echo " ██║     ██║   ██║██╔████╔██║██║   ██║██╔██╗ ██║██║   ██║   ██║"
echo " ██║     ██║   ██║██║╚██╔╝██║██║   ██║██║╚██╗██║██║   ██║   ██║"
echo " ╚██████╗╚██████╔╝██║ ╚═╝ ██║╚██████╔╝██║ ╚████║██║   ██║   ██║"
echo "  ╚═════╝ ╚═════╝ ╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝   ╚═╝   ╚═╝"
echo -e "${NC}"

# --- Información del Proyecto (Estilo Neofetch) ---
echo -e "${G}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━${NC}"
echo -e "${C}  USER${NC}      @ ${W}${USER_HOST}${NC}"
echo -e "${C}  PROJECT${NC}   @ ${W}Comuniti (v1.0.0-beta)${NC}"
echo -e "${C}  OS${NC}        @ ${W}${OS}${NC}"
echo -e "${C}  STATUS${NC}    @ ${G}Experimental / Open Source${NC}"
echo -e "${C}  DATE${NC}      @ ${W}${DATE}${NC}"
echo -e "${C}  LICENSE${NC}   @ ${B}MIT (Free to use)${NC}"
echo -e "${G}━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━${NC}"

# --- Mensaje de Acción ---
echo -e "${W}  ¿Quieres dejar tu huella?${NC}"
echo -e "  1. Haz un Fork del repo."
echo -e "  2. Añade tu nombre en ${C}muro.md${NC}."
echo -e "  3. Envía el Pull Request."
echo ""
echo -e "${R}  [!] El experimento ha comenzado...${NC}"
echo ""






# 🧪 Proyecto: COMUNITI (Experimento de Código Abierto)

Este no es un proyecto normal. Es un **experimento colectivo** para ver qué tan lejos podemos llevar la personalización de la terminal. 

### 🧬 Objetivo del Experimento:
Que cada colaborador cree un script único que represente su identidad digital.

### 🔬 ¿Cómo participar en el experimento?
1. Forkea el repo.
2. Crea tu archivo en `/experimentos/tu_nombre.sh`.
3. veamos asta donde llega 