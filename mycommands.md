# MIS COMANDOS ÚTILES - PABLO

## 🎵 MÚSICA
- ytm italo disco mix         → Reproducir música de YouTube
- ytm patrick cowley           → Buscar artista específico
- ytm synthwave 80s            → Por género

Controles mientras reproduce:
- q o Ctrl+C  → Salir
- Espacio     → Pausa/Play
- 9 / 0       → Bajar/Subir volumen
- < / >       → Canción anterior/siguiente

## 📦 FLATPAK (Apps)
- flatpak list                 → Ver apps instaladas
- flatpak install flathub NOMBRE → Instalar app
- flatpak uninstall NOMBRE     → Desinstalar
- flatpak update               → Actualizar todas las apps

## 🔧 SISTEMA FEDORA
- sudo dnf update              → Actualizar sistema
- sudo dnf install PROGRAMA    → Instalar programa
- sudo dnf remove PROGRAMA     → Desinstalar
- htop                         → Ver procesos/recursos
- which COMANDO                → Ver dónde está instalado algo

## 📁 ARCHIVOS
- ls -la                       → Listar archivos con detalles
- cd CARPETA                   → Entrar a carpeta
- cd ..                        → Volver atrás
- pwd                          → Ver dónde estoy
- cp origen destino            → Copiar archivo
- mv origen destino            → Mover/renombrar
- rm archivo                   → Borrar archivo

## 🔍 ÚTILES
- mycommands                   → Ver esta lista
- history                      → Ver historial de comandos
- Ctrl+R                       → Buscar en historial

## 🎸 MÁS MÚSICA - Rock/New Wave 80s
- ytm paul mccartney 80s       → Paul solista era 80s
- ytm george harrison          → George Harrison solista
- ytm pink floyd 80s           → Pink Floyd (The Wall, etc)
- ytm genesis 80s              → Genesis con Phil Collins
- ytm the police               → The Police, Sting
- ytm new wave 80s rock        → Mix new wave/rock 80s
- ytm depeche mode new order   → Synth-pop británico
- ytm joy division the cure    → Post-punk/new wave
- ytm progressive rock 70s 80s → Rock progresivo
- ytm beatles best hits        → Los Beatles clásicos
- ytm fleetwood mac greatest hits → Fleetwood Mac clásicos
- ytm stevie nicks greatest hits → Stevie Nicks solo
- ytm depeche mode best → Depeche Mode synthpop
- ytm new order best → New Order post-punk/electrónico
- ytm the cure greatest hits → The Cure era 80s
- ytm kraftwerk best → Kraftwerk electrónica alemana
- ytm tears for fears greatest hits → Tears for Fears new wave
- ytm pet shop boys best → Pet Shop Boys synth-pop

Bonus:
- ytm talking heads
- ytm david bowie 80s
- ytm tears for fears
- ytm simple minds


## 📝 NANO - Editor de texto
- Marcar inicio: Ctrl + Shift + 6 (o Alt + A) → Inicia selección
- Movete con flechas → Selecciona texto
- Cortar lo marcado: Ctrl + K → Corta todo lo seleccionado

## 🔐 BITWARDEN
- bwpass → Copia master password de Bitwarden al portapapeles

## 📅 CALCURSE - Calendario Terminal

### Tecnología:
- calcurse → calendario en terminal con notificaciones
- systemd user timer → chequea eventos cada 1 minuto
- dunstify → notificaciones gráficas
- Script: ~/.local/bin/calcurse-check.sh

### Comandos básicos:
- calcurse → abrir calendario interactivo
- calcurse -a → ver agenda del día
- calcurse --next → ver próximo evento
- calcurse -t → ver lista TODO

### Navegación dentro de calcurse:
- A → agregar evento (appointment)
- T → agregar TODO
- D → eliminar item
- E → editar item
- S → guardar cambios
- Q → salir
- TAB → cambiar entre paneles
- G → ir a fecha específica
- ! → marcar como importante

## 📅 CALCURSE

### Navegación
- G → Ir a hoy (mayúscula)
- g → Ir a fecha específica
- TAB → Cambiar entre paneles (Calendar/Appointments/TODO)
- Flechas → Navegar día/semana
- h,j,k,l → Navegación estilo Vim

### Comandos desde terminal
- calcurse -a → Ver appointments de hoy
- calcurse -d 3 → Ver próximos 3 días (o -2 para pasados)
- calcurse -t → Ver TODO list

### Dentro de calcurse
- a → Agregar appointment/evento
- t → Agregar TODO
- s → Guardar (save)
- d → Borrar evento seleccionado
- e → Editar evento
- r → Ver/editar recurrencia
- v → Ver detalles del evento
- q → Salir
- ? → Ayuda
- :help keys → Ver todos los atajos

### Recurrencia
- Al crear evento, presionar r
- d → diario, w → semanal, m → mensual, y → anual
- Frecuencia 1 = cada día/semana/mes/año

### Búsqueda en calcurse
- Ctrl+F → Buscar
- n → Siguiente resultado
- N → Resultado anterior

### Crear evento:
- A → fecha (Enter=hoy) → hora inicio → duración (+5) → descripción → repetir (1=una vez)

### Gestionar notificaciones:
- systemctl --user status calcurse-notify.timer → ver estado
- systemctl --user restart calcurse-notify.timer → reiniciar
- journalctl --user -u calcurse-notify.service -f → ver logs en vivo

## 🖥️ GNOME WORKSPACES - Configuración

### Configurar workspaces fijos:
- gsettings set org.gnome.mutter dynamic-workspaces false → desactivar dinámicos
- gsettings set org.gnome.desktop.wm.preferences num-workspaces 4 → definir 4 fijos
- gsettings get org.gnome.mutter dynamic-workspaces → verificar config
- gsettings get org.gnome.desktop.wm.preferences num-workspaces → ver cantidad

### Instalar extensión para nombres:
- flatpak install flathub com.mattjakeman.ExtensionManager → gestor de extensiones
- flatpak run com.mattjakeman.ExtensionManager → abrir gestor
- Buscar "Workspace Indicator" e instalar

### Atajos de teclado:
- Super + PgUp/PgDown → cambiar de workspace
- Super + Shift + PgUp/PgDown → mover ventana actual a otro workspace
- Super + [1-4] → ir directo al workspace 1, 2, 3 o 4
- Super → ver todos los workspaces (overview)

### Volver a dinámicos:
- gsettings set org.gnome.mutter dynamic-workspaces true → reactivar dinámicos

## 💬 WHATSAPP CLI (mudslide)
- mudslide send me "texto" → enviar mensaje a mi mismo
- mudslide send 5491112345678 "texto" → enviar a contacto
- mudslide login → reconectar WhatsApp



## 📱 WHATSAPP CLI

- `wsend chela "mensaje"` → Enviar WhatsApp a mamá
- `wsend andres "mensaje"` → Enviar WhatsApp a Andrés
- `wsend pato "mensaje"` → Enviar WhatsApp a Pato
- `wsend pali "mensaje"` → Enviar WhatsApp a Pali
- `wsend saulo "mensaje"` → Enviar WhatsApp a Saulo (mi otro celu)
- `wsend yo "mensaje"` → Enviar WhatsApp a mí mismo
- `wme "mensaje"` → Alias para enviar a mí mismo
- `nchat` → Abrir WhatsApp en terminal (interactivo)
- `nchat --send "549..." "mensaje"` → Enviar mensaje por número
- `Ctrl+N` → Buscar chat en nchat
- `Ctrl+Q` → Salir de nchat


## 📱 WHATSAPP CLI - SETUP COMPLETO

### Enviar mensajes:
- `wsend chela "mensaje"` → Enviar a mamá
- `wsend andres "mensaje"` → Enviar a Andrés  
- `wsend saulo "mensaje"` → Enviar a Saulo (mi otro celu)
- `nchat --send "549..." "mensaje"` → Enviar por número

### Cliente interactivo (tmux + nchat):
- `tmux a` → Abrir WhatsApp en terminal
- `Ctrl+B` luego `D` → Desconectar (sigue corriendo)
- `Ctrl+N` → Buscar chat en nchat
- `Ctrl+Q` → Salir de nchat

### Sistema de notificaciones:
- `systemctl --user status whatsapp-notify.timer` → Ver estado
- `systemctl --user stop whatsapp-notify.timer` → Detener notificaciones
- `systemctl --user start whatsapp-notify.timer` → Activar notificaciones
- `journalctl --user -u whatsapp-notify.service -f` → Ver logs
- `python3 ~/whatsapp-notify.py` → Chequeo manual

### Útiles:
- `tmux ls` → Ver sesiones activas
- `tmux kill-session -t whatsapp` → Cerrar sesión WhatsApp
- Script notificaciones: `~/whatsapp-notify.py`


## 🎧 AUDIO DE WHATSAPP

- `wa-audio` → Reproducir último audio de WhatsApp descargado


## 🎤 GRABAR Y ENVIAR AUDIO WHATSAPP

- `ffmpeg -f pulse -i default ~/audio-wa.ogg` → Grabar audio (Ctrl+C para parar)
- `mudslide send-file 5491160394994 ~/audio-wa.ogg` → Enviar audio a Saulo
- `~/scripts/wa-enviar-audio.sh` → Script completo: graba + envía automáticamente
