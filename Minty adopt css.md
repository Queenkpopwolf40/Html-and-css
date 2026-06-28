---
created: 2026-06-28T07:20:31-05:00
modified: 2026-06-28T07:20:42-05:00
---

# Minty adopt css

body {
  background: url("https://files.catbox.moe/ytxips.jpg") center center fixed;
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
.profile-info,
.info,
.profile-about,
.sidebar,
.section,
div[class*="card"],
div[class*="panel"] {
  background: #0f2d2a !important;
  border: 1px solid #4DE1C1 !important;
  border-radius: 15px;
  color: #eafffb !important;
  box-shadow: 0 0 20px rgba(77,225,193,0.3);
}

a {
  color: #4DE1C1 !important;
}

a:hover {
  color: #b9fff1 !important;
}

.profile-header:before {
  content: "ADOPT";
  position: absolute;
  top: 15px;
  right: 15px;
  padding: 8px 16px;
  background: #4DE1C1;
  color: white;
  font-weight: bold;
  border-radius: 20px;
  font-size: 13px;
  box-shadow: 0 0 12px rgba(77,225,193,0.6);
}

.settings,
.settings-menu,
.menu,
.dropdown-menu,
.sidebar-menu,
div[class*="settings"],
div[class*="menu"],
div[class*="dropdown"] {
  background: #b9fff1 !important;
  border: 1px solid #4DE1C1 !important;
  color: #0f2d2a !important;
}

.settings a,
.menu a,
.dropdown-menu a {
  color: #0f2d2a !important;
}
