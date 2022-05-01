---
title: "Episode 3 : L’UX de Notes+ - La Stratégie (1/4)"
date: "2022-04-26"
---

La semaine passée, pour l’épisode 2, nous avons présenté l’intérêt de l’UX (Expérience Utilisateur) et de l’UI (Interface Utilisateur) ?

En tant que solopreneurs, bootstrappers ou développeurs indépendants, vous développez une application pour qu’elle puisse être utilisée par des utilisateurs : ce sont ces utilisateurs qui sont vos juges.

Si votre application n’est pas utilisée, alors elle ne sert à rien, tous vos efforts et vos nuits blanches seront vains. Ce qui n’est pas le cas du chercheur d’emploi qui a pour ambition d’impressionner les potentiels employeurs : il faut démontrer la maîtrise les technologies affichées dans le CV... il doit avoir un portfolio solide, une page Github bien remplie,...etc.

**C’est quoi l’Expérience Utilisateur (UX) ?**

Le meilleur moyen pour ne rien faire en ce qui concerne l’UX est d'aller faire un recherche à Google ou Youtube...

Non seulement les ressources sont abondantes mais très contradictoires... Quel est le processus à adopter en matière d’UX ? Chaque designer a sa démarche. Et lorsque vous êtes débutant ou vous ne vous y connaissez pas en matière de design, il vaut mieux se concentrer sur les designers “_entrepreneurs_” ou freelances car leurs revenus directs dépendent de leur travail... Et pour le faire, je me suis appuyé sur deux (02) ressources :

- [Learn UX Essentials](https://www.kreativepro.io/masterclass/learn-ux-essentials-strategy-wireframes) de Neftali Loria
- [Learn UX Design](https://learnui.design/courses/learn-ux-design.html) de Erik Kennedy

Il est clair que notre objectif ici n’est pas de faire un cours sur l’UX et les ressources présentées ne sont pas exclusives... Si vous voulez un rapide survol de l’UX, l’excellent **[No Bullshit Guide to UX](https://hype4academy.gumroad.com/l/guidetoux)** de Hype4Academy devrait faire l’affaire.

De ce que j’ai retenu en consommant toutes ses ressources, c’est juste que l’UX vous contraint à **prendre en compte l’utilisateur dans votre projet** et c’est une bonne chose car en fin de compte, c’est bien pour cet utilisateur que vous concevez votre application.

Dit ainsi, cela peut paraître trivial mais c’est extrêmement difficile. Lorsque vous avez une idée en tête ou un projet, vous êtes toujours convaincu que vous avez le meilleur projet du monde ou la meilleure idée... et c’est très difficile de lâcher prise, même sur les bords.

Néanmoins, cette prise en compte de l’utilisateur se fait avec METHODE.

Si on jette un coup d’oeil à la METHODE utilisée par Erik Kennedy, cela se résume à ceci :

![UX Design Process_Erik Kennedy](/public/images/Episode3/UX_Design_Process_Erik_Kennedy.png)

Cette méthode est assez classique avec :

1. en premier la compréhension du problème qu’on cherche à résoudre et pour QUI on veut résoudre ce problème,
2. en deuxième lieu le prototypage de la solution,
3. en troisième le test ou la collecte du feedback,
4. et enfin la transmission du dossier à l’équipe de design (UI) ou au développement.

La METHODE utilisée par Neftalia Loria est similaire, à un détail près qu’on y retrouve l**’analyse compétitive** ou encore le “**_flowchart_**” qui est simplement un schéma qui illustre les étapes que vont suivre vos utilisateurs pour atteindre des objectifs spécifiques...

![UX Design Process_Neftali Loria](/public/images/Episode3/UX_Design_Process_Neftali_Loria.png)

Si vous jetez aussi un coup d’oeil à la METHODE de l’agence [FullstackLabs](https://www.fullstacklabs.co/playbook#phase1step3), vous verrez qu’elle ajoute une **carte de fonctionnalités** (_Feature Map_)...

![FullstackLabs Playbook](/public/images/Episode3/FullstackLabs.png)

Donc, l’important est de ne pas s’attarder sur les détails mais d’aller à l’essentiel.

L’essentiel ici se résume à avoir les idées claires sur un **certain nombre de questions avant de commencer l’UX**... Ces questions, je n’ai rien inventé. Cela ressort simplement des ressources mentionnées plus haut.

- **Quel est le problème que vous essayez de résoudre ? Pourquoi est-ce important?**

J’ai remarqué, en ouvrant la dernière fois Ms OneNote, que j’avais d’excellentes notes que j’avais prises il y a de cela trois (3) ans mais que j’avais complètement oublié, noyées sous d’autres notes. Et je ne suis pas le seul : plusieurs personnes prennent des notes sans donner une suite à ces notes. Ces notes matérialisent des idées, et ces idées, nous souhaitons les transformer en actions. Sinon, nous ne devrions pas nous donner la peine pour prendre ces notes. Comment transformer nos notes en ACTIONS ? Voilà le défi auquel nous devons apporter des réponses.

C’est important car nous souhaitons apporter plus d’ordre et d’organiser pour nos notes. On ne peut plus se contenter d’une organisation par tags ou catégories. Il faut rendre les notes plus actionnables.

- **Pour qui vous voulez résoudre ce problème ?**

Hommes, femmes, entrepreneurs, managers, indépendants, qui sont partagés entre plusieurs projets et souhaitent garder en mémoire l’historique de leurs projets...

- **La solution proposée**

Nous allons proposer une application de prises de notes, avec organisation par projets pour le MVP. La particularité de ces notes est que chaque note ne sera modifiable que le jour de sa création, pas après. De cette sorte, on permettra de disposer à la fois une ARCHIVE et un dossier d’analyse d’évolution de la pensée et des objectifs d’un projet... avec possibilité d’exportation du dossier du projet.

- **Qui sont les compétiteurs**
  - [Ms OneNote](https://www.microsoft.com/fr-ww/microsoft-365/onenote/digital-note-taking-app)
  - [Evernote](https://evernote.com/intl/fr)
  - [Google Keep](https://keep.google.com/)
  - [Notion](https://www.notion.so/fr-fr)
  - [Obsidian](https://obsidian.md/)
  - [Simplenote](https://simplenote.com/)
  - [Milanote](https://milanote.com/)
- **Les contraintes du projet**

Le projet sera fait dans un premier temps en mode “web”... Le mobile suivra après.

Il faut noter que ce ne sont que des idées de départ... Lors de notre phase d’UX, nous allons affiner ces idées.

Dans certaines ressources, vous allez voir d’autres questions comme par exemple “_A quoi va ressembler le succès pour votre projet_” ou encore “_quels sont les objectifs de votre projet_”...

Ces différences se résument au **CONTEXTE**. La majorité des méthodes et écrits que vous trouvez sur Internet porte sur des projets déjà établis. On ne fonctionne pas de la même façon lorsqu’on lance un nouveau produit sans marché, ou encore lorsqu’on fait une mise en place d’une nouvelle fonctionnalité ou encore qu’on renforce notre offre en proposant un produit complémentaire à un produit existant...
