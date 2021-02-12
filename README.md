tccsh-completion  es un plugin para autompletar la salida de tmux-cssh, por lo que el nombre del pluging debe ser igual al  nombre con el que se ejecuta el comando o script
Para instalar, copie el directorio $ZSH_HOME/custom/plugin, por ejemplo /.oh-my-zsh/custom/plugins/tmux-cssh-completion. 

Asegurece de tener el compinit activo, para ello dentro del zshrc  agregar la linea 
# Activar autocompletado custom
autoload -Uz compinit && compinit 
