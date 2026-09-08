FROM rocq/rocq-prover:9.2.0-native-ocaml-4.14.2-flambda 
RUN eval $(opam env "--switch=${COMPILER}" --set-switch)
RUN opam update -y
RUN opam install -y rocq-core.9.2.0 rocq-stdlib.9.1.0 rocq-elpi rocq-mathcomp-character.2.6.0 rocq-mathcomp-analysis.1.19.0 vsrocq-language-server rocq-mathcomp-zify rocq-equations coq-deriving
