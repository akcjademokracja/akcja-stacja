
# Akcja Stacja

## Potrzebne
W nowszych Debianach/Ubuntu

```sh
apt install ansible git
git clone https://github.com/akcjademokracja/akcja-stacja
```


Kiedyś: git, python3 i reszta: 
```sh
apt install git python3 python3-pip
pip3 install ansible
git clone https://github.com/akcjademokracja/akcja-stacja
```
## Uruchamianie

```sh
ansible-playbook -K laptop.yml
````

(można dodać `-vvv` dla większej ilości informacji)
