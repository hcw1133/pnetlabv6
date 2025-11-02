# 📜 Índice

- [⚙️ Instalação PnetLab](#pnetlab)
- [⚙️ Instalação do Ishare2](#ishare2)
- [⚙️ Instalação do Client Pack](#client)
- [⚙️ Referências](#Ref)

## 🛠️ Instalação do PNETLAB<a id="pnetlab"></a>

- 👉 Realize o Download do Ubuntu Server 20.04.6 LTS
```linux
https://releases.ubuntu.com/20.04.6/ubuntu-20.04.6-live-server-amd64.iso
```

- 👉 Instale o Ubuntu Server em um ambiente bare metal ou virtualizado de sua preferência (VMware Workstation, ESXI, Proxmox, Hyper-V, VirtualBox, QEMU, etc)
- 👉 Atualize o Sistema Operacional
- 👉 Realize a instalação do PnetLab utilizando o comando abaixo:
```linux
bash -c "$(curl -sL https://drive.labhub.eu.org/0:/upgrades_pnetlab/focal/install_pnetlab_v6.sh)"
```

## 🛠️ Instalação do Ishare2<a id="ishare2"></a>

- 👉 Comando para instalar o Ishare2 (Download de Imagens):
```linux
wget -O /usr/sbin/ishare2 https://raw.githubusercontent.com/ishare2-org/ishare2-cli/main/ishare2 && chmod +x /usr/sbin/ishare2 && ishare2
```

## 🛠️ Instalação do Client Pack<a id="client"></a>

- 👉 Você pode realizar a instalação do Client Pack e acessar os ativos do laboratório através do putty, vnc, etc (se você já tiver o do EVE-NG, é o mesmo):
🔗 https://mega.nz/file/G5liXYzK#oaSC1Jrh5m0HaNkReirurtrXhIHGw6NOZX3jgus1xqo


## 📌 Referências<a id="Ref"></a>
- **LABHUB:** 🔗 https://labhub.eu.org
- **ISHARE2:** 🔗 https://github.com/ishare2-org

