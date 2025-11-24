## What

[entry.csv](https://github.com/paa-li/glossary/blob/main/entry.csv) is the database of the [glossary](https://paa.li/glossary/) page of PaaLi.

We sincerely appreciate any constructive feedback! This is a work in progress, so expect a lot of changes.

## Rules

1. A feedback must be factually correct supported by appropriate sources.

2. The glossary is not intended to serve as a mini-dictionary of the Pāḷi language; the glossary must *mainly* list words of two categories:
    1) Terminologies of Pāḷi linguistics
    2) names and categories of Pāḷi texts, such as Nikāyas.

4. Rows must be listed in the **alphabetical order of the Pāḷi language written in [ISO 15919](https://en.wikipedia.org/wiki/ISO_15919)** based on the Pāḷi word entries. The alphabet order of Pāḷi is as follows (from left to right, top to bottom:)
```
a ā i ī u ū e o
ṁ
k kh g gh ṅ
c ch j jh ñ
ṭ ṭh ḍ ḍh ṇ
t th d dh n
p ph b bh m
y r l ḷ v s h
```

4. **1st column - Pāḷi**
    - A Pāḷi word entry must only contain one word per row.
    - Synonyms of Pāḷi words must be listed as a separate entry.

5. **2nd column - Sanskrit**
    - A Sanskrit term is not simply a Sanskrit translation of the Pāḷi term; it is meant to denote the etymology from wich the Pāḷi word originates.
    - If there is no known or related Sanskrit equivalent of the Pāḷi word, it must be left empty.
    - If the Sanskrit equivalent is identical to the Pāḷi word, it must be marked with an equal sign (`=`).
    - Sanskrit terms should be written in [IAST](https://en.wikipedia.org/wiki/International_Alphabet_of_Sanskrit_Transliteration).

7. **3rd column - English**
    - Varieties of English definitions within a similar context must be separated with a semicolon and a space (`; `).
    - English definitions with a different meaning or context must be divided with a comma and a space (`. `).

8. **4th column - Chinese**
    - A Chinese term is not simply a (modern) Mandarin translation of the Pāḷi term; it must be a **Buddhist term** formally and globally recognized in Mahayana Buddhism.
    - If there is no formally recognized equivalent, it must be left empty.
    - Use 繁體字 instead of 简体字.

9. Double quotes `" "` can be optionally used to group a single entry with spaces into one.

***

`wget` from `https://paa-li.github.io/glossary/entry.csv`
