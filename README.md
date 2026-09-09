<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=00ADD8&background=00000000&center=true&vCenter=true&width=600&lines=Lucas+J.+Da+Cunha;Infra+%7C+Cloud+%7C+SysAdmin;%22Automate+it%2C+then+trust+it.%22;Background+in+security.+Focus+on+infra.;terraform+apply+-auto-approve)

</div>

<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20,24&height=220&section=header&text=Lucas%20J.%20Da%20Cunha&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Infra%20%7C%20Cloud%20%7C%20SysAdmin&descAlignY=60&descSize=22)

> *"Understand the system before you automate it."*

</div>

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucas--j--da--cunha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucas-j-da-cunha)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=lucasj-sec.lucasj-sec&style=for-the-badge&color=00ADD8)
![Focus](https://img.shields.io/badge/Focus-Infra%20%7C%20Cloud-00ADD8?style=for-the-badge&logo=terraform&logoColor=white)
![HTB](https://img.shields.io/badge/HackTheBox-Active-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)

</div>

---

## 🇧🇷 &nbsp;Quem sou

```python
profissional = {
    "nome"       : "Lucas J. Da Cunha",
    "foco"       : ["Infraestrutura", "Cloud", "SysAdmin"],
    "base"       : "Hacker ético (ESCOM, Exército Brasileiro) com badge Cisco, hoje aplicada como fundamento de segurança na infra",
    "filosofia"  : "Entendo o sistema antes de automatizar. Automatizo pra confiar, não pra esquecer.",
    "stack"      : ["Terraform", "Azure", "Linux", "Bash", "Python", "Git"],
    "distros"    : ["Arch Linux", "Debian", "Kali Linux"],
    "formação"   : "Ciências da Computação, Universidade São Francisco (USF)",
    "agora"      : "IaC com Terraform/Azure e trilha CySA+ como próximo passo",
    "motto"      : "terraform apply, e deixa rodar.",
}
```

---

## 🔧 &nbsp;Operações Ativas

<div align="center">

| Projeto | Status | Descrição |
|:---|:---:|:---|
| ☁️ **[Lab Terraform Azure](https://github.com/lucasj-sec/Lab-Azure-Com-IaC)** | `ACTIVE` | Provisionamento de VM Ubuntu na Azure via Terraform, com NSG restrito por IP e troubleshooting documentado |
| 🛡️ **[Citadel SOAR](https://github.com/lucasj-sec/citadel-soar)** | `ACTIVE` | Mini-SOAR headless para defesa ativa de servidor Linux, construído durante prática em labs do HTB |
| ⚔️ **HackTheBox Labs** | `ACTIVE` | Prática regular em ambiente controlado, mantém a base de segurança afiada |
| 🎓 **ESCOM, Hacker Ético** | `COMPLETED ✅` | Curso pela Escola de Telecomunicações do Exército Brasileiro, badge Cisco |
| 🎯 **AWS Certified Solutions Architect - Associate** | `IN PROGRESS` | Certificação em andamento |
| 🎯 **CCNA** | `NEXT TARGET` | Especialização em Redes |

</div>

---

## ⚡ &nbsp;Arsenal

<div align="center">

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Arch](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🗡️ &nbsp;Citadel: base de segurança aplicada à infra

> *Durante um lab no HackTheBox, parei de ler log manualmente e escrevi o defensor.*

O **Citadel** é um mini-SOAR que construí para rodar enquanto praticava pentest.
Ele age como Blue Team autônomo: eu ataco, ele detecta e bloqueia.

Foi esse projeto que me mostrou o lado que mais me interessa hoje: não é o ataque em si, é o sistema que sustenta a defesa. Daí o foco atual em infra e cloud.

```
[Kali, atacando]                     [Debian, Citadel defendendo]
──────────────────────────────────────────────────────────────────
$ hydra -l root -P wordlist.txt      [ALERTA] Falhas: 1/5 -> 2/5 -> 3/5
  ssh://192.168.100.10 -t 4
                                      [ALERTA] Falhas: 4/5 -> 5/5
[DATA] attacking...                  [LIMIAR ATINGIDO] Bloqueando...
                                      [BLOQUEIO] ok blackhole (ip route)

[timeout... timeout... timeout]
[262 tentativas. 0 respostas.]       # silêncio total. kernel descarta tudo.
```

**-> [Ver repositório completo](https://github.com/lucasj-sec/citadel-soar)**

---

## 🌐 &nbsp;English

<details>
<summary><b>Click to expand 🇺🇸</b></summary>

<br>

```python
professional = {
    "name"        : "Lucas J. Da Cunha",
    "focus"       : ["Infrastructure", "Cloud", "SysAdmin"],
    "background"  : "Ethical hacking course (ESCOM, Brazilian Army) with a Cisco badge, now applied as a security foundation for infra work",
    "philosophy"  : "Understand the system before automating it. Automate to trust it, not to forget it.",
    "stack"       : ["Terraform", "Azure", "Linux", "Bash", "Python", "Git"],
    "distros"     : ["Arch Linux", "Debian", "Kali Linux"],
    "education"   : "Computer Science, Universidade São Francisco (Brazil)",
    "currently"   : "IaC with Terraform/Azure, CySA+ as the next certification target",
    "motto"       : "terraform apply, and let it run.",
}
```

### 🔧 Active Operations

| Project | Status | Description |
|:---|:---:|:---|
| ☁️ **[Terraform Azure Lab](https://github.com/lucasj-sec/Lab-Azure-Com-IaC)** | `ACTIVE` | Provisions an Ubuntu VM on Azure via Terraform, with IP-restricted NSG and documented troubleshooting |
| 🛡️ **[Citadel SOAR](https://github.com/lucasj-sec/citadel-soar)** | `ACTIVE` | Headless mini-SOAR for active Linux server defense, built during HTB practice |
| ⚔️ **HackTheBox Labs** | `ACTIVE` | Regular practice in a controlled environment, keeps the security foundation sharp |
| 🎓 **ESCOM, Ethical Hacking** | `COMPLETED ✅` | Course through the Brazilian Army's telecommunications school, Cisco badge |
| 🎯 **AWS Certified Solutions Architect - Associate** | `IN PROGRESS` | Certification underway |
| 🎯 **CCNA** | `NEXT TARGET` | Network Specialization |

### 🎯 What I'm about

I'm moving into infrastructure and cloud, with a security background that shapes how I build things.

During HackTheBox sessions I got tired of reading massive SSH logs manually, so I wrote **Citadel**, a headless mini-SOAR that acts as an autonomous Blue Team operator while I run the pentest. That project taught me I care more about the system holding the defense together than about the attack itself. That is what pulled me toward infra and cloud.

Now I build infrastructure with Terraform on Azure, documenting the real troubleshooting along the way, not just the happy path.

📬 **Let's connect:** [linkedin.com/in/lucas-j-da-cunha](https://linkedin.com/in/lucas-j-da-cunha)

</details>

---

<div align="center">

```
+-------------------------------------------+
|                                           |
|   "Infrastructure you don't think        |
|    about is infrastructure that works."   |
|                                           |
|   and it took a lot of terraform apply   |
|   to get there. |>                        |
|                                           |
+-------------------------------------------+
```

![Containers organizing](https://raw.githubusercontent.com/lucasj-sec/lucasj-sec/main/containers))

</div>
