# protein-foundational-model-research

A protein is a biological molecule made from a chain of amino acids.

> There two things that are important when to protein:
>
> - the sequence $S$ of amino acis. (eg, M A L W M R L L P L L A L L A L W G P D P A A)
> - the position $X$ of each in atom of the protein molecule in 3D space.
>
> This helps us encode two kinds of information about the protein it geomtery (i.e. the way it bends) and the sequence of the amino acids it is made up of.

What are some of the problems that protein foundational models solve / try to solve:

1. **Structure prediction**: Given an amino acid sequence $S$, predict a 3D structure $X$. `AlphaFold is working on this problem`

2. **Inverse folding**: Given a desired protein backbone structure $X$, find sequences likely to be compatible with it. `ProteinMPNN is working on this problem`

3. **De novo protein generation**: Generate previously unseen sequences or structures that are plausible and potentially functional. `RFdiffusion, `

3. **Conditional protein design**: Given a target or desired biological property $C$, design a protein satisfying it.

4. **Property or function prediction**: Predict whether a sequence or structure has a property, such as stability, enzyme activity, binding affinity, or localization.