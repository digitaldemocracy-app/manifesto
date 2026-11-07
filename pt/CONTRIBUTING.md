🌐 [English](../CONTRIBUTING.md) · Português

# Como contribuir

Este manifesto não é de ninguém: é um ponto de partida. Corrija, traduza, melhore.

Tudo acontece às claras, neste repositório. Não há lista de e-mail nem canal privado. Issues e pull requests são o registro.

## Formas de contribuir

| Quero… | Faça isto |
|---|---|
| Assinar o manifesto | Siga [SIGNATURES.md](SIGNATURES.md) |
| Corrigir um erro de digitação ou um link quebrado | Abra um pull request direto |
| Sugerir uma mudança na redação ou nas ideias | Abra uma issue com o modelo **Text suggestion** |
| Traduzir ou revisar uma tradução | Abra uma issue com o modelo **Translation or review** e depois um pull request |
| Fazer uma pergunta ou levantar uma objeção | Veja antes o [FAQ.md](FAQ.md); se não estiver lá, abra uma issue com o modelo **Text suggestion** e coloque o rótulo `question` |

## O texto oficial

- O texto oficial é a versão em inglês, em [README.md](../README.md).
- O texto em português, [pt/README.md](README.md), é o original do autor e a referência de sentido para todas as traduções.
- Mudanças substanciais no texto oficial (qualquer coisa além de erros de digitação, gramática ou links) devem começar como uma issue, para que o raciocínio seja público antes de qualquer edição. O autor e os mantenedores decidem; a discussão fica registrada.
- Toda mudança passa por um pull request revisado por pelo menos um mantenedor. A branch `main` é protegida; ninguém envia nada direto para ela, nem mesmo os mantenedores.

## Traduções

1. Veja em [TRANSLATIONS.md](../TRANSLATIONS.md) como está o seu idioma. Se alguém já estiver trabalhando nele, entre na issue dessa pessoa em vez de abrir outra.
2. Abra uma issue com o modelo **Translation or review**. Diga qual é o idioma, se você é falante nativo e se vai traduzir ou revisar.
3. Traduza a partir do texto em inglês. Quando uma frase for ambígua, use o original em português para decidir o sentido. Mantenha os mesmos títulos e o mesmo número de parágrafos; não acrescente, remova nem reordene seções.
4. Coloque o arquivo em `<code>/README.md`, numa pasta com o código ISO 639-1 de duas letras (`es`, `fr`, `zh`, …); os documentos complementares vão na mesma pasta: `PRINCIPLES.md`, `FAQ.md`, `NEUTRALITY.md`, `CONTRIBUTING.md`, `SIGNATURES.md` e `LICENSE` (a tradução oficial da Creative Commons, quando existir). Se um idioma precisar de variante regional, use hífen e o código da região (`pt-PT`, `zh-TW`).
5. Idiomas escritos da direita para a esquerda (árabe, urdu, persa, hebraico): envolva todo o texto em `<div dir="rtl">` … `</div>`, com uma linha em branco depois da tag de abertura e antes da de fechamento. Veja [ar/README.md](../ar/README.md).
6. Abra um pull request. Uma tradução é marcada como **Reviewed** depois que pelo menos outro falante nativo a aprova no pull request.

Traduções para idiomas além dos dez da lista são bem-vindas. Os dez são um ponto de partida, não um limite.

## Estilo

- Frases curtas. Palavras simples. O manifesto foi feito para ser lido em voz alta e repetido.
- Mantenha o tom: convidar, não acusar. Acusamos a distância, não as pessoas.
- Nenhum partido, candidato, governo ou país é apoiado ou atacado, em nenhum idioma.

## Conduta

Debater não é brigar. Argumentos têm lados, e lados têm argumentos. Discorde das ideias, não das pessoas. Os mantenedores vão encerrar discussões que se tornarem pessoais e podem bloquear contas que insistirem.

## Licença

Ao contribuir, você concorda que sua contribuição seja publicada sob a mesma licença do manifesto, [Creative Commons Atribuição 4.0 Internacional (CC BY 4.0)](LICENSE). Os tradutores são creditados no arquivo da tradução e no histórico do git.
