# DNS_Windows
Quête WCS DNS sous Windows

## 1) Installation du rôle DNS dans Windows Server

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/1-Ajout_role_DNS.png)

## 2) Ouvrir le gestionnaire DNS

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/2-Ouvrir_gestionnaire_DNS.png)


## 3) Ajouter une nouvelle zone de recherche directe : Wilder.Lan

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/3-Ajout_nouvelle_zone_de_recherche_directe-Wilder_Lan.png)


## 4) Ajouter un nouvel_hôte A ns1.Wilders.lan puis ajouter un nouvel Alias CNAME (dns.wilders.lan) et pour finir un nouveau_serveur de_messagerie MX (mail.wilders.lan)


![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/4-Ajout_nouvel_hote_nouvel_Alias_nouveau_serveur_de_messagerie.png)


## 5) Créer une Nouvelle zone de recherche inversée

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/5-Nouvelle_zone_de_recherche_inversée.png)


## 6) Test avec nslookup depuis le serveur Windows

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/6-nslookup_depuis_le_serveur.png)


## 7) Test avec nslookup depuis le client Windows

![Install_role_DNS](https://github.com/Hebus79/DNS_Windows/blob/main/Images/7-nslookup_depuis_le_client.png)
