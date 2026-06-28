---
created: 2026-06-28T07:33:09-05:00
modified: 2026-06-28T07:33:25-05:00
---

# Adopt css blank template

body {
  background: url("PUT_BACKGROUND_IMAGE_LINK_HERE") center center fixed;
  background-size: cover;
  margin: 0;
  padding: 0;
}

/* Main boxes / info boxes */
.container,
.card,
.card-body,
.profile-content,
.panel,
.box,
div[class*="card"],
div[class*="panel"] {
  background: rgba(0,0,0,.75) !important;
  border: 1px solid #ffffff !important;
  border-radius: 15px;
  color: #ffffff !important;
}

/* Links */
a {
  color: #ffffff !important;
}

a:hover {
  color: #cccccc !important;
}

/* Adopt tag */
.profile-header:before {
  content: "ADOPT";
  position: absolute;
  top: 15px;
  right: 15px;
  padding: 8px 14px;
  background: #000000;
  color: #ffffff;
  font-weight: bold;
  border-radius: 20px;
  font-size: 13px;
}

/* Menu / nav areas */
.settings,
.settings-menu,
.menu,
.dropdown-menu,
.sidebar-menu,
nav,
header,
.topbar,
.navbar,
.dropdown,
.dropdown-content,
.sidebar,
div[class*="settings"],
div[class*="menu"],
div[class*="nav"],
div[class*="dropdown"] {
  background: #000000 !important;
  border: 1px solid #ffffff !important;
  color: #ffffff !important;
}

.settings a,
.menu a,
.dropdown-menu a,
nav a,
.sidebar a {
  color: #ffffff !important;
}
