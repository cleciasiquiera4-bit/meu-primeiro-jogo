<!doctype html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Jogo da Clecia — Ganhar Moedas</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;margin:0;min-height:100vh;display:flex;justify-content:center;align-items:center;background:#153a7a;color:#fff;padding:18px}
    .wrap{width:min(520px,100%);text-align:center}
    .card{background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.18);border-radius:18px;padding:14px;backdrop-filter:blur(6px)}
    #grid{display:grid;grid-template-columns:repeat(6,1fr);gap:8px;margin-top:14px}
    .c{aspect-ratio:1/1;border-radius:14px;background:rgba(255,255,255,.16);display:flex;align-items:center;justify-content:center;font-size:22px;user-select:none}
    .hud{display:flex;gap:10px;justify-content:center;flex-wrap
