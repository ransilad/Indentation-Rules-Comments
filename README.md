# Indentation-Rules-Comments

Para configurar el **Reindent** de Sublime Text:
- Agregar un atajo de la siguiente manera (Key Bindings):

![](https://lh3.googleusercontent.com/Dj_i8mPtcCz6vWaInwQ2nwuLhJHgpI3EBlNIUFoE8VnHL4wmN6avsq8GV3TaWZ25fs6q1fQWK9JV9yg=w1920-h895)
```
[
	{ "keys": ["super+alt+ctrl+r"], "command": "reindent"}
]
```
- Cuando en el código existen comentarios, tiende a dañarse la identación, para ello hay que ir o crear la carpeta `Librería ▸ Application Support ▸ Sublime Text 3 ▸ Packages ▸ Default` y agregar un nuevo archivo con el nombre `Indentation Rules - Comments.tmPreferences`
```
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple Computer//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
    <key>scope</key>
    <string>comment</string>
    <key>settings</key>
    <dict>
        <key>preserveIndent</key>
        <false/>
    </dict>
</dict>
</plist>
```
