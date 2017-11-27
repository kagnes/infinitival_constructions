# Infinitival Constructions in Hungarian
## FinInf.txt

The list is created using the Hungarian Gigaword Corpus, version 2.0.4. It contains finite verbs (including particle verbs) which can take an infinitive as their argument. Only verbs occurring at least 5 times with an infinitive are preserved. As for particle verbs, they were counted only if they had immediately preverbal particle (written together with the verb).

Every finite verb can have its replica in infinitive form, e.g. *elmenni elment* 'as for going away, he/she has indeed gone away'. This type of infinitival constructions is not included in this list.

Verbs having a modal or a causative suffix are counted as separate types because they have different lemmata in HGC, e.g. *csinál* 'to do st', *csinálhat* 'to be able/allowed to do st' and *csináltat* 'to make sy do st'.

There are ambiguous cases where the POS-tagger could not choose between the possible lemmata. In this case, the variants are separated by a pipe.

In a lot of cases, a complex predicate should be present instead of the single finite verb. For example, *tekint INF* is mostly *kötelességének tekint INF* 'he/she considers it his/her duty to do something'. At the moment, we can not deal with these cases. Only the finite verbs appear in the list.

All wrong constructions are purged manually.

The file is structured as follows:
1st column: the frequency of the finite lemma
2nd column: the finite lemma
3rd column: the type of the infinitival argument (It shows what kind of subordinate clause / less complex argument could be there instead of the infinitival clause. E.g. *azért* stands for causalis-finalis, *azt* stands for dativus. The *x* means that no decision could be made about the type of the argument. Note that this column was added manually, based on my intuition.)
4th column: an example from the HGC 2.0.4, illustrating the finite verb with its infinitival argument (The *NOPE* means that no valid corpus-example could be found, though the verb can have an infinitival argument, in my opinion.)
5th column: some comments that could be used in further research (The *@* stands for typical lexical arguments, the *%* marks the corrected verb-lemma.)

## Links

- [Hungarian Gigaword Corpus (Magyar Nemzeti Szövegtár 2)](http://clara.nytud.hu/mnsz2-dev/)
- Oravecz, Csaba – Váradi, Tamás – Sass, Bálint (2014):
[The Hungarian Gigaword Corpus.](http://www.lrec-conf.org/proceedings/lrec2014/pdf/681_Paper.pdf) In: Proceedings of LREC 2014. Reykjavík. 1719–1723.
