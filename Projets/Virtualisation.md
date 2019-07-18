Virtualisation
=
D'après [RedHat]([https://www.redhat.com/en/topics/virtualization),

La virtualisation est une technologie permettant de **créer plusieurs environnements** avec des ressources depuis un seul matériel physique.<br/>
Il est **orchestré par un hyperviseur connecté au matériel** et contrôle le découpage du matériel en plusieurs, distincts environnements sécurisés, que l'ont appel des machines virtuelles (VM). Ces VM sont gérés par l'hyperviseur, **qui distribue les ressources**.

**Il y a différents hyperviseurs de virtualisation.**


## Type 1
D'après [Vmware](https://www.vmware.com/topics/glossary/content/hypervisor)

Ces hyperviseurs '''fonctionnent directement sur le matériel'''. Ils ont donc un '''accès direct sur le matériel'''.

Les hyperviseurs de type 1 les plus connus:
* [ESX/ESXi](hhttps://www.vmware.com/products/esxi-and-esx.html) de Vmware
* [Hyper V](https://docs.microsoft.com/fr-fr/virtualization/hyper-v-on-windows/about) de Microsoft
* [Xen](https://www.xenproject.org ) de XenSource

## Type 2
D'après [Vmware](https://www.vmware.com/topics/glossary/content/hypervisor)

Ces hyperviseurs sont installés en tant que logiciel **sur le système d'exploitation qui est nommé "machine hôte"**. ''' La VM crée sera appellé **"machine invité"**.

Les hyperviseurs de type 2 les plus connus (voir même les seuls utilisés):
* [Workstation Pro](https://www.vmware.com/products/workstation-pro.html) de Vmware
* [VirtuaBox](https://www.virtualbox.org) de Oracle Corporation

