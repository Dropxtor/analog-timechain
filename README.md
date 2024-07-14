# Exigences de VPS

 ```bash
RAM : 16 GB
CPU : 8 coeurs
Disque : 300 GB SSD NVME
Debit : 500 Mo/s
```
__Vous pouvez acheter un VPS chez__ :
[Contabo](https://contabo.com/en/vps/) (Carte de crédit/PayPal)
PQ Hosting (Carte de crédit/Paiement cryptomonnaie accepté)

# Configuration du portefeuille et demande d'eau

- Téléchargez l'Extension [Fearless](https://chromewebstore.google.com/detail/fearless-wallet/nhlnehondigmgckngjomcpcefcdplmgc)
- Créez un nouveau portefeuille
- Rejoignez  [Analog Discord](https://discord.gg/analog)
- Demandez de l'eau dans le canal 🚰| faucet en utilisant la commande suivante :
```bash
!faucet your..analog..wallet..address..here
```
# Déploiement

Ouvrez Termius / Putty
- Copiez et collez la commande suivante :
```bash
wget https://raw.githubusercontent.com/Dropxtor/analog-timechain-node/main/analog.sh && chmod +x analog.sh && ./analog.sh
```
- Vous pouvez vérifier les journaux du nœud analog en utilisant cette commande :
```bash
docker logs analog
```
# Configuration validateur

- Visitez : [Ce site](https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc.testnet.analog.one#/staking/actions)
- Cliquez sur l'option `Validator` dans le coin supérieur droit
- Sélectionnez votre portefeuille analog dans la section `stash account` et maintenez les autres détails par défaut
- Cliquez sur le bouton Next
- Écrivez votre  `rotate key` dans la section `keys from rotatekeys`
- Vous pouvez écrire 1 à 10 dans la section `reward commission percentage`
- Cliquez ensuite sur le bouton `Bond & Validate`
# Soumission du formulaire de liste blanche

- Soumettez cette [Formulaire](https://l5d87lam6fy.typeform.com/to/kwlADm6U?typeform-source=docs.analog.one) avec les détails appropriés et attendez l'approbation de l'équipe Analog
