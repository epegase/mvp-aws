---
title: "Episode 0 : De l'idée à l'application avec AWS (Introduction)"
date: "2022-04-05"
---

J’ai décidé de commencer une série de tutoriels sur le processus de création d’une application complète en partant de zéro. Rien d’exceptionnel puisqu’en faisant une petite recherche à Youtube, vous trouvez des centaines de vidéos qui abondent dans ce sens. Mais ma série a pour mission de mettre en exergue le processus pour une application destinée à la production... Cette précision a tout son sens et je vais le développer à la suite.

# Pourquoi cette série ?

Le 04 Mars 2022, j’ai été sélectionné comme AWS Community Builders...

C’est quoi AWS Community Builders ?

![AWS Community Builders Page](/public/images/AWS-Community-Builders.png)

> Le programme AWS Community Builders offre des ressources techniques, du mentorat et des opportunités de réseautage aux passionnés techniques AWS et aux leaders d'opinion émergents passionnés par le partage des connaissances et la connexion avec la communauté technique.

C’est un programme libre d’Amazon Web Services où vous pouvez vous inscrire à la liste d’attente et une fois sélectionné, vous l’intégrez gratuitement.

Passé l’euphorie, je me suis demandé comment je pouvais assurer ma mission de partage de connaissances ? Après tout, tout en bénéficiant de ressources techniques et de mentorat, il faut bien partager ces connaissances.

Après avoir pris le temps d’observer la scène et les publications de plusieurs _community builders_, j’ai observé les mêmes tics rencontrés dans la blogosphère des développeurs :

- copie rephrasée de publications d’autres développeurs,
- appropriation découpée de la documentation,
- approche centrée principalement sur les solutions et non les problèmes,
- etc.

Je ne vais pas me mettre à lister tous les maux de la publication technique du développement web. L’emploi est très rare et il faut forcément se démarquer. Je comprends les motivations des uns et des autres.

Pour ma part, j’ai choisi de faire ma part et de partager les connaissances acquises en partant d’un problème imaginé mais qui peut recouper ce qu’on rencontre dans le réel. Mais parler de problème implique de parler de la cible choisie pour cette série.

# Cible

- Développeurs auto-apprenants
- Solopreneurs
- Développeurs frontend et mobiles

Mon hypothèse de départ vient du fait que j’ai observé nombre de développeurs auto-apprenants suivre des cours à Youtube, acheter des cours à Udemy ou d’autres plateformes et à la fin de ces cours, être incapables de passer d’une idée à une application de leur propre chef.

Comment on peut avoir une idée, avoir consacré de longs mois à suivre des cours, pratiquer les exemples du cours, et être incapable de donner vie à son idée ? C’est un vrai paradoxe. Même le stade de MVP (_Minimum Viable Product_), ces développeurs n y arrivent pas alors que le MVP est moins contraignant qu’un produit complet car l’objectif visé à travers le MVP est d’expérimenter si la solution qu’on propose à travers l’application résoud effectivement un problème rencontré dans le marché visé.

Il est clair qu’à la lecture de ce qui précède, ma cible première concerne les développeurs auto-apprenants... mais pas que ceux la. Il y a aussi les développeurs frontend et mobiles qu’on retrouve en grand nombre dans cette catégorie de développeurs auto-apprenants. Très peu d’auto-apprenants se lancent dans le backend... et vous verrez dans la suite de cette série l’intérêt de combler ce gros déficit à travers les offres de AWS.

Ma cible porte aussi sur les développeurs qui ambitionne d’être solopreneurs ou bootstrappers... C’est une catégorie de développeurs qui choisissent plutôt la voie de l’entreprenariat en proposant de petites applications le plus souvent mobiles, donc les revenus leur permet de maintenir un niveau de vie acceptable avec moins de maintenance.

Abordons maintenant les objectifs du cours.

# Objectifs

Les objectifs du cours sont simples :

- vous permettre de partir d’une idée pour une application complète,
- présenter les produits et services d’Amazon Web Services qui concernent les développeurs front-end et mobiles,
- vous donner les clés pour lire la documentation des technologies.

De mon point de vue, le plus important est le dernier car les technologies évoluent. Mais si vous avez de solides bases et une bonne vue sur le processus, vous pouvez vous adapter sans problèmes à cette évolution.

# Approche pédagogique

Comme je l’ai dit plus haut, l’approche pédagogique est orientée problème. Je pars d’un problème simple et le déroulé des publications chaque semaine présentera la solution. En réalité, chaque produit, service ou technologie apparaît toujours pour résoudre un problème.

React par exemple est apparu pour résoudre un problème et si vous faites une recherche sur Youtube, vous allez trouver la première vidéo de présentation des problèmes qui ont amené sa création en 2013. Après, des fonctionnalités peuvent être ajoutées pour résoudre d’autres problèmes rencontrés lors de l’utilisation.

Par la suite, il peut avoir de la concurrence avec d’autres approches comme Vue, Svelte, ELM et bien d’autres. Sans compter que d’autres solutions peuvent proposer un niveau d’abstraction supérieur comme cela se passe actuellement avec React : Gatsby, NextJs, Remix, Hydrogen, ...etc.

Malheureusement, des camps naissent et il suffit qu’un développeur ait résolu son problème avec satisfaction qu’il publie légitimement son retour d’expérience et hop, c’est repris en boucle avec des fans qui naissent partout.

Je ne vais pas développer cet aspect mais sachez que chaque solution sera présentée en rapport avec le problème.

# Organisation

Comme organisation, j’ai opté pour une publication hebdomadaire. Tous les mardi, une nouvelle vidéo sera publiée. Pour le début, je n’ai pas un script prévu pour chaque vidéo, ou une idée sur la répartition entre la théorie et la pratique.

# Prérequis

Comme pré-réquis, vous devez avoir au minimum les bases en :

- HTML,
- CSS,
- et Javascript.

Une recherche à Google ou à Youtube vous donne les ressources pour disposer de ces bases. Si vous êtes plus rigoureux, allez suivre la formation gratuite “**[Front-end web developer](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer)”** de MDN (Mozilla Developer Network). C’est de loin la plus meilleure.

# Programme

Pour présenter le programme, il faut savoir en premier ce que nous ambitionnons de développer. Puisque la finalité est de développer une application complète en partant de l’idée, l’idée ici est de développer une application de prises de notes. Nous allons donc aborder le processus de création en partant de zéro.

Le programme sera fortement marqué par l’improvisation. Au fur et à mesure que nous allons avancer dans notre application, nous allons ajuster les choses et fixer les défis.

Pour l’instant, les épisodes qui me viennent à l’esprit à court terme porteront sur :

- Episode X : Présentation de l’application Notes
- Episode X : L’UX de l’application Notes
- Episode X : L’UI de l’application Notes
- Episode X : Le Front-end de l’application Notes avec React
- Episode X : le Back-end de l’application Notes avec AWS
- Episode X : La maintenance de l’applications Notes

Vous voyez bien que j’ai marqué X sans numérotation parce qu’un thème peut recouper plusieurs épisodes... Si je constate qu’un thème s’étale sur plusieurs heures, il sera découpé en plusieurs épisodes.

Je vais faire l’effort d’être précis et concis dans ma présentation, tout en allant si possible dans les détails, et en ayant toujours en tête ma cible première : les développeurs auto-apprenants comme moi.

Bien sûr, cette série peut comporter des erreurs et si vous en constater une, vous pouvez toujours m’écrire à duvergerpetga@gmail.com

Portez-vous bien et à la semaine prochaine, précisément Mardi prochain pour l’épisode 1 qui sera consacré à la présentation du processus de développement et de l'application de prise de notes que nous allons développé.
