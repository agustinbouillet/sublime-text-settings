# sublime-text-settings
## Compilación personal de paquetes para sublime text

### Pasos
1. Clonar el directorio Users en: `/Users/agustinbouillet/Library/Application Support/Sublime Text 3/Packages`

```bash
cd /Users/agustinbouillet/Library/Application Support/Sublime Text 3/Packages
git clone https://github.com/agustinbouillet/sublime-text-settings.git User
```

2. Instalar Package Control
https://packagecontrol.io/installation#st3

3. Crear alias `subl`

```
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sublimebash

```

Crear un alias en `~/.profile`, Linux (Mint) 

```bash
alias subl = /opt/sublime_text/sublime_text
```

## Configuración Linux

### Comentarios

```json
[
    { "keys": ["ctrl+keypad_divide"], "command": "toggle_comment", "args": { "block": false } },
    { "keys": ["ctrl+shift+keypad_divide"], "command": "toggle_comment", "args": { "block": true } },   
]
```
