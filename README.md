destruct on functions

equational reasoning with explicit equalities (instead of simpl, unfold/fold)

  `assert (H : a = b). { ... }.` or `replace a with b.`

  imagine `but a is just b.` === `replace a with b by reflexivity.`
  or `but a is just b by H.` === `replace a with b by rewrite H; reflexivity.`

case analysis for its various uses
    destruct (in ctx to break stuff up vs. “what forms could this take”)
    discriminate, injection, inversion (all forms of “how did we get here”)

contradictions of equalities (w/o contradiction tactic)
