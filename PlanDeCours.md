Plan de cours
============


Prérequis :
- version d'essai d'UnityPro
- Mac ou PC
- option : téléphone ou tablette iOs ou Android




Découverte d'Unity3D
---
_Objectif : donner envie d'utiliser le soft. Ce qui est possible et ce qui n'est pas possible avec Unity3D_
- demos/showreels
	- [GDC 2013](http://www.youtube.com/watch?v=rYBaZyqiYZo)
	- [Guns of Icarus](http://gunsoficarus.com/)
	- [Momonga](http://www.paladinstudios.com/)
	- [Fract](http://fractgame.com/)
	- [Lovers in a dangerous Spacetime](http://www.asteroidbase.com/dangerous-spacetime/)
	- [Pulse](http://www.teampixelpi.com/)
	- Bad Piggies, Temple Run2, ZombieVille...
- démo dans l'éditeur : AngryBots, modification de la scène au runtime
- Multi plate-formes : présentation des targets
- points forts et points faibles d'Unity3D
- licences
- tour de table : ce que vous attendez de ce cours. Votre expérience d'U3D, de la 3D temps réel, avec Flash/stage3D, WebGL...




Prise en main de l'interface
---
_Objectif : découverte de l'interface_

- créer des primitives
- les vues de l'interface : Scene, Inspector, Project, Hierarchy
- navigation dans la scene : vue perspective/orthographique, scene gizmo, raccourcis (Alt, clic milieu)
- manipuler des primitives : déplacement, transformation, rotation
- la vue Hierarchy
- enregistrer la scène



Scripting basique
---
_Objectif : démarrer le scripting dans Unity3D_

- Une première compilation : vues Console et Game, Play/Pause/Step. La fenêtre de stats.
- la caméra
- intro au scripting : faire bouger une primitive
- faire tourner notre primitive : Quaternions, la documentation d'Unity
- GameObjects, MonoBehaviours, Component, Object (schéma)
- les fonctions Start(), Awake(), Update()
- ajouter un 2ème script à la primitive
- timing : Time.deltaTime, Time.time (...), Update/FixedUpdate
- point théorique : languages (C#, JS, Boo) et éditeurs dans Unity3D, Unity3D et Mono
- faire bouger la caméra au clavier, à la souris et au doigt (téléphones ou tablette requis)
- La console / print / Debug.Log

 


Gestion des assets et rendu
---
_Objectif : comprendre comment utiliser les assets préparés par l'artiste_ 
- import de modèles avec l'AssetStore : Space Ship Shooter
- les materiaux
- les meshes
- textures :
	- formats (desktop et mobile)
	- atlas
	
- éclairage
- postprocessing
- prefabs



Scripting avancé
---
- prefabs
- caméras (map 2D vue du dessus)
- son
- collisions





Théorie de la 3D
---
_Objectif : comprendre les fondamentaux de la 3D_ 

[GPU sur wikipedia] http://en.wikipedia.org/wiki/Graphics_processing_unit
- la géométrie : un mesh 
- mesh = vertices + faces (triangles) + uvs +vcolor, tangents...
- construction d'une géométrie simple (Quad) en code
- qu'est-ce qu'un materiau? Textures et UVs. Filtrage et mipmaps
- théorie des shaders : 
	- petit historique des GPU
	- présentation des languages 
	- les shaders dans Unity










Physique
---
_Objectif : bases de la simulation physique !_ 

- asset store (nobiax free rocks)
- reprise de l'exemple vu dans 'interaction basique' et ajout de physique simple (forces, gravité)
- collisions et colliders







Débug, optimisation, performance et profiling
---
_Objectif : optimiser le rendu, notamment pour les targets mobiles_ 
- la console, Debug.Log
- déchiffrer les stats
- le concept de draw calls : démonstration du batching (avec matériaux, z-order...)
- le débugeur
- remote
- théorie : Unity3D et Mono (http://www.mono-project.com/What_is_Mono)



Autres sujets possibles...
---
- le son dans Unity
- la 2D dans Unity
	[2.5D](http://www.gamasutra.com/blogs/MattHammill/20130206/186138/Making_Two_and_a_half_D_art_for_Lovers_in_a_Dangerous_Spacetime.php)
- intro à la programmation de shaders (surface shaders)
	[Builtin shaders]: (http://unity3d.com/unity/download/archive)
- particules / Shuriken
- Editor scripting
