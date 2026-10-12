<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Défis & Concours Zappy</title>
<style>
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px);
--bg:#4a0a18;--bg2:#2a0510;--card:rgba(255,255,255,.07);--text:#fff;--muted:#e8c9d0;--line:rgba(255,255,255,.18);--gold:#f6c850;--primary:#a3122f;--ok:#7ee0a0;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px);height:100%}
*,*:before,*:after{box-sizing:inherit}
body{margin:0;min-height:100%;color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.5;background:radial-gradient(ellipse at 50% -10%,#8c1a35 0%,var(--bg) 45%,var(--bg2) 100%) fixed}
#stars{position:fixed;inset:0;pointer-events:none;overflow:hidden;z-index:0}
#stars span{position:absolute;color:var(--gold);animation:tw 3s ease-in-out infinite}
@keyframes tw{0%,100%{opacity:.15;transform:scale(.7)}50%{opacity:.9;transform:scale(1.15)}}
.wrap{position:relative;z-index:1;max-width:1100px;margin:0 auto;padding:20px 16px 40px}
.panel,.banner,.ch{background:var(--card);border:1px solid var(--line);border-radius:16px;backdrop-filter:blur(6px)}
.banner{padding:20px;display:flex;flex-wrap:wrap;gap:16px;justify-content:space-between;align-items:center;margin-bottom:24px}
h1{font-size:1.6rem;margin:0 0 4px;letter-spacing:.5px}h1 b,h2 b{color:var(--gold)}h2{font-size:1.2rem;margin:0}h3{margin:0 0 6px;font-size:1.05rem}
.muted{color:var(--muted);font-size:.9rem;margin:0}
.right{display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.pts{background:linear-gradient(135deg,#f6c850,#e2a21c);color:#4a0a18;font-weight:800;padding:8px 16px;border-radius:99px;font-size:1.05rem}
.btn{display:inline-block;border:0;cursor:pointer;font:inherit;font-weight:700;text-decoration:none;text-align:center;padding:10px 16px;border-radius:10px;background:linear-gradient(135deg,#c0183b,#8c1230);color:#fff;border:1px solid rgba(255,255,255,.25)}
.btn.ghost{background:transparent}.btn.block{display:block;width:100%}
input{font:inherit;padding:11px 12px;border-radius:10px;border:1px solid var(--line);background:rgba(0,0,0,.3);color:#fff;width:100%;margin-bottom:12px}
input::placeholder{color:#c9a0aa}
label{font-size:.85rem;color:var(--muted);display:block;margin-bottom:4px}
.layout{display:grid;grid-template-columns:2fr 1fr;gap:24px}
@media(max-width:800px){.layout{grid-template-columns:1fr}}
.head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
.arrows{display:flex;gap:8px}.arrows button{width:38px;height:38px;border-radius:50%;border:1px solid var(--line);background:var(--card);color:#fff;cursor:pointer}
#slider{display:flex;gap:16px;overflow-x:auto;scroll-behavior:smooth;padding-bottom:12px;scroll-snap-type:x mandatory}
.ch{flex:0 0 250px;scroll-snap-align:start;border-top:4px solid var(--gold);padding:16px;display:flex;flex-direction:column;transition:all .4s}
.ch.out{opacity:0;transform:scale(.85)}
.ch .top{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.badge{background:var(--gold);color:#4a0a18;font-weight:800;border-radius:99px;padding:2px 10px;font-size:.85rem}
.ch p{flex:1}
.panel{padding:16px}
.hist{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid var(--line);font-size:.9rem}
.hist small{color:var(--muted);display:block}
.done{display:none;padding:20px;text-align:center}
#gate{max-width:420px;margin:40px auto}#gate .panel{padding:24px}
#err{color:#ffb3c0;font-size:.9rem;min-height:1.3em;margin:0 0 10px}
#app{display:none}
#admin{display:none;margin-top:24px;border-color:var(--gold)}
table{width:100%;border-collapse:collapse;font-size:.9rem}th,td{text-align:left;padding:8px;border-bottom:1px solid var(--line)}th{color:var(--muted)}.ov{overflow-x:auto}
</style>
</head>
<body>
<div id="stars"></div>
<div class="wrap">

  <div id="gate">
    <div class="panel">
      <h1 style="text-align:center">⭐ <b>Zappy</b> TV ⭐</h1>
      <p class="muted" style="text-align:center;margin-bottom:18px">Inscris-toi pour accéder aux défis et cumuler des étoiles.</p>
      <div id="gload" class="muted" style="text-align:center">Chargement…</div>
      <div id="gform" style="display:none">
        <label for="f-user">Nom d'utilisateur (unique)</label>
        <input id="f-user" maxlength="20" placeholder="ex : star_2026" autocomplete="username">
        <label for="f-mail">Adresse e-mail (unique)</label>
        <input id="f-mail" type="email" placeholder="toi@exemple.com" autocomplete="email">
        <p id="err"></p>
        <button class="btn block" id="go">Valider mon inscription</button>
        <p class="muted" style="margin-top:12px;text-align:center">Déjà inscrit ? Tu es reconnecté automatiquement avec le même compte.</p>
      </div>
      <p id="gmsg" class="muted" style="display:none;text-align:center"></p>
    </div>
  </div>

  <div id="app">
    <div class="banner">
      <div>
        <h1>⭐ Défis &amp; Concours <b>Zappy</b></h1>
        <p class="muted">Relevez les défis pour cumuler des points et tenter de gagner !</p>
      </div>
      <div class="right"><span class="pts">⭐ <span id="pts">0</span> points</span><span style="font-weight:700">👋 <span id="uname"></span></span></div>
    </div>
    <div class="layout">
      <section>
        <div class="head">
          <div><h2>Défis à relever</h2><p class="muted">Faites défiler pour découvrir tous les défis</p></div>
          <div class="arrows"><button id="left" aria-label="Précédent">◀</button><button id="right" aria-label="Suivant">▶</button></div>
        </div>
        <div id="slider"></div>
        <div id="done" class="panel done"><h3>🎉 Bravo ! Tous les défis sont terminés !</h3><p class="muted">Vos points sont bien enregistrés.</p></div>
      </section>
      <aside class="panel">
        <h2 style="margin-bottom:8px">📜 Historique de mes points</h2>
        <p id="empty" class="muted">Aucun défi validé pour le moment.</p>
        <div id="hist"></div>
      </aside>
    </div>
  </div>

  <section id="admin" class="panel"><h2>👑 Espace admin <span class="muted">(visible uniquement par vous)</span></h2><p class="muted" id="admsum">Chargement…</p>
    <div class="ov"><table><thead><tr><th>#</th><th>Utilisateur</th><th>E-mail</th><th>Points</th><th>Défis</th><th>Dernière activité</th></tr></thead><tbody id="adm"></tbody></table></div></section>
</div>

<script>
var CH=[
 {id:"defi-1",name:"Rejoindre TikTok",tag:"TikTok",pts:50,txt:"Abonnez-vous à notre compte TikTok officiel pour remporter 50 points.",url:"https://www.tiktok.com/@_zappy.tv",cta:"Abonne-toi"},
 {id:"defi-2",name:"Suivre sur Instagram",tag:"Instagram",pts:50,txt:"Découvrez nos stories et les coulisses du programme pour remporter 50 points.",url:"https://www.instagram.com/_zappy.tv",cta:"Abonne-toi"},
 {id:"defi-3",name:"Page Facebook",tag:"Facebook",pts:50,txt:"Rejoignez notre communauté sur Facebook pour gagner 50 points.",url:"https://www.facebook.com/p/Staracpromo2024-61567288072427/",cta:"Abonne-toi"},
 {id:"defi-4",name:"Cote de popularité",tag:"Sondage",pts:100,txt:"Vote pour ton élève préféré de cette première semaine et gagne 100 points.",url:"https://pollforall.com/p3mpemmr",cta:"Votez maintenant !"}
];
var DB=null,U=null,UID=null,user="",email="",profile={points:0,completed:[],history:[]};
function $(i){return document.getElementById(i)}
(function(){var s=$("stars");for(var i=0;i<45;i++){var e=document.createElement("span");e.textContent="★";e.style.left=Math.random()*100+"%";e.style.top=Math.random()*100+"%";e.style.fontSize=(8+Math.random()*16)+"px";e.style.animationDelay=(Math.random()*3)+"s";e.style.animationDuration=(2+Math.random()*3)+"s";s.appendChild(e)}})();
function save(){if(!DB||!UID||!user)return;
 try{DB.collection("scores").doc(UID).set({name:user,email:email,points:profile.points,completed:profile.completed,history:profile.history,updated:Date.now()}).catch(function(){})}catch(e){}}
function render(){
 $("pts").textContent=profile.points;$("uname").textContent=user;
 var s=$("slider"),left=CH.filter(function(c){return profile.completed.indexOf(c.id)<0});s.innerHTML="";
 left.forEach(function(c){
  var d=document.createElement("div");d.className="ch";
  d.innerHTML='<div class="top"><span class="badge">+'+c.pts+' pts</span><span class="muted">'+c.tag+'</span></div><h3>'+c.name+'</h3><p class="muted">'+c.txt+'</p><a class="btn block" target="_blank" rel="noopener" href="'+c.url+'">'+c.cta+'</a>';
  d.querySelector("a").onclick=function(){
   profile.points+=c.pts;profile.completed.push(c.id);
   var n=new Date();profile.history.unshift({name:c.name,points:c.pts,date:n.toLocaleDateString("fr-FR",{day:"2-digit",month:"2-digit"})+" à "+n.toLocaleTimeString("fr-FR",{hour:"2-digit",minute:"2-digit"})});
   save();d.classList.add("out");setTimeout(render,400)};
  s.appendChild(d)});
 var all=!left.length;s.style.display=all?"none":"flex";$("done").style.display=all?"block":"none";
 var h=$("hist");h.innerHTML="";$("empty").style.display=profile.history.length?"none":"block";
 profile.history.forEach(function(i){var e=document.createElement("div");e.className="hist";
  var a=document.createElement("div"),sm=document.createElement("small");a.textContent=i.name;sm.textContent=i.date;a.appendChild(sm);
  var b=document.createElement("span");b.className="badge";b.textContent="+"+i.points+" pts";e.appendChild(a);e.appendChild(b);h.appendChild(e)});
}
function enter(){$("gate").style.display="none";$("app").style.display="block";render()}
async function sha(s){var b=await crypto.subtle.digest("SHA-256",new TextEncoder().encode(s));return Array.from(new Uint8Array(b)).map(function(x){return x.toString(16).padStart(2,"0")}).join("")}
async function register(){
 var n=$("f-user").value.trim(),k=n.toLowerCase(),e=$("f-mail").value.trim().toLowerCase(),er=$("err");er.textContent="";
 if(!/^[a-z0-9_.-]{3,20}$/.test(k)){er.textContent="Nom d'utilisateur : 3 à 20 caractères (lettres, chiffres, _ . -).";return}
 if(!/^[^@\s]+@[^@\s]+\.[^@\s]+$/.test(e)){er.textContent="Adresse e-mail invalide.";return}
 $("go").disabled=true;
 try{
  var eh=await sha(e);
  var a=await DB.collection("usernames").doc(k).get();
  if(a.exists){er.textContent="Ce nom d'utilisateur est déjà pris.";$("go").disabled=false;return}
  var b=await DB.collection("emails").doc(eh).get();
  if(b.exists){er.textContent="Cette adresse e-mail est déjà utilisée.";$("go").disabled=false;return}
  await DB.collection("usernames").doc(k).set({uid:UID});
  await DB.collection("emails").doc(eh).set({uid:UID});
  user=n;email=e;profile={points:0,completed:[],history:[]};save();enter();
 }catch(x){er.textContent="Erreur d'inscription, réessayez.";$("go").disabled=false}
}
function renderAdmin(snap){
 var b=$("adm");b.innerHTML="";$("admsum").textContent=snap.docs.length+" participant(s)";
 snap.docs.forEach(function(d,i){var v=d.data()||{},tr=document.createElement("tr");
  [i+1,v.name||"?",v.email||"-",v.points||0,(v.completed||[]).length+"/"+CH.length,v.updated?new Date(v.updated).toLocaleString("fr-FR"):"-"].forEach(function(x){var td=document.createElement("td");td.textContent=x;tr.appendChild(td)});
  b.appendChild(tr)})}
$("go").onclick=register;
$("left").onclick=function(){$("slider").scrollBy({left:-270,behavior:"smooth"})};
$("right").onclick=function(){$("slider").scrollBy({left:270,behavior:"smooth"})};
(async function(){
 try{
  U=await claude.use("user");DB=await claude.use("db");
  if(!U||!DB){$("gload").style.display="none";$("gmsg").style.display="block";$("gmsg").textContent="Ouvrez ce lien avec votre compte claude.ai pour vous inscrire et jouer.";return}
  UID=await U.id();
  if(U.isOwner()){$("admin").style.display="block";DB.collection("scores").orderBy("points","desc").onSnapshot(renderAdmin,function(){})}
  var s=await DB.collection("scores").doc(UID).get(),v=s.exists?s.data():null;
  if(v&&v.name){user=v.name;email=v.email||"";profile={points:v.points||0,completed:v.completed||[],history:v.history||[]};enter()}
  else{$("gload").style.display="none";$("gform").style.display="block"}
 }catch(e){$("gload").textContent="Erreur de chargement."}
})();
setTimeout(function(){if($("gload").style.display!=="none"&&$("gload").textContent==="Chargement…"){$("gload").style.display="none";$("gmsg").style.display="block";$("gmsg").textContent="Ouvrez ce lien avec votre compte claude.ai pour vous inscrire et jouer."}},11000);
</script>
</body>
</html>
