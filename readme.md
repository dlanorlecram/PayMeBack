# PayMeBack

*__Objectif__* : Mise en place d'une application web sur la gestion des prêts financier entre amis.

Cette application doit permettre à un utilisateur de créer un compte personnel. Il pourra accéder à son compte en se connectant via une interface de connexion et d'inscription. Lors de la phase d'authentification il sera redirigé vers une plateforme. Cette dernière se présentera sur la forme d'un __dashboard__, qui sera composé d'une menu
et une zone réservée aux dernières activités (ex: Dernière dette, dernier prêt, dernier amis ajouté).

## Utilisateur

Un utilisateur se définira comme tel:

- Nom
- Prénom
- Adresse email
- Mot de passe

L'utilisateur peut être dans certain cas un prêteur et dans d'autre cas un emprunteur.

## Prêteur

Un prêteur se défini comme une personne prêtant une somme pour un évènement définit 'ex: achat de boisson pour la soirée' à un ou x emprunteur.

## Emprunteur

Un emprunteur aura un seul en prêteur par prêt.

## Prêt

Un prêt reprendra le nom du prêteur,  l'intitulé du prêt accompagner ou non d'une court text descriptif, ainsi que la liste des emprêteurs qui on ou nous déjà payer leur dette.
