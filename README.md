<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=FF0000&background=00000000&center=true&vCenter=true&width=600&lines=Lucas+J.+Da+Cunha;Red+Team+%7C+Pentester+%7C+SecOps;%22Sunrise%2C+parabellum.%22;I+break+things+to+understand+them.;Then+I+build+the+defense.)

</div>

<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=Lucas%20J.%20Da%20Cunha&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Red%20Team%20%7C%20Pentester%20%7C%20SecOps&descAlignY=60&descSize=22)

> *"Attack to understand. Understand to defend."*

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucas--j--da--cunha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucas-j-da-cunha)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=lucasj-sec.lucasj-sec&style=for-the-badge&color=FF0000)
![Focus](https://img.shields.io/badge/Focus-Red%20Team%20%7C%20Pentesting-FF0000?style=for-the-badge&logo=kalilinux&logoColor=white)
![HTB](https://img.shields.io/badge/HackTheBox-Active-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)

</div>

---

## 🇧🇷 &nbsp;Quem sou

```python
operator = {
    "nome"      : "Lucas J. Da Cunha",
    "role"      : ["Red Team", "Pentester", "SecOps", "SRE"],
    "filosofia" : "Ataco para entender. Entendo para construir defesas melhores.",
    "stack"     : ["Python", "Linux", "Kali", "Nmap", "Hydra", "Metasploit"],
    "distros"   : ["Kali Linux", "Debian", "Arch"],
    "formação"  : "Engenharia de Software — Universidade São Francisco (USF)",
    "agora"     : "Monitoramento de Sistemas + labs ativos no HackTheBox",
    "diferencial": "Construo as próprias ferramentas pra entender o que ataco",
    "motto"     : "Sunrise, parabellum.",
}
```

---

## 🔴 &nbsp;Operações Ativas

<div align="center">

| Projeto | Status | Descrição |
|:---|:---:|:---|
| 🛡️ **[Citadel SOAR](https://github.com/lucasj-sec/citadel-soar)** | `ACTIVE` | Mini-SOAR que construí nos labs do HTB — o lado azul que corre enquanto faço pentest |
| ⚔️ **HackTheBox Labs** | `ACTIVE` | Sessões regulares de pentest em ambiente controlado |
| ⚔️ **OverTheWire: Bandit** | `COMPLETED ✅` | Wargame de segurança Linux — todos os níveis concluídos |
| ☁️ **Azure Architecture** | `IN PROGRESS` | Stack Azure para ambientes de produção |
| 🎯 **CompTIA CySA+** | `NEXT TARGET` | Análise de ameaças e resposta a incidentes |

</div>

---

## ⚡ &nbsp;Arsenal

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🗡️ &nbsp;Citadel — Purple Team na Prática

> *Durante um lab no HackTheBox, parei de ler log manualmente e escrevi o defensor.*

O **Citadel** é um mini-SOAR que construí para rodar enquanto faço pentest.
Ele age como Blue Team autônomo — eu ataco, ele detecta e bloqueia.

Isso me forçou a pensar nos dois lados simultaneamente: Red e Blue.
**É assim que Purple Team funciona na prática.**

```
[Kali — eu, atacando]                [Debian — Citadel, defendendo]
──────────────────────────────────────────────────────────────────
$ hydra -l root -P wordlist.txt      [ALERTA] Falhas: 1/5 → 2/5 → 3/5
  ssh://192.168.100.10 -t 4
                                     [ALERTA] Falhas: 4/5 → 5/5
[DATA] attacking...                  [LIMIAR ATINGIDO] Bloqueando...
                                     [BLOQUEIO] ✓ blackhole (ip route)

[timeout... timeout... timeout]
[262 tentativas. 0 respostas.]       # silêncio total. kernel descarta tudo.
```

**→ [Ver repositório completo](https://github.com/lucasj-sec/citadel-soar)**

---

## 🌐 &nbsp;English

<details>
<summary><b>Click to expand 🇺🇸</b></summary>

<br>

```python
operator = {
    "name"       : "Lucas J. Da Cunha",
    "role"       : ["Red Team", "Pentester", "SecOps", "SRE"],
    "philosophy" : "I break things to understand them. Then I build better defenses.",
    "stack"      : ["Python", "Linux", "Kali", "Nmap", "Hydra", "Metasploit"],
    "distros"    : ["Kali Linux", "Debian", "Arch"],
    "education"  : "Software Engineering — Universidade São Francisco (Brazil)",
    "currently"  : "Systems Monitoring + active labs on HackTheBox",
    "edge"       : "I build my own tools to understand what I'm attacking",
    "motto"      : "Sunrise, parabellum.",
}
```

### 🔴 Active Operations

| Project | Status | Description |
|:---|:---:|:---|
| 🛡️ **[Citadel SOAR](https://github.com/lucasj-sec/citadel-soar)** | `ACTIVE` | Mini-SOAR I built during HTB labs — the blue side running while I pentest |
| ⚔️ **HackTheBox Labs** | `ACTIVE` | Regular pentest sessions in controlled environment |
| ⚔️ **OverTheWire: Bandit** | `COMPLETED ✅` | Linux security wargame — all levels cleared |
| ☁️ **Azure Architecture** | `IN PROGRESS` | Mastering Azure stack for production environments |
| 🎯 **CompTIA CySA+** | `NEXT TARGET` | Threat analysis and incident response certification |

### 🎯 What I'm about

I'm a Red Teamer who builds his own tools.

During HackTheBox sessions I got tired of reading massive SSH logs manually — so I wrote **Citadel**, a headless mini-SOAR that acts as an autonomous Blue Team operator while I run the pentest. It detects brute-force patterns, tracks IPs with a sliding window, and blocks them via kernel-level routing blackhole.

Building the defense taught me more about attacking than any tutorial ever did.
That's Purple Team in practice.

📬 **Let's connect:** [linkedin.com/in/lucas-j-da-cunha](https://linkedin.com/in/lucas-j-da-cunha)

</details>

---

<div align="center">

```
╔═══════════════════════════════════════════╗
║                                           ║
║   "The quieter you become,                ║
║    the more you are able to hear."        ║
║                                           ║
║   — and the more damage you can do. 🗡️   ║
║                                           ║
╚═══════════════════════════════════════════╝
```

![Snake animation](https://github.com/lucasj-sec/lucasj-sec/blob/output/github-contribution-grid-snake-dark.svg)

</div>
