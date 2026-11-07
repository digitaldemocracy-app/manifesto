🌐 [English](../CONTRIBUTING.md) · Français

> ⚠️ Cette traduction a été réalisée avec l'aide d'une IA et n'a pas encore été relue par un locuteur natif. Elle peut contenir des erreurs. Le texte officiel est la [version anglaise](../CONTRIBUTING.md). Aidez-nous : relisez-la ou retraduisez-la.

# Contribuer

Ce manifeste n'appartient à personne : c'est un point de départ. Corrigez-le, traduisez-le, améliorez-le.

Tout se passe au grand jour, dans ce dépôt. Il n'y a ni liste de diffusion ni canal privé. Les issues et les pull requests font foi.

## Façons de contribuer

| Je veux… | Faites ceci |
|---|---|
| Signer le manifeste | Suivez [SIGNATURES.md](SIGNATURES.md) |
| Corriger une coquille ou un lien cassé | Ouvrez directement une pull request |
| Proposer un changement de formulation ou d'idées | Ouvrez une issue avec le modèle **Text suggestion** |
| Traduire ou relire une traduction | Ouvrez une issue avec le modèle **Translation or review**, puis une pull request |
| Poser une question ou soulever une objection | Consultez d'abord [FAQ.md](FAQ.md) ; si elle n'y est pas, ouvrez une issue avec le modèle **Text suggestion** et ajoutez l'étiquette `question` |

## Le texte officiel

- Le texte officiel est la version anglaise, dans [README.md](../README.md).
- Le texte portugais, [pt/README.md](../pt/README.md), est l'original de l'auteur et la référence de sens pour toutes les traductions.
- Les modifications de fond du texte officiel (tout ce qui dépasse les coquilles, la grammaire ou les liens) doivent commencer par une issue, afin que le raisonnement soit public avant toute modification. L'auteur et les mainteneurs tranchent ; la discussion reste consultable.
- Toute modification passe par une pull request relue par au moins un mainteneur. La branche `main` est protégée ; rien n'y est poussé directement, y compris par les mainteneurs.

## Traductions

1. Consultez [TRANSLATIONS.md](../TRANSLATIONS.md) pour connaître l'état de votre langue. Si quelqu'un y travaille déjà, rejoignez son issue au lieu d'en ouvrir une nouvelle.
2. Ouvrez une issue avec le modèle **Translation or review**. Indiquez la langue, si vous êtes locuteur natif, et si vous traduisez ou relisez.
3. Traduisez à partir du texte anglais. Quand une phrase est ambiguë, appuyez-vous sur l'original portugais pour trancher le sens. Gardez les mêmes titres et le même nombre de paragraphes ; n'ajoutez, ne supprimez ni ne réordonnez aucune section.
4. Placez le fichier dans `<code>/README.md`, dans un dossier nommé d'après le code ISO 639-1 à deux lettres (`es`, `fr`, `zh`, …) ; les documents associés vont dans le même dossier : `PRINCIPLES.md`, `FAQ.md`, `NEUTRALITY.md`, `CONTRIBUTING.md`, `SIGNATURES.md` et `LICENSE` (la traduction officielle de Creative Commons, quand elle existe). Si une langue a besoin d'une variante régionale, utilisez un trait d'union et le code de région (`pt-PT`, `zh-TW`).
5. Langues s'écrivant de droite à gauche (arabe, ourdou, persan, hébreu) : enveloppez tout le texte dans `<div dir="rtl">` … `</div>`, avec une ligne vide après la balise ouvrante et avant la balise fermante. Voir [ar/README.md](../ar/README.md).
6. Ouvrez une pull request. Une traduction est marquée **Reviewed** une fois qu'au moins un autre locuteur natif l'a approuvée dans la pull request.

Les traductions vers d'autres langues que les dix listées sont les bienvenues. Les dix sont un point de départ, pas une limite.

## Style

- Phrases courtes. Mots simples. Le manifeste est fait pour être lu à voix haute et répété.
- Gardez le ton : invitant, jamais accusateur. Nous accusons la distance, pas les personnes.
- Aucun parti, candidat, gouvernement ou pays n'est soutenu ni attaqué, dans aucune langue.

## Comportement

Débattre n'est pas se battre. Les arguments ont des camps, et les camps ont des arguments. Désaccord avec les idées, pas avec les personnes. Les mainteneurs fermeront les discussions qui deviennent personnelles et pourront bloquer les comptes qui insistent.

## Licence

En contribuant, vous acceptez que votre contribution soit publiée sous la même licence que le manifeste, [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Les traducteurs sont crédités dans le fichier de traduction et dans l'historique git.
