# Note

## Zapier

### Qu'est-ce que Zapier ?

Zapier est un outil qui aide à automatiser des tâches répétitives entre deux ou plusieurs applications, sans besoin de coder. Lorsqu'un événement se produit dans une application, Zapier peut indiquer à une autre application d'exécuter une action particulière.

### Que devrais-je automatiser avec Zapier ?

- Les tâches que je dois effectuer fréquemment. Exemple : Envoyer un rappel hebdomadaire à mon équipe pour remplir un ordre du jour de réunion.
- Toute tâche nécessitant de transférer des informations d'une application à une autre. Exemple : Ajouter des tâches d'une application de gestion de projet à ma liste de tâches personnelle.
- Les tâches qui ne demandent pas beaucoup de réflexion. Exemple : Copier les adresses email des participants à un événement dans une feuille de calcul.

### Qu'est-ce qu'un Zap ?

Un Zap est un flux de travail automatisé qui indique à mes applications de suivre cette commande simple : "Quand cela se produit, faire ceci."

Chaque Zap a un déclencheur et une ou plusieurs actions. Un déclencheur est un événement qui lance un Zap, et une action est ce que le Zap effectue. Chaque action accomplie par un Zap compte comme une tâche.

### Créer son premier Zap

Avant de créer un Zap, il est utile de réfléchir à ce que l'on essaie d'accomplir. Par exemple, supposons qu'un formulaire de contact est présent sur un site web. Il est souhaité de stocker les soumissions du formulaire dans une feuille Google, sans avoir à les copier-coller manuellement.

**Les étapes pour créer un Zap :**

1. Préparer la feuille de calcul et le formulaire.
2. Configurer le déclencheur : Choisir l'application déclencheur, connecter le compte et personnaliser l'événement déclencheur, puis tester le déclencheur.
3. Configurer l'action : Choisir l'application d'action, connecter le compte et personnaliser l'événement d'action, puis mapper les champs.
4. Tester le Zap.

### Intégrations d'applications avec Zapier

Zapier fonctionne avec des milliers d'applications, mais les déclencheurs et actions disponibles varient selon l'application. Pour en savoir plus sur ce qui est possible avec une application sur Zapier, il suffit de la rechercher dans le répertoire des applications.

#### Configurer le déclencheur

L'éditeur de Zap est l'endroit où sont créés de nouveaux Zaps et où les Zaps existants sont modifiés. Un déclencheur est ce qui lance un Zap. (Il représente le QUAND de toute automatisation).

1. **Sélectionner l'application et l'événement déclencheur :**
   - Lorsque l'éditeur de Zap est ouvert, il est demandé de choisir une application en tant que déclencheur.
   - Ensuite, choisir un événement déclencheur. C'est l'événement qui se produit dans l'application déclencheur et qui signale à Zapier de démarrer le Zap. Dans ce cas, c'est lorsqu'une nouvelle entrée de formulaire est soumise.

2. **Se connecter au compte de l'application et personnaliser l'événement déclencheur :**
   - Il faut se connecter à l'application si ce n'est pas encore fait. Une fois connecté, il faut sélectionner le compte à utiliser avec le Zap.
   - Ensuite, personnaliser l'événement déclencheur en choisissant les bonnes options dans les menus déroulants. Dans ce cas, il s'agit de sélectionner le formulaire spécifique qui déclenchera le Zap.

3. **Tester le déclencheur :**
   - Une fois le déclencheur configuré, il faut le tester pour s'assurer qu'il fonctionne. Lors du test du déclencheur, Zapier recherche des données existantes dans le compte de l'application déclencheur et les importe dans l'éditeur de Zap.

#### Configurer l'action

L'action est la partie FAIRE de l'automatisation. Les actions sont les événements que le Zap doit effectuer après le déclencheur.

1. **Sélectionner l'application et l'événement d'action :**
   - Comme pour le déclencheur, il faut sélectionner l'application d'action dans le menu déroulant et choisir l'événement d'action—ce que le Zap doit faire.

2. **Se connecter au compte de l'application et personnaliser l'événement d'action :**
   - Ensuite, il faut se connecter au compte de l'application d'action, puis personnaliser l'événement d'action.
   - Zapier sépare les données provenant de l'événement déclencheur en éléments individuels, qui peuvent ensuite être utilisés dans les champs de l'action.

3. **Mapper les champs :**
   - Dans cet exemple, les colonnes étiquetées de la feuille de calcul sont maintenant des champs à remplir avec les informations de l'application de formulaire.

4. **Tester le Zap :**
   - Après avoir configuré l'action, il est temps de tester le Zap. Lors du test, Zapier exécute l'action selon la manière dont les champs ont été mappés. Le test permet de vérifier si le Zap fonctionne correctement. 

### Les Zaps pré-fabriqués et les tâches

Il existe des Zaps pré-fabriqués (appelés Zap templates) qui permettent de démarrer rapidement. Une fois le Zap activé, il automatisera les tâches selon les actions configurées. Rappel : Chaque action réussie effectuée par un Zap est appelée une tâche. Les tâches sont toujours associées aux actions réussies.