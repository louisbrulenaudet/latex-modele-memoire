# La rédaction d'un mémoire de recherche universitaire avec LaTeX et BibTeX
[![Documentation](https://img.shields.io/badge/Template-LaTeX-blue.svg)](https://github.com/latex3/)

Synthétiquement, LaTeX est un langage et un système de composition de documents. Il s’agit d’une collection de macro-commandes destinées à faciliter le processus de création documentaire par la conformité automatique à des normes typographiques spécifiques et modulables. La spécificité de LaTeX repose dans le principe de séparation du fond et de la forme. Il encourage le rédacteur à se concentrer sur la structure logique et le contenu de son document, tandis que sa mise en page (pagination, césure des mots, alinéas insertion d’en-têtes et de pieds-de-pages) est laissée au compilateur. 

Pour cette raison, bien qu’il nécessite une courbe d’apprentissage supérieure à celle relative à l’utilisation des logiciels de traitement de texte traditionnels, ce dernier confère des avantages décisifs pour les chercheurs dépendant de la fonction rédactionnelle, dont les étudiants en université et les enseingants.

## Qualités intrinsèques du langage pour la rédaction de documents académiques

Si l’on devait cristalliser les besoins exprimés par les étudiants chercheurs en ce qui concerne la production et la conservation de l’acte documentaire, on observerait une convergence naturelle vers un triptyque qualité-immutabilité-portabilité. Qualité, en premier lieu, dans le rendu proposé par l’outil de production et sa capacité à se présenter comme un support efficace du transfert d’informations entre les parties contractantes. 

Nous l’avons évoqué, le processus de composition de LaTeX repose sur une épreuve de compilation du code source, fondamentale dans la production de sortie. La délégation du contenu au processeur de texte permet alors de disposer de meilleurs algorithmes de crénage, de césure et de justification, reposant sur le concept de minimisation de l’erreur d’affichage :

>Par l’expérimentation de permutations successives de paramètres, les algorithmes vont permettre de déterminer les coefficients rendant la sortie la « plus agréable » possible. 

En réalité, l’avenir réserve encore de grandes choses pour cet avantage, notamment du fait que les logiciels de traitement de texte de disposent pas (encore) des ressources informatiques suffisantes pour effectuer les calculs équivalents, et restent interactifs. 

On le comprend assez rapidement, LaTeX n’est pas destiné au grand public, son usage est d’ailleurs implicitement réservé, dans l’imaginaire collectif, aux chercheurs en mathématiques et aux éditeurs de publications scientifiques, pour une raison : 

>Le rendu proposé à la suite de la compilation d’un document `.tex` est professionnel. Dans le cadre d’une application à la production universitaire, on perçoit pourtant aisément l’intérêt d’un tel procédé. 

Le chercheur se retrouve amené à rédiger des actes documentaires de la plus haute qualité typographique en se libérant de toutes les tâches de mise en page et de construction, lui permettant de concentrer son attention pleine sur le raisonnement.

Ceci étant évoqué, on peut s’interroger sur la structure organique d’un document `.tex` et les conséquences que son architecture entraine en matière d’opportunités et de performances. En d’autres termes, en quoi un document LaTeX est-il diffèrent structurellement d’un fichier destiné à une utilisation sur un logiciel de traitement de texte conventionnel ? Le point de divergence tiendrait notamment à la binarité partielle des fichiers .docx ou .doc induite par leur caractère d’extension en partie propriétaire, par rapport à la simplicité d’un document `.tex`. Les formats de fichiers bureautiques ont toujours été à l’origine de problèmes de sécurité, en grande partie à cause de la richesse de leurs fonctionnalités actives, à la manière des macros, de l’inclusion d’objets OLE, ou de la fuite d’informations cachées dans les documents. Un fichier LaTeX serait quant à lui nettement plus simple dans sa composition, et se présenterait comme un fichier texte pouvant être visualisé par n’importe quel éditeur, le rendant moins vulnérable aux dommages involontaires. 

Enfin, à la frontière entre la portabilité et l’immutabilité, l’argument majeur pour une systématisation du langage LaTeX réside dans le fait qu’il est un protocole backward et forward compatible. Cette persistance permet d’exploiter un fichier indépendamment de sa date de création, sans se soucier de possibles modifications visuelles. On trouve en réalité ici une caractéristique déterminante pour l’adoption d’une telle solution : 

>Il deviendra quasiment impossible de satisfaire une situation ou des données deviennent illisibles, se dégradent, et, ou un mode de compatibilité doit être mis en œuvre afin d’espérer une récupération correcte de la mise en page ancienne.

En d’autres termes : un document LaTeX est, du fait de la fixité de ses spécifications, conçu pour être lisible indéfiniment, au même titre que le format `.pdf`.

[Louis Brulé Naudet](https://louisbrulenaudet.com)

