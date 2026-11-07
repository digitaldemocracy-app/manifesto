🌐 [English](../PRINCIPLES.md) · [Português](../pt/PRINCIPLES.md) · Français

> ⚠️ Cette traduction a été produite avec l'aide d'une intelligence artificielle et n'a pas encore été relue par une personne de langue maternelle française. Elle peut contenir des erreurs. Le texte officiel est la [version anglaise](../PRINCIPLES.md). Aidez-nous : relisez-la, ou retraduisez-la — voir [CONTRIBUTING](../CONTRIBUTING.md).

---

# Les Sept Principes

Le Manifeste énonce sept principes en quelques lignes chacun. Ce document les explique. Il est plus long parce que les questions méritent des réponses, et plus court qu'un livre parce que des principes doivent tenir dans une tête.

---

## 1. Tout est visible

**Ce que cela signifie.** Chaque proposition, chaque argument, chaque décompte de votes, chaque règle de la plateforme et chaque ligne de code qui applique ces règles est publique, permanente et vérifiable par n'importe qui, sans compte.

**Pourquoi.** La confiance dans la démocratie s'est érodée parce que les décisions se prennent dans des lieux que nous ne voyons pas. Une plateforme qui demande aux gens de lui confier leur voix doit mériter cette confiance en n'ayant rien à cacher. C'est dans le secret du processus que vit la distorsion.

**Comment.** Tous les événements publics sont consignés dans un registre en ajout seul (*ledger*) à chaînage cryptographique : une fois écrite, une entrée ne peut être modifiée sans rompre la chaîne, et n'importe qui peut vérifier la chaîne. Les contenus modérés sont masqués de la vue par défaut, pas supprimés, et la décision de modération elle-même est consignée. Lorsque la loi exige le retrait de quelque chose — une décision de justice, une demande de protection des données —, le retrait est effectué, et le fait qu'il ait eu lieu est consigné dans le *ledger*. Rien n'est effacé en silence. Le code source est ouvert dès le premier jour, sous une licence qui le garde ouvert.

**Ce que cela ne signifie pas.** Cela ne signifie pas que votre vote est public (voir le Principe 2), ni que les données personnelles sont exposées. La visibilité s'applique au processus et aux résultats, pas aux informations privées sur les personnes.

---

## 2. Votre vote vous appartient

**Ce que cela signifie.** Votre vote est secret, toujours. Vous pouvez vérifier qu'il a été compté. Vous êtes libre de dire à qui vous voulez comment vous avez voté. Mais le système ne produira jamais de preuve de votre vote — de sorte que personne ne pourra jamais vous exiger cette preuve.

**Pourquoi.** Le scrutin secret existe pour protéger les gens des pressions : un employeur, un propriétaire, un proche, un notable local, un gouvernement. Si un vote peut être prouvé, il peut être acheté ou extorqué. S'il ne peut être que déclaré, la contrainte perd prise : une affirmation sans preuve ne vaut rien pour celui qui contraint. Cette conception préserve les deux libertés : celle de vous protéger et celle de vous afficher au grand jour.

**Comment.** Le nom technique de cette propriété est l'impossibilité de prouver son vote à un tiers (*receipt-freeness*), combinée à la vérifiabilité de bout en bout (*end-to-end verifiability*). Plusieurs schémas cryptographiques de vote l'offrent. Notre engagement porte sur la propriété, pas sur un schéma particulier ; le schéma retenu sera public, examiné et remplaçable.

**Ce que cela ne signifie pas.** Les délégations (Principe 4) et les positions publiques prises dans un débat ne sont pas secrètes : confier votre voix à quelqu'un, ou défendre un camp, est un acte public.

---

## 3. Chaque personne n'existe qu'une seule fois, et compte exactement autant que les autres

**Ce que cela signifie.** Un être humain, une identité, un vote. Pas de comptes multiples, pas de bots, pas de foules achetées, et aucun vote qui pèse plus qu'un autre.

**Pourquoi.** La participation en ligne a été empoisonnée par les faux comptes et l'amplification artificielle. Une démocratie où une personne peut parler comme mille n'est pas une démocratie. Le même poids pour tous est la plus ancienne des promesses démocratiques, et celle qui est le plus souvent rompue dans la pratique.

**Comment.** La participation grandit avec la vérification, par niveaux. Une adresse e-mail permet de lire et de débattre ; une pièce d'identité vérifiée permet de voter avec un poids complet ; une vérification supplémentaire peut ajouter un marqueur de confiance. Chaque décompte est présenté séparément par niveau de vérification, si bien que chacun peut voir combien de personnes vérifiées ont soutenu un résultat. La vérification est une porte d'accès au vote, jamais un multiplicateur de votes.

**Ce que cela ne signifie pas.** Cela ne signifie pas que les experts, les responsables ou les fondateurs aient plus de poids. L'expertise est affichée (Principe 6) ; elle n'est jamais pondérée.

---

## 4. Chaque décision appartient à ceux qu'elle concerne

**Ce que cela signifie.** Les décisions se prennent au niveau où elles ont un effet : quartier, ville, État, pays, région, monde. Seul ce qui appartient véritablement à tous est décidé par tous.

**Pourquoi.** Centraliser les décisions loin des personnes qu'elles concernent est l'une des principales causes de la distance que nous décrivons dans le Manifeste. L'erreur inverse, tout décider à l'échelle mondiale, remplacerait une distance par une autre. Ce principe est parfois appelé *subsidiarité* : le plus petit niveau compétent décide.

**Comment.** La plateforme est organisée en périmètres géographiques. Une proposition naît dans un périmètre et ne peut être votée que par les personnes qui en font partie. Le périmètre est fixé dès que la proposition sort du brouillon. Les personnes à double nationalité et les résidents peuvent appartenir à plusieurs périmètres. Un périmètre mondial existe pour ce qui n'a pas de frontières : le climat, les océans, les pandémies, les règles de la plateforme elle-même.

**Ce que cela ne signifie pas.** Ce n'est pas un gouvernement mondial. Il n'existe sur la plateforme aucune autorité globale capable d'annuler une décision locale. « Chaque peuple décide jusqu'où cela va » s'applique ici plus qu'ailleurs.

---

## 5. Débattre, ce n'est pas se battre

**Ce que cela signifie.** Les arguments sont organisés, pas empilés. Chaque proposition a des arguments pour et contre ; chaque argument ne peut recevoir qu'une seule réponse ; la communauté évalue les arguments selon la qualité de leur raisonnement, pas selon qu'ils plaisent.

**Pourquoi.** Les forums et les réseaux sociaux récompensent l'indignation et la répétition. Une démocratie a besoin du contraire : que la meilleure idée s'impose même si elle est d'abord impopulaire. C'est la structure qui le rend possible.

**Comment.** Les arguments sont classés par camp. Les réponses sont limitées à un niveau pour garder le cap. Un score de constructivité, calculé à partir de l'évaluation de la communauté, ordonne ce que les gens voient. La modération est assurée par la communauté et consignée ; le contenu qui enfreint les règles est masqué, pas effacé.

**Ce que cela ne signifie pas.** Cela ne signifie pas un silence poli. Le désaccord est le but. Ce qui est exclu, ce sont l'insulte, la manipulation et le bruit.

---

## 6. Nous choisissons les plus capables pour réaliser ce que nous décidons ensemble

**Ce que cela signifie.** Décider de ce qu'il faut faire est égal pour tous. Choisir qui le planifie et l'exécute est aussi l'affaire de tous, mais en voyant clairement ce que chaque candidat a fait et sait faire. La compétence est transparente ; ce n'est pas un privilège.

**Pourquoi.** L'échec de la démocratie représentative n'est pas que nous choisissions des gens pour agir à notre place. C'est que nous les choisissons à l'aveugle, puis ne voyons pas ce qu'ils font. Des parcours visibles et une expertise vérifiée permettent de bien choisir, puis de contrôler.

**Comment.** L'expertise vérifiée apparaît sous forme d'un badge lié à un domaine, après vérification des titres. Le badge ne donne aucun poids supplémentaire au vote. Ceux qui sont choisis pour exécuter une décision voient leur mandat, leurs engagements et leurs résultats consignés dans le *ledger*, afin que le choix suivant soit mieux informé que le précédent.

**Ce que cela ne signifie pas.** Ce n'est pas de la technocratie. Aucun comité ne décide qui est compétent. Ce sont les gens qui décident, au grand jour, avec de meilleures informations.

---

## 7. Certaines choses ne se votent pas

**Ce que cela signifie.** La dignité, la liberté et les droits fondamentaux de chaque personne ne sont pas soumis à la décision de la majorité sur cette plateforme.

**Pourquoi.** Une majorité peut se tromper, et l'histoire montre que des majorités ont été utilisées contre des minorités. Une démocratie qui ne protège pas la personne n'est qu'une machine à compter. La limite posée à ce qui peut être voté est ce qui rend le vote digne de confiance.

**Comment.** Les règles de la plateforme excluent les propositions qui priveraient de ses droits une personne ou un groupe. La Déclaration universelle des droits de l'homme en est la référence. Les propositions de ce type sont retirées du vote, et la décision de les retirer est elle-même publique et contestable.

**Ce que cela ne signifie pas.** Cela ne signifie pas une liste de sujets interdits. Les gens peuvent débattre de tout. Ce qu'ils ne peuvent pas faire, c'est voter pour retirer ses droits à quelqu'un d'autre.

---

## Comment ces principes évoluent

Ces principes sont la constitution de la plateforme. Ils peuvent être amendés, mais seulement par la plateforme elle-même, par les personnes qui l'utilisent, au grand jour, et avec un seuil plus élevé que pour les décisions ordinaires. Le tout premier vote organisé sur la plateforme portera sur ce Manifeste et ces principes.
