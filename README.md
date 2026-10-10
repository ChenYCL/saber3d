# Saber 3D v2
ES modules can't load from file://, so serve the folder first:
    cd v2 && python3 -m http.server 8778     # then open http://127.0.0.1:8778/
Works fully offline (three.js vendored). Query modes: ?demo=idle  ?demo=attack  ?demo=victory  ?bench=1
