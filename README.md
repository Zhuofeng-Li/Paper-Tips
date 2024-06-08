# Tips for Research Paper

## Before submitting

You should complete your work at least one day before the conference deadline. Afterward, take a break and stay calm. To ensure your paper is state-of-art, check the following points carefully:

0. Number of pages, double-blind, no evidence of vspace and other conference requirements.

1. whether there is “??”, “[]” in the text.

2. read through all table and figure captions and contents again to make sure no errors.

3. figure font size legible.

4. make sure all the figures and tables have been cited and EXPLAINED in the text.

5. read through the abstract and introduction again, and carefully do two-round proofreading, one by Grammarly, and one by your eyes.

6. scan every single symbol to see if its first appearance has an explanation, and make sure all the same symbol has the same meaning, all different symbol has different meanings.

7. carefully check equations, especially whether subscripts and superscripts are correct, and whether deductions are correct.

8. remove obvious error in references, lacking page number and other information.

9. Use Grammarly to proofread the whole paper.

10. Use your eyes to proofread the whole paper.

11. Ensure no links will expose your identity for anonymous requirement, avoid your identity leakage in link text, in the website the link leading to, or in other website that can be easily reached from the link.

## Some Magic Latex Commands

### Compact contents

```Latex
% ============================
\usepackage{titlesec}
\titlespacing*{\section}{0pt}{0.1\baselineskip}{0.1\baselineskip}
\titlespacing*{\subsection}{0pt}{0.1\baselineskip}{0.1\baselineskip}
\titlespacing*{\subsubsection}{0pt}{0.1\baselineskip}{0.1\baselineskip}
```

### Delete the left margin for the unordered list

This is extremely useful when writing contributions!

```Latex
\begin{itemize}[left=0pt]
    \item contribution 1.
    \item contribution 2.
    \item contribution 3.
\end{itemize}
```



















