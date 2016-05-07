# Module-Remote-Relay
Module Remote Relay for Svxlink to drive 4 relays by DTMF Code

RemoteRelay.tcl  -> /usr/share/svxlink/events.d\
ModuleRemoteRelay -> /usr/share/svxlink/modules.d\

Les sons sont à mettre dans le repertoire: /usr/share/svxlink/sounds/repertoire langue/

Par exemple pour le français: /usr/share/svxlink/sounds/fr_FR/

Un repertoire RemoteRelay dans le repertoire langue:

Par exemple pour la langue française: /usr/share/svxlink/sounds/fr_FR/RemoteRelay

Vous avez besoin des sons suivants:

name.wav -> le nom du module, svxlink dira name.wav activé

relay1off.wav   dit: Relais 1 off
relay2off.wav
relay3off.wav
relay4off.wav

relay1on.wav dit: Relais 1 on
relay2on.wav
relay3on.wav
relay4on.wav
 
relay1pulse.wav: dit Relais 1 impulsion
relay2pulse.wav
relay3pulse.wav
relay4pulse.wav
