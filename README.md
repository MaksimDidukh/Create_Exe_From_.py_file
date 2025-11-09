WIN+R -> CMD + PASTE↓
!"app.py  <---------write path file  ↓
pyinstaller --onefile --windowed app.py
upx --best --compress-icons=0 dist\GlassMenuPro.exe
