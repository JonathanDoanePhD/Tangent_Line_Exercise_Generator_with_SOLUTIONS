# Tangent line exercise generator

A PythonTeX and SymPy document that generates a customizable set of calculus tangent line exercises with worked solutions. This is a teaching tool for producing many related practice problems from one source.

## Explore

- [Source document](NumProbTangLine.tex)
- [Example PDF output](NumProbTangLine.pdf)

## Generate a new set

In `NumProbTangLine.tex`, find the **QUICK START** section near the start of the document and set `NumProb` to the desired number of questions (the source asks for more than four). The original project uses Python 3.9, a LaTeX distribution with PythonTeX and SymPy, and a LaTeX editor such as TeXstudio.

The source describes a LaTeX → PythonTeX → LaTeX workflow. The exact PythonTeX invocation depends on your installation; run the generated PythonTeX helper for `NumProbTangLine` between the two LaTeX compilation passes. The checked-in PDF is an example of the produced worksheet, not a guarantee that a different local toolchain will reproduce it unchanged.

## What it demonstrates

Symbolic computation applied to assessment design, programmatic document generation, and reusable mathematics instruction. The generator predates current environments and has not been retested here.
