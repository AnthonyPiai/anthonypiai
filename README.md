<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Design que vende | Sites, criativos e vídeos com IA em até 24h</title>
  <meta name="description" content="Sites, criativos, edição e vídeos com IA para o seu Instagram vender mais. Entrega em até 24h ou 2 dias úteis. Chame no WhatsApp." />
  <meta property="og:title" content="Seu Instagram vendendo mais com design profissional em 24h" />
  <meta property="og:description" content="Sites, criativos, edição e vídeos com IA. Entrega em até 24h ou 2 dias úteis." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#0a0a0a" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230a0a0a'/%3E%3Ccircle cx='46' cy='46' r='7' fill='%23e10600'/%3E%3C/svg%3E" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,500;0,9..144,700;1,9..144,500&family=Inter+Tight:wght@400;500;600;700&display=swap" rel="stylesheet" />
  <style>
/* =========================================================
   Landing page — Preto, Vermelho e Branco
   Fontes: Fraunces (títulos, serifada premium) + Inter Tight (texto)
   ========================================================= */
:root {
  --black: #0a0a0a;
  --ink: #141414;
  --ink-2: #1d1d1d;
  --line: #2a2a2a;
  --red: #e10600;
  --red-2: #ff2a1f;
  --red-deep: #9e0400;
  --white: #ffffff;
  --paper: #f6f4f1;
  --muted: #8f8f8f;
  --text: #121212;
  --radius: 18px;
  --shadow: 0 20px 60px -20px rgba(0, 0, 0, .35);
  --serif: "Fraunces", Georgia, "Times New Roman", serif;
  --sans: "Inter Tight", system-ui, -apple-system, "Segoe UI", Roboto, sans-serif;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; -webkit-text-size-adjust: 100%; }
html { overflow-x: clip; }
body { margin: 0; font-family: var(--sans); color: var(--text); background: var(--white); line-height: 1.55; overflow-x: clip; }
img, svg { display: block; max-width: 100%; }
a { color: inherit; }
h1, h2, h3 { margin: 0; }
em { font-style: italic; color: var(--red); }
.skip { position: absolute; left: -999px; top: 8px; background: var(--red); color: #fff; padding: 8px 12px; z-index: 99; }
.skip:focus { left: 8px; }
:focus-visible { outline: 3px solid var(--red-2); outline-offset: 3px; }

.wrap { width: 100%; max-width: 1180px; margin: 0 auto; padding: 0 16px; }
.narrow { max-width: 820px; }
.center { text-align: center; }
.i { width: 1.15em; height: 1.15em; flex: none; }
.i--red { color: var(--red); }
.tiny { font-size: .82rem; color: var(--muted); }

/* ---------- Botões ---------- */
.btn {
  --bg: var(--red); --fg: #fff;
  display: inline-flex; align-items: center; justify-content: center; gap: .55em;
  background: var(--bg); color: var(--fg); text-decoration: none; font-weight: 600;
  padding: .85em 1.35em; border-radius: 999px; border: 2px solid var(--bg);
  transition: transform .15s ease, box-shadow .2s ease, background .2s ease; cursor: pointer; font: inherit; font-weight: 600;
  box-shadow: 0 10px 30px -10px rgba(225, 6, 0, .6);
}
.btn:hover { transform: translateY(-2px); background: var(--red-2); border-color: var(--red-2); }
.btn--lg { font-size: 1.05rem; padding: 1em 1.6em; }
.btn--sm { font-size: .88rem; padding: .55em 1em; box-shadow: none; }
.btn--ghost { --bg: transparent; --fg: #fff; border-color: rgba(255,255,255,.25); box-shadow: none; }
.btn--ghost:hover { background: rgba(255,255,255,.08); border-color: #fff; }
.btn--white { --bg: #fff; --fg: var(--red-deep); box-shadow: 0 10px 30px -10px rgba(0,0,0,.4); }
.btn--white:hover { background: var(--paper); border-color: var(--paper); }
.btn--dark { --bg: var(--black); --fg: #fff; width: 100%; box-shadow: none; }
.btn--dark:hover { background: #222; border-color: #222; }
.btn[disabled] { opacity: .6; pointer-events: none; }

/* ---------- Faixa promo ---------- */
.promo { background: var(--red); color: #fff; text-align: center; font-size: .9rem; font-weight: 600; padding: 9px 16px; }
.promo:empty { display: none; }
.promo b { background: #fff; color: var(--red); padding: 1px 8px; border-radius: 6px; margin: 0 4px; }

/* ---------- Topo ---------- */
.topbar { position: sticky; top: 0; z-index: 50; background: var(--black); color: #fff; border-bottom: 1px solid rgba(255,255,255,.06); }
.topbar__in { display: flex; align-items: center; justify-content: space-between; height: 64px; gap: 16px; }
.logo { font-family: var(--serif); font-weight: 700; font-size: 1.3rem; text-decoration: none; letter-spacing: -.01em; }
.logo::after { content: "."; color: var(--red); }
.nav { display: none; gap: 28px; font-size: .92rem; }
.nav a { text-decoration: none; color: rgba(255,255,255,.75); }
.nav a:hover { color: #fff; }
@media (min-width: 900px) { .nav { display: flex; } }

/* ---------- Hero ---------- */
.hero { background: radial-gradient(1000px 500px at 85% 10%, rgba(225,6,0,.28), transparent 60%), var(--black); color: #fff; padding: 48px 0 72px; overflow: hidden; }
.hero__grid { display: grid; gap: 48px; align-items: center; }
@media (min-width: 960px) { .hero__grid { grid-template-columns: 1.1fr .9fr; } .hero { padding: 80px 0 110px; } }
.eyebrow { text-transform: uppercase; letter-spacing: .16em; font-size: .74rem; font-weight: 600; color: rgba(255,255,255,.65); margin: 0 0 18px; }
.eyebrow--red { color: var(--red); }
.hero__title { font-family: var(--serif); font-weight: 500; font-size: clamp(2.3rem, 6.2vw, 4.3rem); line-height: 1.03; letter-spacing: -.025em; }
.hero__title em { color: var(--red-2); }
.hero__sub { font-size: clamp(1.02rem, 1.6vw, 1.2rem); color: rgba(255,255,255,.75); max-width: 560px; margin: 22px 0 30px; }
.hero__ctas { display: flex; flex-wrap: wrap; gap: 12px; }
.hero__note { display: flex; align-items: center; gap: 8px; color: rgba(255,255,255,.6); font-size: .9rem; margin-top: 18px; }

/* Celular */
.hero__visual { position: relative; display: grid; place-items: center; min-height: 460px; }
.phone { width: 260px; height: 530px; border-radius: 42px; background: #050505; padding: 12px; border: 1px solid #333; box-shadow: 0 40px 100px -20px rgba(225,6,0,.45), inset 0 0 0 2px #1a1a1a; transform: rotate(-4deg); position: relative; }
.phone__notch { position: absolute; top: 18px; left: 50%; width: 80px; height: 22px; background: #000; border-radius: 20px; transform: translateX(-50%); z-index: 2; }
.ig { background: #fff; border-radius: 32px; height: 100%; padding: 48px 12px 12px; overflow: hidden; color: #111; }
.ig__head { display: flex; align-items: center; justify-content: space-between; gap: 6px; }
.ig__avatar { width: 52px; height: 52px; border-radius: 50%; background: conic-gradient(var(--red), #111, var(--red)); padding: 3px; flex: none; position: relative; }
.ig__avatar::after { content: ""; position: absolute; inset: 3px; border-radius: 50%; background: #111; border: 2px solid #fff; }
.ig__stats { text-align: center; line-height: 1.1; }
.ig__stats b { display: block; font-size: .8rem; }
.ig__stats small { font-size: .6rem; color: #777; }
.ig__bio { margin: 12px 0; display: grid; gap: 5px; }
.ig__bio span { height: 7px; background: #e9e9e9; border-radius: 4px; }
.ig__bio .short { width: 55%; }
.ig__btn { background: var(--red); color: #fff; text-align: center; font-size: .7rem; font-weight: 700; padding: 7px; border-radius: 8px; margin-bottom: 10px; }
.ig__grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 3px; }
.t { aspect-ratio: 1; display: grid; place-items: center; font-family: var(--serif); color: #fff; font-size: .9rem; }
.t1, .t5, .t9 { background: var(--red); }
.t2, .t6, .t7 { background: #111; }
.t3 { background: linear-gradient(135deg, #111 50%, var(--red) 50%); }
.t4 { background: repeating-linear-gradient(45deg, #f1f1f1 0 6px, #ddd 6px 12px); }
.t8 { background: radial-gradient(circle at 30% 30%, var(--red) 25%, #111 26%); }
.t7 b { color: var(--red-2); }
.chip { position: absolute; display: flex; align-items: center; gap: 8px; background: #fff; color: #111; font-size: .82rem; padding: 10px 14px; border-radius: 14px; box-shadow: var(--shadow); white-space: nowrap; animation: float 6s ease-in-out infinite; }
.chip--a { top: 8%; left: 0; }
.chip--b { bottom: 22%; right: 0; background: var(--red); color: #fff; animation-delay: -2s; }
.chip--c { bottom: 2%; left: 4%; animation-delay: -4s; }
.dot { width: 8px; height: 8px; background: #22c55e; border-radius: 50%; box-shadow: 0 0 0 4px rgba(34,197,94,.2); }
@keyframes float { 50% { transform: translateY(-10px); } }
@media (max-width: 420px) { .chip { font-size: .72rem; padding: 8px 10px; } .phone { width: 230px; height: 470px; } }
@media (prefers-reduced-motion: reduce) { .chip { animation: none; } html { scroll-behavior: auto; } }

/* ---------- Credibilidade ---------- */
.cred { background: var(--ink); color: #fff; border-top: 1px solid var(--line); border-bottom: 1px solid var(--line); }
.cred__row { display: grid; grid-template-columns: repeat(2, 1fr); }
@media (min-width: 760px) { .cred__row { grid-template-columns: repeat(4, 1fr); } }
.cred__item { padding: 26px 12px; text-align: center; border-right: 1px solid var(--line); }
.cred__item:nth-child(2n) { border-right: 0; }
@media (min-width: 760px) { .cred__item:nth-child(2n) { border-right: 1px solid var(--line); } .cred__item:last-child { border-right: 0; } }
@media (max-width: 759px) { .cred__item:nth-child(-n+2) { border-bottom: 1px solid var(--line); } }
.cred__item b { display: block; font-family: var(--serif); font-size: clamp(1.7rem, 3.5vw, 2.3rem); color: var(--red-2); font-weight: 500; line-height: 1.1; }
.cred__item span { font-size: .85rem; color: rgba(255,255,255,.6); }

/* ---------- Seções ---------- */
.sec { padding: 80px 0; }
@media (min-width: 900px) { .sec { padding: 110px 0; } }
.sec--dark { background: var(--black); color: #fff; }
.sec--soft { background: var(--paper); }
.sec--red { background: linear-gradient(135deg, var(--red) 0%, var(--red-deep) 100%); color: #fff; }
.sec--red em { color: #fff; text-decoration: underline; text-decoration-thickness: 2px; text-underline-offset: 6px; }
.sec__head { max-width: 720px; margin-bottom: 44px; }
.h2 { font-family: var(--serif); font-weight: 500; font-size: clamp(1.9rem, 4.4vw, 3rem); line-height: 1.08; letter-spacing: -.02em; }
.lead { font-size: 1.1rem; color: inherit; opacity: .8; margin: 18px 0 28px; }
.sec__close { font-size: 1.15rem; margin-top: 36px; color: rgba(255,255,255,.8); }
.sec__close b { color: #fff; }
.split { display: grid; gap: 48px; align-items: center; }
@media (min-width: 900px) { .split { grid-template-columns: 1fr 1fr; } }

/* Problema */
.pains { list-style: none; padding: 0; margin: 36px 0 0; display: grid; gap: 14px; }
.pains li { display: flex; gap: 14px; align-items: flex-start; background: var(--ink); border: 1px solid var(--line); padding: 18px 20px; border-radius: var(--radius); font-size: 1.05rem; }
.pains .i { color: var(--red); margin-top: 3px; }

/* Ponte */
.bridge { display: grid; grid-template-columns: 1fr auto 1fr; align-items: stretch; gap: 10px; }
.bridge__col { border-radius: var(--radius); padding: 20px 16px; }
.bridge__col small { text-transform: uppercase; letter-spacing: .14em; font-size: .7rem; font-weight: 700; }
.bridge__col ul { list-style: none; padding: 0; margin: 12px 0 0; display: grid; gap: 10px; font-size: .92rem; }
.bridge__col li { display: flex; gap: 8px; align-items: flex-start; }
.bridge__col .i { margin-top: 3px; }
.bridge__col--from { background: var(--paper); color: #555; }
.bridge__col--from .i { color: #999; }
.bridge__col--to { background: var(--black); color: #fff; }
.bridge__col--to .i { color: var(--red-2); }
.bridge__arrow { display: grid; place-items: center; color: var(--red); }
@media (max-width: 560px) { .bridge { grid-template-columns: 1fr; } .bridge__arrow { transform: rotate(90deg); } }

/* Serviços */
.services { display: grid; gap: 14px; grid-template-columns: 1fr; }
@media (min-width: 640px) { .services { grid-template-columns: repeat(2, 1fr); } }
@media (min-width: 980px) { .services { grid-template-columns: repeat(3, 1fr); } }
.service { background: #fff; border-radius: var(--radius); padding: 26px; border: 1px solid #ebe7e2; display: flex; flex-direction: column; gap: 10px; transition: transform .2s, box-shadow .2s, border-color .2s; }
.service:hover { transform: translateY(-4px); box-shadow: var(--shadow); border-color: var(--red); }
.service__ico { width: 46px; height: 46px; border-radius: 12px; background: var(--black); color: var(--red-2); display: grid; place-items: center; }
.service h3 { font-family: var(--serif); font-weight: 500; font-size: 1.35rem; }
.service p { margin: 0; color: #555; flex: 1; }
.service__price { font-weight: 700; color: var(--text); font-size: .95rem; }
.service a { font-weight: 600; color: var(--red); text-decoration: none; display: inline-flex; gap: 6px; align-items: center; }

/* Benefícios */
.benefits { display: grid; gap: 1px; background: #e8e4df; border: 1px solid #e8e4df; border-radius: var(--radius); overflow: hidden; }
@media (min-width: 640px) { .benefits { grid-template-columns: repeat(2, 1fr); } }
@media (min-width: 980px) { .benefits { grid-template-columns: repeat(3, 1fr); } }
.benefit { background: #fff; padding: 30px 26px; }
.benefit__ico { width: 44px; height: 44px; border-radius: 50%; background: rgba(225,6,0,.08); color: var(--red); display: grid; place-items: center; margin-bottom: 16px; }
.benefit h3 { font-size: 1.12rem; font-weight: 700; margin-bottom: 6px; }
.benefit p { margin: 0; color: #5a5a5a; }

/* Passos */
.steps { list-style: none; padding: 0; margin: 0 0 44px; display: grid; gap: 16px; counter-reset: s; }
@media (min-width: 860px) { .steps { grid-template-columns: repeat(3, 1fr); } }
.step { counter-increment: s; background: var(--ink); border: 1px solid var(--line); border-radius: var(--radius); padding: 30px 26px; position: relative; }
.step::before { content: "0" counter(s); font-family: var(--serif); font-size: 3rem; color: var(--red); line-height: 1; display: block; margin-bottom: 18px; }
.step h3 { font-size: 1.2rem; margin-bottom: 6px; }
.step p { margin: 0; color: rgba(255,255,255,.65); }

/* Depoimentos */
.testis { display: grid; gap: 16px; }
@media (min-width: 900px) { .testis { grid-template-columns: repeat(3, 1fr); } }
.testi { border: 1px solid #ece8e3; border-radius: var(--radius); padding: 28px; display: flex; flex-direction: column; gap: 16px; position: relative; background: #fff; }
.testi__result { display: inline-flex; align-self: flex-start; align-items: center; gap: 6px; background: var(--black); color: #fff; font-weight: 600; font-size: .85rem; padding: 6px 12px; border-radius: 999px; }
.testi__result .i { color: var(--red-2); }
.testi__stars { display: flex; color: var(--red); gap: 2px; }
.testi blockquote { margin: 0; font-family: var(--serif); font-size: 1.12rem; line-height: 1.45; flex: 1; }
.testi__who { display: flex; align-items: center; gap: 12px; }
.testi__who img, .avatar { width: 46px; height: 46px; border-radius: 50%; object-fit: cover; flex: none; }
.avatar { background: var(--red); color: #fff; display: grid; place-items: center; font-weight: 700; }
.testi__who b { display: block; }
.testi__who small { color: var(--muted); }
.tag-demo { position: absolute; top: 14px; right: 14px; font-size: .65rem; font-weight: 700; letter-spacing: .1em; background: #fff3cd; color: #7a5b00; padding: 3px 8px; border-radius: 6px; }

/* Oferta */
.offer { background: radial-gradient(700px 300px at 50% 0%, rgba(225,6,0,.35), transparent 70%), var(--black); }
.offer .h2 { font-size: clamp(2.2rem, 6vw, 3.8rem); }
.countdown { display: flex; justify-content: center; gap: 10px; margin: 0 0 28px; }
.countdown div { background: var(--ink); border: 1px solid var(--line); border-radius: 12px; padding: 12px 6px; min-width: 70px; }
.countdown b { display: block; font-family: var(--serif); font-size: 2rem; color: var(--red-2); line-height: 1; }
.countdown small { font-size: .7rem; text-transform: uppercase; letter-spacing: .1em; color: var(--muted); }
.offer .tiny { margin-top: 16px; }

/* FAQ */
.faq { display: grid; gap: 10px; }
.faq details { border: 1px solid #e6e2dd; border-radius: 14px; padding: 0 20px; background: #fff; }
.faq details[open] { border-color: var(--red); }
.faq summary { cursor: pointer; list-style: none; padding: 18px 0; font-weight: 600; font-size: 1.05rem; display: flex; justify-content: space-between; gap: 12px; }
.faq summary::-webkit-details-marker { display: none; }
.faq summary::after { content: "+"; color: var(--red); font-size: 1.4rem; line-height: 1; transition: transform .2s; }
.faq details[open] summary::after { transform: rotate(45deg); }
.faq p { margin: 0 0 18px; color: #555; }

/* Formulário */
.form { background: #fff; color: var(--text); border-radius: 22px; padding: 26px; display: grid; gap: 14px; box-shadow: 0 30px 80px -30px rgba(0,0,0,.5); }
.form h3 { font-family: var(--serif); font-weight: 500; font-size: 1.5rem; }
.form label { display: grid; gap: 6px; font-size: .88rem; font-weight: 600; }
.form input, .form select { font: inherit; padding: 12px 14px; border: 1.5px solid #ddd; border-radius: 12px; background: #fff; color: inherit; width: 100%; }
.form input:focus, .form select:focus { border-color: var(--red); outline: none; box-shadow: 0 0 0 4px rgba(225,6,0,.12); }
.form .check { display: flex; gap: 10px; align-items: flex-start; font-weight: 400; font-size: .8rem; color: #555; }
.form .check input { width: 18px; height: 18px; margin-top: 2px; accent-color: var(--red); flex: none; }
.form [aria-invalid="true"] { border-color: var(--red); }
.form__msg { margin: 0; font-size: .9rem; min-height: 1.2em; }
.form__msg.ok { color: #15803d; }
.form__msg.err { color: var(--red); }
.hp { position: absolute; left: -9999px; width: 1px; height: 1px; opacity: 0; }

/* Aviso de cookies (LGPD) */
.consent { position: fixed; left: 16px; right: 16px; bottom: calc(16px + env(safe-area-inset-bottom)); z-index: 90; max-width: 560px; margin: 0 auto; background: #fff; color: var(--text); border-radius: 16px; box-shadow: 0 20px 60px -10px rgba(0,0,0,.45); padding: 16px 18px; display: flex; flex-wrap: wrap; align-items: center; gap: 12px; font-size: .9rem; }
.consent p { margin: 0; flex: 1 1 260px; }
.consent a { color: var(--red); }
.consent div { display: flex; gap: 8px; }
.btn--ghost-dark { --bg: transparent; --fg: var(--text); border-color: #ddd; box-shadow: none; }
.btn--ghost-dark:hover { background: #f3f3f3; border-color: #ccc; }

/* Rodapé */
.footer { background: var(--black); color: #fff; padding: 48px 0 110px; }
.footer__in { display: grid; gap: 20px; }
@media (min-width: 860px) { .footer__in { grid-template-columns: 1fr 1.6fr auto; align-items: start; } .footer { padding-bottom: 48px; } }

/* Barra fixa no celular */
.mobilebar { position: fixed; left: 0; right: 0; bottom: 0; padding: 10px 16px calc(10px + env(safe-area-inset-bottom)); background: linear-gradient(to top, rgba(10,10,10,.95), rgba(10,10,10,.7)); z-index: 60; transform: translateY(110%); transition: transform .3s; }
.mobilebar .btn { width: 100%; }
.mobilebar.show { transform: none; }
@media (min-width: 860px) { .mobilebar { display: none; } }



/* =========================================================
   EFEITOS E TRANSIÇÕES
   Tudo respeita "prefers-reduced-motion" (quem desativa animações no celular não vê).
   ========================================================= */
:root { interpolate-size: allow-keywords; }

/* Barra de progresso da leitura */
.progress { position: fixed; top: env(safe-area-inset-top, 0px); left: 0; right: 0; height: 3px; z-index: 80; pointer-events: none; }
.progress span { display: block; height: 100%; background: linear-gradient(90deg, var(--red), var(--red-2)); transform-origin: 0 50%; transform: scaleX(0); box-shadow: 0 0 12px rgba(225,6,0,.7); }

@media (prefers-reduced-motion: no-preference) {
  /* Entrada do hero em sequência */
  .hero .eyebrow, .hero__sub, .hero__ctas, .hero__note { animation: rise .8s cubic-bezier(.2,.7,.2,1) both; }
  .hero .eyebrow { animation-delay: .05s; }
  .hero__sub { animation-delay: .75s; }
  .hero__ctas { animation-delay: .9s; }
  .hero__note { animation-delay: 1.05s; }
  .hero__title .w { display: inline-block; animation: wordUp .9s cubic-bezier(.2,.8,.2,1) both; animation-delay: calc(.15s + var(--i) * .07s); }
  .hero__visual { animation: phoneIn 1.2s cubic-bezier(.2,.8,.2,1) .3s both; }
  .chip--a { animation: chipIn .6s 1.2s both, float 6s 1.8s ease-in-out infinite; }
  .chip--b { animation: chipIn .6s 1.45s both, float 6s 2s ease-in-out infinite; }
  .chip--c { animation: chipIn .6s 1.7s both, float 6s 2.3s ease-in-out infinite; }
  .hero::after { content: ""; position: absolute; inset: 0; background: radial-gradient(600px 300px at var(--gx, 80%) var(--gy, 20%), rgba(225,6,0,.22), transparent 70%); pointer-events: none; transition: background .2s; }

  /* Sublinhado vermelho que "desenha" sob o destaque do título */
  .hero__title em { position: relative; }
  .hero__title em::after { content: ""; position: absolute; left: 0; right: 0; bottom: .02em; height: .08em; background: var(--red-2); border-radius: 4px; transform-origin: 0 50%; animation: draw .8s cubic-bezier(.7,0,.2,1) 1.1s both; }

  /* Feed do celular "acendendo" em sequência, em loop */
  .ig__grid .t { animation: tilePop 4.5s ease-in-out infinite; }
  .ig__grid .t:nth-child(1) { animation-delay: 0s } .ig__grid .t:nth-child(2) { animation-delay: .15s } .ig__grid .t:nth-child(3) { animation-delay: .3s }
  .ig__grid .t:nth-child(4) { animation-delay: .45s } .ig__grid .t:nth-child(5) { animation-delay: .6s } .ig__grid .t:nth-child(6) { animation-delay: .75s }
  .ig__grid .t:nth-child(7) { animation-delay: .9s } .ig__grid .t:nth-child(8) { animation-delay: 1.05s } .ig__grid .t:nth-child(9) { animation-delay: 1.2s }
  .ig__btn { animation: btnPulse 2.4s ease-in-out infinite; }

  /* Faixa de serviços rolando */
  .marquee__track { animation: marquee 28s linear infinite; }
  .marquee:hover .marquee__track { animation-play-state: paused; }

  /* Brilho que passa pelos botões */
  .btn { position: relative; overflow: hidden; isolation: isolate; }
  .btn::after { content: ""; position: absolute; inset: -2px; background: linear-gradient(105deg, transparent 35%, rgba(255,255,255,.45) 50%, transparent 65%); transform: translateX(-120%); transition: transform .7s ease; z-index: -1; pointer-events: none; }
  .btn:hover::after { transform: translateX(120%); }
  .hero .btn:not(.btn--ghost) { animation: rise .8s cubic-bezier(.2,.7,.2,1) .9s both, glow 2.8s ease-in-out 2s infinite; }
  .mobilebar .btn { animation: glow 2.4s ease-in-out infinite; }

  /* Seções aparecendo conforme a rolagem (sem esconder nada se o navegador não suportar) */
  @supports (animation-timeline: view()) {
    .reveal, .sec__head, .pains li, .bridge__col, .faq details, .form, .offer .h2, .countdown {
      animation: revealUp linear both;
      animation-timeline: view();
      animation-range: entry 0% cover 28%;
    }
    .pains li:nth-child(2n) { animation-name: revealLeft; }
    .pains li:nth-child(2n+1) { animation-name: revealRight; }
    .bridge__col--from { animation-name: revealRight; }
    .bridge__col--to { animation-name: revealLeft; }
    .step::before { animation: numberIn linear both; animation-timeline: view(); animation-range: entry 10% cover 35%; }
    .progress span { animation: grow linear both; animation-timeline: scroll(root); }
  }
}

/* Cartões: luz que segue o cursor + elevação */
.service, .benefit, .testi, .step { position: relative; overflow: hidden; transition: transform .35s cubic-bezier(.2,.8,.2,1), box-shadow .35s, border-color .35s; }
.service::before, .benefit::before, .testi::before, .step::after {
  content: ""; position: absolute; inset: 0; pointer-events: none; opacity: 0; transition: opacity .3s;
  background: radial-gradient(260px circle at var(--mx, 50%) var(--my, 50%), rgba(225,6,0,.13), transparent 70%);
}
.step::after { background: radial-gradient(260px circle at var(--mx, 50%) var(--my, 50%), rgba(255,42,31,.18), transparent 70%); }
.service:hover::before, .benefit:hover::before, .testi:hover::before, .step:hover::after { opacity: 1; }
.benefit:hover, .testi:hover, .step:hover { transform: translateY(-4px); }
.testi:hover { box-shadow: var(--shadow); border-color: var(--red); }
.step:hover { border-color: var(--red); }
.service__ico, .benefit__ico { transition: transform .45s cubic-bezier(.3,1.6,.5,1), background .3s, color .3s; }
.service:hover .service__ico { transform: rotate(-8deg) scale(1.12); background: var(--red); color: #fff; }
.benefit:hover .benefit__ico { transform: scale(1.15); background: var(--red); color: #fff; }
.service a .i { transition: transform .3s; }
.service a:hover .i { transform: translateX(5px); }
.nav a { position: relative; }
.nav a::after { content: ""; position: absolute; left: 0; right: 0; bottom: -6px; height: 2px; background: var(--red); transform: scaleX(0); transform-origin: right; transition: transform .35s; }
.nav a:hover::after { transform: scaleX(1); transform-origin: left; }
.topbar { transition: box-shadow .3s; }
.topbar.scrolled { box-shadow: 0 10px 30px -12px rgba(0,0,0,.6); }

/* Celular em 3D seguindo o mouse */
.hero { position: relative; }
.hero__visual { perspective: 1000px; }
.phone { transform: rotate(-4deg) rotateX(var(--rx, 0deg)) rotateY(var(--ry, 0deg)); transition: transform .25s ease-out; transform-style: preserve-3d; }

/* Faixa de serviços */
.marquee { background: var(--red); color: #fff; overflow: hidden; border-block: 1px solid var(--red-deep); }
.marquee__track { display: flex; width: max-content; }
.marquee__track span { font-family: var(--serif); font-size: clamp(1.1rem, 2.4vw, 1.5rem); padding: 14px 0; white-space: nowrap; display: flex; align-items: center; }
.marquee__track span::after { content: "✦"; font-size: .8em; margin: 0 28px; opacity: .7; }
.marquee__track span:nth-child(2n) { font-style: italic; }

/* FAQ abrindo suave */
.faq details::details-content { block-size: 0; overflow: hidden; transition: block-size .35s ease, content-visibility .35s allow-discrete; }
.faq details[open]::details-content { block-size: auto; }
.faq details { transition: border-color .3s, box-shadow .3s; }
.faq details:hover { box-shadow: 0 10px 30px -18px rgba(0,0,0,.35); }

/* Contagem regressiva: dígito "vira" ao mudar */
.countdown b.tick { animation: flip .45s cubic-bezier(.3,1.4,.5,1); }

/* Campos do formulário */
.form input, .form select { transition: border-color .2s, box-shadow .2s, transform .2s; }
.form input:focus, .form select:focus { transform: translateY(-1px); }

@keyframes rise { from { opacity: 0; transform: translateY(22px); } to { opacity: 1; transform: none; } }
@keyframes wordUp { from { opacity: 0; transform: translateY(.6em) rotate(4deg); filter: blur(6px); } to { opacity: 1; transform: none; filter: none; } }
@keyframes phoneIn { from { opacity: 0; transform: translateY(60px) scale(.92); } to { opacity: 1; transform: none; } }
@keyframes chipIn { from { opacity: 0; transform: scale(.6) translateY(10px); } to { opacity: 1; transform: none; } }
@keyframes draw { from { transform: scaleX(0); } to { transform: scaleX(1); } }
@keyframes tilePop { 0%, 70%, 100% { transform: none; filter: none; } 80% { transform: scale(.9); filter: brightness(1.35); } }
@keyframes btnPulse { 50% { box-shadow: 0 0 0 6px rgba(225,6,0,.18); } }
@keyframes glow { 0%, 100% { box-shadow: 0 10px 30px -10px rgba(225,6,0,.6), 0 0 0 0 rgba(225,6,0,.45); } 50% { box-shadow: 0 10px 30px -10px rgba(225,6,0,.6), 0 0 0 10px rgba(225,6,0,0); } }
@keyframes marquee { to { transform: translateX(-50%); } }
@keyframes revealUp { from { opacity: 0; transform: translateY(40px) scale(.98); } to { opacity: 1; transform: none; } }
@keyframes revealLeft { from { opacity: 0; transform: translateX(-50px); } to { opacity: 1; transform: none; } }
@keyframes revealRight { from { opacity: 0; transform: translateX(50px); } to { opacity: 1; transform: none; } }
@keyframes numberIn { from { opacity: 0; transform: translateY(20px) scale(.6); letter-spacing: .3em; } to { opacity: 1; transform: none; } }
@keyframes grow { to { transform: scaleX(1); } }
@keyframes flip { from { transform: rotateX(90deg); opacity: .3; } to { transform: none; opacity: 1; } }

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after { animation: none !important; transition: none !important; }
}
.hero__grid { position: relative; z-index: 1; }

</style>
</head>
<!--
  data-api: endereço do painel (ex.: https://painel.seudominio.com).
  Vazio = a página funciona sozinha (sem enviar leads/eventos ao painel).
-->
<body data-api="">
  <a class="skip" href="#conteudo">Pular para o conteúdo</a>
  <div class="progress" aria-hidden="true"><span id="progress"></span></div>

  <!-- Faixa de oferta (Black Friday / 10% à vista) — preenchida pelo app.js -->
  <div class="promo" id="promo" role="region" aria-label="Oferta"></div>

  <header class="topbar" id="topbar">
    <div class="wrap topbar__in">
      <a href="#topo" class="logo" data-c="brand.name"></a>
      <nav class="nav" aria-label="Seções">
        <a href="#servicos">Serviços</a>
        <a href="#como-funciona">Como funciona</a>
        <a href="#depoimentos">Depoimentos</a>
        <a href="#faq">Dúvidas</a>
      </nav>
      <a class="btn btn--sm" data-wa="topbar" href="#">WhatsApp</a>
    </div>
  </header>

  <main id="conteudo">
    <!-- 1. HERO -->
    <section class="hero" id="topo">
      <div class="wrap hero__grid">
        <div class="hero__copy">
          <p class="eyebrow" data-c="hero.eyebrow"></p>
          <h1 class="hero__title" data-c-html="hero.headline"></h1>
          <p class="hero__sub" data-c="hero.subheadline"></p>
          <div class="hero__ctas">
            <a class="btn btn--lg" data-wa="hero" href="#"><span data-c="hero.ctaLabel"></span> <svg class="i" aria-hidden="true"><use href="#i-arrow"/></svg></a>
            <a class="btn btn--ghost btn--lg" href="#servicos">Ver serviços</a>
          </div>
          <p class="hero__note"><svg class="i i--red" aria-hidden="true"><use href="#i-bolt"/></svg> <span data-c="hero.ctaNote"></span></p>
        </div>

        <!-- Elemento visual: celular com perfil de Instagram "antes de vender" -> "vendendo" -->
        <div class="hero__visual" aria-hidden="true">
          <div class="phone">
            <div class="phone__notch"></div>
            <div class="ig">
              <div class="ig__head">
                <div class="ig__avatar"></div>
                <div class="ig__stats"><b>248</b><small>posts</small></div>
                <div class="ig__stats"><b>12,4k</b><small>seguidores</small></div>
                <div class="ig__stats"><b>310</b><small>seguindo</small></div>
              </div>
              <div class="ig__bio"><span></span><span></span><span class="short"></span></div>
              <div class="ig__btn">Comprar agora</div>
              <div class="ig__grid">
                <div class="t t1"><b>-50%</b></div><div class="t t2"><b>NOVO</b></div><div class="t t3"></div>
                <div class="t t4"></div><div class="t t5"><b>DROP</b></div><div class="t t6"></div>
                <div class="t t7"><b>24H</b></div><div class="t t8"></div><div class="t t9"><b>SALE</b></div>
              </div>
            </div>
          </div>
          <div class="chip chip--a"><svg class="i i--red"><use href="#i-clock"/></svg> Entregue em <b>18h</b></div>
          <div class="chip chip--b"><svg class="i"><use href="#i-check"/></svg> Criativo aprovado</div>
          <div class="chip chip--c"><span class="dot"></span> Nova mensagem: <b>"quero comprar!"</b></div>
        </div>
      </div>
    </section>

    <!-- Faixa animada com os serviços -->
    <div class="marquee" aria-hidden="true"><div class="marquee__track" id="marquee"></div></div>

    <!-- 2. BARRA DE CREDIBILIDADE -->
    <section class="cred" aria-label="Por que confiar">
      <div class="wrap cred__row" id="cred"></div>
    </section>

    <!-- 3. PROBLEMA -->
    <section class="sec sec--dark" id="problema">
      <div class="wrap narrow">
        <p class="eyebrow eyebrow--red" data-c="problem.eyebrow"></p>
        <h2 class="h2" data-c-html="problem.title"></h2>
        <ul class="pains" id="pains"></ul>
        <p class="sec__close" data-c-html="problem.closing"></p>
      </div>
    </section>

    <!-- 4. SOLUÇÃO -->
    <section class="sec" id="solucao">
      <div class="wrap split">
        <div>
          <p class="eyebrow eyebrow--red" data-c="solution.eyebrow"></p>
          <h2 class="h2" data-c-html="solution.title"></h2>
          <p class="lead" data-c="solution.text"></p>
          <a class="btn" data-wa="solucao" href="#">Quero meu orçamento <svg class="i"><use href="#i-arrow"/></svg></a>
        </div>
        <div class="bridge" aria-label="Da dor ao resultado">
          <div class="bridge__col bridge__col--from"><small>Hoje</small><ul id="bridgeFrom"></ul></div>
          <div class="bridge__arrow"><svg class="i"><use href="#i-arrow"/></svg></div>
          <div class="bridge__col bridge__col--to"><small>Depois</small><ul id="bridgeTo"></ul></div>
        </div>
      </div>
    </section>

    <!-- Serviços (vitrine) -->
    <section class="sec sec--soft" id="servicos">
      <div class="wrap">
        <div class="sec__head">
          <p class="eyebrow eyebrow--red">O que eu faço por você</p>
          <h2 class="h2">Seis formas de deixar sua marca <em>impossível de ignorar</em></h2>
        </div>
        <div class="services" id="services"></div>
      </div>
    </section>

    <!-- 5. BENEFÍCIOS -->
    <section class="sec" id="beneficios">
      <div class="wrap">
        <div class="sec__head">
          <p class="eyebrow eyebrow--red">O que muda pra você</p>
          <h2 class="h2" data-c-html="benefitsTitle"></h2>
        </div>
        <div class="benefits" id="benefits"></div>
      </div>
    </section>

    <!-- 6. COMO FUNCIONA -->
    <section class="sec sec--dark" id="como-funciona">
      <div class="wrap">
        <div class="sec__head">
          <p class="eyebrow eyebrow--red">Simples assim</p>
          <h2 class="h2">3 passos. <em>Zero dor de cabeça.</em></h2>
        </div>
        <ol class="steps" id="steps"></ol>
        <div class="center"><a class="btn btn--lg" data-wa="passos" href="#">Começar pelo passo 1 <svg class="i"><use href="#i-arrow"/></svg></a></div>
      </div>
    </section>

    <!-- 7. PROVA SOCIAL -->
    <section class="sec" id="depoimentos">
      <div class="wrap">
        <div class="sec__head">
          <p class="eyebrow eyebrow--red">Quem já fez</p>
          <h2 class="h2">Resultados de quem <em>parou de esperar</em></h2>
        </div>
        <div class="testis" id="testis"></div>
      </div>
    </section>

    <!-- Oferta -->
    <section class="sec sec--dark offer" id="oferta">
      <div class="wrap narrow center">
        <p class="eyebrow eyebrow--red" id="offerEyebrow"></p>
        <h2 class="h2" id="offerTitle"></h2>
        <p class="lead" id="offerText"></p>
        <div class="countdown" id="countdown" hidden></div>
        <a class="btn btn--lg" data-wa="oferta" href="#"><span id="offerCta"></span> <svg class="i"><use href="#i-arrow"/></svg></a>
        <p class="tiny" id="offerFine"></p>
      </div>
    </section>

    <!-- Objeções (FAQ) -->
    <section class="sec" id="faq">
      <div class="wrap narrow">
        <div class="sec__head">
          <p class="eyebrow eyebrow--red">Antes que você pergunte</p>
          <h2 class="h2">Dúvidas frequentes</h2>
        </div>
        <div class="faq" id="faqList"></div>
      </div>
    </section>

    <!-- CTA final + formulário opcional (alimenta o CRM do painel) -->
    <section class="sec sec--red" id="contato">
      <div class="wrap split">
        <div>
          <h2 class="h2" data-c-html="finalCta.title"></h2>
          <p class="lead" data-c="finalCta.text"></p>
          <a class="btn btn--white btn--lg" data-wa="final" href="#"><svg class="i"><use href="#i-wa"/></svg> <span data-c="finalCta.ctaLabel"></span></a>
        </div>
        <form class="form" id="leadForm" novalidate>
          <h3>Prefere que eu te chame?</h3>
          <label>Seu nome<input name="name" required maxlength="80" autocomplete="name" /></label>
          <label>WhatsApp<input name="phone" required inputmode="tel" maxlength="20" placeholder="(15) 99999-9999" autocomplete="tel" /></label>
          <label>@ do Instagram (opcional)<input name="instagram" maxlength="40" placeholder="@suamarca" /></label>
          <label>O que você precisa?
            <select name="service" id="serviceSelect"></select>
          </label>
          <!-- honeypot anti-spam: humanos não veem este campo -->
          <input class="hp" name="website" tabindex="-1" autocomplete="off" aria-hidden="true" />
          <label class="check"><input type="checkbox" name="consent" required /> <span>Autorizo o contato pelo WhatsApp e o uso dos meus dados conforme a <a href="#privacidade">Política de Privacidade</a> (LGPD).</span></label>
          <button class="btn btn--dark" type="submit">Quero ser chamado</button>
          <p class="form__msg" id="formMsg" role="status" aria-live="polite"></p>
        </form>
      </div>
    </section>
  </main>

  <footer class="footer" id="privacidade">
    <div class="wrap footer__in">
      <div>
        <strong class="logo" data-c="brand.name"></strong>
        <p class="tiny">Site pessoal. Atendimento direto comigo pelo WhatsApp.</p>
      </div>
      <p class="tiny"><b>Privacidade (LGPD):</b> seus dados são usados apenas para responder ao seu contato. Você pode pedir a cópia ou a exclusão a qualquer momento pelo WhatsApp.</p>
      <p class="tiny">© <span id="year"></span> <span data-c="brand.name"></span></p>
    </div>
  </footer>

  <!-- Barra fixa de CTA no celular -->
  <div class="mobilebar"><a class="btn btn--lg" data-wa="mobilebar" href="#"><svg class="i"><use href="#i-wa"/></svg> Chamar no WhatsApp</a></div>

  <noscript><p style="padding:16px;text-align:center"><a href="https://wa.me/5515996337454">Chamar no WhatsApp: (15) 99633-7454</a></p></noscript>

  <!-- Ícones (SVG sprite) -->
  <svg width="0" height="0" style="position:absolute" aria-hidden="true">
    <symbol id="i-arrow" viewBox="0 0 24 24"><path d="M5 12h14M13 6l6 6-6 6" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></symbol>
    <symbol id="i-bolt" viewBox="0 0 24 24"><path d="M13 2 4 14h7l-1 8 9-12h-7l1-8z" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/></symbol>
    <symbol id="i-clock" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9" fill="none" stroke="currentColor" stroke-width="2"/><path d="M12 7v5l3 2" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-check" viewBox="0 0 24 24"><path d="m5 12 5 5L20 7" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/></symbol>
    <symbol id="i-x" viewBox="0 0 24 24"><path d="M6 6l12 12M18 6 6 18" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round"/></symbol>
    <symbol id="i-trend" viewBox="0 0 24 24"><path d="M3 17l6-6 4 4 8-8M15 7h6v6" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></symbol>
    <symbol id="i-eye" viewBox="0 0 24 24"><path d="M2 12s3.5-7 10-7 10 7 10 7-3.5 7-10 7S2 12 2 12z" fill="none" stroke="currentColor" stroke-width="2"/><circle cx="12" cy="12" r="3" fill="none" stroke="currentColor" stroke-width="2"/></symbol>
    <symbol id="i-shield" viewBox="0 0 24 24"><path d="M12 3 4 6v6c0 5 3.5 8 8 9 4.5-1 8-4 8-9V6l-8-3z" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/><path d="m9 12 2 2 4-4" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-wallet" viewBox="0 0 24 24"><rect x="3" y="6" width="18" height="13" rx="2" fill="none" stroke="currentColor" stroke-width="2"/><path d="M16 12h2M3 9h18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-spark" viewBox="0 0 24 24"><path d="M12 3v4M12 17v4M3 12h4M17 12h4M6 6l2.5 2.5M15.5 15.5 18 18M18 6l-2.5 2.5M8.5 15.5 6 18" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-chat" viewBox="0 0 24 24"><path d="M4 5h16v11H8l-4 4V5z" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/></symbol>
    <symbol id="i-globe" viewBox="0 0 24 24"><circle cx="12" cy="12" r="9" fill="none" stroke="currentColor" stroke-width="2"/><path d="M3 12h18M12 3c3 3 3 15 0 18M12 3c-3 3-3 15 0 18" fill="none" stroke="currentColor" stroke-width="2"/></symbol>
    <symbol id="i-film" viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="16" rx="2" fill="none" stroke="currentColor" stroke-width="2"/><path d="M7 4v16M17 4v16M3 9h4M3 15h4M17 9h4M17 15h4" fill="none" stroke="currentColor" stroke-width="2"/></symbol>
    <symbol id="i-image" viewBox="0 0 24 24"><rect x="3" y="4" width="18" height="16" rx="2" fill="none" stroke="currentColor" stroke-width="2"/><circle cx="9" cy="10" r="2" fill="none" stroke="currentColor" stroke-width="2"/><path d="m21 16-5-5-9 9" fill="none" stroke="currentColor" stroke-width="2"/></symbol>
    <symbol id="i-cpu" viewBox="0 0 24 24"><rect x="6" y="6" width="12" height="12" rx="2" fill="none" stroke="currentColor" stroke-width="2"/><path d="M9 2v4M15 2v4M9 18v4M15 18v4M2 9h4M2 15h4M18 9h4M18 15h4" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-star" viewBox="0 0 24 24"><path d="m12 3 2.8 5.7 6.2.9-4.5 4.4 1 6.2L12 17.3 6.5 20.2l1-6.2L3 9.6l6.2-.9L12 3z" fill="currentColor"/></symbol>
    <symbol id="i-cap" viewBox="0 0 24 24"><path d="M2 9l10-5 10 5-10 5L2 9z" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/><path d="M6 11v5c3 2 9 2 12 0v-5" fill="none" stroke="currentColor" stroke-width="2"/></symbol>
    <symbol id="i-mic" viewBox="0 0 24 24"><rect x="9" y="3" width="6" height="11" rx="3" fill="none" stroke="currentColor" stroke-width="2"/><path d="M5 11a7 7 0 0 0 14 0M12 18v3" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></symbol>
    <symbol id="i-wa" viewBox="0 0 24 24"><path d="M12 3a9 9 0 0 0-7.8 13.5L3 21l4.6-1.2A9 9 0 1 0 12 3z" fill="none" stroke="currentColor" stroke-width="2" stroke-linejoin="round"/><path d="M8.5 8.5c.3 2.8 3.2 6 6.5 6.8l1.4-1.4-2-1-1 .8c-1-.4-2.2-1.6-2.6-2.6l.8-1-1-2-1.4 1.4" fill="currentColor"/></symbol>
  </svg>

  <!--
    ===================== CONTEÚDO DO SITE (EDITE AQUI) =====================
    - "name": troque "SEU NOME" pelo seu nome ou marca.
    - "instagram": seu @.
    - Depoimentos: quando tiver depoimentos REAIS, preencha "testimonials",
      mude "placeholder" para false e apague "depoimentos" de "hiddenSections".
    - Cuidado para não apagar aspas, vírgulas ou chaves { }.
    =========================================================================
  -->
  <script type="application/json" id="site-content">
{
  "version": "site-1",
  "variant": null,
  "brand": {
    "name": "SEU NOME",
    "instagram": "@seuinsta",
    "whatsapp": "5515996337454",
    "whatsappLabel": "(15) 99633-7454"
  },
  "hero": {
    "eyebrow": "Design • Sites • Vídeo com IA",
    "headline": "Seu Instagram vendendo mais com design profissional <em>em 24h</em>",
    "subheadline": "Eu crio os criativos, vídeos com IA, edições e sites que transformam seguidores em clientes. Você me conta o objetivo, eu entrego pronto para postar em até 24h ou 2 dias úteis.",
    "ctaLabel": "Pedir orçamento no WhatsApp",
    "ctaNote": "Resposta rápida • Orçamento sem compromisso"
  },
  "credibility": [
    {
      "value": "24h",
      "label": "entrega expressa"
    },
    {
      "value": "2 dias",
      "label": "úteis no máximo"
    },
    {
      "value": "6",
      "label": "serviços em um só lugar"
    },
    {
      "value": "-10%",
      "label": "pagando à vista"
    }
  ],
  "problem": {
    "eyebrow": "Se identifica?",
    "title": "Você posta, posta, posta… <em>e o dinheiro não vem.</em>",
    "items": [
      "“Faço story todo dia e ninguém pergunta o preço.”",
      "“Meu perfil parece amador perto do concorrente que cobra o dobro.”",
      "“Bate o medo: e se amanhã eu ficar sem dinheiro porque ninguém me vê?”",
      "“Já paguei alguém, esperei semanas e o resultado não mudou nada.”"
    ],
    "closing": "O problema não é o seu produto. É que <b>ninguém para no seu post tempo suficiente para querer comprar.</b>"
  },
  "solution": {
    "eyebrow": "A ponte",
    "title": "Design feito para <em>vender</em>, não só para ficar bonito",
    "text": "Cada peça que eu entrego tem um objetivo: prender a atenção, gerar desejo e levar o seguidor até a compra. Você ganha uma identidade profissional e conteúdo pronto, sem precisar aprender programa nenhum e sem esperar semanas.",
    "from": [
      "Posts sem padrão",
      "Ninguém pergunta o preço",
      "Semanas esperando entrega",
      "Medo do mês que vem"
    ],
    "to": [
      "Perfil com cara de marca grande",
      "Direct com pedidos de orçamento",
      "Material pronto em até 24h",
      "Mais vendas pelo Instagram"
    ]
  },
  "services": [
    {
      "icon": "image",
      "name": "Criativos",
      "desc": "Posts, carrosséis e stories que param o dedo no feed."
    },
    {
      "icon": "cpu",
      "name": "Vídeos com IA",
      "desc": "Vídeos que chamam atenção sem você precisar gravar."
    },
    {
      "icon": "film",
      "name": "Edição de vídeo",
      "desc": "Reels com ritmo, legenda e corte que prendem até o fim."
    },
    {
      "icon": "globe",
      "name": "Criação de sites",
      "desc": "Sua vitrine profissional, rápida e pronta para vender."
    },
    {
      "icon": "mic",
      "name": "Influencer para marcas",
      "desc": "Divulgação da sua marca para o meu público."
    },
    {
      "icon": "cap",
      "name": "Cursos",
      "desc": "Aprenda a criar o seu próprio conteúdo que vende."
    }
  ],
  "benefitsTitle": "Menos tempo editando. <em>Mais tempo vendendo.</em>",
  "benefits": [
    {
      "icon": "clock",
      "title": "Pronto amanhã",
      "text": "Peça hoje, poste amanhã. Sua marca não fica parada esperando."
    },
    {
      "icon": "eye",
      "title": "Mais gente parando no seu post",
      "text": "Visual profissional faz o seguidor olhar, salvar e compartilhar."
    },
    {
      "icon": "chat",
      "title": "Direct com pedido, não só curtida",
      "text": "Conteúdo pensado para gerar a pergunta: “quanto custa?”."
    },
    {
      "icon": "trend",
      "title": "Você cobra mais",
      "text": "Marca com cara de grande passa confiança e justifica um preço melhor."
    },
    {
      "icon": "wallet",
      "title": "Cabe no bolso",
      "text": "Paga à vista com 10% de desconto. Sem mensalidade obrigatória."
    },
    {
      "icon": "shield",
      "title": "Ajuste até ficar certo",
      "text": "Você aprova antes. Se não ficou do seu jeito, eu ajusto."
    }
  ],
  "steps": [
    {
      "title": "Me chama no WhatsApp",
      "text": "Conta o que você vende e o que precisa. Leva 2 minutos."
    },
    {
      "title": "Receba o orçamento",
      "text": "Você recebe preço e prazo na hora. Aprovou, eu começo."
    },
    {
      "title": "Poste e venda",
      "text": "Em até 24h ou 2 dias úteis está tudo pronto para publicar."
    }
  ],
  "testimonials": [
    {
      "placeholder": true,
      "name": "Nome do cliente",
      "role": "@perfil • loja de roupas",
      "result": "+3x mensagens no direct",
      "text": "Substitua este texto pelo depoimento real do seu cliente no painel.",
      "photo": ""
    },
    {
      "placeholder": true,
      "name": "Nome do cliente",
      "role": "@perfil • confeitaria",
      "result": "Esgotou a encomenda da semana",
      "text": "Substitua este texto pelo depoimento real do seu cliente no painel.",
      "photo": ""
    },
    {
      "placeholder": true,
      "name": "Nome do cliente",
      "role": "@perfil • personal trainer",
      "result": "Site no ar em 2 dias",
      "text": "Substitua este texto pelo depoimento real do seu cliente no painel.",
      "photo": ""
    }
  ],
  "offer": {
    "blackFridayDate": "2026-11-27",
    "blackFridayDiscount": 50,
    "cashDiscount": 10
  },
  "faq": [
    {
      "q": "É caro?",
      "a": "Você paga por peça ou por pacote, sem mensalidade obrigatória, e ainda ganha 10% de desconto à vista. Compare com o que você perde por mês com um perfil que não vende."
    },
    {
      "q": "Não tenho tempo para isso.",
      "a": "Você só precisa me mandar uma mensagem explicando o que quer. Eu cuido de todo o resto e entrego pronto para postar."
    },
    {
      "q": "Já tentei e não funcionou.",
      "a": "Normalmente o problema é design sem objetivo. Aqui cada peça é pensada para gerar conversa e venda, e você aprova tudo antes de publicar."
    },
    {
      "q": "Qual é o prazo de entrega?",
      "a": "Até 24h para peças expressas e no máximo 2 dias úteis para projetos maiores. O prazo exato vem junto com o orçamento."
    },
    {
      "q": "Como funciona o pagamento?",
      "a": "À vista com 10% de desconto. No dia da Black Friday, 50% de desconto em todos os serviços."
    }
  ],
  "finalCta": {
    "title": "Seu próximo cliente está rolando o feed <em>agora</em>.",
    "text": "Faça ele parar no seu perfil. Me chama e receba seu orçamento hoje.",
    "ctaLabel": "Chamar no WhatsApp"
  },
  "hiddenSections": [
    "depoimentos"
  ]
}
  </script>
  <script>
/* =========================================================
   Landing page — renderização do conteúdo, oferta automática,
   rastreamento (UTM + eventos) e envio de leads para o painel.
   JavaScript puro, sem dependências.
   ========================================================= */
(function () {
  "use strict";

  const C = JSON.parse(document.getElementById("site-content").textContent);
  // data-api: "" = sem painel | "self" = servida pelo próprio painel | "https://..." = painel em outro endereço
  const rawApi = document.body.dataset.api || "";
  const API = rawApi === "self" ? location.origin : rawApi.replace(/\/$/, "");
  const $ = (s, el = document) => el.querySelector(s);

  /* ---------- Segurança: escapar texto e permitir só <em>, <b>, <br> ---------- */
  const esc = (s) => String(s ?? "").replace(/[&<>"']/g, (c) => ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", '"': "&quot;", "'": "&#39;" }[c]));
  const safeHtml = (s) => esc(s).replace(/&lt;(\/?)(em|b|br)&gt;/g, "<$1$2>");
  const get = (path) => path.split(".").reduce((o, k) => (o == null ? o : o[k]), C);
  const icon = (name, cls = "i") => `<svg class="${cls}" aria-hidden="true"><use href="#i-${esc(name)}"/></svg>`;

  /* ---------- Armazenamento seguro (pode falhar em aba anônima) ---------- */
  const store = {
    get(k) { try { return localStorage.getItem(k); } catch { return null; } },
    set(k, v) { try { localStorage.setItem(k, v); } catch { /* sem storage */ } },
  };

  /* ---------- Visitante + UTM (primeiro toque) ---------- */
  let visitorId = store.get("vid");
  if (!visitorId) {
    visitorId = (crypto.randomUUID ? crypto.randomUUID() : String(Date.now()) + Math.random().toString(16).slice(2));
    store.set("vid", visitorId);
  }
  const params = new URLSearchParams(location.search);
  const UTM_KEYS = ["utm_source", "utm_medium", "utm_campaign", "utm_term", "utm_content"];
  let utm = {};
  try { utm = JSON.parse(store.get("utm") || "{}"); } catch { utm = {}; }
  if (UTM_KEYS.some((k) => params.get(k))) {
    utm = {};
    UTM_KEYS.forEach((k) => { if (params.get(k)) utm[k] = params.get(k).slice(0, 120); });
    store.set("utm", JSON.stringify(utm));
  }

  /* ---------- Envio de eventos ao painel (visita, clique no WhatsApp...) ---------- */
  function track(type, data = {}) {
    if (!API) return;
    const payload = JSON.stringify({ type, visitorId, variant: C.variant, path: location.pathname, referrer: document.referrer || null, utm, data });
    // text/plain evita "preflight" de CORS; o servidor faz o parse do JSON
    const blob = new Blob([payload], { type: "text/plain" });
    if (!(navigator.sendBeacon && navigator.sendBeacon(API + "/api/public/events", blob))) {
      fetch(API + "/api/public/events", { method: "POST", body: payload, headers: { "Content-Type": "text/plain" }, keepalive: true }).catch(() => {});
    }
  }


  /* ---------- Pixels (Meta e Google) só com consentimento (LGPD) ---------- */
  const T = C.tracking || {};
  const hasPixels = !document.body.dataset.preview && (T.metaPixelId || T.ga4Id);
  function loadPixels() {
    if (T.metaPixelId && /^\d+$/.test(T.metaPixelId)) {
      /* eslint-disable */
      !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version="2.0";n.queue=[];t=b.createElement(e);t.async=!0;t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,document,"script","https://connect.facebook.net/en_US/fbevents.js");
      window.fbq("init", T.metaPixelId); window.fbq("track", "PageView");
    }
    if (T.ga4Id && /^G-[A-Z0-9]+$/.test(T.ga4Id)) {
      const s = document.createElement("script"); s.async = true; s.src = "https://www.googletagmanager.com/gtag/js?id=" + T.ga4Id; document.head.appendChild(s);
      window.dataLayer = window.dataLayer || []; window.gtag = function () { window.dataLayer.push(arguments); };
      window.gtag("js", new Date()); window.gtag("config", T.ga4Id);
    }
  }
  function pixelEvent(kind) {
    try {
      if (kind === "contact") { window.fbq && window.fbq("track", "Contact"); window.gtag && window.gtag("event", "contact", { method: "whatsapp" }); }
      if (kind === "lead") { window.fbq && window.fbq("track", "Lead"); window.gtag && window.gtag("event", "generate_lead"); }
    } catch { /* pixel bloqueado */ }
  }
  function wireConsent() {
    if (!hasPixels) return;
    const saved = store.get("cookie-consent");
    if (saved === "yes") { loadPixels(); return; }
    if (saved === "no") return;
    const bar = document.createElement("div");
    bar.className = "consent"; bar.setAttribute("role", "dialog"); bar.setAttribute("aria-label", "Cookies");
    bar.innerHTML = '<p>Usamos cookies para medir nossos anúncios e melhorar o site. Você aceita? <a href="#privacidade">Saiba mais</a></p><div><button class="btn btn--sm" data-consent="yes">Aceitar</button><button class="btn btn--sm btn--ghost-dark" data-consent="no">Recusar</button></div>';
    bar.addEventListener("click", (e) => {
      const b = e.target.closest("[data-consent]"); if (!b) return;
      store.set("cookie-consent", b.dataset.consent);
      if (b.dataset.consent === "yes") loadPixels();
      bar.remove();
    });
    document.body.appendChild(bar);
  }

  /* ---------- Oferta: Black Friday automática + 10% à vista ---------- */
  const TZ = "America/Sao_Paulo";
  const todayBR = new Intl.DateTimeFormat("en-CA", { timeZone: TZ, year: "numeric", month: "2-digit", day: "2-digit" }).format(new Date());
  const bf = C.offer.blackFridayDate;               // "AAAA-MM-DD"
  const bfStart = new Date(bf + "T00:00:00-03:00"); // meia-noite em Brasília
  const bfEnd = new Date(bf + "T23:59:59-03:00");
  const offerState = todayBR === bf ? "bf" : todayBR < bf ? "pre" : "normal";

  function waMessage(extra) {
    let msg = "Olá! Vim pelo site e quero um orçamento.";
    if (extra) msg += " " + extra;
    if (offerState === "bf") msg += ` Quero aproveitar os ${C.offer.blackFridayDiscount}% da Black Friday!`;
    return "https://wa.me/" + C.brand.whatsapp + "?text=" + encodeURIComponent(msg);
  }

  function renderOffer() {
    const p = $("#promo");
    const bfDateLabel = new Intl.DateTimeFormat("pt-BR", { timeZone: TZ, day: "2-digit", month: "2-digit" }).format(bfStart);
    if (offerState === "bf") {
      p.innerHTML = `BLACK FRIDAY: <b>${C.offer.blackFridayDiscount}% OFF</b> em tudo, só hoje.`;
      $("#offerEyebrow").textContent = "Black Friday • só hoje";
      $("#offerTitle").innerHTML = `<em>${C.offer.blackFridayDiscount}% OFF</em> em todos os serviços`;
      $("#offerText").textContent = "Uma vez por ano. Termina hoje à meia-noite. Garanta seu orçamento antes que o desconto acabe.";
      $("#offerCta").textContent = `Garantir meus ${C.offer.blackFridayDiscount}% OFF`;
      $("#offerFine").textContent = "Válido para pedidos fechados hoje até 23h59 (horário de Brasília).";
      countdown(bfEnd, "Termina em");
    } else if (offerState === "pre") {
      p.innerHTML = `Black Friday ${bfDateLabel}: <b>${C.offer.blackFridayDiscount}% OFF</b> só no dia. Hoje: ${C.offer.cashDiscount}% à vista.`;
      $("#offerEyebrow").textContent = `Black Friday • ${bfDateLabel}`;
      $("#offerTitle").innerHTML = `Vem aí <em>${C.offer.blackFridayDiscount}% OFF</em>. Só por 24 horas.`;
      $("#offerText").textContent = `Me chama agora e garanta seu lugar na fila. Até lá, pagando à vista você já tem ${C.offer.cashDiscount}% de desconto.`;
      $("#offerCta").textContent = "Quero entrar na lista";
      $("#offerFine").textContent = `${C.offer.blackFridayDiscount}% de desconto válido somente em ${bfDateLabel}, horário de Brasília.`;
      countdown(bfStart, "Começa em");
    } else {
      p.innerHTML = `Pagando à vista: <b>${C.offer.cashDiscount}% OFF</b> em qualquer serviço.`;
      $("#offerEyebrow").textContent = "Condição especial";
      $("#offerTitle").innerHTML = `<em>${C.offer.cashDiscount}% OFF</em> pagando à vista`;
      $("#offerText").textContent = "Em qualquer serviço, sem letra miúda. Peça seu orçamento e receba preço e prazo na hora.";
      $("#offerCta").textContent = "Pedir meu orçamento";
      $("#offerFine").textContent = "Desconto aplicado no pagamento à vista (Pix).";
    }
  }

  function countdown(target, label) {
    const el = $("#countdown");
    el.hidden = false;
    el.setAttribute("aria-label", label);
    let prev = [];
    const tick = () => {
      let s = Math.max(0, Math.floor((target - Date.now()) / 1000));
      if (s === 0) { location.reload(); return; }
      const d = Math.floor(s / 86400); s %= 86400;
      const h = Math.floor(s / 3600); s %= 3600;
      const m = Math.floor(s / 60); s %= 60;
      const pad = (n) => String(n).padStart(2, "0");
      const parts = (d ? [[d, "dias"]] : []).concat([[pad(h), "horas"], [pad(m), "min"], [pad(s), "seg"]]);
      if (el.children.length !== parts.length) el.innerHTML = parts.map(([, l]) => `<div><b></b><small>${l}</small></div>`).join("");
      parts.forEach(([v], i) => {
        const b = el.children[i].firstElementChild;
        if (prev[i] !== String(v)) { b.textContent = v; b.classList.remove("tick"); void b.offsetWidth; if (prev.length) b.classList.add("tick"); }
      });
      prev = parts.map(([v]) => String(v));
    };
    tick();
    setInterval(tick, 1000);
  }

  /* ---------- Renderização do conteúdo ---------- */
  function render() {
    document.querySelectorAll("[data-c]").forEach((el) => { el.textContent = get(el.dataset.c) ?? ""; });
    document.querySelectorAll("[data-c-html]").forEach((el) => { el.innerHTML = safeHtml(get(el.dataset.cHtml)); });

    $("#cred").innerHTML = C.credibility.map((c) => `<div class="cred__item"><b>${esc(c.value)}</b><span>${esc(c.label)}</span></div>`).join("");
    $("#pains").innerHTML = C.problem.items.map((t) => `<li>${icon("x")}<span>${esc(t)}</span></li>`).join("");
    $("#bridgeFrom").innerHTML = C.solution.from.map((t) => `<li>${icon("x")}${esc(t)}</li>`).join("");
    $("#bridgeTo").innerHTML = C.solution.to.map((t) => `<li>${icon("check")}${esc(t)}</li>`).join("");

    $("#services").innerHTML = C.services.map((s) => `
      <article class="service reveal">
        <div class="service__ico">${icon(s.icon)}</div>
        <h3>${esc(s.name)}</h3>
        <p>${esc(s.desc)}</p>
        ${s.price ? `<p class="service__price">${esc(s.price)}</p>` : ""}
        <a href="#" data-wa="servico" data-service="${esc(s.name)}">Pedir orçamento ${icon("arrow")}</a>
      </article>`).join("");

    $("#benefits").innerHTML = C.benefits.map((b) => `
      <div class="benefit reveal"><div class="benefit__ico">${icon(b.icon)}</div><h3>${esc(b.title)}</h3><p>${esc(b.text)}</p></div>`).join("");

    $("#steps").innerHTML = C.steps.map((s) => `<li class="step reveal"><h3>${esc(s.title)}</h3><p>${esc(s.text)}</p></li>`).join("");

    $("#testis").innerHTML = C.testimonials.map((t) => {
      const initials = esc(t.name.split(" ").map((w) => w[0]).slice(0, 2).join("").toUpperCase());
      const photo = t.photo ? `<img src="${esc(t.photo)}" alt="Foto de ${esc(t.name)}" loading="lazy" width="46" height="46">` : `<span class="avatar" aria-hidden="true">${initials}</span>`;
      return `
      <figure class="testi reveal">
        ${t.placeholder ? '<span class="tag-demo">EXEMPLO</span>' : ""}
        <span class="testi__result">${icon("trend")} ${esc(t.result)}</span>
        <div class="testi__stars" aria-label="5 estrelas">${icon("star").repeat(5)}</div>
        <blockquote>“${esc(t.text)}”</blockquote>
        <figcaption class="testi__who">${photo}<div><b>${esc(t.name)}</b><small>${esc(t.role)}</small></div></figcaption>
      </figure>`;
    }).join("");

    $("#faqList").innerHTML = C.faq.map((f, i) => `<details${i === 0 ? " open" : ""}><summary>${esc(f.q)}</summary><p>${esc(f.a)}</p></details>`).join("");

    $("#serviceSelect").innerHTML = '<option value="">Ainda não sei</option>' + C.services.map((s) => `<option>${esc(s.name)}</option>`).join("");
    $("#year").textContent = new Date().getFullYear();
    // Seções escondidas pelo CMS ou por uma variante do teste A/B
    (C.hiddenSections || []).forEach((id) => { const el = document.getElementById(id); if (el) el.hidden = true; });
  }

  /* ---------- Links de WhatsApp (todos os CTAs) ---------- */
  function wireWhatsApp() {
    document.addEventListener("click", (e) => {
      const a = e.target.closest("[data-wa]");
      if (!a) return;
      const service = a.dataset.service;
      a.href = waMessage(service ? `Tenho interesse em: ${service}.` : "");
      a.target = "_blank";
      a.rel = "noopener";
      track("whatsapp_click", { placement: a.dataset.wa, service: service || null });
      pixelEvent("contact");
    });
    // href real já no carregamento (funciona com botão do meio / copiar link)
    document.querySelectorAll("[data-wa]").forEach((a) => {
      a.href = waMessage(a.dataset.service ? `Tenho interesse em: ${a.dataset.service}.` : "");
      a.target = "_blank";
      a.rel = "noopener";
    });
  }

  /* ---------- Formulário de lead ---------- */
  function wireForm() {
    const form = $("#leadForm");
    const msg = $("#formMsg");
    form.addEventListener("submit", async (e) => {
      e.preventDefault();
      const fd = new FormData(form);
      const data = Object.fromEntries(fd.entries());
      const phoneDigits = String(data.phone || "").replace(/\D/g, "");

      // validação no navegador (o servidor valida de novo)
      let ok = true;
      form.querySelectorAll("[aria-invalid]").forEach((el) => el.removeAttribute("aria-invalid"));
      if (String(data.name || "").trim().length < 2) { form.name.setAttribute("aria-invalid", "true"); ok = false; }
      if (phoneDigits.length < 10 || phoneDigits.length > 13) { form.phone.setAttribute("aria-invalid", "true"); ok = false; }
      if (!form.consent.checked) { ok = false; }
      if (!ok) { msg.className = "form__msg err"; msg.textContent = "Confira nome, WhatsApp e o consentimento."; return; }

      if (data.website) return; // honeypot preenchido = robô

      const extra = `Meu nome é ${data.name}.` + (data.service ? ` Tenho interesse em: ${data.service}.` : "");
      if (!API) { // modo sem painel: abre o WhatsApp direto
        window.open(waMessage(extra), "_blank", "noopener");
        msg.className = "form__msg ok"; msg.textContent = "Abrimos o WhatsApp para você.";
        return;
      }

      const btn = form.querySelector("button");
      btn.disabled = true; btn.textContent = "Enviando…";
      try {
        const res = await fetch(API + "/api/public/leads", {
          method: "POST",
          headers: { "Content-Type": "application/json" },
          body: JSON.stringify({
            name: data.name, phone: phoneDigits, instagram: data.instagram || null, service: data.service || null,
            consent: true, visitorId, variant: C.variant, utm, referrer: document.referrer || null, website: data.website || "",
          }),
        });
        if (!res.ok) throw new Error(String(res.status));
        form.reset();
        pixelEvent("lead");
        msg.className = "form__msg ok";
        msg.innerHTML = `Recebido! Vou te chamar em breve. Quer adiantar? <a href="${waMessage(extra)}" target="_blank" rel="noopener">Abrir WhatsApp</a>`;
      } catch {
        msg.className = "form__msg err";
        msg.innerHTML = `Não consegui enviar agora. <a href="${waMessage(extra)}" target="_blank" rel="noopener">Me chama direto no WhatsApp</a>.`;
      } finally {
        btn.disabled = false; btn.textContent = "Quero ser chamado";
      }
    });
  }

  /* ---------- Animações e barra fixa no celular ---------- */
  function wireUi() {
    const bar = $(".mobilebar");
    const hero = $(".hero");
    const top = $("#topbar");
    const progress = $("#progress");
    const scrollDriven = CSS.supports && CSS.supports("animation-timeline: scroll()");
    const onScroll = () => {
      bar.classList.toggle("show", hero.getBoundingClientRect().bottom < 0);
      top.classList.toggle("scrolled", scrollY > 10);
      if (!scrollDriven) {
        const max = document.documentElement.scrollHeight - innerHeight;
        progress.style.transform = `scaleX(${max > 0 ? scrollY / max : 0})`;
      }
    };
    addEventListener("scroll", onScroll, { passive: true });
    onScroll();
  }

  /* ---------- Efeitos (só quando o usuário não pediu "reduzir movimento") ---------- */
  function wireEffects() {
    // Faixa de serviços (duplicada para rolar sem emenda)
    const items = C.services.map((s) => `<span>${esc(s.name)}</span>`).join("") + `<span>Entrega em 24h</span>`;
    $("#marquee").innerHTML = items + items;

    // Título palavra por palavra
    const h1 = $(".hero__title");
    let i = 0;
    [...h1.childNodes].forEach((node) => {
      if (node.nodeType === 3) {
        const frag = document.createDocumentFragment();
        node.textContent.split(/(\s+)/).forEach((part) => {
          if (!part) return;
          if (/^\s+$/.test(part)) { frag.append(part); return; }
          const w = document.createElement("span");
          w.className = "w"; w.style.setProperty("--i", i++); w.textContent = part;
          frag.append(w);
        });
        node.replaceWith(frag);
      } else if (node.nodeType === 1) {
        node.classList.add("w"); node.style.setProperty("--i", i++);
      }
    });

    if (matchMedia("(prefers-reduced-motion: reduce)").matches) return;

    // Números da barra de credibilidade contando
    const countUp = (el) => {
      const m = el.textContent.match(/^([-+]?)(\d+)(.*)$/);
      if (!m) return;
      const [, sign, num, rest] = m;
      const end = Number(num); const t0 = performance.now(); const dur = 1300;
      const step = (t) => {
        const p = Math.min(1, (t - t0) / dur); const e = 1 - Math.pow(1 - p, 3);
        el.textContent = sign + Math.round(end * e) + rest;
        if (p < 1) requestAnimationFrame(step);
      };
      requestAnimationFrame(step);
    };
    if ("IntersectionObserver" in window) {
      const io = new IntersectionObserver((entries) => entries.forEach((en) => {
        if (en.isIntersecting) { countUp(en.target); io.unobserve(en.target); }
      }), { threshold: .6 });
      document.querySelectorAll(".cred__item b").forEach((b) => io.observe(b));
    }

    const finePointer = matchMedia("(pointer: fine)").matches;
    if (!finePointer) return;

    // Celular em 3D + brilho do fundo seguindo o mouse
    const visual = $(".hero__visual"); const phone = $(".phone"); const heroEl = $(".hero");
    heroEl.addEventListener("pointermove", (e) => {
      const r = heroEl.getBoundingClientRect();
      heroEl.style.setProperty("--gx", ((e.clientX - r.left) / r.width) * 100 + "%");
      heroEl.style.setProperty("--gy", ((e.clientY - r.top) / r.height) * 100 + "%");
      const v = visual.getBoundingClientRect();
      const x = (e.clientX - (v.left + v.width / 2)) / v.width;
      const y = (e.clientY - (v.top + v.height / 2)) / v.height;
      phone.style.setProperty("--ry", (x * 18).toFixed(2) + "deg");
      phone.style.setProperty("--rx", (-y * 14).toFixed(2) + "deg");
    });
    heroEl.addEventListener("pointerleave", () => { phone.style.setProperty("--rx", "0deg"); phone.style.setProperty("--ry", "0deg"); });

    // Luz que segue o cursor nos cartões
    document.addEventListener("pointermove", (e) => {
      const card = e.target.closest(".service, .benefit, .testi, .step");
      if (!card) return;
      const r = card.getBoundingClientRect();
      card.style.setProperty("--mx", e.clientX - r.left + "px");
      card.style.setProperty("--my", e.clientY - r.top + "px");
    }, { passive: true });

    // Botões "magnéticos" no hero e na oferta
    document.querySelectorAll(".hero .btn, .offer .btn").forEach((btn) => {
      btn.addEventListener("pointermove", (e) => {
        const r = btn.getBoundingClientRect();
        btn.style.transform = `translate(${(e.clientX - r.left - r.width / 2) * .15}px, ${(e.clientY - r.top - r.height / 2) * .25}px)`;
      });
      btn.addEventListener("pointerleave", () => { btn.style.transform = ""; });
    });
  }

  render();
  renderOffer();
  wireWhatsApp();
  wireForm();
  wireUi();
  wireEffects();
  wireConsent();
  track("page_view");
})();

</script>
</body>
</html>
