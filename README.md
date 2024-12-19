# Serveur DHCP sous Linux
- Installer le server (sudo apt install isc-dhcp-server)
- Changer l'interface ipv4 (sudo nano /etc/default/isc-dhcp-server)
- Configurer le serveur (sudo nano /etc/dhcp/dhcpd.conf)
- Mettre son IP statique, avec l'adresse MAC du client cible
- Redémarrer le serveur, aprè avoir s'être mis en réseau interne
- lancer sa deuxiéme VM, Pinger de la Debian vers l'Ubuntu
- Quand le ping est fini, le test est terminer.

## Félicitation vous avez réussi à faire, votre premier serveur sous Linux 🎉
