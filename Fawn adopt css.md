---
created: 2026-06-28T07:23:54-05:00
modified: 2026-06-28T07:24:07-05:00
---

# Fawn adopt css

body {
  background: url("https://files.catbox.moe/4voh4j.jpg") center center fixed;
  background-size: cover;
  margin: 0;
  padding: 0;
}

.container,
.card,
.card-body,
.profile-content,
.panel,
.box,
div[class*="card"],
div[class*="panel"] {
  background: rgba(38,91,22,.75) !important;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(57,255,212,.5);
  border-radius: 15px;
  color: #eafff8 !important;
  animation: breathe 6s infinite ease-in-out;
  box-shadow: 0 0 25px rgba(0,0,0,.5);
}

@keyframes breathe {
  0%,100% {
    box-shadow: 0 0 10px rgba(38,91,22,.2);
    transform: translateY(0);
  }
  50% {
    box-shadow: 0 0 25px rgba(57,255,212,.35);
    transform: translateY(-2px);
  }
}

.container:hover,
.card:hover,
.box:hover {
  transform: scale(1.01);
  box-shadow: 0 10px 30px rgba(0,0,0,.5);
}

a {
  color: #39FFD4 !important;
}

a:hover {
  color: #b6fff1 !important;
  text-shadow: 0 0 6px rgba(57,255,212,.4);
}

.profile-header:before {
  content: "ADOPT";
  position: absolute;
  top: 15px;
  right: 15px;
  padding: 8px 14px;
  background: linear-gradient(135deg,#265B16,#39FFD4);
  color: #eafff8;
  font-weight: bold;
  border-radius: 20px;
  font-size: 13px;
  letter-spacing: 1px;
  box-shadow: 0 0 12px rgba(57,255,212,.4);
}

body:before {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  opacity: .05;
  background: url("https://www.transparenttextures.com/patterns/noise.png");
}

body:after {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  background: radial-gradient(circle, rgba(0,0,0,.1), rgba(0,0,0,.65));
}

.settings,
.settings-menu,
.menu,
.dropdown-menu,
.sidebar-menu,
nav,
header,
.navbar,
.topbar,
.sidebar,
div[class*="menu"],
div[class*="nav"],
div[class*="dropdown"] {
  background: #265B16 !important;
  border: 1px solid #39FFD4 !important;
  color: #eafff8 !important;
}

.settings a,
.menu a,
.dropdown-menu a,
nav a,
.sidebar a {
  color: #39FFD4 !important;
}

.settings a:hover,
.menu a:hover,
.dropdown-menu a:hover,
nav a:hover,
.sidebar a:hover {
  color: #b6fff1 !important;
  text-shadow: 0 0 6px rgba(57,255,212,.4);
}
