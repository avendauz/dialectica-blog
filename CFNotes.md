A quick overview of the contents extracted from the section names:
1. Introduction (<1 page)
2. Linear Logic (1 page)
3. Dialectica Categories (2 pages)
4. Interpretation of linear logic into DC (1 page)
5. Bean (1 page)
6. BEL (~1 page)
7. Interpretation of Bean into BEL (<1 page)
8. (Future) goals 
9. Concluding remarks

I think that (8) could be lumped into (9) with just a few sentences (e.g. `We are currently investigating whether BEL has a nice closed structure to extend Bean to higher-order programs').


A few ways I see to make this more compact.

1. Section 2.1: In principle, this passage could be omitted. It is the kind of thing that you might just provide a nice reference to (e.g. an overview of sequent calculi). You explain how to read the weakening and contraction in the next subsection in any case.
2. In Section 2.2, I would omit the reading of the rules and instead explain the connectives. In principle, this will shorten the presentation. It might be more concise (and informative) to give the grammar of iLL. Isn't the lollipop just the usual intuitionistic implication?
3. In the definition of DC, it might be helpful to carry out the construction in Set and then only later explain that it works in any category with finite limits. (You seem to assume this immediately in any case)
4. Section 3.2: You might focus explicitly on one of the four constructions and then explain how the other connectives are modeled only briefly (e.g. along the lines of 3.2.0)
5. Theorem 1. I would not provide the full proof. Instead, I would explain that it is by induction on the structure of derivations and then *maybe* explain the inductive step corresponding to the connective you chose in point 4 above. I guess the converse (completeness) is actually much harder if it is true. Theorem 1 basically says that Dialectica categories are sound for iLL.
6. Hardcore type theorists might scoff at "are elements of" on l.130
7. A picture might be nice between l.133 and 134
8. Would be nice to give a typing grammar for Bean
8. "The category Bel"
9. L.166: straightforward composition --> ordinary function composition
10. Section 7: link this back to sec 4. (We follow the same recipe...)
11. Theorem 2: Maybe formulate in the exact wording of Theorem 1.
12. Just occurred to me: have you worked out the classifying category of Bean? One could then take models as categories C with a functor Cl(Bean)-->C.
