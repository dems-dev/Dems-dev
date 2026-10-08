<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:714B67,50:875A7B,100:00A09D&height=220&section=header&text=Hi,%20I'm%20Dhimas%20Agung%20👋&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Odoo%20Implementor%20•%20ERP%20%26%20E-Commerce%20Builder&descAlignY=58&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=00A09D&center=true&vCenter=true&width=620&lines=Turning+business+processes+into+Odoo+modules+%E2%9A%99%EF%B8%8F;Building+e-commerce+on+Odoo+19+%F0%9F%9B%92;From+requirement+doc+to+go-live+%F0%9F%9A%80;Python+%E2%80%A2+XML+%E2%80%A2+OWL+%E2%80%A2+PostgreSQL" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Dems_dev&label=Profile%20views&color=714B67&style=flat-square" alt="profile views"/>
<img src="https://img.shields.io/badge/Based%20in-Jakarta,%20ID-00A09D?style=flat-square&logo=googlemaps&logoColor=white" alt="location"/>
<img src="https://img.shields.io/badge/Open%20to-Collaborate-875A7B?style=flat-square&logo=handshake&logoColor=white" alt="open to collab"/>

</div>

---

### 🧩 `whoami.py`

```python
from odoo import models, fields


class Developer(models.Model):
    _name = "dhimas.developer"
    _description = "Odoo Implementor who actually reads the requirement doc"

    name        = fields.Char(default="Dhimas")
    role        = fields.Char(default="Odoo Implementor")
    location    = fields.Char(default="Jakarta, Indonesia 🇮🇩")
    current     = fields.Char(default="Shipping a B2B/B2C e-commerce on Odoo 19 (Odoo.sh)")
    stack       = fields.Many2many(default=["Python", "XML", "OWL/JS", "QWeb", "PostgreSQL"])
    focus       = fields.Selection([
        ("website",  "Website & eCommerce"),
        ("sales",    "Sales & Inventory flows"),
        ("custom",   "Custom modules & integrations"),
    ], default="website")
    fun_fact    = fields.Text(default="I debug faster with a cup of kopi susu ☕")

    def action_build(self):
        return "Requirement ➜ Fit-gap ➜ Config ➜ Custom ➜ Test ➜ Go-live 🚀"
```

---

### 🛠️ Tech Stack

<div align="center">

**ERP & Backend**

<img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/XML-FF6600?style=for-the-badge&logo=xml&logoColor=white"/>

**Frontend & Website**

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/OWL-00A09D?style=for-the-badge&logo=odoo&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white"/>
<img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>

**Tools & DevOps**

<img src="https://img.shields.io/badge/Odoo.sh-875A7B?style=for-the-badge&logo=odoo&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

</div>

---

### 🔄 How I Work

```mermaid
flowchart LR
    A[📄 Requirement] --> B[🔍 Fit-Gap]
    B --> C[⚙️ Configure]
    C --> D[🧑‍💻 Custom Module]
    D --> E[🧪 UAT]
    E --> F[🚀 Go-Live]
    F --> G[🛟 Support]
    G -.feedback.-> A
```

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Dems_dev&show_icons=true&theme=transparent&hide_border=true&title_color=875A7B&icon_color=00A09D&text_color=9f9f9f&ring_color=714B67" alt="stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dems_dev&layout=compact&theme=transparent&hide_border=true&title_color=875A7B&text_color=9f9f9f" alt="top langs"/>

<img src="https://streak-stats.demolab.com?user=Dems_dev&theme=transparent&hide_border=true&ring=714B67&fire=00A09D&currStreakLabel=875A7B&sideLabels=9f9f9f&dates=9f9f9f&currStreakNum=9f9f9f&sideNums=9f9f9f" alt="streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Dems_dev&bg_color=00000000&color=9f9f9f&line=00A09D&point=875A7B&area=true&area_color=714B67&hide_border=true" width="100%" alt="activity graph"/>

</div>

---

### 🤝 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/dhimasagung-dp/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:dhimasagung2004@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Dems_dev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/><br/>

> *"Good ERP is invisible — users just feel their work got easier."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00A09D,50:875A7B,100:714B67&height=120&section=footer" width="100%"/>

</div>
