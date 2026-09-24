<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sopaan · Statistics</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Source+Sans+3:wght@400;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap">
<style>
  html,body{margin:0;} img{max-width:100%;} [hidden]{display:none !important;}
  :root{
    --navy:#16264A; --navy-2:#1F3B6B; --gold:#C79A3E; --gold-soft:#F3E7C9;
    --paper:#FBF9F4; --paper-2:#F1EAD8; --card:#FFFFFF;
    --ink:#211E1A; --ink-soft:#655D4C; --rule:#E4DCC8;
    --success:#2E8B57; --success-soft:#E1F2E7;
    --danger:#BF4B45; --danger-soft:#FAE3E1;
    --locked:#C7BEA9;
    --focus:#1F3B6B;
    --accent-text:#1F3B6B; --retry-text:#8A661F;
    color-scheme:light;
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
      --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
      --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
      --success:#7BC79A; --success-soft:#1B2E22;
      --danger:#E38884; --danger-soft:#331D1B;
      --locked:#4A4436;
      --focus:#E0B75B;
      --accent-text:#E0B75B; --retry-text:#E0B75B;
      color-scheme:dark;
    }
  }
  :root[data-theme="dark"]{
    --navy:#0E1830; --navy-2:#16264A; --gold:#E0B75B; --gold-soft:#3A2F16;
    --paper:#141210; --paper-2:#1C1914; --card:#1C1914;
    --ink:#EDE7DA; --ink-soft:#B2A996; --rule:#3A342A;
    --success:#7BC79A; --success-soft:#1B2E22;
    --danger:#E38884; --danger-soft:#331D1B;
    --locked:#4A4436;
    --focus:#E0B75B;
    --accent-text:#E0B75B; --retry-text:#E0B75B;
    color-scheme:dark;
  }

  *{box-sizing:border-box;}
  body{background:var(--paper); color:var(--ink); font-family:'Source Sans 3',-apple-system,'Segoe UI',sans-serif; padding-inline:0; padding-block:0;}
  h1,h2,h3{font-family:'Fraunces',Georgia,serif; text-wrap:balance; margin:0;}
  .num{font-family:'IBM Plex Mono',ui-monospace,monospace; font-variant-numeric:tabular-nums;}

  header.brand{
    background:linear-gradient(155deg,var(--navy) 0%, var(--navy-2) 100%);
    color:#F4EFDF; padding-block:calc(20px + env(safe-area-inset-top,0px)) 18px; padding-inline:20px;
  }
  .brand-row{display:flex; align-items:center; gap:12px; max-width:900px; margin:0 auto;}
  .crest{
    width:42px; height:42px; border-radius:10px; background:var(--gold); color:var(--navy);
    display:flex; align-items:center; justify-content:center; font-family:'Fraunces',serif; font-weight:700; font-size:18px; flex-shrink:0;
  }
  .brand-name{font-size:12px; letter-spacing:.08em; text-transform:uppercase; color:var(--gold); font-weight:700;}
  .series-name{font-size:19px; font-weight:700; font-family:'Fraunces',serif;}
  .chapter-eyebrow{max-width:900px; margin:14px auto 0; font-size:12px; letter-spacing:.06em; text-transform:uppercase; color:#AEB9D6;}
  .chapter-title{font-size:28px; max-width:900px; margin:2px auto 0;}
  .chapter-sub{font-size:14.5px; color:var(--gold); font-weight:700; max-width:900px; margin:3px auto 0;}

  .chapter-progress{max-width:900px; margin:14px auto 0; display:flex; align-items:center; gap:10px;}
  .cp-track{flex:1; height:6px; border-radius:99px; background:rgba(255,255,255,.18); overflow:hidden;}
  .cp-fill{height:100%; background:var(--gold); border-radius:99px; transition:width .3s ease;}
  .cp-label{font-size:11.5px; color:#CFD7EA; white-space:nowrap;}

  .tabbar{position:sticky; top:env(safe-area-inset-top,0px); z-index:15; background:var(--paper); border-bottom:1px solid var(--rule); overflow-x:auto; white-space:nowrap;}
  .tabbar-inner{max-width:900px; margin:0 auto; display:flex; padding-inline:16px;}
  .tab-btn{font-family:inherit; font-size:14px; font-weight:600; color:var(--ink-soft); background:none; border:none; padding:13px 16px; cursor:pointer; position:relative; flex-shrink:0;}
  .tab-btn.active{color:var(--accent-text);}
  .tab-btn.active::after{content:''; position:absolute; left:12px; right:12px; bottom:0; height:3px; background:var(--gold); border-radius:3px 3px 0 0;}
  .tab-count{font-size:11px; color:var(--ink-soft); margin-left:5px;}

  .slide-progress{max-width:900px; margin:0 auto; padding:10px 16px 0; display:flex; align-items:center; gap:10px;}
  .sp-track{flex:1; height:5px; border-radius:99px; background:var(--rule); overflow:hidden;}
  .sp-fill{height:100%; background:var(--accent-text); border-radius:99px; transition:width .3s ease;}
  .sp-label{font-size:12px; color:var(--ink-soft); white-space:nowrap; font-weight:600;}

  .wrap{max-width:900px; margin:0 auto; padding:16px 16px calc(110px + env(safe-area-inset-bottom,0px));}

  .qcard{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px;}
  .qhead{display:flex; align-items:flex-start; gap:10px; margin-bottom:10px;}
  .qnum{width:32px; height:32px; border-radius:8px; background:var(--gold-soft); color:var(--accent-text); display:flex; align-items:center; justify-content:center; font-weight:700; font-family:'Fraunces',serif; flex-shrink:0; font-size:14px;}
  .qtext{font-size:16px; line-height:1.55; flex:1;}
  .qtag{font-size:10.5px; color:var(--gold); background:var(--gold-soft); padding:2px 7px; border-radius:99px; font-weight:700; margin-left:6px; white-space:nowrap;}
  .marks-pill{font-size:11px; font-weight:700; color:var(--ink-soft); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; margin-left:auto; flex-shrink:0; white-space:nowrap;}
  .step-badge{font-size:11px; font-weight:700; color:var(--accent-text); background:var(--paper-2); border:1px solid var(--rule); padding:3px 9px; border-radius:99px; display:inline-block; margin-bottom:12px;}

  .options{display:flex; flex-direction:column; gap:8px; margin-top:10px;}
  .opt{display:flex; align-items:center; gap:10px; padding:11px 12px; border:1.5px solid var(--rule); border-radius:10px; cursor:pointer; font-size:15px; background:var(--paper);}
  .opt input{accent-color:var(--navy-2);}
  .opt.is-correct{border-color:var(--success); background:var(--success-soft);}
  .opt.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .opt.locked{cursor:not-allowed;}

  .subpart-label{font-weight:700; font-size:12.5px; color:var(--accent-text); text-transform:uppercase; letter-spacing:.03em; margin:14px 0 6px;}
  .or-divider{text-align:center; font-size:11px; font-weight:700; letter-spacing:.08em; color:var(--ink-soft); margin:8px 0;}

  .steps{display:flex; flex-direction:column; gap:10px;}
  .step-line{font-size:14.5px; line-height:1.9; background:var(--paper); border:1px dashed var(--rule); border-radius:10px; padding:9px 12px;}
  .step-line.resolved{opacity:.9;}
  .blank-input{font-family:'IBM Plex Mono',monospace; font-size:14px; border:1.5px solid var(--rule); border-radius:6px; padding:3px 8px; width:120px; background:var(--card); color:var(--ink); margin:0 2px;}
  .blank-input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .blank-input.is-correct{border-color:var(--success); background:var(--success-soft);}
  .blank-input.is-wrong{border-color:var(--danger); background:var(--danger-soft);}
  .blank-input[disabled]{opacity:.85;}
  .reveal-note{font-size:12px; color:var(--danger); padding-left:2px; margin-top:-2px;}

  .feedback{font-size:13.5px; padding:10px 12px; border-radius:9px; margin-top:14px; display:none;}
  .feedback.show{display:block;}
  .feedback.ok{background:var(--success-soft); color:var(--success);}
  .feedback.retry{background:var(--gold-soft); color:var(--retry-text);}
  .feedback.reveal{background:var(--danger-soft); color:var(--danger);}
  .feedback.err{background:var(--danger-soft); color:var(--danger);}
  .attempts-dots{display:inline-flex; gap:4px; margin-left:2px;}
  .attempts-dots span{width:6px; height:6px; border-radius:50%; background:var(--ink-soft); opacity:.3; display:inline-block;}
  .attempts-dots span.used{opacity:1; background:var(--danger);}

  .ar-box{background:var(--paper-2); border-radius:10px; padding:10px 12px; margin-bottom:12px; font-size:13px; color:var(--ink-soft);}

  .navbar{
    position:fixed; left:0; right:0; bottom:0; z-index:30; background:var(--paper);
    border-top:1px solid var(--rule); padding:10px 16px calc(10px + env(safe-area-inset-bottom,0px));
  }
  .navbar-inner{max-width:900px; margin:0 auto; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
  .btn{font-family:inherit; font-size:13.5px; font-weight:700; padding:10px 14px; border-radius:9px; border:1.5px solid var(--rule); background:var(--card); color:var(--ink); cursor:pointer;}
  .btn:hover{border-color:var(--navy-2);}
  .btn:disabled{opacity:.4; cursor:not-allowed;}
  .btn-primary{background:var(--navy-2); color:#fff; border-color:var(--navy-2);}
  .navbar .spacer{flex:1;}

  .fab{position:fixed; right:16px; bottom:calc(74px + env(safe-area-inset-bottom,0px)); background:var(--gold); color:var(--navy); border:none; border-radius:999px; padding:11px 16px; font-family:inherit; font-weight:700; font-size:13px; display:flex; align-items:center; gap:7px; cursor:pointer; box-shadow:0 6px 16px rgba(0,0,0,.18); z-index:35;}
  .fab-badge{background:rgba(255,255,255,.55); border-radius:99px; padding:1px 7px; font-size:11px;}

  .overlay{position:fixed; inset:0; background:rgba(20,18,14,.45); z-index:50; display:none; align-items:flex-end; justify-content:center;}
  .overlay.show{display:flex;}
  .palette{background:var(--card); width:min(480px,100%); max-height:78vh; overflow-y:auto; border-radius:18px 18px 0 0; padding:18px 18px calc(18px + env(safe-area-inset-bottom,0px)); border:1px solid var(--rule); border-bottom:none;}
  @media (min-width:640px){ .overlay{align-items:center;} .palette{border-radius:18px; border-bottom:1px solid var(--rule); max-height:74vh;} }
  .palette-head{display:flex; align-items:center; justify-content:space-between; margin-bottom:6px;}
  .palette-head h2{font-size:16px;}
  .palette-close{background:none; border:none; font-size:20px; color:var(--ink-soft); cursor:pointer; padding:4px;}
  .palette-legend{display:flex; gap:12px; flex-wrap:wrap; font-size:11px; color:var(--ink-soft); margin:10px 0 14px;}
  .palette-legend span{display:inline-flex; align-items:center; gap:5px;}
  .dot{width:9px; height:9px; border-radius:50%; display:inline-block;}
  .dot.correct{background:var(--success);} .dot.revealed{background:var(--danger);}
  .dot.skipped{background:var(--gold);} .dot.locked{background:var(--locked);}
  .dot.current{background:var(--navy-2);}
  .chip-grid{display:grid; grid-template-columns:repeat(auto-fill,minmax(48px,1fr)); gap:8px;}
  .chip{border:1.5px solid var(--rule); border-radius:9px; padding:8px 4px; text-align:center; font-family:'IBM Plex Mono',monospace; font-size:12.5px; font-weight:600; cursor:pointer; background:var(--paper); color:var(--ink);}
  .chip[data-status="correct"]{border-color:var(--success); background:var(--success-soft); color:var(--success);}
  .chip[data-status="revealed"]{border-color:var(--danger); background:var(--danger-soft); color:var(--danger);}
  .chip[data-status="skipped"]{border-color:var(--gold); background:var(--gold-soft); color:var(--retry-text);}
  .chip[data-status="locked"]{border-color:var(--rule); color:var(--locked); cursor:not-allowed; background:var(--paper-2);}
  .chip[data-status="current"]{outline:2px solid var(--navy-2); outline-offset:1px;}

  .toast{position:fixed; left:50%; bottom:calc(140px + env(safe-area-inset-bottom,0px)); transform:translateX(-50%); background:var(--ink); color:var(--paper); padding:9px 16px; border-radius:99px; font-size:13px; opacity:0; pointer-events:none; transition:opacity .25s ease; z-index:60;}
  .toast.show{opacity:1;}

  .done-card{text-align:center; padding:36px 20px;}
  .done-card .big{font-size:38px; margin-bottom:6px;}
  .score-pills{display:flex; gap:10px; justify-content:center; flex-wrap:wrap; margin:16px 0;}
  .score-pill{padding:8px 16px; border-radius:99px; font-size:13px; font-weight:700;}

  footer.brandfoot{max-width:900px; margin:14px auto 0; padding:0 16px calc(110px + env(safe-area-inset-bottom,0px)); text-align:center; font-size:12px; color:var(--ink-soft);}

  .mode-pill{font-family:inherit; font-size:12.5px; font-weight:700; color:var(--navy); background:var(--gold); border:none; border-radius:99px; padding:6px 14px; cursor:pointer; margin-top:12px; display:inline-flex; align-items:center; gap:6px;}
  .mode-pick{display:flex; flex-direction:column; gap:14px; padding:8px 0 24px;}
  .mode-card{background:var(--card); border:1.5px solid var(--rule); border-radius:16px; padding:22px; cursor:pointer; text-align:left;}
  .mode-card:hover{border-color:var(--navy-2);}
  .mode-card .mode-icon{font-size:26px; margin-bottom:8px;}
  .mode-card h3{font-size:18px; margin-bottom:6px;}
  .mode-card p{font-size:13.5px; color:var(--ink-soft); line-height:1.5; margin:0;}
  .quiz-hint{font-size:12.5px; color:var(--ink-soft); background:var(--paper-2); border-radius:9px; padding:8px 12px; margin-bottom:14px;}
  .review-row{border:1px solid var(--rule); border-radius:10px; padding:11px 13px; margin-bottom:10px;}
  .review-tag{font-size:11.5px; font-weight:700; margin-bottom:4px; display:block;}
  .review-tag.ok{color:var(--success);} .review-tag.bad{color:var(--danger);} .review-tag.na{color:var(--ink-soft);}
  .review-q{font-size:13.5px; margin-bottom:6px; color:var(--ink-soft);}
  .review-ans{font-size:13px; margin-bottom:2px;}

  .who-row{max-width:900px; margin:12px auto 0; display:flex; flex-wrap:wrap; gap:8px; align-items:center;}
  .who-row .mode-pill{margin-top:0;}
  .who{display:inline-flex; flex-wrap:wrap; align-items:center; gap:6px; font-size:12.5px; color:#CFD7EA;}
  .who b{color:#F4EFDF;}
  .who button{font-family:inherit; font-size:12px; font-weight:700; color:#F4EFDF; background:rgba(255,255,255,.12); border:1px solid rgba(255,255,255,.22); border-radius:99px; padding:5px 11px; cursor:pointer;}
  .who button:hover{background:rgba(255,255,255,.2);}
  .login-card{max-width:460px; margin:8px auto 0; background:var(--card); border:1px solid var(--rule); border-radius:16px; padding:22px;}
  .login-card h2{font-size:21px; margin-bottom:4px;}
  .login-card p.lead{font-size:13.5px; color:var(--ink-soft); margin:0 0 16px; line-height:1.5;}
  .fld{display:flex; flex-direction:column; gap:5px; margin-bottom:12px;}
  .fld label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .fld input{font-family:inherit; font-size:15px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:9px; background:var(--paper); color:var(--ink);}
  .fld input:focus{outline:none; border-color:var(--focus); box-shadow:0 0 0 3px var(--gold-soft);}
  .fld-row{display:grid; grid-template-columns:1fr 1fr; gap:10px;}
  .login-err{font-size:13px; color:var(--danger); background:var(--danger-soft); border-radius:8px; padding:8px 10px; margin-bottom:12px;}
  .login-note{font-size:12px; color:var(--ink-soft); margin-top:12px; line-height:1.5;}
  .known{margin:0 0 16px; display:flex; flex-direction:column; gap:6px;}
  .known-label{font-size:12px; font-weight:700; letter-spacing:.04em; text-transform:uppercase; color:var(--ink-soft);}
  .known-btn{display:flex; justify-content:space-between; align-items:center; gap:10px; text-align:left; font-family:inherit; font-size:14.5px; padding:10px 12px; border:1.5px solid var(--rule); border-radius:10px; background:var(--paper); color:var(--ink); cursor:pointer;}
  .known-btn:hover{border-color:var(--navy-2);}
  .known-btn small{font-size:12px; color:var(--ink-soft);}
  .rec-card{background:var(--card); border:1px solid var(--rule); border-radius:14px; padding:18px; margin-bottom:14px;}
  .rec-card h2{font-size:19px; margin-bottom:10px;}
  .rec-card h3{font-size:15px; margin:4px 0 8px;}
  .rec-table-wrap{overflow-x:auto;}
  .rec-table{width:100%; border-collapse:collapse; font-size:13.5px; font-variant-numeric:tabular-nums;}
  .rec-table th{text-align:left; font-size:11.5px; text-transform:uppercase; letter-spacing:.04em; color:var(--ink-soft); padding:6px 8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-table td{padding:8px; border-bottom:1px solid var(--rule); white-space:nowrap;}
  .rec-bar{display:inline-block; width:70px; height:6px; border-radius:99px; background:var(--rule); overflow:hidden; vertical-align:middle; margin-right:6px;}
  .rec-bar i{display:block; height:100%; background:var(--success);}
  .rec-empty{font-size:13.5px; color:var(--ink-soft);}
  .sec-sub{max-width:900px; margin:0 auto; padding:10px 16px 0; font-size:12.5px; font-weight:700; color:var(--accent-text); letter-spacing:.02em;}
  .opt{flex-wrap:wrap;}
  .opt-l{font-family:'IBM Plex Mono',monospace; font-size:13px; font-weight:600; color:var(--ink-soft);}
  .opt-t{flex:1; min-width:0;}
  .opt.is-chosen:not(.is-correct):not(.is-wrong){border-color:var(--navy-2); background:var(--gold-soft);}
  .opt-tag{font-size:11px; font-weight:700; padding:2px 8px; border-radius:99px; background:var(--card); border:1px solid currentColor; white-space:nowrap;}
  .opt.is-correct .opt-tag{color:var(--success);} .opt.is-wrong .opt-tag{color:var(--danger);} .opt.is-chosen:not(.is-correct):not(.is-wrong) .opt-tag{color:var(--accent-text);}
  .chosen{font-size:13.5px; margin-top:10px; padding:8px 12px; border-radius:9px;}
  .chosen.ok{background:var(--success-soft); color:var(--success);} .chosen.bad{background:var(--danger-soft); color:var(--danger);}
  .chosen + .chosen{margin-top:6px;}
  .solution{margin-top:14px; border:1px solid var(--rule); border-left:4px solid var(--gold); background:var(--paper-2); border-radius:10px; padding:12px 14px;}
  .sol-h{font-family:'Fraunces',Georgia,serif; font-weight:700; font-size:14px; color:var(--accent-text); margin-bottom:6px;}
  .sol-line{font-size:14.5px; line-height:1.7;}
  .rev-sol summary{cursor:pointer; font-size:12.5px; font-weight:700; color:var(--accent-text); margin-top:6px;}
  .rev-sol .solution{margin-top:8px;}
  .chapter-credit{max-width:900px; margin:4px auto 0; font-size:12px; color:#CFD7EA;}
  footer.brandfoot a{color:inherit;}
  .blank-input.wide{width:260px; max-width:100%; font-family:'Source Sans 3',sans-serif;}
  .blank-input.expr{width:170px; max-width:100%;}
  /*fix-layout*/ .cp-fill,.sp-fill{width:0;} .fld{min-width:0;} .fld input{width:100%; min-width:0; box-sizing:border-box;}
  .fig{margin:6px 0 10px; display:flex; justify-content:center;}
  .figsvg{width:100%; max-width:340px; height:auto; overflow:visible;}
  .figsvg .ln,.figsvg .arm{stroke:var(--ink); stroke-width:1.6; fill:none;}
  .figsvg .arm{stroke:var(--accent-text); stroke-width:2;}
  .figsvg .pt{fill:var(--ink);}
  .figsvg .lb{fill:var(--ink); font:600 13px 'Source Sans 3',sans-serif;}
  .figsvg .al{fill:var(--accent-text); font:700 12px 'Source Sans 3',sans-serif;}
  .figsvg .wg{fill:var(--gold-soft); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .wg2{fill:rgba(199,154,62,.35); stroke:var(--gold); stroke-width:1.2;}
  .figsvg .ra{fill:none; stroke:var(--ink); stroke-width:1.2;}
  .figsvg .ahd{fill:var(--ink);}
  .figsvg .pr{fill:var(--paper-2); stroke:var(--ink-soft); stroke-width:1.2;}
  .figsvg .tk{stroke:var(--ink-soft); stroke-width:.8;}
  .figsvg .po{fill:var(--ink); font:600 8.5px 'IBM Plex Mono',monospace;}
  .figsvg .pi{fill:var(--danger); font:600 7.5px 'IBM Plex Mono',monospace;}
  .figsvg .sh{fill:var(--gold-soft); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh2{fill:rgba(199,154,62,.38); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .sh3{fill:rgba(199,154,62,.22); stroke:var(--ink); stroke-width:1.5; stroke-linejoin:round;}
  .figsvg .none{fill:none;}
  .figsvg .hid{stroke-dasharray:5 4; fill:none;}
  .figsvg .tick{stroke:var(--ink); stroke-width:1.4; fill:none;}
  .figsvg .shd{fill:var(--accent-text); fill-opacity:.55;}
  .figsvg .cell{fill:var(--card); stroke:var(--ink); stroke-width:1.1;}
  .figsvg .dr{fill:var(--danger);} .figsvg .dw{fill:var(--card); stroke:var(--ink); stroke-width:1.2;}
  .figsvg .dotfill{fill:var(--danger);}
  .tt{border-collapse:collapse; font-size:13.5px; margin:4px auto; font-variant-numeric:tabular-nums;} .tt th,.tt td{border:1px solid var(--rule); padding:4px 9px; text-align:left;} .tt th{background:var(--paper-2); font-weight:700;} .ttw{overflow-x:auto; max-width:100%;}
  .fq{display:inline-flex; flex-direction:column; vertical-align:middle; text-align:center; font-size:.82em; line-height:1.12; margin:0 2px;}
  .fq>span:first-child{border-bottom:1.5px solid currentColor; padding:0 2px;}
  .fq>span:last-child{padding:0 2px;}
  .mx{white-space:nowrap;}
  .blank-input.fr{width:110px;}
  @media (prefers-reduced-motion:reduce){ *{transition:none !important;} }
.datline{display:block;margin-top:8px;padding:8px 10px;border-radius:8px;background:var(--paper-2);font:500 14px/1.7 'IBM Plex Mono',monospace;word-spacing:2px;overflow-wrap:anywhere;}
</style>
</head>
<body>
<header class="brand">
  <div class="brand-row">
    <div class="crest">BM</div>
    <div>
      <div class="brand-name">Brain &amp; Mind Academy</div>
      <div class="series-name">Sopaan <span style="font-weight:400;font-size:14px;color:#CFD7EA;">Practice Series</span></div>
    </div>
  </div>
  <div class="chapter-eyebrow">Grade 6 Mathematics · Chapter 18</div>
  <div class="chapter-title">Statistics</div>
  <div class="chapter-sub">Exercises 18A–18G · Review Sets · Step-by-Step Practice</div><div class="chapter-credit">Follows Haese Mathematics 6 (MYP 1), Chapter 18</div>
  <div class="chapter-progress">
    <div class="cp-track"><div class="cp-fill" id="cpFill"></div></div>
    <div class="cp-label" id="cpLabel">0% complete</div>
  </div>
  <div class="who-row"><button class="mode-pill" id="modePill" hidden>Choose a mode</button><span class="who" id="whoBar" hidden></span></div>
</header>

<nav class="tabbar"><div class="tabbar-inner" id="tabbar"></div></nav>
<div class="sec-sub" id="secSub"></div><div class="slide-progress"><div class="sp-track"><div class="sp-fill" id="spFill"></div></div><div class="sp-label" id="spLabel">Question 1 of 49</div></div>
<div class="wrap" id="wrap"></div>
<footer class="brandfoot">Brain &amp; Mind Academy · Sopaan Practice Series · Grade 6 Mathematics<br>Exercises follow the structure of <i>Mathematics 6 (MYP 1), 3rd edition</i>, Haese Mathematics. Questions, steps and solutions written by Brain &amp; Mind Academy.</footer>

<div class="navbar"><div class="navbar-inner" id="navbarInner"></div></div>
<button class="fab" id="paletteFab"><span>Questions</span><span class="fab-badge" id="fabBadge">0/49</span></button>

<div class="overlay" id="overlay">
  <div class="palette" role="dialog" aria-label="Question palette">
    <div class="palette-head"><h2 id="paletteTitle">Question palette</h2><button class="palette-close" id="paletteClose">&times;</button></div>
    <div class="palette-legend">
      <span><i class="dot current"></i>Current</span><span><i class="dot correct"></i>Correct</span>
      <span><i class="dot revealed"></i>Revealed</span><span><i class="dot skipped"></i>Skipped</span>
      <span><i class="dot locked"></i>Locked</span>
    </div>
    <div class="chip-grid" id="paletteBody"></div>
  </div>
</div>
<div class="toast" id="toast"></div>

<script>
(function(){
"use strict";

/* ================= audio ================= */
var audioCtx=null;
function ensureAudio(){ if(!audioCtx){ try{ audioCtx=new (window.AudioContext||window.webkitAudioContext)(); }catch(e){} } return audioCtx; }
function playTone(freqs,dur,type){
  var ctx=ensureAudio(); if(!ctx) return;
  try{
    var t0=ctx.currentTime;
    freqs.forEach(function(f,i){
      var o=ctx.createOscillator(), g=ctx.createGain();
      o.type=type||'sine'; o.frequency.value=f;
      var start=t0+i*dur;
      g.gain.setValueAtTime(0.0001,start);
      g.gain.exponentialRampToValueAtTime(0.16,start+0.02);
      g.gain.exponentialRampToValueAtTime(0.0001,start+dur);
      o.connect(g); g.connect(ctx.destination);
      o.start(start); o.stop(start+dur+0.02);
    });
  }catch(e){}
}
function playSuccess(){ playTone([523.25,659.25,783.99],0.11,'sine'); }
function playWrong(){ playTone([220,185],0.14,'square'); }
function playReveal(){ playTone([300,220],0.16,'triangle'); }

/* ================= helpers ================= */
function norm(s){
  return String(s===undefined||s===null?'':s).trim().toLowerCase().replace(/\s+/g,'')
    .replace(/[×∗*·]/g,'x').replace(/÷/g,'/').replace(/–|—|−/g,'-')
    .replace(/[²]/g,'^2').replace(/[³]/g,'^3').replace(/[⁴]/g,'^4').replace(/[⁵]/g,'^5')
    .replace(/[⁶]/g,'^6').replace(/[⁷]/g,'^7').replace(/[⁸]/g,'^8').replace(/[⁹]/g,'^9')
    .replace(/\^/g,'');
}
function parseNum(s){
  if(s===undefined||s===null) return null;
  var t=String(s).trim().replace(/,/g,'').replace(/[−–—]/g,'-').replace(/\s+/g,''); if(t==='') return null;
  var neg=false; if(t[0]==='-'){neg=true;t=t.slice(1);}
  var m=t.match(/^(\d+)\/(\d+)$/);
  if(m){ var v=parseInt(m[1],10)/parseInt(m[2],10); return neg?-v:v; }
  if(/^\d+(\.\d+)?$/.test(t)){ var v2=parseFloat(t); return neg?-v2:v2; }
  return null;
}
/* ---- expression checker: compares answers like (P-2w)/2 and P/2-w at random values ---- */
function exprPrep(s){
  return String(s).replace(/\s+/g,'').replace(/[×∗·]/g,'*').replace(/÷/g,'/').replace(/[−–—]/g,'-')
    .replace(/²/g,'^2').replace(/³/g,'^3').replace(/π/g,'#').replace(/pi/gi,'#').replace(/½/g,'(1/2)');
}
function exprCompile(src){
  var s=exprPrep(src), i=0, toks=[];
  while(i<s.length){
    var ch=s[i];
    if(/[0-9.]/.test(ch)){ var j=i; while(j<s.length && /[0-9.]/.test(s[j])) j++; toks.push({k:'n',v:parseFloat(s.slice(i,j))}); i=j; continue; }
    if(/[a-zA-Z#]/.test(ch)){ toks.push({k:'v',v:ch}); i++; continue; }
    if('+-*/^()'.indexOf(ch)>=0){ toks.push({k:ch}); i++; continue; }
    return null;
  }
  var out=[];
  for(var t=0;t<toks.length;t++){
    var a=toks[t], b=out[out.length-1];
    if(b && (b.k==='n'||b.k==='v'||b.k===')') && (a.k==='n'||a.k==='v'||a.k==='(')) out.push({k:'&'});
    out.push(a);
  }
  var p=0;
  function peek(){ return out[p]; }
  function parseE(){ var n=parseT(); while(peek() && (peek().k==='+'||peek().k==='-')){ var o=out[p++].k, r=parseT(); n=(function(l,r,o){return function(e){ return o==='+'?l(e)+r(e):l(e)-r(e); };})(n,r,o); } return n; }
  function parseI(){ var n=parseU(); while(peek() && peek().k==='&'){ p++; var r=parseP(); n=(function(l,r){return function(e){ return l(e)*r(e); };})(n,r); } return n; }
  function parseT(){ var n=parseI(); while(peek() && (peek().k==='*'||peek().k==='/')){ var o=out[p++].k, r=parseI(); n=(function(l,r,o){return function(e){ return o==='*'?l(e)*r(e):l(e)/r(e); };})(n,r,o); } return n; }
  function parseU(){ if(peek() && peek().k==='-'){ p++; var u=parseU(); return function(e){ return -u(e); }; } if(peek() && peek().k==='+'){ p++; return parseU(); } return parseP(); }
  function parseP(){ var b=parseA(); if(peek() && peek().k==='^'){ p++; var x=parseU(); return function(e){ return Math.pow(b(e),x(e)); }; } return b; }
  function parseA(){
    var t=out[p++]; if(!t) throw 0;
    if(t.k==='n') return function(){ return t.v; };
    if(t.k==='v') return t.v==='#' ? function(){ return Math.PI; } : function(e){ return e[t.v]; };
    if(t.k==='('){ var n=parseE(); if(!peek()||peek().k!==')') throw 0; p++; return n; }
    throw 0;
  }
  try{ var f=parseE(); if(p!==out.length) return null; return f; }catch(e){ return null; }
}
function exprEqual(input,answer){
  var f=exprCompile(input), g=exprCompile(answer); if(!f||!g) return false;
  var hits=0;
  for(var trial=0;trial<8;trial++){
    var env={}; 'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'.split('').forEach(function(c){ env[c]=1.3+Math.random()*4.1; });
    var x=f(env), y=g(env);
    if(!isFinite(x)||!isFinite(y)) continue;
    if(Math.abs(x-y)>1e-7*Math.max(1,Math.abs(x),Math.abs(y))) return false;
    hits++;
  }
  return hits>=3;
}
function wordsNorm(s){ return String(s||'').toLowerCase().replace(/\band\b/g,' ').replace(/[^a-z]/g,''); }
function listNorm(s){ return (String(s||'').replace(/[−–—]/g,'-').replace(/(\d) (?=\d{3}\b)/g,'$1').match(/-?\d+(\.\d+)?/g)||[]).join(','); }
function powNorm(s){ return String(s||'').toLowerCase().replace(/\s+/g,'').replace(/[×∗*·.]/g,'x').replace(/[⁰¹²³⁴⁵⁶⁷⁸⁹]+/g,function(m){ return '^'+m.split('').map(function(c){ return '⁰¹²³⁴⁵⁶⁷⁸⁹'.indexOf(c); }).join(''); }).replace(/\^1(?!\d)/g,''); }
function fr(s){ return String(s).replace(/\{(\d+) (\d+)\/(\d+)\}/g,'<span class="mx">$1<span class="fq"><span>$2</span><span>$3</span></span></span>').replace(/\{(\d+)\/(\d+)\}/g,'<span class="fq"><span>$1</span><span>$2</span></span>'); }
function gcdI(a,b){ a=Math.abs(a); b=Math.abs(b); while(b){ var t=a%b; a=b; b=t; } return a; }
function fracParse(s){ s=String(s===undefined||s===null?'':s).trim().replace(/[\u2044\u2215\u00f7]/g,'/').replace(/\s+/g,' ').replace(/\s*\/\s*/g,'/'); var m;
  if((m=s.match(/^(-?\d+)$/))) return {v:+m[1],form:'int',n:+m[1],d:1};
  if((m=s.match(/^(-?\d+)\/(\d+)$/))){ if(+m[2]===0) return null; return {v:m[1]/m[2],form:'frac',n:+m[1],d:+m[2]}; }
  if((m=s.match(/^(\d+)(?: |\+|-)(\d+)\/(\d+)$/))){ if(+m[3]===0) return null; return {v:+m[1]+m[2]/m[3],form:'mixed',w:+m[1],n:+m[2],d:+m[3]}; }
  if((m=s.match(/^-?\d*\.\d+$/))) return {v:parseFloat(s),form:'dec'};
  return null; }
function fracOK(mode,input,answer){
  if(mode==='flist'){ var A=String(input).split(/[,;]/).map(function(x){return x.trim();}).filter(Boolean), K=String(answer).split(/[,;]/).map(function(x){return x.trim();});
    if(A.length!==K.length) return false; return A.every(function(x,i){ var a=fracParse(x), k=fracParse(K[i]); return a&&k&&Math.abs(a.v-k.v)<1e-9; }); }
  var a=fracParse(input), k=fracParse(answer); if(!a||!k) return false;
  var same=Math.abs(a.v-k.v)<1e-9; if(!same) return false;
  if(mode==='fv') return true;
  if(mode==='dec') return a.form==='dec'||a.form==='int';
  if(mode==='fe') return (a.form==='frac'&&k.form==='frac'&&a.n===k.n&&a.d===k.d)||(a.form==='int'&&k.form==='int');
  if(mode==='fi') return a.form==='frac'||(a.form==='int'&&k.form==='int');
  if(mode==='fl') return a.form==='int'||(a.form==='frac'&&gcdI(a.n,a.d)===1)||(a.form==='mixed'&&a.n<a.d&&gcdI(a.n,a.d)===1);
  if(mode==='fm') return a.form==='int'||(a.form==='mixed'&&a.n>0&&a.n<a.d&&gcdI(a.n,a.d)===1);
  return false; }
function answerMatches(input,answer,accept,expr){
  if(expr==='dec'||expr==='fv'||expr==='fe'||expr==='fl'||expr==='fm'||expr==='fi'||expr==='flist'){ if(input===undefined||input===null||String(input).trim()==='') return false; return fracOK(expr,input,answer); }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  if(expr==='words'){ return [answer].concat(accept||[]).some(function(a){ return wordsNorm(a)===wordsNorm(input); }); }
  if(expr==='list'){ return [answer].concat(accept||[]).some(function(a){ return listNorm(a)===listNorm(input); }); }
  if(expr==='pow'){ return [answer].concat(accept||[]).some(function(a){ return powNorm(a)===powNorm(input); }); }
  if(expr==='time'){ var tn=function(x){ var t=String(x).toLowerCase().replace(/[\s.]/g,'').replace(/[:h]/g,''); if(/^\d{3}(am|pm)?$/.test(t)) t='0'+t; return t; }; return [answer].concat(accept||[]).some(function(a){ return tn(a)===tn(input); }); }
  if(expr==='glist'){ var gn=function(x){ return String(x).toUpperCase().split(/[\s,;]+/).filter(Boolean).sort().join(','); }; return [answer].concat(accept||[]).some(function(a){ return gn(a)===gn(input); }); }
  if(expr==='coord'){ var cn=function(x){ return String(x).replace(/[\u2212\u2013\u2014]/g,'-').replace(/[\s()\[\]]/g,''); }; return [answer].concat(accept||[]).some(function(a){ return cn(a)===cn(input); }); }
  if(expr==='dlist'){ var dn=function(x){ return (String(x).match(/-?\d*\.?\d+/g)||[]).map(Number).join(','); }; return [answer].concat(accept||[]).some(function(a){ return dn(a)===dn(input); }); }
  if(expr==='set'){ var sn=function(x){ return (String(x).match(/-?\d+/g)||[]).map(Number).sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return sn(a)===sn(input); }); }
  if(expr==='primes'){ var pn=function(x){ var t=powNorm(x).replace(/[^0-9x^]/g,''); var out=[]; t.split('x').forEach(function(tok){ if(!tok) return; var m=tok.split('^'); var b=+m[0], e=m[1]?+m[1]:1; for(var i=0;i<e;i++) out.push(b); }); return out.sort(function(a,b){return a-b;}).join(','); }; return [answer].concat(accept||[]).some(function(a){ return pn(a)===pn(input); }); }
  if(expr==='angle'){ var an=function(x){ return String(x).toUpperCase().replace(/[^A-Z]/g,''); }; var k=an(answer), v=an(input); return v===k || v===k.split('').reverse().join(''); }
  if(expr==='trans'){ var tv=function(x){ var s=String(x).toLowerCase().replace(/[−–—]/g,'-').replace(/\b(units?|squares?|and|then|steps?|to|the|a)\b/g,' ').replace(/[,;.]/g,' '); var re=/(\d+)\s*(right|left|up|down|r|l|u|d)\b/g, m, dx=0, dy=0, n=0; while((m=re.exec(s))){ var v=+m[1], d=m[2][0]; if(d==='r')dx+=v; else if(d==='l')dx-=v; else if(d==='u')dy+=v; else dy-=v; n++; } if(!n||s.replace(re,'').replace(/\s+/g,'')!=='') return null; return dx+','+dy; }; var ti=tv(input); return ti!==null && [answer].concat(accept||[]).some(function(a){ return tv(a)===ti; }); }
  if(expr==='rot'){ var rv=function(x){ var s=String(x).toLowerCase().replace(/quarter[\s-]*turn/g,'90').replace(/half[\s-]*turn/g,'180').replace(/three[\s-]*quarter[\s-]*turn/g,'270'); var m=s.match(/\b(90|180|270)\b/); if(!m) return null; var a=+m[1]; if(a===180) return '180'; var dir=/anti|counter|acw|ccw/.test(s)?-1:(/clockwise|\bcw\b/.test(s)?1:0); if(!dir) return null; return String(((a*dir)%360+360)%360); }; var ri=rv(input); return ri!==null && ri===rv(answer); }
  if(expr==='expanded'){ var f=function(x){ return String(x).replace(/\s+/g,'').replace(/,/g,''); }; return [answer].concat(accept||[]).some(function(a){ return f(a)===f(input); }); }
  if(expr===true && input!==undefined && input!==null && String(input).trim()!==''){
    if(exprEqual(input,answer)) return true;
    return (accept||[]).some(function(a){ return exprEqual(input,a); });
  }
  if(input===undefined||input===null||String(input).trim()==='') return false;
  var n1=parseNum(input), n2=parseNum(answer);
  if(n1!==null && n2!==null) return Math.abs(n1-n2)<1e-3;
  var cands=[answer].concat(accept||[]); var ni=norm(input);
  for(var i=0;i<cands.length;i++){ if(norm(cands[i])===ni) return true; }
  return false;
}
function esc(s){ return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;'); }

/* ================= DATA ================= */
var AR_OPTIONS = ["Both A and R are true, and R is the correct explanation of A","Both A and R are true, but R is NOT the correct explanation of A","A is true but R is false","A is false but R is true"];
var SECTIONS = [{"id": "s1", "label": "Ex 18A", "sub": "Categorical data", "slides": [{"kind": "blank", "p": "Arjun (A), Bela (B), Chetan (C) and Diya (D) played carrom. The winner of each game was:\nA D A D  B B B C  B D D A  D D C B\nComplete the frequency column of a tally and frequency table.", "tag": "", "marks": "", "flat": [{"t": "a) Arjun: __B1__", "a": {"B1": "3"}}, {"t": "b) Bela: __B1__", "a": {"B1": "5"}}, {"t": "c) Chetan: __B1__", "a": {"B1": "2"}}, {"t": "d) Diya: __B1__", "a": {"B1": "6"}}, {"t": "e) total games: __B1__", "a": {"B1": "16"}}, {"t": "f) Who won the most games? __B1__", "a": {"B1": "Diya"}, "accept": ["D"]}, {"t": "g) Who won the fewest games? __B1__", "a": {"B1": "Chetan"}, "accept": ["C"]}], "sol": "Make one tally mark for each letter, bundling in fives.\nA: ||| = 3\nB: 卌 = 5\nC: || = 2\nD: 卌 | = 6\nTotal = 16\nMost: Diya (6) · fewest: Chetan (2)"}, {"kind": "blank", "p": "A school canteen recorded snacks sold in one break: samosa (S), juice (J), idli (I), poha (P).\nS I I J S  P S S J J  I I J I S  J I P S I  S S I S J  P S S P P", "tag": "", "marks": "", "flat": [{"t": "a) samosas sold: __B1__", "a": {"B1": "11"}}, {"t": "b) juices sold: __B1__", "a": {"B1": "6"}}, {"t": "c) idlis sold: __B1__", "a": {"B1": "8"}}, {"t": "d) poha sold: __B1__", "a": {"B1": "5"}}, {"t": "e) mode (write the snack name): __B1__", "a": {"B1": "samosa"}, "accept": ["S", "samosas"]}], "sol": "Count each letter with tally marks.\nS = 11, J = 6, I = 8, P = 5\nThe mode is the most frequent category: samosa. Samosas were the most popular snack."}, {"kind": "blank", "p": "On a zoo trip, each student named a favourite animal: tiger (T), elephant (E), peacock (Pe), monkey (M), rhino (R).\nT Pe M Pe T  T M E E E  R E T E M  R T T Pe E  T M M T", "tag": "", "marks": "", "flat": [{"t": "a) number of students: __B1__", "a": {"B1": "24"}}, {"t": "b) number who chose the tiger: __B1__", "a": {"B1": "8"}}, {"t": "c) most popular animal: __B1__", "a": {"B1": "tiger"}, "accept": ["T"]}, {"t": "d) fraction who chose the peacock (lowest terms): __B1__", "a": {"B1": "1/8"}, "expr": "fl"}], "sol": "a) 24 data values\nb) T appears 8 times\nc) tiger has the highest frequency\nd) 3 out of 24 = {1/8}"}, {"kind": "blank", "p": "Guests at a hotel rated the service: excellent (E), good (G), satisfactory (S), unsatisfactory (U).\nU U G S G  U S G G G  G E S E E  S S E G G", "tag": "", "marks": "", "flat": [{"t": "a) number who said excellent: __B1__", "a": {"B1": "4"}}, {"t": "b) number who said good: __B1__", "a": {"B1": "8"}}, {"t": "c) mode (write the word): __B1__", "a": {"B1": "good"}, "accept": ["G"]}, {"t": "d) fraction who said unsatisfactory (lowest terms): __B1__", "a": {"B1": "3/20"}, "expr": "fl"}, {"t": "e) percentage who said good or excellent: __B1__ %", "a": {"B1": "60"}}], "sol": "There are 20 responses.\na) 4\nb) 8\nc) good occurs most often\nd) 3 out of 20 = {3/20}\ne) 8 + 4 = 12 out of 20 = 60 %"}]}, {"id": "s2", "label": "Ex 18B", "sub": "Dot plots", "slides": [{"kind": "blank", "p": "Students at a school camp chose one afternoon activity. The dot plot shows their choices.", "tag": "", "marks": "", "flat": [{"t": "a) How many chose orienteering? __B1__", "a": {"B1": "3"}}, {"t": "b) How many students were at the camp? __B1__", "a": {"B1": "19"}}, {"t": "c) mode: __B1__", "a": {"B1": "canoeing"}}], "sol": "Each dot is one student.\na) 3\nb) 4 + 3 + 7 + 5 = 19\nc) the tallest column: canoeing", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 139\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Camp activities</text><line class=\"ln\" x1=\"1.0\" y1=\"105.0\" x2=\"329.0\" y2=\"105.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><text class=\"po\" x=\"48.0\" y=\"118.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Rope course</text><circle cx=\"48.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"48.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"48.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"48.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"126.0\" y=\"118.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Orienteering</text><circle cx=\"126.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"126.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"126.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"204.0\" y=\"118.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Canoeing</text><circle cx=\"204.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"204.0\" cy=\"30\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"282.0\" y=\"118.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Fishing</text><circle cx=\"282.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"282.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"282.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"282.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"282.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"322.0\" y=\"131.0\" text-anchor=\"end\" dominant-baseline=\"middle\">activity</text></svg>"}, {"kind": "blank", "p": "At a fancy-dress party each child came as a ghost (G), pumpkin (P), witch (W) or mummy (M):\nG P G G W  M M G G W  P G W P W  G M W P M", "tag": "", "marks": "", "flat": [{"t": "a) How many children were at the party? __B1__", "a": {"B1": "20"}}, {"t": "b) dots needed above 'witch' in a dot plot: __B1__", "a": {"B1": "5"}}, {"t": "c) mode: __B1__", "a": {"B1": "ghost"}, "accept": ["G"]}, {"t": "d) One child wins a prize at random. P(the child is a witch) = __B1__", "a": {"B1": "1/4"}, "expr": "fl"}], "sol": "a) 20\nb) 5 witches, so 5 dots\nc) ghost (7)\nd) 5 out of 20 = {1/4}"}, {"kind": "blank", "p": "A spinner with red, blue, yellow and green sectors is spun 30 times:\nY Y Y G R  Y Y G B G  R R B B Y  Y B B G G  R R R B G  Y R G Y G", "tag": "", "marks": "", "flat": [{"t": "a) dots above red: __B1__", "a": {"B1": "7"}}, {"t": "b) dots above yellow: __B1__", "a": {"B1": "9"}}, {"t": "c) mode (colour): __B1__", "a": {"B1": "yellow"}, "accept": ["Y"]}, {"t": "d) fraction of results that were yellow (lowest terms): __B1__", "a": {"B1": "3/10"}, "expr": "fl"}], "sol": "R = 7, B = 6, Y = 9, G = 8\nc) yellow is most frequent\nd) 9 out of 30 = {3/10}"}, {"kind": "blank", "p": "This dot plot shows the musicians in a school orchestra. Strings: violin, cello, double bass. Woodwind: flute, clarinet, saxophone. Brass: trumpet, trombone.", "tag": "", "marks": "", "flat": [{"t": "a) mode (instrument): __B1__", "a": {"B1": "violin"}}, {"t": "b) How many musicians are in the orchestra? __B1__", "a": {"B1": "40"}}, {"t": "c) How many play the clarinet? __B1__", "a": {"B1": "5"}}, {"t": "d) How many play stringed instruments? __B1__", "a": {"B1": "16"}}, {"t": "e) fraction who play brass (lowest terms): __B1__", "a": {"B1": "1/5"}, "expr": "fl"}, {"t": "f) percentage who play brass or woodwind: __B1__ %", "a": {"B1": "50"}}], "sol": "a) violin has 10 dots\nb) 10+4+2+3+5+4+4+4+4 = 40\nc) 5\nd) 10 + 4 + 2 = 16\ne) 4 + 4 = 8 of 40 = {1/5}\nf) brass 8 + woodwind 12 = 20 of 40 = 50 %", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 210\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Orchestra</text><line class=\"ln\" x1=\"8.5\" y1=\"138.0\" x2=\"321.5\" y2=\"138.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><text class=\"po\" x=\"33.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 33.0 147)\">violin</text><circle cx=\"33.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"33.0\" cy=\"30\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"66.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 66.0 147)\">cello</text><circle cx=\"66.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"66.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"66.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"66.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"99.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 99.0 147)\">double bass</text><circle cx=\"99.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"99.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"132.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 132.0 147)\">flute</text><circle cx=\"132.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"132.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"132.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"165.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 165.0 147)\">clarinet</text><circle cx=\"165.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"198.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 198.0 147)\">saxophone</text><circle cx=\"198.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"198.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"198.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"198.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"231.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 231.0 147)\">trumpet</text><circle cx=\"231.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"231.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"231.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"231.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"264.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 264.0 147)\">trombone</text><circle cx=\"264.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"264.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"264.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"264.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"297.0\" y=\"147\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-45 297.0 147)\">drums</text><circle cx=\"297.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"297.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"297.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"297.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/></svg>"}]}, {"id": "s3", "label": "Ex 18C", "sub": "Pictograms", "slides": [{"kind": "blank", "p": "In a pictogram, one symbol represents 4 rabbits at an animal shelter. How many symbols are needed to show: (e.g. 3, {3/4}, 2 1/2)", "tag": "", "marks": "", "flat": [{"t": "a) 8 rabbits: __B1__", "a": {"B1": "2"}, "expr": "fv"}, {"t": "b) 3 rabbits: __B1__", "a": {"B1": "3/4"}, "expr": "fv"}, {"t": "c) 14 rabbits: __B1__", "a": {"B1": "3 1/2"}, "expr": "fv"}, {"t": "d) 21 rabbits: __B1__", "a": {"B1": "5 1/4"}, "expr": "fv"}], "sol": "Divide by 4.\na) 8 ÷ 4 = 2\nb) 3 ÷ 4 = {3/4}\nc) 14 ÷ 4 = 3 {2/4} = 3{1/2}\nd) 21 ÷ 4 = 5{1/4}"}, {"kind": "blank", "p": "One symbol represents 8 bottles of juice sold. How many bottles does each row show?", "tag": "", "marks": "", "flat": [{"t": "a) row a: __B1__", "a": {"B1": "24"}}, {"t": "b) row b: __B1__", "a": {"B1": "10"}}, {"t": "c) row c: __B1__", "a": {"B1": "4"}}, {"t": "d) row d: __B1__", "a": {"B1": "22"}}], "sol": "Multiply the number of symbols by 8.\na) 3 × 8 = 24\nb) 1{1/4} × 8 = 8 + 2 = 10\nc) {1/2} × 8 = 4\nd) 2{3/4} × 8 = 16 + 6 = 22", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 148\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"6\" width=\"40\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"44\" y=\"6\" width=\"282\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"24.0\" y=\"20.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">a</text><clipPath id=\"pc1\"><rect x=\"50\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc1)\"><rect x=\"50\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"59.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc2\"><rect x=\"72\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc2)\"><rect x=\"72\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"81.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc3\"><rect x=\"94\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc3)\"><rect x=\"94\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"103.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"34\" width=\"40\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"44\" y=\"34\" width=\"282\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"24.0\" y=\"48.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">b</text><clipPath id=\"pc4\"><rect x=\"50\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc4)\"><rect x=\"50\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"59.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc5\"><rect x=\"72\" y=\"34\" width=\"4.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc5)\"><rect x=\"72\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"81.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"62\" width=\"40\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"44\" y=\"62\" width=\"282\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"24.0\" y=\"76.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">c</text><clipPath id=\"pc6\"><rect x=\"50\" y=\"62\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc6)\"><rect x=\"50\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"59.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"90\" width=\"40\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"44\" y=\"90\" width=\"282\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"24.0\" y=\"104.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">d</text><clipPath id=\"pc7\"><rect x=\"50\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc7)\"><rect x=\"50\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"59.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc8\"><rect x=\"72\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc8)\"><rect x=\"72\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"81.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc9\"><rect x=\"94\" y=\"90\" width=\"13.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc9)\"><rect x=\"94\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"103.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"95.0\" y=\"124\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"104.0\" cy=\"133\" r=\"4\" style=\"fill:#fff6e0\"/><text class=\"lb\" x=\"119.0\" y=\"133.0\" text-anchor=\"start\" dominant-baseline=\"middle\">= 8 bottles</text></svg>"}, {"kind": "blank", "p": "Flights leaving an airport each day for a week:", "tag": "", "marks": "", "flat": [{"t": "a) flights on Thursday: __B1__", "a": {"B1": "15"}}, {"t": "b) day with the most departures: __B1__", "a": {"B1": "Friday"}, "accept": ["Fri"]}, {"t": "c) flights over the weekend (Saturday and Sunday): __B1__", "a": {"B1": "32"}}], "sol": "Each symbol is 4 flights; a quarter symbol is 1 flight.\na) 3{3/4} × 4 = 15\nb) Friday has 6 symbols = 24 flights\nc) Saturday 5{1/2} × 4 = 22, Sunday 2{1/2} × 4 = 10; 22 + 10 = 32", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 232\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"6\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"6\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"20.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Monday</text><clipPath id=\"pc10\"><rect x=\"102\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc10)\"><rect x=\"102\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc11\"><rect x=\"124\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc11)\"><rect x=\"124\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc12\"><rect x=\"146\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc12)\"><rect x=\"146\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc13\"><rect x=\"168\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc13)\"><rect x=\"168\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc14\"><rect x=\"190\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc14)\"><rect x=\"190\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"34\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"34\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"48.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Tuesday</text><clipPath id=\"pc15\"><rect x=\"102\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc15)\"><rect x=\"102\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc16\"><rect x=\"124\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc16)\"><rect x=\"124\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc17\"><rect x=\"146\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc17)\"><rect x=\"146\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc18\"><rect x=\"168\" y=\"34\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc18)\"><rect x=\"168\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"62\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"62\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"76.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Wednesday</text><clipPath id=\"pc19\"><rect x=\"102\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc19)\"><rect x=\"102\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc20\"><rect x=\"124\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc20)\"><rect x=\"124\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc21\"><rect x=\"146\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc21)\"><rect x=\"146\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc22\"><rect x=\"168\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc22)\"><rect x=\"168\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc23\"><rect x=\"190\" y=\"62\" width=\"4.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc23)\"><rect x=\"190\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"90\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"90\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"104.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Thursday</text><clipPath id=\"pc24\"><rect x=\"102\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc24)\"><rect x=\"102\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc25\"><rect x=\"124\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc25)\"><rect x=\"124\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc26\"><rect x=\"146\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc26)\"><rect x=\"146\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc27\"><rect x=\"168\" y=\"90\" width=\"13.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc27)\"><rect x=\"168\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"118\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"118\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"132.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Friday</text><clipPath id=\"pc28\"><rect x=\"102\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc28)\"><rect x=\"102\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc29\"><rect x=\"124\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc29)\"><rect x=\"124\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc30\"><rect x=\"146\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc30)\"><rect x=\"146\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc31\"><rect x=\"168\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc31)\"><rect x=\"168\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc32\"><rect x=\"190\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc32)\"><rect x=\"190\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc33\"><rect x=\"212\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc33)\"><rect x=\"212\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"221.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"146\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"146\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Saturday</text><clipPath id=\"pc34\"><rect x=\"102\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc34)\"><rect x=\"102\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc35\"><rect x=\"124\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc35)\"><rect x=\"124\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc36\"><rect x=\"146\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc36)\"><rect x=\"146\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc37\"><rect x=\"168\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc37)\"><rect x=\"168\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc38\"><rect x=\"190\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc38)\"><rect x=\"190\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc39\"><rect x=\"212\" y=\"146\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc39)\"><rect x=\"212\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"221.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"174\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"174\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"188.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Sunday</text><clipPath id=\"pc40\"><rect x=\"102\" y=\"174\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc40)\"><rect x=\"102\" y=\"179\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"188\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc41\"><rect x=\"124\" y=\"174\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc41)\"><rect x=\"124\" y=\"179\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"188\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc42\"><rect x=\"146\" y=\"174\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc42)\"><rect x=\"146\" y=\"179\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"188\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"95.0\" y=\"208\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"104.0\" cy=\"217\" r=\"4\" style=\"fill:#fff6e0\"/><text class=\"lb\" x=\"119.0\" y=\"217.0\" text-anchor=\"start\" dominant-baseline=\"middle\">= 4 flights</text></svg>"}, {"kind": "blank", "p": "Kiran counted the vehicles that passed while he waited for his bus:", "tag": "", "marks": "", "flat": [{"t": "a) trucks: __B1__", "a": {"B1": "7"}}, {"t": "b) how many more motorbikes than bicycles? __B1__", "a": {"B1": "4"}}, {"t": "c) vehicles in total: __B1__", "a": {"B1": "45"}}, {"t": "d) fraction that were vans (lowest terms): __B1__", "a": {"B1": "1/9"}, "expr": "fl"}, {"t": "e) Were there more cars than all other vehicles together? (yes or no) __B1__", "a": {"B1": "yes"}}], "sol": "Each symbol is 2 vehicles.\na) 3{1/2} × 2 = 7\nb) motorbikes 5, bicycles 1: 4 more\nc) 7 + 4 + 23 + 5 + 5 + 1 = 45\nd) {5/45} = {1/9}\ne) cars 23; others 7 + 4 + 5 + 5 + 1 = 22; yes", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 340 204\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"6\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"6\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"20.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Trucks</text><clipPath id=\"pc43\"><rect x=\"102\" y=\"6\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc43)\"><rect x=\"102\" y=\"11\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc44\"><rect x=\"121\" y=\"6\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc44)\"><rect x=\"121\" y=\"11\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"128.5\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc45\"><rect x=\"140\" y=\"6\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc45)\"><rect x=\"140\" y=\"11\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"147.5\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc46\"><rect x=\"159\" y=\"6\" width=\"7.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc46)\"><rect x=\"159\" y=\"11\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"166.5\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"34\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"34\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"48.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Buses</text><clipPath id=\"pc47\"><rect x=\"102\" y=\"34\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc47)\"><rect x=\"102\" y=\"39\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc48\"><rect x=\"121\" y=\"34\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc48)\"><rect x=\"121\" y=\"39\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"128.5\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"62\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"62\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"76.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Cars</text><clipPath id=\"pc49\"><rect x=\"102\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc49)\"><rect x=\"102\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc50\"><rect x=\"121\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc50)\"><rect x=\"121\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"128.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc51\"><rect x=\"140\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc51)\"><rect x=\"140\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"147.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc52\"><rect x=\"159\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc52)\"><rect x=\"159\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"166.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc53\"><rect x=\"178\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc53)\"><rect x=\"178\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"185.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc54\"><rect x=\"197\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc54)\"><rect x=\"197\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"204.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc55\"><rect x=\"216\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc55)\"><rect x=\"216\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"223.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc56\"><rect x=\"235\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc56)\"><rect x=\"235\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"242.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc57\"><rect x=\"254\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc57)\"><rect x=\"254\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"261.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc58\"><rect x=\"273\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc58)\"><rect x=\"273\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"280.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc59\"><rect x=\"292\" y=\"62\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc59)\"><rect x=\"292\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"299.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc60\"><rect x=\"311\" y=\"62\" width=\"7.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc60)\"><rect x=\"311\" y=\"67\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"318.5\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"90\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"90\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"104.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Vans</text><clipPath id=\"pc61\"><rect x=\"102\" y=\"90\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc61)\"><rect x=\"102\" y=\"95\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc62\"><rect x=\"121\" y=\"90\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc62)\"><rect x=\"121\" y=\"95\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"128.5\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc63\"><rect x=\"140\" y=\"90\" width=\"7.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc63)\"><rect x=\"140\" y=\"95\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"147.5\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"118\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"118\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"132.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Motorbikes</text><clipPath id=\"pc64\"><rect x=\"102\" y=\"118\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc64)\"><rect x=\"102\" y=\"123\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc65\"><rect x=\"121\" y=\"118\" width=\"15.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc65)\"><rect x=\"121\" y=\"123\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"128.5\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc66\"><rect x=\"140\" y=\"118\" width=\"7.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc66)\"><rect x=\"140\" y=\"123\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"147.5\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"146\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"146\" width=\"240\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bicycles</text><clipPath id=\"pc67\"><rect x=\"102\" y=\"146\" width=\"7.5\" height=\"28\"/></clipPath><g clip-path=\"url(#pc67)\"><rect x=\"102\" y=\"151\" width=\"15\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.5\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"100.0\" y=\"180\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"109.0\" cy=\"189\" r=\"4\" style=\"fill:#fff6e0\"/><text class=\"lb\" x=\"124.0\" y=\"189.0\" text-anchor=\"start\" dominant-baseline=\"middle\">= 2 vehicles</text></svg>"}, {"kind": "blank", "p": "Jasmine recorded what people were doing on a park path: walking 24, jogging 7, cycling 15, skating 5. She draws a pictogram where one symbol = 2 people. How many symbols for:", "tag": "", "marks": "", "flat": [{"t": "a) walking: __B1__", "a": {"B1": "12"}, "expr": "fv"}, {"t": "b) jogging: __B1__", "a": {"B1": "3 1/2"}, "expr": "fv"}, {"t": "c) cycling: __B1__", "a": {"B1": "7 1/2"}, "expr": "fv"}, {"t": "d) skating: __B1__", "a": {"B1": "2 1/2"}, "expr": "fv"}], "sol": "Divide by 2.\na) 12\nb) 3{1/2}\nc) 7{1/2}\nd) 2{1/2}"}]}, {"id": "s4", "label": "Ex 18D", "sub": "Column graphs", "slides": [{"kind": "blank", "p": "This column graph shows items handed in to Lost Property at a sports centre.", "tag": "", "marks": "", "flat": [{"t": "a) How many T-shirts were handed in? __B1__", "a": {"B1": "6"}}, {"t": "b) mode: __B1__", "a": {"B1": "bottles"}, "accept": ["bottle"]}, {"t": "c) How many more towels than shoes? __B1__", "a": {"B1": "3"}}], "sol": "a) 6\nb) bottles have the tallest column (7)\nc) 5 − 2 = 3", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 220\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"170.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Lost property items</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"180.0\" x2=\"300\" y2=\"180.0\"/><text class=\"po\" x=\"34.0\" y=\"180.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"141.5\" x2=\"300\" y2=\"141.5\"/><text class=\"po\" x=\"34.0\" y=\"141.5\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"103.0\" x2=\"300\" y2=\"103.0\"/><text class=\"po\" x=\"34.0\" y=\"103.0\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"64.5\" x2=\"300\" y2=\"64.5\"/><text class=\"po\" x=\"34.0\" y=\"64.5\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"26.0\" x2=\"300\" y2=\"26.0\"/><text class=\"po\" x=\"34.0\" y=\"26.0\" text-anchor=\"end\" dominant-baseline=\"middle\">8</text><rect x=\"49.4\" y=\"122.2\" width=\"33.3\" height=\"57.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"66.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Caps</text><rect x=\"101.4\" y=\"45.2\" width=\"33.3\" height=\"134.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"118.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bottles</text><rect x=\"153.4\" y=\"141.5\" width=\"33.3\" height=\"38.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"170.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Shoes</text><rect x=\"205.4\" y=\"64.5\" width=\"33.3\" height=\"115.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"222.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">T-shirts</text><rect x=\"257.4\" y=\"83.8\" width=\"33.3\" height=\"96.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"274.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Towels</text><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"308.0\" y2=\"180.0\" marker-end=\"url(#ah)\"/><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"40.0\" y2=\"18.0\" marker-end=\"url(#ah)\"/><text class=\"po\" x=\"44.0\" y=\"12.0\" text-anchor=\"start\" dominant-baseline=\"middle\">frequency</text><text class=\"po\" x=\"306.0\" y=\"206.0\" text-anchor=\"end\" dominant-baseline=\"middle\">item</text></svg>"}, {"kind": "blank", "p": "The column graph shows the type of car driven by 120 people.", "tag": "", "marks": "", "flat": [{"t": "a) How many drive a hatchback? __B1__", "a": {"B1": "30"}}, {"t": "b) How many drive a sedan? __B1__", "a": {"B1": "25"}}, {"t": "c) most popular type: __B1__", "a": {"B1": "SUV"}}, {"t": "d) fraction who drive a van (lowest terms): __B1__", "a": {"B1": "1/12"}, "expr": "fl"}], "sol": "a) 30\nb) 25\nc) SUV (35)\nd) {10/120} = {1/12}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 250\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"170.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Type of car driven</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"170.0\" x2=\"300\" y2=\"170.0\"/><text class=\"po\" x=\"34.0\" y=\"170.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"152.0\" x2=\"300\" y2=\"152.0\"/><text class=\"po\" x=\"34.0\" y=\"152.0\" text-anchor=\"end\" dominant-baseline=\"middle\">5</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"134.0\" x2=\"300\" y2=\"134.0\"/><text class=\"po\" x=\"34.0\" y=\"134.0\" text-anchor=\"end\" dominant-baseline=\"middle\">10</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"116.0\" x2=\"300\" y2=\"116.0\"/><text class=\"po\" x=\"34.0\" y=\"116.0\" text-anchor=\"end\" dominant-baseline=\"middle\">15</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"98.0\" x2=\"300\" y2=\"98.0\"/><text class=\"po\" x=\"34.0\" y=\"98.0\" text-anchor=\"end\" dominant-baseline=\"middle\">20</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"80.0\" x2=\"300\" y2=\"80.0\"/><text class=\"po\" x=\"34.0\" y=\"80.0\" text-anchor=\"end\" dominant-baseline=\"middle\">25</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"62.0\" x2=\"300\" y2=\"62.0\"/><text class=\"po\" x=\"34.0\" y=\"62.0\" text-anchor=\"end\" dominant-baseline=\"middle\">30</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"44.0\" x2=\"300\" y2=\"44.0\"/><text class=\"po\" x=\"34.0\" y=\"44.0\" text-anchor=\"end\" dominant-baseline=\"middle\">35</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"26.0\" x2=\"300\" y2=\"26.0\"/><text class=\"po\" x=\"34.0\" y=\"26.0\" text-anchor=\"end\" dominant-baseline=\"middle\">40</text><rect x=\"49.4\" y=\"62.0\" width=\"33.3\" height=\"108.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"66.0\" y=\"178\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-40 66.0 178)\">Hatchback</text><rect x=\"101.4\" y=\"44.0\" width=\"33.3\" height=\"126.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"118.0\" y=\"178\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-40 118.0 178)\">SUV</text><rect x=\"153.4\" y=\"80.0\" width=\"33.3\" height=\"90.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"170.0\" y=\"178\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-40 170.0 178)\">Sedan</text><rect x=\"205.4\" y=\"134.0\" width=\"33.3\" height=\"36.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"222.0\" y=\"178\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-40 222.0 178)\">Van</text><rect x=\"257.4\" y=\"98.0\" width=\"33.3\" height=\"72.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"274.0\" y=\"178\" text-anchor=\"end\" dominant-baseline=\"middle\" transform=\"rotate(-40 274.0 178)\">Other</text><line class=\"ln\" x1=\"40.0\" y1=\"170.0\" x2=\"308.0\" y2=\"170.0\" marker-end=\"url(#ah)\"/><line class=\"ln\" x1=\"40.0\" y1=\"170.0\" x2=\"40.0\" y2=\"18.0\" marker-end=\"url(#ah)\"/><text class=\"po\" x=\"44.0\" y=\"12.0\" text-anchor=\"start\" dominant-baseline=\"middle\">frequency</text><text class=\"po\" x=\"306.0\" y=\"234.0\" text-anchor=\"end\" dominant-baseline=\"middle\">car type</text></svg>"}, {"kind": "blank", "p": "This table describes the stalls at a weekend market.", "tag": "", "marks": "", "flat": [{"t": "a) How many stalls are there? __B1__", "a": {"B1": "24"}}, {"t": "b) Height of the 'Craft' column in a column graph: __B1__", "a": {"B1": "5"}}, {"t": "c) mode: __B1__", "a": {"B1": "clothing"}}, {"t": "d) How many more clothing stalls than toy stalls? __B1__", "a": {"B1": "5"}}], "sol": "a) 6 + 5 + 9 + 4 = 24\nb) 5\nc) clothing (9)\nd) 9 − 4 = 5", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 238 128\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"130\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Stall type</text><rect x=\"134\" y=\"4\" width=\"100\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Number</text><rect x=\"4\" y=\"28\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Food</text><rect x=\"134\" y=\"28\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"4\" y=\"52\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Craft</text><rect x=\"134\" y=\"52\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><rect x=\"4\" y=\"76\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Clothing</text><rect x=\"134\" y=\"76\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><rect x=\"4\" y=\"100\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Toys</text><rect x=\"134\" y=\"100\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text></svg>"}, {"kind": "blank", "p": "Ticket types at a cinema show: adult (A), concession (C), student (S):\nC S A S S  S A S C A  S A S A C  S C A S A  A S C A C", "tag": "", "marks": "", "flat": [{"t": "a) How many people attended? __B1__", "a": {"B1": "25"}}, {"t": "b) adults: __B1__", "a": {"B1": "9"}}, {"t": "c) students: __B1__", "a": {"B1": "10"}}, {"t": "d) percentage with a concession ticket: __B1__ %", "a": {"B1": "24"}}], "sol": "a) 25\nb) 9\nc) 10\nd) 6 out of 25 = 24 %"}, {"kind": "blank", "p": "Adults in a survey said whether they work full-time (F), part-time (P), are unemployed (U) or retired (R):\nU P U R F  R P P U F  P R F F R  R R F F F  F P P F", "tag": "", "marks": "", "flat": [{"t": "a) How many adults took part? __B1__", "a": {"B1": "24"}}, {"t": "b) number retired: __B1__", "a": {"B1": "6"}}, {"t": "c) mode (write the word): __B1__", "a": {"B1": "full-time"}, "accept": ["F", "full time", "fulltime"]}, {"t": "d) How many work full-time or part-time? __B1__", "a": {"B1": "15"}}], "sol": "a) 24\nb) 6\nc) F occurs most often (9)\nd) 9 + 6 = 15"}]}, {"id": "s5", "label": "Ex 18E", "sub": "Pie charts", "slides": [{"kind": "blank", "p": "The pie chart shows how a household uses water.", "tag": "", "marks": "", "flat": [{"t": "a) For what purpose is the most water used? __B1__", "a": {"B1": "garden"}}, {"t": "b) True or false: more water was used in the kitchen than for laundry. __B1__", "a": {"B1": "true"}}, {"t": "c) True or false: less than one fifth of the water is used for laundry and cleaning. __B1__", "a": {"B1": "false"}}, {"t": "d) The household used 400 kL over summer. How much was used in the garden? __B1__ kL", "a": {"B1": "160"}}], "sol": "a) garden has the largest sector (40 %)\nb) 16 % > 12 %: true\nc) 12 % + 8 % = 20 %, which is exactly one fifth, not less: false\nd) 40 % of 400 = 160 kL", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Household water use</text><path d=\"M165,122 L165.0,34.0 A88,88 0 0 1 216.7,193.2 Z\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1.1\"/><text x=\"215.2\" y=\"98.7\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Garden</text><text x=\"215.2\" y=\"113.7\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">40%</text><path d=\"M165,122 L216.7,193.2 A88,88 0 0 1 97.2,178.1 Z\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"158.4\" y=\"167.4\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Bathroom</text><text x=\"158.4\" y=\"182.4\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">24%</text><path d=\"M165,122 L97.2,178.1 A88,88 0 0 1 81.3,94.8 Z\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1.1\"/><text x=\"113.1\" y=\"124.9\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Kitchen</text><text x=\"113.1\" y=\"139.9\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">16%</text><path d=\"M165,122 L81.3,94.8 A88,88 0 0 1 122.6,44.9 Z\" style=\"fill:#f6d0cc;stroke:var(--ink);stroke-width:1.1\"/><text x=\"91.0\" y=\"60.8\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Laundry 12%</text><path d=\"M165,122 L122.6,44.9 A88,88 0 0 1 165.0,34.0 Z\" style=\"fill:#e3d6f3;stroke:var(--ink);stroke-width:1.1\"/><text x=\"141.1\" y=\"29.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Cleaning 8%</text></svg>"}, {"kind": "blank", "p": "The pie chart shows the shirt sizes of the Grade 6 boys in a school.", "tag": "", "marks": "", "flat": [{"t": "a) most commonly worn size: __B1__", "a": {"B1": "12"}, "accept": ["size 12"]}, {"t": "b) True or false: more than half of the boys wear size 12 or 14. __B1__", "a": {"B1": "false"}}, {"t": "c) True or false: size 8 is the least common of sizes 8, 10, 12 and 14. __B1__", "a": {"B1": "true"}}, {"t": "d) There are 200 boys. How many wear size 14? __B1__", "a": {"B1": "32"}}, {"t": "e) How many wear size 10? __B1__", "a": {"B1": "56"}}], "sol": "a) size 12 (34 %)\nb) 34 % + 16 % = 50 %, which is not more than half: false\nc) 12 % is the smallest of the four sizes: true\nd) 16 % of 200 = 32\ne) 28 % of 200 = 56", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Shirt sizes</text><path d=\"M165,122 L165.0,34.0 A88,88 0 0 1 239.3,169.2 Z\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1.1\"/><text x=\"211.3\" y=\"89.6\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Size 12</text><text x=\"211.3\" y=\"104.6\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">34%</text><path d=\"M165,122 L239.3,169.2 A88,88 0 0 1 165.0,210.0 Z\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"190.4\" y=\"161.3\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Size 14</text><text x=\"190.4\" y=\"176.3\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">16%</text><path d=\"M165,122 L165.0,210.0 A88,88 0 0 1 113.3,193.2 Z\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1.1\"/><text x=\"135.3\" y=\"213.3\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Other 10%</text><path d=\"M165,122 L113.3,193.2 A88,88 0 0 1 78.6,138.5 Z\" style=\"fill:#f6d0cc;stroke:var(--ink);stroke-width:1.1\"/><text x=\"83.9\" y=\"173.4\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Size 8 12%</text><path d=\"M165,122 L78.6,138.5 A88,88 0 0 1 165.0,34.0 Z\" style=\"fill:#e3d6f3;stroke:var(--ink);stroke-width:1.1\"/><text x=\"124.3\" y=\"81.3\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Size 10</text><text x=\"124.3\" y=\"96.3\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">28%</text></svg>"}, {"kind": "blank", "p": "A table tennis club has 36 members: A grade 8, B grade 6, C grade 10, Junior 12.", "tag": "", "marks": "", "flat": [{"t": "a) In a pie chart, what angle does each member represent? __B1__ °", "a": {"B1": "10"}}, {"t": "b) A grade sector angle: __B1__ °", "a": {"B1": "80"}}, {"t": "c) B grade: __B1__ °", "a": {"B1": "60"}}, {"t": "d) C grade: __B1__ °", "a": {"B1": "100"}}, {"t": "e) Junior: __B1__ °", "a": {"B1": "120"}}], "sol": "a) 360° ÷ 36 = 10°\nb) 8 × 10° = 80°\nc) 6 × 10° = 60°\nd) 10 × 10° = 100°\ne) 12 × 10° = 120° (check: 80 + 60 + 100 + 120 = 360)"}, {"kind": "blank", "p": "30 children in a library named their favourite type of book.", "tag": "", "marks": "", "flat": [{"t": "a) mode: __B1__", "a": {"B1": "fantasy"}}, {"t": "b) angle for each child: __B1__ °", "a": {"B1": "12"}}, {"t": "c) sector angle for non-fiction: __B1__ °", "a": {"B1": "96"}}, {"t": "d) sector angle for horror: __B1__ °", "a": {"B1": "36"}}, {"t": "e) fraction who prefer non-fiction (lowest terms): __B1__", "a": {"B1": "4/15"}, "expr": "fl"}], "sol": "a) fantasy (9)\nb) 360° ÷ 30 = 12°\nc) 8 × 12° = 96°\nd) 3 × 12° = 36°\ne) {8/30} = {4/15}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 238 152\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"130\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Type</text><rect x=\"134\" y=\"4\" width=\"100\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Frequency</text><rect x=\"4\" y=\"28\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Non-fiction</text><rect x=\"134\" y=\"28\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><rect x=\"4\" y=\"52\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Crime</text><rect x=\"134\" y=\"52\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><rect x=\"4\" y=\"76\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Adventure</text><rect x=\"134\" y=\"76\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"4\" y=\"100\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Fantasy</text><rect x=\"134\" y=\"100\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><rect x=\"4\" y=\"124\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Horror</text><rect x=\"134\" y=\"124\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text></svg>"}, {"kind": "blank", "p": "Students were asked what they ate for lunch.", "tag": "", "marks": "", "flat": [{"t": "a) How many students were surveyed? __B1__", "a": {"B1": "40"}}, {"t": "b) percentage who ate a sandwich or roll: __B1__ %", "a": {"B1": "35"}}, {"t": "c) percentage who ate noodles: __B1__ %", "a": {"B1": "20"}}, {"t": "d) percentage who ate rice and dal: __B1__ %", "a": {"B1": "25"}}, {"t": "e) sector angle for 'Other': __B1__ °", "a": {"B1": "18"}}], "sol": "a) 14 + 8 + 10 + 6 + 2 = 40\nb) {14/40} = 35 %\nc) {8/40} = 20 %\nd) {10/40} = 25 %\ne) 2 × (360° ÷ 40) = 2 × 9° = 18°", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 258 152\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"150\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Food</text><rect x=\"154\" y=\"4\" width=\"100\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Frequency</text><rect x=\"4\" y=\"28\" width=\"150\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Sandwich or roll</text><rect x=\"154\" y=\"28\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">14</text><rect x=\"4\" y=\"52\" width=\"150\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Noodles</text><rect x=\"154\" y=\"52\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><rect x=\"4\" y=\"76\" width=\"150\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Rice and dal</text><rect x=\"154\" y=\"76\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">10</text><rect x=\"4\" y=\"100\" width=\"150\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Fruit</text><rect x=\"154\" y=\"100\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"4\" y=\"124\" width=\"150\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"79.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Other</text><rect x=\"154\" y=\"124\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"204.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text></svg>"}]}, {"id": "s6", "label": "Ex 18F", "sub": "Numerical data", "slides": [{"kind": "blank", "p": "A class was asked how many hats each student owns.", "tag": "", "marks": "", "flat": [{"t": "a) How many students own 2 hats? __B1__", "a": {"B1": "6"}}, {"t": "b) How many students are in the class? __B1__", "a": {"B1": "26"}}, {"t": "c) mode: __B1__ hats", "a": {"B1": "3"}}], "sol": "a) 6\nb) 3 + 6 + 7 + 4 + 5 + 1 = 26\nc) 3 hats has the tallest column, so owning 3 hats is most common", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 220\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"170.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Number of hats owned</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"180.0\" x2=\"300\" y2=\"180.0\"/><text class=\"po\" x=\"34.0\" y=\"180.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"141.5\" x2=\"300\" y2=\"141.5\"/><text class=\"po\" x=\"34.0\" y=\"141.5\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"103.0\" x2=\"300\" y2=\"103.0\"/><text class=\"po\" x=\"34.0\" y=\"103.0\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"64.5\" x2=\"300\" y2=\"64.5\"/><text class=\"po\" x=\"34.0\" y=\"64.5\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"26.0\" x2=\"300\" y2=\"26.0\"/><text class=\"po\" x=\"34.0\" y=\"26.0\" text-anchor=\"end\" dominant-baseline=\"middle\">8</text><rect x=\"47.8\" y=\"122.2\" width=\"27.7\" height=\"57.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"61.7\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><rect x=\"91.1\" y=\"64.5\" width=\"27.7\" height=\"115.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"105.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><rect x=\"134.5\" y=\"45.2\" width=\"27.7\" height=\"134.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"148.3\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><rect x=\"177.8\" y=\"103.0\" width=\"27.7\" height=\"77.0\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"191.7\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><rect x=\"221.1\" y=\"83.8\" width=\"27.7\" height=\"96.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"235.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><rect x=\"264.5\" y=\"160.8\" width=\"27.7\" height=\"19.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"278.3\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"308.0\" y2=\"180.0\" marker-end=\"url(#ah)\"/><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"40.0\" y2=\"18.0\" marker-end=\"url(#ah)\"/><text class=\"po\" x=\"44.0\" y=\"12.0\" text-anchor=\"start\" dominant-baseline=\"middle\">frequency</text><text class=\"po\" x=\"306.0\" y=\"206.0\" text-anchor=\"end\" dominant-baseline=\"middle\">number of hats</text></svg>"}, {"kind": "blank", "p": "The dot plot shows the number of fillings children had at their last dental visit.", "tag": "", "marks": "", "flat": [{"t": "a) How many children had at least 2 fillings? __B1__", "a": {"B1": "7"}}, {"t": "b) mode: __B1__", "a": {"B1": "1"}}, {"t": "c) How many children were surveyed? __B1__", "a": {"B1": "18"}}], "sol": "a) 4 + 2 + 0 + 1 = 7\nb) 1 filling (6 dots)\nc) 5 + 6 + 4 + 2 + 0 + 1 = 18", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 128\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Number of fillings</text><line class=\"ln\" x1=\"12.0\" y1=\"94.0\" x2=\"318.0\" y2=\"94.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><text class=\"po\" x=\"44.2\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><circle cx=\"44.2\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"44.2\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"44.2\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"44.2\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"44.2\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"92.5\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><circle cx=\"92.5\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"92.5\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"92.5\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"92.5\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"92.5\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"92.5\" cy=\"30\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"140.8\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><circle cx=\"140.8\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"140.8\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"140.8\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"140.8\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"189.2\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><circle cx=\"189.2\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"189.2\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"237.5\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><text class=\"po\" x=\"285.8\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><circle cx=\"285.8\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"322.0\" y=\"120.0\" text-anchor=\"end\" dominant-baseline=\"middle\">fillings</text></svg>"}, {"kind": "blank", "p": "Athletes ran laps at the end of training.", "tag": "", "marks": "", "flat": [{"t": "a) mode: __B1__ laps", "a": {"B1": "5"}}, {"t": "b) How many athletes ran fewer than 4 laps? __B1__", "a": {"B1": "5"}}, {"t": "c) How many athletes were there? __B1__", "a": {"B1": "20"}}], "sol": "a) 5 laps (8 athletes)\nb) 2 + 3 = 5\nc) 2 + 3 + 6 + 8 + 1 = 20", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 238 152\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"130\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Laps</text><rect x=\"134\" y=\"4\" width=\"100\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Frequency</text><rect x=\"4\" y=\"28\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><rect x=\"134\" y=\"28\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><rect x=\"4\" y=\"52\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><rect x=\"134\" y=\"52\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><rect x=\"4\" y=\"76\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><rect x=\"134\" y=\"76\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"4\" y=\"100\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><rect x=\"134\" y=\"100\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><rect x=\"4\" y=\"124\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"134\" y=\"124\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text></svg>"}, {"kind": "blank", "p": "The number of children in 30 families:\n2, 4, 4, 3, 3, 2, 3, 1, 2, 4, 1, 2, 1, 4, 3, 2, 0, 3, 0, 5, 2, 2, 0, 3, 1, 1, 1, 2, 3, 2", "tag": "", "marks": "", "flat": [{"t": "a) frequency of 0 children: __B1__", "a": {"B1": "3"}}, {"t": "b) frequency of 2 children: __B1__", "a": {"B1": "9"}}, {"t": "c) frequency of 3 children: __B1__", "a": {"B1": "7"}}, {"t": "d) mode: __B1__ children", "a": {"B1": "2"}}], "sol": "0: 3 · 1: 6 · 2: 9 · 3: 7 · 4: 4 · 5: 1 (total 30)\nd) 2 children is most common"}, {"kind": "blank", "p": "A hockey player's goals in 25 matches:\n1 1 5 3 6  4 3 7 2 2  4 5 1 3 3  2 6 4 2 0  8 4 3 0 5", "tag": "", "marks": "", "flat": [{"t": "a) matches with exactly 3 goals: __B1__", "a": {"B1": "5"}}, {"t": "b) matches with 5 or more goals: __B1__", "a": {"B1": "7"}}, {"t": "c) mode: __B1__ goals", "a": {"B1": "3"}}], "sol": "a) 5\nb) 5: 3, 6: 2, 7: 1, 8: 1 → 7\nc) 3 goals (5 matches)"}, {"kind": "blank", "p": "Runs scored by a school cricket team in the last over of each of 20 games:\n1 3 1 0 2  3 1 0 4 2  2 2 2 3 0  1 5 5 4 3", "tag": "", "marks": "", "flat": [{"t": "a) games with exactly 3 runs: __B1__", "a": {"B1": "4"}}, {"t": "b) fraction of games with no runs (lowest terms): __B1__", "a": {"B1": "3/20"}, "expr": "fl"}, {"t": "c) percentage of games with at least 4 runs: __B1__ %", "a": {"B1": "20"}}, {"t": "d) mode: __B1__ runs", "a": {"B1": "2"}}], "sol": "a) 4\nb) 3 out of 20 = {3/20}\nc) 2 + 2 = 4 of 20 = 20 %\nd) 2 runs (5 games)"}]}, {"id": "s7", "label": "Ex 18G", "sub": "Measuring the centre (mean)", "slides": [{"kind": "blank", "p": "Find the mean of each data set:", "tag": "", "marks": "", "flat": [{"t": "a) 3, 6, 8, 11 → mean = __B1__", "a": {"B1": "7"}, "expr": "dec"}, {"t": "b) 4, 4, 5, 9, 13 → mean = __B1__", "a": {"B1": "7"}, "expr": "dec"}, {"t": "c) 12, 7, 9, 14, 8 → mean = __B1__", "a": {"B1": "10"}, "expr": "dec"}, {"t": "d) 15, 8, 11, 20, 6, 12 → mean = __B1__", "a": {"B1": "12"}, "expr": "dec"}, {"t": "e) 6, 0, 3, 9, 2, 4 → mean = __B1__", "a": {"B1": "4"}, "expr": "dec"}, {"t": "f) 2, 5, 5, 7, 9, 10, 11, 15 → mean = __B1__", "a": {"B1": "8"}, "expr": "dec"}, {"t": "g) 2.4, 1.8, 3.1, 2.7, 2.0 → mean = __B1__", "a": {"B1": "2.4"}, "expr": "dec"}, {"t": "h) 1.25, 1.36, 1.48, 1.31, 1.40 → mean = __B1__", "a": {"B1": "1.36"}, "expr": "dec"}], "sol": "mean = sum of the data values ÷ number of data values\na) 28 ÷ 4 = 7\nb) 35 ÷ 5 = 7\nc) 50 ÷ 5 = 10\nd) 72 ÷ 6 = 12\ne) 24 ÷ 6 = 4\nf) 64 ÷ 8 = 8\ng) 12 ÷ 5 = 2.4\nh) 6.8 ÷ 5 = 1.36"}, {"kind": "blank", "p": "In a long jump event, Sana's jumps were 3.8 m, 4.1 m, 3.6 m, 4.3 m and 4.2 m. Find her mean jump length.", "tag": "", "marks": "", "flat": [{"t": "mean = __B1__ m", "a": {"B1": "4"}, "expr": "dec"}], "sol": "(3.8 + 4.1 + 3.6 + 4.3 + 4.2) ÷ 5 = 20 ÷ 5 = 4 m"}, {"kind": "blank", "p": "People outside a sweet shop said how many chocolates they ate last week:\n3, 0, 5, 2, 7, 1, 2, 4, 0, 2", "tag": "", "marks": "", "flat": [{"t": "a) mean = __B1__ chocolates", "a": {"B1": "2.6"}, "expr": "dec"}, {"t": "b) mode = __B1__", "a": {"B1": "2"}}], "sol": "a) 26 ÷ 10 = 2.6\nb) 2 appears three times\nThe mode is a value in the data set; the mean often is not."}, {"kind": "blank", "p": "The masses of six newborn kittens were 98 g, 105 g, 110 g, 96 g, 101 g and 102 g. Find the mean mass.", "tag": "", "marks": "", "flat": [{"t": "mean = __B1__ g", "a": {"B1": "102"}}], "sol": "(98 + 105 + 110 + 96 + 101 + 102) ÷ 6 = 612 ÷ 6 = 102 g"}, {"kind": "blank", "p": "Ritu recorded how many minutes it took her to cycle to school for 15 days. Find the mean time.\n16, 13, 21, 22, 18, 23, 24, 19, 16, 17, 22, 15, 21, 20, 18", "tag": "", "marks": "", "flat": [{"t": "mean = __B1__ min", "a": {"B1": "19"}}], "sol": "285 ÷ 15 = 19 minutes"}, {"kind": "blank", "p": "The number of letters delivered to each of 16 houses on a street in one week:\n3, 1, 0, 2, 1, 4, 2, 1, 0, 3, 2, 1, 5, 1, 2, 4", "tag": "", "marks": "", "flat": [{"t": "a) How many houses received more than 2 letters? __B1__", "a": {"B1": "5"}}, {"t": "b) mode: __B1__", "a": {"B1": "1"}}, {"t": "c) mean: __B1__", "a": {"B1": "2"}}], "sol": "a) the 3s, 4s and 5 → 5 houses\nb) 1 appears 5 times\nc) 32 ÷ 16 = 2"}, {"kind": "blank", "p": "Kunal took these numbers of wickets in 16 cricket matches:\n0, 3, 4, 2, 3, 1, 4, 2, 3, 0, 4, 2, 1, 5, 2, 2", "tag": "", "marks": "", "flat": [{"t": "a) mode: __B1__", "a": {"B1": "2"}}, {"t": "b) mean number of wickets per match: __B1__", "a": {"B1": "2.375"}, "expr": "dec"}, {"t": "c) Can Kunal take exactly this mean number of wickets in one match? (yes or no) __B1__", "a": {"B1": "no"}}], "sol": "a) 2 appears 5 times, more than any other value\nb) 38 ÷ 16 = 2.375\nc) no: wickets are whole numbers"}]}, {"id": "s8", "label": "Review 18A", "sub": "Review set 18A", "slides": [{"kind": "blank", "p": "A dosa stall recorded its orders on Saturday.", "tag": "", "marks": "", "flat": [{"t": "a) How many orders were received? __B1__", "a": {"B1": "50"}}, {"t": "b) mode: __B1__", "a": {"B1": "masala"}, "accept": ["masala dosa"]}, {"t": "c) fraction of orders that were rava dosa (lowest terms): __B1__", "a": {"B1": "6/25"}, "expr": "fl"}], "sol": "a) 17 + 9 + 8 + 12 + 4 = 50\nb) masala (17)\nc) {12/50} = {6/25}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 238 152\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"4\" width=\"130\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Dosa</text><rect x=\"134\" y=\"4\" width=\"100\" height=\"24\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"16.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Frequency</text><rect x=\"4\" y=\"28\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Masala</text><rect x=\"134\" y=\"28\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"40.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">17</text><rect x=\"4\" y=\"52\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Plain</text><rect x=\"134\" y=\"52\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"64.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><rect x=\"4\" y=\"76\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Onion</text><rect x=\"134\" y=\"76\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"88.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><rect x=\"4\" y=\"100\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Rava</text><rect x=\"134\" y=\"100\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"112.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">12</text><rect x=\"4\" y=\"124\" width=\"130\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"69.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Paper</text><rect x=\"134\" y=\"124\" width=\"100\" height=\"24\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"184.0\" y=\"136.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text></svg>"}, {"kind": "blank", "p": "Milk sold at a dairy shop:", "tag": "", "marks": "", "flat": [{"t": "a) day with the greatest sales: __B1__", "a": {"B1": "Friday"}, "accept": ["Fri"]}, {"t": "b) day with the least sales: __B1__", "a": {"B1": "Wednesday"}, "accept": ["Wed"]}, {"t": "c) milk sold on Thursday: __B1__ L", "a": {"B1": "30"}}, {"t": "d) milk sold on Friday: __B1__ L", "a": {"B1": "55"}}], "sol": "Each symbol is 10 litres; half a symbol is 5 litres.\na) Friday (5{1/2} symbols)\nb) Wednesday (2{1/2})\nc) 3 × 10 = 30 L\nd) 5{1/2} × 10 = 55 L", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 204\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"6\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"6\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"20.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Monday</text><clipPath id=\"pc68\"><rect x=\"102\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc68)\"><rect x=\"102\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc69\"><rect x=\"124\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc69)\"><rect x=\"124\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc70\"><rect x=\"146\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc70)\"><rect x=\"146\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc71\"><rect x=\"168\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc71)\"><rect x=\"168\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"34\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"34\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"48.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Tuesday</text><clipPath id=\"pc72\"><rect x=\"102\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc72)\"><rect x=\"102\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc73\"><rect x=\"124\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc73)\"><rect x=\"124\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc74\"><rect x=\"146\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc74)\"><rect x=\"146\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc75\"><rect x=\"168\" y=\"34\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc75)\"><rect x=\"168\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"62\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"62\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"76.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Wednesday</text><clipPath id=\"pc76\"><rect x=\"102\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc76)\"><rect x=\"102\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc77\"><rect x=\"124\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc77)\"><rect x=\"124\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc78\"><rect x=\"146\" y=\"62\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc78)\"><rect x=\"146\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"90\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"90\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"104.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Thursday</text><clipPath id=\"pc79\"><rect x=\"102\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc79)\"><rect x=\"102\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc80\"><rect x=\"124\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc80)\"><rect x=\"124\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc81\"><rect x=\"146\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc81)\"><rect x=\"146\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"118\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"118\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"132.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Friday</text><clipPath id=\"pc82\"><rect x=\"102\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc82)\"><rect x=\"102\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc83\"><rect x=\"124\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc83)\"><rect x=\"124\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc84\"><rect x=\"146\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc84)\"><rect x=\"146\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc85\"><rect x=\"168\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc85)\"><rect x=\"168\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc86\"><rect x=\"190\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc86)\"><rect x=\"190\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc87\"><rect x=\"212\" y=\"118\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc87)\"><rect x=\"212\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"221.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"146\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"146\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Saturday</text><clipPath id=\"pc88\"><rect x=\"102\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc88)\"><rect x=\"102\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc89\"><rect x=\"124\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc89)\"><rect x=\"124\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc90\"><rect x=\"146\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc90)\"><rect x=\"146\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc91\"><rect x=\"168\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc91)\"><rect x=\"168\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc92\"><rect x=\"190\" y=\"146\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc92)\"><rect x=\"190\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"199.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"95.0\" y=\"180\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"104.0\" cy=\"189\" r=\"4\" style=\"fill:#fff6e0\"/><text class=\"lb\" x=\"119.0\" y=\"189.0\" text-anchor=\"start\" dominant-baseline=\"middle\">= 10 litres</text></svg>"}, {"kind": "blank", "p": "The dot plot shows the shoe sizes of Grade 6 students.", "tag": "", "marks": "", "flat": [{"t": "a) How many students? __B1__", "a": {"B1": "40"}}, {"t": "b) mode: size __B1__", "a": {"B1": "8"}}, {"t": "c) percentage who wear size 6 or less: __B1__ %", "a": {"B1": "20"}}, {"t": "d) percentage who wear size 9 or more: __B1__ %", "a": {"B1": "35"}}], "sol": "a) add the dots: 40\nb) size 8 (10 dots)\nc) 1 + 2 + 5 = 8 of 40 = 20 %\nd) 7 + 4 + 2 + 1 = 14 of 40 = 35 %", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 172\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Shoe sizes</text><line class=\"ln\" x1=\"13.0\" y1=\"138.0\" x2=\"317.0\" y2=\"138.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><text class=\"po\" x=\"37.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><circle cx=\"37.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"69.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><circle cx=\"69.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"69.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"101.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><circle cx=\"101.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"101.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"101.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"101.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"101.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"133.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text><circle cx=\"133.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"133.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"165.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><circle cx=\"165.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"30\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"197.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><circle cx=\"197.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"197.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"229.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">10</text><circle cx=\"229.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"229.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"229.0\" cy=\"107\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"229.0\" cy=\"96\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"261.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">11</text><circle cx=\"261.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"261.0\" cy=\"118\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"293.0\" y=\"151.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">12</text><circle cx=\"293.0\" cy=\"129\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"322.0\" y=\"164.0\" text-anchor=\"end\" dominant-baseline=\"middle\">size</text></svg>"}, {"kind": "blank", "p": "A basketball player's points in 60 matches:", "tag": "", "marks": "", "flat": [{"t": "a) most frequent score: __B1__ points", "a": {"B1": "7"}}, {"t": "b) How many times did the player score 10 or more points? __B1__", "a": {"B1": "8"}}], "sol": "a) 7 points (11 matches)\nb) 4 + 2 + 2 = 8", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 220\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"170.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Points per match</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"180.0\" x2=\"300\" y2=\"180.0\"/><text class=\"po\" x=\"34.0\" y=\"180.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"154.3\" x2=\"300\" y2=\"154.3\"/><text class=\"po\" x=\"34.0\" y=\"154.3\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"128.7\" x2=\"300\" y2=\"128.7\"/><text class=\"po\" x=\"34.0\" y=\"128.7\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"103.0\" x2=\"300\" y2=\"103.0\"/><text class=\"po\" x=\"34.0\" y=\"103.0\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"77.3\" x2=\"300\" y2=\"77.3\"/><text class=\"po\" x=\"34.0\" y=\"77.3\" text-anchor=\"end\" dominant-baseline=\"middle\">8</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"51.7\" x2=\"300\" y2=\"51.7\"/><text class=\"po\" x=\"34.0\" y=\"51.7\" text-anchor=\"end\" dominant-baseline=\"middle\">10</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"26.0\" x2=\"300\" y2=\"26.0\"/><text class=\"po\" x=\"34.0\" y=\"26.0\" text-anchor=\"end\" dominant-baseline=\"middle\">12</text><rect x=\"43.6\" y=\"167.2\" width=\"12.8\" height=\"12.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"50.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">0</text><rect x=\"63.6\" y=\"167.2\" width=\"12.8\" height=\"12.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"70.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><rect x=\"83.6\" y=\"167.2\" width=\"12.8\" height=\"12.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"90.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><rect x=\"103.6\" y=\"141.5\" width=\"12.8\" height=\"38.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"110.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><rect x=\"123.6\" y=\"115.8\" width=\"12.8\" height=\"64.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"130.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><rect x=\"143.6\" y=\"77.3\" width=\"12.8\" height=\"102.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"150.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><rect x=\"163.6\" y=\"64.5\" width=\"12.8\" height=\"115.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"170.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><rect x=\"183.6\" y=\"38.8\" width=\"12.8\" height=\"141.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"190.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text><rect x=\"203.6\" y=\"77.3\" width=\"12.8\" height=\"102.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"210.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">8</text><rect x=\"223.6\" y=\"115.8\" width=\"12.8\" height=\"64.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"230.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">9</text><rect x=\"243.6\" y=\"128.7\" width=\"12.8\" height=\"51.3\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"250.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">10</text><rect x=\"263.6\" y=\"154.3\" width=\"12.8\" height=\"25.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"270.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">11</text><rect x=\"283.6\" y=\"154.3\" width=\"12.8\" height=\"25.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"290.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">12</text><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"308.0\" y2=\"180.0\" marker-end=\"url(#ah)\"/><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"40.0\" y2=\"18.0\" marker-end=\"url(#ah)\"/><text class=\"po\" x=\"44.0\" y=\"12.0\" text-anchor=\"start\" dominant-baseline=\"middle\">frequency</text><text class=\"po\" x=\"306.0\" y=\"206.0\" text-anchor=\"end\" dominant-baseline=\"middle\">points</text></svg>"}, {"kind": "blank", "p": "Tanvi rolled a die 36 times:\n4 1 2 4 6 2  4 5 5 1 3 6  5 1 5 2 5 5  1 5 6 2 4 6  3 4 2 3 2 1  3 2 5 6 4 6", "tag": "", "marks": "", "flat": [{"t": "a) number of 5s: __B1__", "a": {"B1": "8"}}, {"t": "b) How many times did she roll a number greater than 4? __B1__", "a": {"B1": "14"}}, {"t": "c) fraction of rolls that were less than 3 (lowest terms): __B1__", "a": {"B1": "1/3"}, "expr": "fl"}], "sol": "1: 5 · 2: 7 · 3: 4 · 4: 6 · 5: 8 · 6: 6\nb) 8 + 6 = 14\nc) 5 + 7 = 12 of 36 = {1/3}"}, {"kind": "blank", "p": "A town council's spending on services (percentages):", "tag": "", "marks": "", "flat": [{"t": "a) percentage spent on health: __B1__ %", "a": {"B1": "9"}}, {"t": "b) percentage on transport or admin: __B1__ %", "a": {"B1": "30"}}, {"t": "c) service with the least spending: __B1__", "a": {"B1": "libraries"}, "accept": ["library"]}, {"t": "d) service receiving one fifth of the money: __B1__", "a": {"B1": "roads"}}, {"t": "e) sector angle for waste: __B1__ °", "a": {"B1": "18"}}, {"t": "f) The budget is ₹150 crore. Amount spent on parks: ₹ __B1__ crore", "a": {"B1": "12"}}], "sol": "a) 9 %\nb) 12 % + 18 % = 30 %\nc) libraries (4 %)\nd) one fifth = 20 %: roads\ne) 5 % of 360° = 18°\nf) 8 % of 150 = 12", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 230\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Council spending</text><path d=\"M165,122 L165.0,34.0 A88,88 0 0 1 252.8,116.5 Z\" style=\"fill:#f3d9a4;stroke:var(--ink);stroke-width:1.1\"/><text x=\"201.1\" y=\"76.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Water</text><text x=\"201.1\" y=\"91.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">24%</text><path d=\"M165,122 L252.8,116.5 A88,88 0 0 1 251.4,138.5 Z\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text x=\"260.8\" y=\"128.0\" text-anchor=\"start\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Libraries 4%</text><path d=\"M165,122 L251.4,138.5 A88,88 0 0 1 176.0,209.3 Z\" style=\"fill:#d8efd9;stroke:var(--ink);stroke-width:1.1\"/><text x=\"201.1\" y=\"153.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Roads</text><text x=\"201.1\" y=\"168.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">20%</text><path d=\"M165,122 L176.0,209.3 A88,88 0 0 1 148.5,208.4 Z\" style=\"fill:#f6d0cc;stroke:var(--ink);stroke-width:1.1\"/><text x=\"162.0\" y=\"218.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Waste 5%</text><path d=\"M165,122 L148.5,208.4 A88,88 0 0 1 79.8,143.9 Z\" style=\"fill:#e3d6f3;stroke:var(--ink);stroke-width:1.1\"/><text x=\"128.9\" y=\"153.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:700 11px 'Source Sans 3',sans-serif\">Admin</text><text x=\"128.9\" y=\"168.5\" text-anchor=\"middle\" style=\"fill:#1b1b1b;font:600 11px 'Source Sans 3',sans-serif\">18%</text><path d=\"M165,122 L79.8,143.9 A88,88 0 0 1 79.8,100.1 Z\" style=\"fill:#fbe7b8;stroke:var(--ink);stroke-width:1.1\"/><text x=\"69.0\" y=\"122.0\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Parks 8%</text><path d=\"M165,122 L79.8,100.1 A88,88 0 0 1 117.8,47.7 Z\" style=\"fill:#d5ecec;stroke:var(--ink);stroke-width:1.1\"/><text x=\"87.3\" y=\"65.6\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Transport 12%</text><path d=\"M165,122 L117.8,47.7 A88,88 0 0 1 165.0,34.0 Z\" style=\"fill:#f2e0c9;stroke:var(--ink);stroke-width:1.1\"/><text x=\"138.2\" y=\"29.8\" text-anchor=\"end\" dominant-baseline=\"middle\" style=\"fill:var(--ink);font:600 11px 'Source Sans 3',sans-serif\">Health 9%</text></svg>"}]}, {"id": "s9", "label": "Review 18B", "sub": "Review set 18B", "slides": [{"kind": "blank", "p": "Neha recorded birds in her garden: myna (M), sparrow (S), robin (R), woodpecker (W), finch (F):\nR M R S F  M S S S F  S S M S S  S M W F W  M F S R S  F F W S S", "tag": "", "marks": "", "flat": [{"t": "a) sparrows: __B1__", "a": {"B1": "13"}}, {"t": "b) finches: __B1__", "a": {"B1": "6"}}, {"t": "c) mode: __B1__", "a": {"B1": "sparrow"}, "accept": ["S", "sparrows"]}], "sol": "M 5 · S 13 · R 3 · W 3 · F 6\nc) sparrow"}, {"kind": "blank", "p": "60 people were asked where they were when a power cut started. Find each sector angle for a pie chart.", "tag": "", "marks": "", "flat": [{"t": "a) angle for each person: __B1__ °", "a": {"B1": "6"}}, {"t": "b) At home (12): __B1__ °", "a": {"B1": "72"}}, {"t": "c) At work (20): __B1__ °", "a": {"B1": "120"}}, {"t": "d) Shopping (5): __B1__ °", "a": {"B1": "30"}}, {"t": "e) Travelling (10): __B1__ °", "a": {"B1": "60"}}, {"t": "f) Visiting friends (13): __B1__ °", "a": {"B1": "78"}}], "sol": "a) 360° ÷ 60 = 6°\nb) 72°\nc) 120°\nd) 30°\ne) 60°\nf) 78° (check: total 360°)"}, {"kind": "blank", "p": "Houses sold by an estate agent:", "tag": "", "marks": "", "flat": [{"t": "a) houses sold in September: __B1__", "a": {"B1": "35"}}, {"t": "b) houses sold in May: __B1__", "a": {"B1": "15"}}, {"t": "c) month with the most sales: __B1__", "a": {"B1": "April"}, "accept": ["Apr"]}, {"t": "d) 35 sales in October: how many symbols? __B1__", "a": {"B1": "3 1/2"}, "expr": "fv"}], "sol": "Each symbol is 10 houses.\na) 3{1/2} × 10 = 35\nb) 1{1/2} × 10 = 15\nc) April (4 symbols = 40)\nd) 35 ÷ 10 = 3{1/2}", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 204\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><rect x=\"4\" y=\"6\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"6\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"20.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">April</text><clipPath id=\"pc93\"><rect x=\"102\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc93)\"><rect x=\"102\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc94\"><rect x=\"124\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc94)\"><rect x=\"124\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc95\"><rect x=\"146\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc95)\"><rect x=\"146\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc96\"><rect x=\"168\" y=\"6\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc96)\"><rect x=\"168\" y=\"11\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"20\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"34\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"34\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"48.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">May</text><clipPath id=\"pc97\"><rect x=\"102\" y=\"34\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc97)\"><rect x=\"102\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc98\"><rect x=\"124\" y=\"34\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc98)\"><rect x=\"124\" y=\"39\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"48\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"62\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"62\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"76.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">June</text><clipPath id=\"pc99\"><rect x=\"102\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc99)\"><rect x=\"102\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc100\"><rect x=\"124\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc100)\"><rect x=\"124\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc101\"><rect x=\"146\" y=\"62\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc101)\"><rect x=\"146\" y=\"67\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"76\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"90\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"90\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"104.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">July</text><clipPath id=\"pc102\"><rect x=\"102\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc102)\"><rect x=\"102\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc103\"><rect x=\"124\" y=\"90\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc103)\"><rect x=\"124\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc104\"><rect x=\"146\" y=\"90\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc104)\"><rect x=\"146\" y=\"95\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"104\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"118\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"118\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"132.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">August</text><clipPath id=\"pc105\"><rect x=\"102\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc105)\"><rect x=\"102\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc106\"><rect x=\"124\" y=\"118\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc106)\"><rect x=\"124\" y=\"123\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"132\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"4\" y=\"146\" width=\"92\" height=\"28\" style=\"fill:var(--paper-2);stroke:var(--ink);stroke-width:1\"/><rect x=\"96\" y=\"146\" width=\"230\" height=\"28\" style=\"fill:var(--card);stroke:var(--ink);stroke-width:1\"/><text class=\"lb\" x=\"50.0\" y=\"160.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">September</text><clipPath id=\"pc107\"><rect x=\"102\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc107)\"><rect x=\"102\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"111.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc108\"><rect x=\"124\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc108)\"><rect x=\"124\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"133.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc109\"><rect x=\"146\" y=\"146\" width=\"18.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc109)\"><rect x=\"146\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"155.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><clipPath id=\"pc110\"><rect x=\"168\" y=\"146\" width=\"9.0\" height=\"28\"/></clipPath><g clip-path=\"url(#pc110)\"><rect x=\"168\" y=\"151\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"177.0\" cy=\"160\" r=\"4\" style=\"fill:#fff6e0\"/></g><rect x=\"95.0\" y=\"180\" width=\"18\" height=\"18\" rx=\"4\" style=\"fill:#e8a93b;stroke:#7a5410;stroke-width:1.2\"/><circle cx=\"104.0\" cy=\"189\" r=\"4\" style=\"fill:#fff6e0\"/><text class=\"lb\" x=\"119.0\" y=\"189.0\" text-anchor=\"start\" dominant-baseline=\"middle\">= 10 houses</text></svg>"}, {"kind": "blank", "p": "A class's marks on a test out of 10 are shown. Find the mean mark.\n8, 7, 6, 9, 10, 6, 7, 9, 8, 5, 9, 8, 7, 7, 7, 9, 4, 8, 7, 9", "tag": "", "marks": "", "flat": [{"t": "mean = __B1__", "a": {"B1": "7.5"}, "expr": "dec"}], "sol": "150 ÷ 20 = 7.5"}, {"kind": "blank", "p": "The dot plot shows how many phone calls Sunita received at work each day for 4 weeks.", "tag": "", "marks": "", "flat": [{"t": "a) mode: __B1__ calls", "a": {"B1": "4"}}, {"t": "b) On how many days did she receive fewer than 4 calls? __B1__", "a": {"B1": "8"}}], "sol": "a) 4 calls (6 days)\nb) 1 + 3 + 4 = 8", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 128\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"165.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Telephone calls</text><line class=\"ln\" x1=\"12.0\" y1=\"94.0\" x2=\"318.0\" y2=\"94.0\" marker-end=\"url(#ah)\" marker-start=\"url(#ahs)\"/><text class=\"po\" x=\"40.7\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">1</text><circle cx=\"40.7\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"82.1\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">2</text><circle cx=\"82.1\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"82.1\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"82.1\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"123.6\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">3</text><circle cx=\"123.6\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"123.6\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"123.6\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"123.6\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"165.0\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">4</text><circle cx=\"165.0\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"52\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"41\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"165.0\" cy=\"30\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"206.4\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">5</text><circle cx=\"206.4\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"206.4\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"206.4\" cy=\"63\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"247.9\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">6</text><circle cx=\"247.9\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><circle cx=\"247.9\" cy=\"74\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"289.3\" y=\"107.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">7</text><circle cx=\"289.3\" cy=\"85\" r=\"3.8\" style=\"fill:var(--accent-text)\"/><text class=\"po\" x=\"322.0\" y=\"120.0\" text-anchor=\"end\" dominant-baseline=\"middle\">calls</text></svg>"}, {"kind": "blank", "p": "Working adults said how they travel to work.", "tag": "", "marks": "", "flat": [{"t": "a) How many adults were surveyed? __B1__", "a": {"B1": "22"}}, {"t": "b) percentage who used the most common transport: __B1__ %", "a": {"B1": "50"}}], "sol": "a) 5 + 3 + 11 + 2 + 1 = 22\nb) car: {11/22} = 50 %", "fig": "<svg class=\"figsvg\" viewBox=\"0 0 330 220\" role=\"img\"><defs><marker id=\"ah\" viewBox=\"0 0 10 10\" refX=\"9\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M0,1 L10,5 L0,9 z\" class=\"ahd\"/></marker><marker id=\"ahs\" viewBox=\"0 0 10 10\" refX=\"1\" refY=\"5\" markerWidth=\"7\" markerHeight=\"7\" orient=\"auto\"><path d=\"M10,1 L0,5 L10,9 z\" class=\"ahd\"/></marker></defs><text class=\"lb\" x=\"170.0\" y=\"10.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Transport to work</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"180.0\" x2=\"300\" y2=\"180.0\"/><text class=\"po\" x=\"34.0\" y=\"180.0\" text-anchor=\"end\" dominant-baseline=\"middle\">0</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"154.3\" x2=\"300\" y2=\"154.3\"/><text class=\"po\" x=\"34.0\" y=\"154.3\" text-anchor=\"end\" dominant-baseline=\"middle\">2</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"128.7\" x2=\"300\" y2=\"128.7\"/><text class=\"po\" x=\"34.0\" y=\"128.7\" text-anchor=\"end\" dominant-baseline=\"middle\">4</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"103.0\" x2=\"300\" y2=\"103.0\"/><text class=\"po\" x=\"34.0\" y=\"103.0\" text-anchor=\"end\" dominant-baseline=\"middle\">6</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"77.3\" x2=\"300\" y2=\"77.3\"/><text class=\"po\" x=\"34.0\" y=\"77.3\" text-anchor=\"end\" dominant-baseline=\"middle\">8</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"51.7\" x2=\"300\" y2=\"51.7\"/><text class=\"po\" x=\"34.0\" y=\"51.7\" text-anchor=\"end\" dominant-baseline=\"middle\">10</text><line style=\"stroke:var(--rule)\" x1=\"40\" y1=\"26.0\" x2=\"300\" y2=\"26.0\"/><text class=\"po\" x=\"34.0\" y=\"26.0\" text-anchor=\"end\" dominant-baseline=\"middle\">12</text><rect x=\"49.4\" y=\"115.8\" width=\"33.3\" height=\"64.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"66.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bus</text><rect x=\"101.4\" y=\"141.5\" width=\"33.3\" height=\"38.5\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"118.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Train</text><rect x=\"153.4\" y=\"38.8\" width=\"33.3\" height=\"141.2\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"170.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Car</text><rect x=\"205.4\" y=\"154.3\" width=\"33.3\" height=\"25.7\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"222.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Bicycle</text><rect x=\"257.4\" y=\"167.2\" width=\"33.3\" height=\"12.8\" style=\"fill:#cfe3f5;stroke:var(--ink);stroke-width:1.1\"/><text class=\"po\" x=\"274.0\" y=\"192.0\" text-anchor=\"middle\" dominant-baseline=\"middle\">Walk</text><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"308.0\" y2=\"180.0\" marker-end=\"url(#ah)\"/><line class=\"ln\" x1=\"40.0\" y1=\"180.0\" x2=\"40.0\" y2=\"18.0\" marker-end=\"url(#ah)\"/><text class=\"po\" x=\"44.0\" y=\"12.0\" text-anchor=\"start\" dominant-baseline=\"middle\">frequency</text><text class=\"po\" x=\"306.0\" y=\"206.0\" text-anchor=\"end\" dominant-baseline=\"middle\">transport</text></svg>"}, {"kind": "blank", "p": "The ages of children at a party were: 8, 7, 8, 5, 7, 4, 7, 6, 6, 8, 7, 5", "tag": "", "marks": "", "flat": [{"t": "a) How many children were at the party? __B1__", "a": {"B1": "12"}}, {"t": "b) How many were aged 7 or 8? __B1__", "a": {"B1": "7"}}, {"t": "c) fraction younger than 6 (lowest terms): __B1__", "a": {"B1": "1/4"}, "expr": "fl"}, {"t": "d) mode: __B1__", "a": {"B1": "7"}}, {"t": "e) mean: __B1__", "a": {"B1": "6.5"}, "expr": "dec"}], "sol": "a) 12\nb) 7\nc) 4, 5, 5 → 3 of 12 = {1/4}\nd) 7 appears 4 times\ne) 78 ÷ 12 = 6.5"}]}];
/* ================= build slide lists ================= */
var SLIDES = {}; SECTIONS.forEach(function(sec){ SLIDES[sec.id]=sec.slides; });
var TAB_DEFS = SECTIONS.map(function(sec){ return {id:sec.id, label:sec.label, sub:sec.sub}; });

/* ================= state ================= */
function blankItem(slide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    return {status:'unanswered', attempts:0, choice:undefined};
  }
  return {status:'unanswered', curStep:0, stepStates: slide.flat.map(function(){ return {status:'unanswered', attempts:0, inputs:{}}; })};
}
function defaultState(){
  var s={tabs:{}};
  TAB_DEFS.forEach(function(td){
    s.tabs[td.id] = { idx:0, maxReached:0, items: SLIDES[td.id].map(function(sl){ return blankItem(sl); }) };
  });
  return s;
}
var appState = {mode:null, learning:null, quiz:null};
var state = null;      // alias for appState[appState.mode]
var MODE = null;
var activeTab=TAB_DEFS[0].id;

function setMode(m){
  appState.mode = m;
  if(!appState[m]) appState[m] = defaultState();
  state = appState[m];
  MODE = m;
}
/* ================= student accounts (saved on this device) ================= */
var SHEET_KEY='sopaan-g6-ch18';
var ACC_KEY='sopaan-students-v1';
var storageOK=true;
var MEM={};
function lsGet(k){ var r=null; try{ r=localStorage.getItem(k); }catch(e){ storageOK=false; }
  if(r===null||r===undefined) r=MEM[k]||null; try{ return r?JSON.parse(r):null; }catch(e){ return null; } }
function lsSet(k,v){ var j=JSON.stringify(v); MEM[k]=j; try{ localStorage.setItem(k,j); return true; }catch(e){ storageOK=false; return false; } }
try{ localStorage.setItem('sopaan-probe','1'); localStorage.removeItem('sopaan-probe'); }catch(e){ storageOK=false; }
function hashPin(pin,salt){ var h=2166136261, str=salt+'|'+pin; for(var i=0;i<str.length;i++){ h^=str.charCodeAt(i); h=Math.imul(h,16777619)>>>0; } return h.toString(36); }
function accKey(name,roll){ return (name.trim().toLowerCase().replace(/\s+/g,' ')+'#'+roll.trim().toLowerCase()); }
function accounts(){ return lsGet(ACC_KEY)||{students:{}}; }
var student=null; // {key,name,roll}
var records=[];   // finished-tab history for this student on this sheet
function progKey(){ return SHEET_KEY+'::'+student.key; }

function loadState(){
  appState = {mode:null, learning:null, quiz:null}; records=[]; activeTab=TAB_DEFS[0].id;
  var saved=lsGet(progKey());
  if(!saved) return;
  try{
    ['learning','quiz'].forEach(function(m){
      if(saved[m] && saved[m].tabs){
        var fresh = defaultState();
        TAB_DEFS.forEach(function(td){
          if(saved[m].tabs[td.id] && saved[m].tabs[td.id].items && saved[m].tabs[td.id].items.length===SLIDES[td.id].length){
            fresh.tabs[td.id] = saved[m].tabs[td.id];
          }
        });
        appState[m] = fresh;
      }
    });
    if(saved.mode==='learning' || saved.mode==='quiz') appState.mode = saved.mode;
    if(saved.activeTab && TAB_DEFS.some(function(t){ return t.id===saved.activeTab; })) activeTab = saved.activeTab;
    if(Array.isArray(saved.records)) records = saved.records;
  }catch(e){}
}
function saveState(){
  if(!student) return;
  lsSet(progKey(), {mode:appState.mode, learning:appState.learning, quiz:appState.quiz, activeTab:activeTab, records:records, updated:Date.now()});
  var acc=accounts(); if(acc.students[student.key]){ acc.students[student.key].last=Date.now(); lsSet(ACC_KEY,acc); }
}
function addRecord(mode, tabId, correct, revealed, skipped, total){
  records.unshift({at:Date.now(), mode:mode, tab:tabId, correct:correct, revealed:revealed, skipped:skipped, total:total});
  if(records.length>60) records.length=60;
  saveState();
}
function fmtDate(ms){ try{ return new Date(ms).toLocaleString(undefined,{day:'numeric',month:'short',hour:'2-digit',minute:'2-digit'}); }catch(e){ return ''; } }

function renderWho(){
  var el=document.getElementById('whoBar');
  if(!student){ el.hidden=true; el.innerHTML=''; return; }
  el.hidden=false;
  el.innerHTML='Signed in as <b>'+esc(student.name)+'</b> · Roll '+esc(student.roll)+
    ' <button id="btnRecord">My record</button> <button id="btnSignOut">Sign out</button>';
  document.getElementById('btnRecord').addEventListener('click', renderRecord);
  document.getElementById('btnSignOut').addEventListener('click', signOut);
}
function signOut(){
  saveState(); student=null; state=null; MODE=null;
  var acc=accounts(); delete acc.current; lsSet(ACC_KEY,acc);
  document.getElementById('modePill').hidden=true;
  renderWho(); renderLogin();
}
function signIn(key){
  var acc=accounts(); var st=acc.students[key]; if(!st) return;
  student={key:key, name:st.name, roll:st.roll};
  acc.current=key; st.last=Date.now(); lsSet(ACC_KEY,acc);
  loadState(); renderWho();
  if(appState.mode==='learning' || appState.mode==='quiz'){
    setMode(appState.mode); document.getElementById('modePill').hidden=false; updateModePill();
    showChrome(true); buildTabbar(); renderSlide();
    showToast('Welcome back, '+st.name.split(' ')[0]+'. Picking up where you left off.');
  } else {
    renderModePicker();
  }
}
function renderLogin(msg){
  showChrome(false);
  var acc=accounts(); var keys=Object.keys(acc.students).sort(function(a,b){ return (acc.students[b].last||0)-(acc.students[a].last||0); });
  var h='<div class="login-card"><h2>Student sign-in</h2>'+
    '<p class="lead">Sign in to save your answers, see your record and continue where you left off next time.</p>';
  if(!storageOK) h+='<div class="login-err">This browser is blocking saved data (for example, a private window). You can still practise, but progress will not be kept after you close the page.</div>';
  if(msg) h+='<div class="login-err">'+esc(msg)+'</div>';
  if(keys.length){
    h+='<div class="known"><span class="known-label">Continue as</span>';
    keys.slice(0,6).forEach(function(k){ var st=acc.students[k];
      h+='<button class="known-btn" data-k="'+esc(k)+'"><span>'+esc(st.name)+' <small>· Roll '+esc(st.roll)+'</small></span><small>'+(st.last?'Last active '+fmtDate(st.last):'')+'</small></button>'; });
    h+='</div>';
  }
  h+='<form id="loginForm" novalidate>'+
    '<div class="fld"><label for="lgName">Full name</label><input id="lgName" autocomplete="name" required></div>'+
    '<div class="fld-row"><div class="fld"><label for="lgRoll">Roll no.</label><input id="lgRoll" required></div>'+
    '<div class="fld"><label for="lgPin">4-digit PIN</label><input id="lgPin" type="password" inputmode="numeric" maxlength="4" autocomplete="off" required></div></div>'+
    '<button class="btn btn-primary" type="submit" style="width:100%;">Sign in</button>'+
    '<p class="login-note">New here? Enter your name, roll no. and a PIN you will remember, and your profile is created. Progress is saved on this device, so use the same device and browser to continue.</p>'+
    '</form></div>';
  var wrap=document.getElementById('wrap'); wrap.innerHTML=h;
  wrap.querySelectorAll('.known-btn').forEach(function(b){
    b.addEventListener('click', function(){
      var st=accounts().students[b.dataset.k];
      document.getElementById('lgName').value=st.name; document.getElementById('lgRoll').value=st.roll;
      document.getElementById('lgPin').focus();
    });
  });
  document.getElementById('loginForm').addEventListener('submit', function(e){
    e.preventDefault();
    var name=document.getElementById('lgName').value.trim(), roll=document.getElementById('lgRoll').value.trim(), pin=document.getElementById('lgPin').value.trim();
    if(!name||!roll){ renderLoginErr('Enter your name and roll no.'); return; }
    if(!/^\d{4}$/.test(pin)){ renderLoginErr('Your PIN must be exactly 4 digits.'); return; }
    var k=accKey(name,roll); var acc=accounts();
    if(acc.students[k]){
      if(acc.students[k].pin!==hashPin(pin,k)){ renderLoginErr('That PIN does not match this name and roll no. Try again.'); return; }
    } else {
      acc.students[k]={name:name.replace(/\s+/g,' '), roll:roll, pin:hashPin(pin,k), created:Date.now()};
      lsSet(ACC_KEY,acc);
    }
    signIn(k);
  });
}
function renderLoginErr(m){
  var n=document.getElementById('lgName').value, r=document.getElementById('lgRoll').value;
  renderLogin(m); document.getElementById('lgName').value=n; document.getElementById('lgRoll').value=r; document.getElementById('lgPin').focus();
}
function tabSummary(m){
  var st=appState[m]; if(!st) return null;
  return TAB_DEFS.map(function(td){
    var items=st.tabs[td.id].items, n=items.length;
    var c=items.filter(function(i){return i.status==='correct';}).length;
    var done=items.filter(function(i){return i.status!=='unanswered';}).length;
    return {label:td.label, n:n, done:done, correct:c};
  });
}
function renderRecord(){
  showChrome(false);
  var tabLabel=function(id){ var t=TAB_DEFS.find(function(x){return x.id===id;}); return t?t.label:id; };
  var h='<div class="rec-card"><h2>'+esc(student.name)+'’s record</h2><p class="rec-empty" style="margin:0 0 12px;">Roll '+esc(student.roll)+' · Statistics</p>';
  ['learning','quiz'].forEach(function(m){
    var sum=tabSummary(m);
    h+='<h3>'+(m==='learning'?'📘 Learning Sheet':'📝 Quiz Mode')+'</h3>';
    if(!sum){ h+='<p class="rec-empty">Not started yet.</p>'; return; }
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>Section</th><th>Progress</th><th>Correct first time</th></tr></thead><tbody>';
    sum.forEach(function(r){ var pct=Math.round(r.done/r.n*100);
      h+='<tr><td>'+r.label+'</td><td><span class="rec-bar"><i style="width:'+pct+'%"></i></span>'+r.done+' / '+r.n+'</td><td>'+(m==='quiz'?'—':r.correct+' / '+r.n)+'</td></tr>'; });
    h+='</tbody></table></div>';
  });
  h+='</div><div class="rec-card"><h3>Finished sections</h3>';
  if(!records.length){ h+='<p class="rec-empty">No sections finished yet. Each time you finish a tab, your score is recorded here.</p>'; }
  else {
    h+='<div class="rec-table-wrap"><table class="rec-table"><thead><tr><th>When</th><th>Mode</th><th>Section</th><th>Score</th></tr></thead><tbody>';
    records.forEach(function(r){ h+='<tr><td>'+fmtDate(r.at)+'</td><td>'+(r.mode==='quiz'?'Quiz':'Learning')+'</td><td>'+tabLabel(r.tab)+'</td><td>'+r.correct+' / '+r.total+(r.mode==='learning'?' <span class="rec-empty">('+r.revealed+' revealed, '+r.skipped+' skipped)</span>':'')+'</td></tr>'; });
    h+='</tbody></table></div>';
  }
  h+='</div><button class="btn btn-primary" id="btnBack">'+(MODE?'Back to practice':'Choose a mode')+'</button>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('btnBack').addEventListener('click', function(){
    if(MODE){ showChrome(true); buildTabbar(); renderSlide(); } else renderModePicker();
  });
  window.scrollTo({top:0});
}

/* ================= tab bar ================= */
function buildTabbar(){
  var el=document.getElementById('tabbar');
  el.innerHTML = TAB_DEFS.map(function(t){
    return '<button class="tab-btn'+(t.id===activeTab?' active':'')+'" data-tab="'+t.id+'">'+t.label+'<span class="tab-count">'+SLIDES[t.id].length+'</span></button>';
  }).join('');
  el.querySelectorAll('.tab-btn').forEach(function(btn){
    btn.addEventListener('click', function(){ activeTab=btn.dataset.tab; buildTabbar(); renderSlide(); window.scrollTo({top:0,behavior:'smooth'}); });
  });
}

/* ================= rendering ================= */
function canProceed(item){ return item.status==='correct'||item.status==='revealed'||item.status==='skipped'; }

function renderSlide(){
  if(!state.tabs[activeTab]){ activeTab=TAB_DEFS[0].id; }
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  if(ts.idx>=slides.length||ts.idx<0) ts.idx=0;
  var idx = ts.idx;
  var slide = slides[idx];
  var item = ts.items[idx];

  var tdef=TAB_DEFS.find(function(t){return t.id===activeTab;});
  document.getElementById('spLabel').textContent = tdef.label+' · Question '+(idx+1)+' of '+slides.length;
  document.getElementById('secSub').textContent = tdef.label+' — '+tdef.sub;
  document.getElementById('spFill').style.width = Math.round(((idx)/(Math.max(slides.length-1,1)))*100)+'%';

  var h='<div class="qcard">';
  if(slide.kind==='mcq' || slide.kind==='ar'){
    h += renderChoiceBody(slide, item, idx);
  } else {
    h += renderBlankBody(slide, item, idx);
  }
  h += '<div class="feedback" id="feedbackBox"></div>';
  if(MODE==='learning' && (item.status==='correct'||item.status==='revealed')) h += solutionHTML(slide);
  h += '</div>';

  document.getElementById('wrap').innerHTML = h;
  wireSlideEvents(slide, item, idx);
  restoreFeedback(item);
  renderNavbar(item);
  updateFab();
  saveState();
}

function solutionHTML(slide){
  if(!slide.sol) return '';
  return '<div class="solution"><div class="sol-h">Solution</div>'+slide.sol.split('\n').map(function(l){ return '<div class="sol-line">'+fr(esc(l))+'</div>'; }).join('')+'</div>';
}
var LETTERS=['a','b','c','d'];
function chosenHTML(slide,item){
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(item.choice===undefined) return '';
  var ok=item.choice===slide.correct;
  var h='<div class="chosen '+(ok?'ok':'bad')+'"><b>Your answer:</b> ('+LETTERS[item.choice]+') '+fr(esc(opts[item.choice]))+(ok?' ✓':' ✗')+'</div>';
  if(!ok) h+='<div class="chosen ok"><b>Correct answer:</b> ('+LETTERS[slide.correct]+') '+fr(esc(opts[slide.correct]))+'</div>';
  return h;
}
function renderChoiceBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div>';
  if(slide.kind==='mcq'){
    h += '<div class="qtext">'+fr(esc(slide.text))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  } else {
    h += '<div class="qtext"><span class="qtag" style="margin-left:0;margin-right:6px;">A / R</span>Assertion (A): '+fr(esc(slide.a))+'<br>Reason (R): '+fr(esc(slide.r))+(slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  }
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';
  var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
  if(MODE==='quiz') h += '<div class="quiz-hint">Quiz mode — pick an option. The correct answer is revealed once you finish this tab.</div>';
  var locked = MODE==='learning' && (item.status==='correct' || item.status==='revealed');
  h += '<div class="options">';
  opts.forEach(function(opt,i){
    var cls='opt';
    if(locked){
      if(i===slide.correct) cls+=' is-correct';
      else if(item.choice===i) cls+=' is-wrong';
      cls+=' locked';
    }
    if(item.choice===i) cls+=' is-chosen';
    h += '<label class="'+cls+'"><input type="radio" name="choice" value="'+i+'" '+(item.choice===i?'checked':'')+' '+(locked?'disabled':'')+'> <span class="opt-l">('+LETTERS[i]+')</span> <span class="opt-t">'+fr(esc(opt))+'</span>'+(item.choice===i?'<span class="opt-tag">'+(locked?(i===slide.correct?'Your answer ✓':'Your answer ✗'):'Selected')+'</span>':'')+'</label>';
  });
  h += '</div>';
  if(locked) h += chosenHTML(slide,item);
  return h;
}

function renderBlankBody(slide, item, idx){
  var h='<div class="qhead"><div class="qnum">'+(idx+1)+'</div><div class="qtext">';
  if(slide.kind==='case'){ h += '<b>'+esc(slide.title)+'.</b> '+esc(slide.body); }
  else { var pp=fr(esc(slide.p)).split('\n'); h += pp[0]+pp.slice(1).map(function(x){return '<span class="datline">'+x+'</span>';}).join(''); }
  h += (slide.tag?'<span class="qtag">'+esc(slide.tag)+'</span>':'')+'</div>';
  if(slide.marks) h += '<div class="marks-pill">'+slide.marks+'</div>';
  h += '</div>';
  if(slide.fig) h += '<div class="fig">'+slide.fig+'</div>';

  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  var blankCount=0; slide.flat.forEach(function(s){ blankCount+=Object.keys(s.a).length; });

  if(MODE==='quiz'){
    h += '<div class="step-badge">'+blankCount+' blank'+(blankCount===1?'':'s')+' in this question</div>';
    h += '<div class="quiz-hint">Quiz mode — fill in what you can. Correct answers are revealed once you finish this tab.</div>';
    if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
    if(hasExpr) h += '<div class="quiz-hint">Type expressions like <b>(P-2w)/2</b>, <b>2A/b</b> or <b>V/(pi*r^2)</b>. Use ^ for powers and pi for π. Any equivalent form is accepted.</div>';
    h += '<div class="steps">';
    for(var qi=0; qi<total; qi++){
      var qstep = slide.flat[qi];
      var qss = item.stepStates[qi];
      if(qstep.partLabel) h += '<div class="subpart-label">'+esc(qstep.partLabel)+'</div>';
      if(qstep.orDivider) h += '<div class="or-divider">OR</div>';
      var qline = fr(qstep.t);
      Object.keys(qstep.a).forEach(function(bkey){
        var val = qss.inputs[bkey]||'';
        var inp='<input class="blank-input'+(['fv','fe','fl','fm','fi','dec'].indexOf(qstep.expr)>=0?' fr':(qstep.expr==='flist'||qstep.expr==='dlist'||qstep.expr==='glist')?' wide':qstep.expr===true?' expr':(qstep.expr==='words'||qstep.expr==='list'||qstep.expr==='expanded'||qstep.expr==='set'||qstep.expr==='primes'||qstep.expr==='trans'||qstep.expr==='rot'?' wide':''))+'" data-step="'+qi+'" data-bkey="'+bkey+'" value="'+esc(val)+'">';
        qline = qline.replace('__'+bkey+'__', inp);
      });
      if(qstep.fig) h += '<div class="fig">'+qstep.fig+'</div>';
      h += '<div class="step-line">'+qline+'</div>';
    }
    h += '</div>';
    return h;
  }

  if(hasFrac) h += '<div class="quiz-hint">Type fractions like <b>3/4</b> and mixed numbers like <b>2 3/4</b> (whole number, space, fraction).</div>';
  if(hasExpr) h += '<div class="quiz-hint">Type expressions like <b>(P-2w)/2</b>, <b>2A/b</b> or <b>V/(pi*r^2)</b>. Use ^ for powers and pi for π. Any equivalent form is accepted.</div>';
  var locked = item.status==='correct' || item.status==='revealed';
  var upto = locked ? total-1 : item.curStep;
  h += '<div class="step-badge">Step '+(Math.min(item.curStep,total-1)+1)+' of '+total+'</div>';
  h += '<div class="steps">';
  for(var i=0;i<=upto;i++){
    var step = slide.flat[i];
    var ss = item.stepStates[i];
    if(step.partLabel) h += '<div class="subpart-label">'+esc(step.partLabel)+'</div>';
    if(step.orDivider) h += '<div class="or-divider">OR</div>';
    var resolved = ss.status==='correct' || ss.status==='revealed';
    var line = fr(step.t);
    Object.keys(step.a).forEach(function(bkey){
      var fs = ss.inputs['fs_'+bkey];
      var cls = fs==='correct'?'is-correct':(fs==='wrong'?'is-wrong':'');
      var val = ss.inputs[bkey]||'';
      var dis = resolved ? 'disabled':'';
      var inp='<input class="blank-input '+cls+(['fv','fe','fl','fm','fi','dec'].indexOf(step.expr)>=0?' fr':(step.expr==='flist'||step.expr==='dlist'||step.expr==='glist')?' wide':step.expr===true?' expr':(step.expr==='words'||step.expr==='list'||step.expr==='expanded'||step.expr==='set'||step.expr==='primes'||step.expr==='trans'||step.expr==='rot'?' wide':''))+'" data-step="'+i+'" data-bkey="'+bkey+'" value="'+esc(val)+'" '+dis+'>';
      line = line.replace('__'+bkey+'__', inp);
    });
    if(step.fig) h += '<div class="fig">'+step.fig+'</div>';
    h += '<div class="step-line'+(resolved?' resolved':'')+'">'+line+'</div>';
    if(ss.status==='revealed'){
      var reveals=[];
      Object.keys(step.a).forEach(function(bkey){ reveals.push(bkey+' = '+esc(step.a[bkey])); });
      h += '<div class="reveal-note">correct: '+reveals.join(', ')+'</div>';
    }
  }
  h += '</div>';
  return h;
}

var __flash=null;
function restoreFeedback(item){
  var fb=document.getElementById('feedbackBox'); if(!fb) return;
  if(__flash){ fb.className='feedback show '+__flash.c; fb.innerHTML=__flash.h; __flash=null; return; }
  if(MODE==='quiz'){ fb.className='feedback'; fb.innerHTML=''; return; }
  if(item.status==='correct'){ fb.className='feedback show ok'; fb.innerHTML='<b>All done — correct!</b>'; }
  else if(item.status==='revealed'){ fb.className='feedback show reveal'; fb.innerHTML='<b>Answer revealed above.</b> Move on whenever you’re ready.'; }
  else if(item.status==='skipped'){ fb.className='feedback show retry'; fb.innerHTML='Skipped — revisit it anytime from the Question Palette.'; }
  else { fb.className='feedback'; fb.innerHTML=''; }
}

function slideIsAnswered(slide,item){
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return item.stepStates.some(function(ss){ return Object.keys(ss.inputs).some(function(k){ return k.indexOf('fs_')!==0 && ss.inputs[k] && String(ss.inputs[k]).trim()!==''; }); });
}
function renderNavbar(item){
  var ts = state.tabs[activeTab];
  var slides = SLIDES[activeTab];
  var slide = slides[ts.idx];
  var isLast = ts.idx === slides.length-1;
  var h='';
  h += '<button class="btn" id="btnPrev" '+(ts.idx===0?'disabled':'')+'>&larr; Previous</button>';

  if(MODE==='quiz'){
    h += '<button class="btn" id="btnSkip">Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnNext">'+(isLast?'Finish':'Next →')+'</button>';
  } else {
    h += '<button class="btn" id="btnSkip" '+(item.status!=='unanswered'?'disabled':'')+'>Skip</button>';
    h += '<span class="spacer"></span>';
    h += '<button class="btn btn-primary" id="btnCheck" '+(item.status!=='unanswered'?'disabled':'')+'>Check</button>';
    h += '<button class="btn btn-primary" id="btnNext" '+(canProceed(item)?'':'disabled')+'>'+(isLast?'Finish':'Next →')+'</button>';
  }
  document.getElementById('navbarInner').innerHTML = h;

  document.getElementById('btnPrev').addEventListener('click', function(){ if(ts.idx>0){ ts.idx--; renderSlide(); } });

  if(MODE==='quiz'){
    document.getElementById('btnSkip').addEventListener('click', function(){
      item.status='skipped';
      advanceQuiz(ts, slides);
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      item.status = slideIsAnswered(slide,item) ? 'answered' : 'unanswered';
      advanceQuiz(ts, slides);
    });
  } else {
    document.getElementById('btnSkip').addEventListener('click', function(){
      if(item.status==='unanswered'){ item.status='skipped'; renderSlide(); }
    });
    document.getElementById('btnNext').addEventListener('click', function(){
      if(!canProceed(item)) return;
      if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
      else { renderFinished(); }
    });
    document.getElementById('btnCheck').addEventListener('click', function(){ handleCheck(); });
  }
}
function advanceQuiz(ts, slides){
  if(ts.idx < slides.length-1){ ts.idx++; ts.maxReached=Math.max(ts.maxReached, ts.idx); renderSlide(); }
  else { renderFinished(); }
}

function wireSlideEvents(slide, item, idx){
  document.querySelectorAll('input[type="radio"][name="choice"]').forEach(function(r){
    r.addEventListener('change', function(){ item.choice=parseInt(r.value,10); saveState();
      document.querySelectorAll('.opt').forEach(function(l){ l.classList.remove('is-chosen'); var t=l.querySelector('.opt-tag'); if(t) t.remove(); });
      var lab=r.closest('.opt'); lab.classList.add('is-chosen'); var tg=document.createElement('span'); tg.className='opt-tag'; tg.textContent='Selected'; lab.appendChild(tg); });
  });
  document.querySelectorAll('.blank-input').forEach(function(inp){
    inp.addEventListener('input', function(){
      var si=parseInt(inp.dataset.step,10), bk=inp.dataset.bkey;
      item.stepStates[si].inputs[bk]=inp.value;
      saveState();
    });
  });
}

function handleCheck(){
  var ts = state.tabs[activeTab];
  var slide = SLIDES[activeTab][ts.idx];
  var item = ts.items[ts.idx];
  var fb = document.getElementById('feedbackBox');

  if(slide.kind==='mcq' || slide.kind==='ar'){
    if(item.choice===undefined){ fb.className='feedback show err'; fb.innerHTML='Please choose an option first.'; return; }
    var ok = item.choice===slide.correct;
    if(ok){
      item.status='correct'; playSuccess();
      fb.className='feedback show ok'; fb.innerHTML='<b>Correct!</b>';
    } else {
      item.attempts=(item.attempts||0)+1;
      if(item.attempts>=2){ item.status='revealed'; playReveal(); }
      else { playWrong(); fb.className='feedback show retry'; fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'}; }
    }
    renderSlide();
    return;
  }

  // blank / case
  var step = slide.flat[item.curStep];
  var ss = item.stepStates[item.curStep];
  var blanks = Object.keys(step.a);
  var missing = blanks.some(function(k){ return !ss.inputs[k] || String(ss.inputs[k]).trim()===''; });
  if(missing){ fb.className='feedback show err'; fb.innerHTML='Fill in every blank in this step before checking.'; return; }

  var allGood=true;
  blanks.forEach(function(k){
    var good=answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr);
    ss.inputs['fs_'+k]=good?'correct':'wrong';
    if(!good) allGood=false;
  });

  if(allGood){
    ss.status='correct'; playSuccess();
    advanceStepOrFinish(item, slide);
  } else {
    ss.attempts=(ss.attempts||0)+1;
    if(ss.attempts>=2){
      ss.status='revealed'; playReveal();
      advanceStepOrFinish(item, slide);
    } else {
      playWrong();
      fb.className='feedback show retry';
      fb.innerHTML='<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'; __flash={c:'retry',h:'<b>Not quite — try again</b> (attempt 1 of 2) <span class="attempts-dots"><span class="used"></span><span></span></span>'};
      renderSlide();
      return;
    }
  }
  renderSlide();
}

function advanceStepOrFinish(item, slide){
  var total = slide.flat.length;
  var hasExpr = slide.flat.some(function(s){ return s.expr===true; });
  var hasFrac = slide.flat.some(function(s){ return ['fv','fe','fl','fm','fi','flist'].indexOf(s.expr)>=0; });
  if(item.curStep < total-1){
    item.curStep++;
  } else {
    var anyRevealed = item.stepStates.some(function(ss){ return ss.status==='revealed'; });
    item.status = anyRevealed ? 'revealed' : 'correct';
  }
}

/* ================= palette ================= */
var overlay=document.getElementById('overlay');
function statusOf(tabId,i){
  var ts=state.tabs[tabId];
  if(i>ts.maxReached) return 'locked';
  if(i===ts.idx) return 'current';
  return ts.items[i].status==='unanswered' ? 'locked' : ts.items[i].status;
}
function buildPalette(){
  var slides=SLIDES[activeTab];
  document.getElementById('paletteTitle').textContent = TAB_DEFS.find(function(t){return t.id===activeTab;}).label+' · Question palette';
  var body=document.getElementById('paletteBody');
  var html='';
  for(var i=0;i<slides.length;i++){
    html += '<div class="chip" data-status="'+statusOf(activeTab,i)+'" data-idx="'+i+'">'+(i+1)+'</div>';
  }
  body.innerHTML = html;
  body.querySelectorAll('.chip').forEach(function(chip){
    chip.addEventListener('click', function(){
      var i=parseInt(chip.dataset.idx,10);
      var ts=state.tabs[activeTab];
      if(i>ts.maxReached){ showToast('Finish the earlier questions to unlock this one.'); return; }
      ts.idx=i; closePalette(); renderSlide();
    });
  });
}
function openPalette(){ buildPalette(); overlay.classList.add('show'); }
function closePalette(){ overlay.classList.remove('show'); }
var toastTimer;
function showToast(msg){
  var t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(toastTimer); toastTimer=setTimeout(function(){ t.classList.remove('show'); },2200);
}
document.getElementById('paletteFab').addEventListener('click', openPalette);
document.getElementById('paletteClose').addEventListener('click', closePalette);
overlay.addEventListener('click', function(e){ if(e.target===overlay) closePalette(); });

function updateFab(){
  var slides=SLIDES[activeTab];
  var done=state.tabs[activeTab].items.filter(function(it){ return it.status==='correct'||it.status==='revealed'||it.status==='skipped'; }).length;
  document.getElementById('fabBadge').textContent = done+'/'+slides.length;
}

/* ================= overall progress + finish ================= */
function updateChapterProgress(){
  var total=0, done=0;
  TAB_DEFS.forEach(function(td){
    state.tabs[td.id].items.forEach(function(it){
      total++;
      if(it.status==='correct'||it.status==='revealed'||it.status==='skipped') done++;
    });
  });
  var pct = total>0 ? Math.round((done/total)*100) : 0;
  document.getElementById('cpFill').style.width=pct+'%';
  document.getElementById('cpLabel').textContent=pct+'% complete';
}
function isSlideCorrect(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice===slide.correct;
  return slide.flat.every(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).every(function(k){ return answerMatches(ss.inputs[k], step.a[k], step.accept, step.expr); });
  });
}
function isSlideAttempted(tabId,i){
  var slide=SLIDES[tabId][i], item=state.tabs[tabId].items[i];
  if(slide.kind==='mcq'||slide.kind==='ar') return item.choice!==undefined;
  return slide.flat.some(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).some(function(k){ return ss.inputs[k] && String(ss.inputs[k]).trim()!==''; });
  });
}
function slideLabel(slide){
  var t = slide.kind==='case' ? slide.title : (slide.kind==='ar' ? slide.a : (slide.p||slide.text||''));
  t = String(t);
  return t.length>90 ? t.slice(0,90)+'…' : t;
}
function slideAnswerText(slide, item, correctSide){
  if(slide.kind==='mcq'||slide.kind==='ar'){
    var opts = slide.kind==='mcq' ? slide.opts : AR_OPTIONS;
    if(correctSide) return '('+LETTERS[slide.correct]+') '+opts[slide.correct];
    return item.choice!==undefined ? '('+LETTERS[item.choice]+') '+opts[item.choice] : '— not attempted —';
  }
  return slide.flat.map(function(step,si){
    var ss=item.stepStates[si];
    return Object.keys(step.a).map(function(k){
      return correctSide ? step.a[k] : (ss.inputs[k] || '—');
    }).join(', ');
  }).join('  |  ');
}

function renderFinished(){
  if(MODE==='quiz'){ renderQuizResults(); return; }
  var ts=state.tabs[activeTab];
  var correct=ts.items.filter(function(i){return i.status==='correct';}).length;
  var revealed=ts.items.filter(function(i){return i.status==='revealed';}).length;
  var skipped=ts.items.filter(function(i){return i.status==='skipped';}).length;
  var h='<div class="qcard done-card"><div class="big">✨</div><h2>Tab complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">You worked through all '+ts.items.length+' questions in this tab.</p>';
  if(!ts.recorded){ ts.recorded=true; addRecord('learning', activeTab, correct, revealed, skipped, ts.items.length); }
  h+='<div class="score-pills">'+
     '<span class="score-pill" style="background:var(--success-soft);color:var(--success);">'+correct+' correct</span>'+
     '<span class="score-pill" style="background:var(--danger-soft);color:var(--danger);">'+revealed+' revealed</span>'+
     '<span class="score-pill" style="background:var(--gold-soft);color:var(--retry-text);">'+skipped+' skipped</span></div>'+
     '<button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; ts.recorded=false; renderSlide(); });
  updateChapterProgress(); saveState();
}

function renderQuizResults(){
  var ts=state.tabs[activeTab];
  var slides=SLIDES[activeTab];
  var correctCount=0, attemptedCount=0;
  var rowsHtml = slides.map(function(slide,i){
    var item=ts.items[i];
    var ok=isSlideCorrect(activeTab,i);
    var att=isSlideAttempted(activeTab,i);
    if(ok) correctCount++;
    if(att) attemptedCount++;
    var tagCls = ok?'ok':(att?'bad':'na');
    var tagText = ok?'Correct':(att?'Incorrect':'Not attempted');
    var row='<div class="review-row">';
    row+='<span class="review-tag '+tagCls+'">Q'+(i+1)+' · '+tagText+'</span>';
    row+='<div class="review-q">'+fr(esc(slideLabel(slide)))+'</div>';
    row+='<div class="review-ans"><b>Your answer:</b> '+fr(esc(slideAnswerText(slide,item,false)))+'</div>';
    if(!ok) row+='<div class="review-ans" style="color:var(--success);"><b>Correct answer:</b> '+fr(esc(slideAnswerText(slide,item,true)))+'</div>';
    if(slide.sol) row+='<details class="rev-sol"><summary>Show solution</summary>'+solutionHTML(slide)+'</details>';
    row+='</div>';
    return row;
  }).join('');

  addRecord('quiz', activeTab, correctCount, 0, 0, slides.length);
  var h='<div class="qcard done-card" style="text-align:left;">';
  h+='<div style="text-align:center;"><div class="big">🏁</div><h2>Quiz complete</h2>';
  h+='<p style="color:var(--ink-soft);font-size:14px;">'+correctCount+' / '+slides.length+' correct · '+attemptedCount+' attempted</p></div>';
  h+='<div style="margin-top:16px;">'+rowsHtml+'</div>';
  h+='<div style="text-align:center;margin-top:6px;"><button class="btn btn-primary" id="btnReview">Review from question 1</button></div>';
  h+='</div>';
  document.getElementById('wrap').innerHTML=h;
  document.getElementById('navbarInner').innerHTML='';
  document.getElementById('btnReview').addEventListener('click', function(){ ts.idx=0; renderSlide(); });
  playSuccess();
  updateChapterProgress(); saveState();
}

/* ================= mode picker ================= */
function updateModePill(){
  var btn=document.getElementById('modePill');
  if(!btn) return;
  btn.textContent = MODE==='quiz' ? '📝 Quiz Mode · switch' : '📘 Learning Sheet · switch';
}
function showChrome(show){
  document.querySelector('.tabbar').style.display = show?'':'none';
  document.querySelector('.slide-progress').style.display = show?'':'none';
  document.querySelector('.navbar').style.display = show?'':'none';
  document.getElementById('paletteFab').style.display = show?'':'none';
}
function renderModePicker(){
  showChrome(false);
  var wrap=document.getElementById('wrap');
  wrap.innerHTML =
    '<div class="mode-pick">'+
      '<div class="mode-card" data-pick="learning"><div class="mode-icon">📘</div><h3>Learning Sheet</h3>'+
      '<p>Work through each question step by step with instant feedback — two tries, then the correct value is revealed right there so you can keep moving.</p></div>'+
      '<div class="mode-card" data-pick="quiz"><div class="mode-icon">📝</div><h3>Quiz Mode</h3>'+
      '<p>Attempt every question with no hints along the way. Your score and the full answer key are shown together once you finish the tab — just like the real exam.</p></div>'+
    '</div>';
  wrap.querySelectorAll('[data-pick]').forEach(function(card){
    card.addEventListener('click', function(){
      setMode(card.dataset.pick);
      document.getElementById('modePill').hidden=false;
      updateModePill();
      showChrome(true);
      buildTabbar();
      renderSlide();
    });
  });
}
document.getElementById('modePill').addEventListener('click', function(){
  if(!appState.mode){ return; }
  setMode(appState.mode==='quiz' ? 'learning' : 'quiz');
  updateModePill();
  showChrome(true);
  buildTabbar();
  renderSlide();
});

/* ================= boot ================= */
var _origRenderSlide = renderSlide;
renderSlide = function(){ _origRenderSlide(); updateChapterProgress(); updateModePill(); };

renderLogin();
})();
</script>
</body>
</html>
