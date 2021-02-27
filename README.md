#Linux info

Le but de ce repo est de fournir un script qui permet de générer une page html avec les infos d'une machine linux

## Usage

Installer ansible et git

```
apt install ansible git
```


Cloner ce repo et lancer ansible

```
git clone https://github.com/TanguyPatte/linux_infos.git
cd linux_infos
ansible-playbook playbook.yml
```

Le fichier généré se trouve dans le répertoire courant sous le nom `./infos.html`
