[Retour à la page principale](../README.md)

# Pourquoi je ne recommande pas Java pour faire des jeux ?
Lorsque l'on me demande quel langage je recommanderais pour faire des jeux, je réponds toujours que ça n'a pas d'importance. Le plus important, c'est de savoir ce que l'on veut :

# Approche bidouille/hacker
Si vous êtes un pro de la bidouille, un "hacker" dans l'âme, que vous aimez tout faire en partant de rien (et c'est très bien, il en faut !), je vous conseille d'utiliser un langage assez bas niveau et de vous intéresser aux API graphiques, telles qu'OpenGL ou Vulkan. Des librairies les implémentant existent dans la plupart des langages bas niveau (et un peu plus haut niveau), tels que C, C++, Rust, Java. Mais attention, vous ne sortirez probablement jamais un jeu commercialisable de cette manière si vous êtes seul (même si d'autres l'on fait), car le développement risque d'être très long. Vous devrez utiliser toutes vos connaissances du langage et de l'architecture logicielle afin de recoller toutes les librairies graphiques, sonores, de gestion des input, et moult d'autres, afin de recréer un outil de création de jeu qu'on pourra peut-être comparer à un moteur de jeu moderne. Je ne procède pas comme cela personnellement, je trouve cette approche passionnante et pleine de mérite, mais je souhaite avant tout créer des jeux beaux et amusants, et pour faire ça il y a plus simple.

J'aime aussi appeler cette approche l'approche "[Jonathan Blow](https://www.youtube.com/watch?v=pW-SOdj4Kkk)", à l'image du créateur génial du jeu également génial *The Witness*, et qui développe depuis plus de 7 ans (je crois) son propre langage, le *Jai* qui sert à coder ensuite son propre moteur de jeu, avec lequel il développe maintenant son propre jeu. Un vrai fou, mais avec des idées passionnantes.
 
# Fan d'un langage en particulier ?
Si vous croyez dur comme fer en un langage que vous aimez profondément (bon, déjà ouvrez un peu les yeux et regardez autours de vous), utilisez-le ! Tout simplement. Si ce langage vous permet de développer plus vite que votre ombre, que vous le connaissez sur le bout des doigts, toutes ses petites optimisations et tous ses usages idiomatiques, vous allez gagner beaucoup de temps de développement à vous en servir. Vous pouvez alors vous pencher sur des librairies de création de jeux dans votre langage. Il en existe pour tous. Si vous êtes fan de Java, je vous conseille LibGDX. Mais l'expérience ne sera jamais comme avec un vrai moteur. Vous devrez recréer certains outils avant par vous-même, ou les chercher à droite à gauche sur internet. Personnellement, je ne trouve pas de langage si approprié et si efficace que j'irai me mettre à accepter de sacrifier de la simplicité juste pour pouvoir travailler avec. Même si Java serait sûrement parmi mes premiers choix, avec Python et pourquoi pas même Haxe.

# Je veux juste faire un jeu maintenant
Si, comme moi, vous êtes plutôt un polyglotte des langages de programmation, si tout ce que vous souhaitez est faire un bon jeu commercialisable le plus simplement et le plus rapidement possible, alors penchez vous sur les moteurs de jeu. Prenez le plus aboutit pour les fonctionnalités qui vous intéressent (3D ou 2D, légèreté ou richesse, payant ou gratuit, plateformes supportées...), repérez les extensions disponibles qui vous faciliteront la vie (jeux en réseaux, modules d'animation automatique, assets ...) et lancez-vous ! Des milliers de guides et tutoriels existent pour la plupart des gros moteurs de jeu. Il sont conçu pour ça, et ce sont les meilleurs outils pour faire des jeux. Le langage utilisé n'est qu'une considération secondaire. De manière générale, si je ne suis pas fan du langage, mais que le moteur est vraiment bien pour le reste, alors ça ne compte pas pour moi.

# Langage moteur vs. "scripting"
Il faut aussi différentier le langage du moteur et le langage de scripting. Le moteur est souvent écrit en C++, car c'est le langage traditionnel pour écrire des moteurs. Mais les jeux ne sont pas écrits en C++ pour autant. Le C++ présente une interopérabilité avec de nombreux langages plus haut niveau. Comme ça, vous utilisez les performances du C++ pour que le moteur soit optimisé, et vous codez la logique du jeu dans un langage haut niveau, donc plus rapide à utiliser, afin de ne pas multiplier le temps de développement par 10. Ces fameux langages de scripting sont souvent des mélanges d'orienté fonction et d'orienté objet, comme par exemple : lua, python, C# ou javascript (et autres langages propriétaires s'inspirant d'eux : GDscript (Godot engine), GML (Game Maker studio), Visual Scripting (Unreal Engine 4)).

De manière générale, tous les langages se ressemblent. L'important est de maîtriser les grands principes transversaux, tels que l'orienté objet, l'orienté fonction, l'orienté données, le réseau, les shaders, les design patterns, l'architecture logicielle ... Et ensuite de les appliquer, quel que soit le langage, le moteur ou la librairie que vous utiliserez.

Donc non, je ne recommande pas Java car il n'y a pas de gros moteur bien ficelé et facile d'utilisation qui permet de coder la logique du jeu en Java, sinon j'aime bien Java, c'est chouette, un peu rigide mais chouette. Mais le moteur Unity propose le C#, c'est presque comme Java, allez y jeter un coup d’œil ensuite !

—

[Retour à la page principale](../README.md)

