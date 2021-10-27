  Orientational Flexibility of Organic Structure Directing Agents in CHA and AEI   <!--/\*--><!\[CDATA\[/\*><!--\*/ .title { text-align: center; margin-bottom: .2em; } .subtitle { text-align: center; font-size: medium; font-weight: bold; margin-top:0; } .todo { font-family: monospace; color: red; } .done { font-family: monospace; color: green; } .priority { font-family: monospace; color: orange; } .tag { background-color: #eee; font-family: monospace; padding: 2px; font-size: 80%; font-weight: normal; } .timestamp { color: #bebebe; } .timestamp-kwd { color: #5f9ea0; } .org-right { margin-left: auto; margin-right: 0px; text-align: right; } .org-left { margin-left: 0px; margin-right: auto; text-align: left; } .org-center { margin-left: auto; margin-right: auto; text-align: center; } .underline { text-decoration: underline; } #postamble p, #preamble p { font-size: 90%; margin: .2em; } p.verse { margin-left: 3%; } pre { border: 1px solid #ccc; box-shadow: 3px 3px 3px #eee; padding: 8pt; font-family: monospace; overflow: auto; margin: 1.2em; } pre.src { position: relative; overflow: visible; padding-top: 1.2em; } pre.src:before { display: none; position: absolute; background-color: white; top: -10px; right: 10px; padding: 3px; border: 1px solid black; } pre.src:hover:before { display: inline;} /\* Languages per Org manual \*/ pre.src-asymptote:before { content: 'Asymptote'; } pre.src-awk:before { content: 'Awk'; } pre.src-C:before { content: 'C'; } /\* pre.src-C++ doesn't work in CSS \*/ pre.src-clojure:before { content: 'Clojure'; } pre.src-css:before { content: 'CSS'; } pre.src-D:before { content: 'D'; } pre.src-ditaa:before { content: 'ditaa'; } pre.src-dot:before { content: 'Graphviz'; } pre.src-calc:before { content: 'Emacs Calc'; } pre.src-emacs-lisp:before { content: 'Emacs Lisp'; } pre.src-fortran:before { content: 'Fortran'; } pre.src-gnuplot:before { content: 'gnuplot'; } pre.src-haskell:before { content: 'Haskell'; } pre.src-hledger:before { content: 'hledger'; } pre.src-java:before { content: 'Java'; } pre.src-js:before { content: 'Javascript'; } pre.src-latex:before { content: 'LaTeX'; } pre.src-ledger:before { content: 'Ledger'; } pre.src-lisp:before { content: 'Lisp'; } pre.src-lilypond:before { content: 'Lilypond'; } pre.src-lua:before { content: 'Lua'; } pre.src-matlab:before { content: 'MATLAB'; } pre.src-mscgen:before { content: 'Mscgen'; } pre.src-ocaml:before { content: 'Objective Caml'; } pre.src-octave:before { content: 'Octave'; } pre.src-org:before { content: 'Org mode'; } pre.src-oz:before { content: 'OZ'; } pre.src-plantuml:before { content: 'Plantuml'; } pre.src-processing:before { content: 'Processing.js'; } pre.src-python:before { content: 'Python'; } pre.src-R:before { content: 'R'; } pre.src-ruby:before { content: 'Ruby'; } pre.src-sass:before { content: 'Sass'; } pre.src-scheme:before { content: 'Scheme'; } pre.src-screen:before { content: 'Gnu Screen'; } pre.src-sed:before { content: 'Sed'; } pre.src-sh:before { content: 'shell'; } pre.src-sql:before { content: 'SQL'; } pre.src-sqlite:before { content: 'SQLite'; } /\* additional languages in org.el's org-babel-load-languages alist \*/ pre.src-forth:before { content: 'Forth'; } pre.src-io:before { content: 'IO'; } pre.src-J:before { content: 'J'; } pre.src-makefile:before { content: 'Makefile'; } pre.src-maxima:before { content: 'Maxima'; } pre.src-perl:before { content: 'Perl'; } pre.src-picolisp:before { content: 'Pico Lisp'; } pre.src-scala:before { content: 'Scala'; } pre.src-shell:before { content: 'Shell Script'; } pre.src-ebnf2ps:before { content: 'ebfn2ps'; } /\* additional language identifiers per "defun org-babel-execute" in ob-\*.el \*/ pre.src-cpp:before { content: 'C++'; } pre.src-abc:before { content: 'ABC'; } pre.src-coq:before { content: 'Coq'; } pre.src-groovy:before { content: 'Groovy'; } /\* additional language identifiers from org-babel-shell-names in ob-shell.el: ob-shell is the only babel language using a lambda to put the execution function name together. \*/ pre.src-bash:before { content: 'bash'; } pre.src-csh:before { content: 'csh'; } pre.src-ash:before { content: 'ash'; } pre.src-dash:before { content: 'dash'; } pre.src-ksh:before { content: 'ksh'; } pre.src-mksh:before { content: 'mksh'; } pre.src-posh:before { content: 'posh'; } /\* Additional Emacs modes also supported by the LaTeX listings package \*/ pre.src-ada:before { content: 'Ada'; } pre.src-asm:before { content: 'Assembler'; } pre.src-caml:before { content: 'Caml'; } pre.src-delphi:before { content: 'Delphi'; } pre.src-html:before { content: 'HTML'; } pre.src-idl:before { content: 'IDL'; } pre.src-mercury:before { content: 'Mercury'; } pre.src-metapost:before { content: 'MetaPost'; } pre.src-modula-2:before { content: 'Modula-2'; } pre.src-pascal:before { content: 'Pascal'; } pre.src-ps:before { content: 'PostScript'; } pre.src-prolog:before { content: 'Prolog'; } pre.src-simula:before { content: 'Simula'; } pre.src-tcl:before { content: 'tcl'; } pre.src-tex:before { content: 'TeX'; } pre.src-plain-tex:before { content: 'Plain TeX'; } pre.src-verilog:before { content: 'Verilog'; } pre.src-vhdl:before { content: 'VHDL'; } pre.src-xml:before { content: 'XML'; } pre.src-nxml:before { content: 'XML'; } /\* add a generic configuration mode; LaTeX export needs an additional (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs \*/ pre.src-conf:before { content: 'Configuration File'; } table { border-collapse:collapse; } caption.t-above { caption-side: top; } caption.t-bottom { caption-side: bottom; } td, th { vertical-align:top; } th.org-right { text-align: center; } th.org-left { text-align: center; } th.org-center { text-align: center; } td.org-right { text-align: right; } td.org-left { text-align: left; } td.org-center { text-align: center; } dt { font-weight: bold; } .footpara { display: inline; } .footdef { margin-bottom: 1em; } .figure { padding: 1em; } .figure p { text-align: center; } .inlinetask { padding: 10px; border: 2px solid gray; margin: 10px; background: #ffffcc; } #org-div-home-and-up { text-align: right; font-size: 70%; white-space: nowrap; } textarea { overflow-x: auto; } .linenr { font-size: smaller } .code-highlighted { background-color: #ffff00; } .org-info-js\_info-navigation { border-style: none; } #org-info-js\_console-label { font-size: 10px; font-weight: bold; white-space: nowrap; } .org-info-js\_search-highlight { background-color: #ffff00; color: #000000; font-weight: bold; } .org-svg { width: 90%; } /\*\]\]>\*/-->   /\* @licstart The following is the entire license notice for the JavaScript code in this tag. Copyright (C) 2012-2018 Free Software Foundation, Inc. The JavaScript code in this tag is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License (GNU GPL) as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. The code is distributed WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU GPL for more details. As additional permission under GNU GPL version 3 section 7, you may distribute non-source (e.g., minimized or compacted) forms of that code without the copy of the GNU GPL normally required by section 4, provided you include this license notice and a URL through which recipients can access the Corresponding Source. @licend The above is the entire license notice for the JavaScript code in this tag. \*/ <!--/\*--><!\[CDATA\[/\*><!--\*/ function CodeHighlightOn(elem, id) { var target = document.getElementById(id); if(null != target) { elem.cacheClassElem = elem.className; elem.cacheClassTarget = target.className; target.className = "code-highlighted"; elem.className = "code-highlighted"; } } function CodeHighlightOff(elem, id) { var target = document.getElementById(id); if(elem.cacheClassElem) elem.className = elem.cacheClassElem; if(elem.cacheClassTarget) target.className = elem.cacheClassTarget; } /\*\]\]>\*///-->   MathJax.Hub.Config({ displayAlign: "center", displayIndent: "0em", "HTML-CSS": { scale: 100, linebreaks: { automatic: "false" }, webFont: "TeX" }, SVG: {scale: 100, linebreaks: { automatic: "false" }, font: "TeX"}, NativeMML: {scale: 100}, TeX: { equationNumbers: {autoNumber: "AMS"}, MultLineWidth: "85%", TagSide: "right", TagIndent: ".8em" } });  

Orientational Flexibility of Organic Structure Directing Agents in CHA and AEI
==============================================================================

\\newpage

1 Workflow
----------

### 1.1 Motivations

1.  OSDA/FW IE has been used as a reporter of an OSDAs crystallization affinity for a particular FW
2.  While OSDA will “fit”, some floppiness and even orientation flexibility exist which can influence computed IE
3.  We have two approaches to sample orientational flexibility and compute IE:
    1.  Asexual Genetic Algorithm (AGA):
        1.  Uses information based on previously computed structures (orientations) to search for minimum structures
            1.  Energies evaluated with DFT
    2.  Classical Molecular Dynamics (CMD):
        1.  Randomly insert OSDA into FW
        2.  Run Dynamics at high Temp (5000 K)
        3.  Bin orientations
        4.  Re-run dynamics at “reasonable” Temp (500 K) on binned orientations to search for available orientations
            1.  Energies evaluated with Drieding force field (as used in the literature when sampling OSDA orientation space)

### 1.2 Objectives

1.  Compare FW/IE interactions across two similar frameworks (CHA and AEI) across a family of OSDAs
2.  Compare OSDA orientational flexibility
3.  Compare strategies for extracting orientations and IE (mean IE in the CMD cases).
4.  Compare predictive ability, dangers strategies.

### 1.3 Plan of Attack

1.  Craig will be doing the DFT/GA calculations in siliceous zeolites with CN OSDAs.
    
    1.  FWs are obtained from IZA (using IZA lattice constants)
    2.  A single OSDA is placed into one of the CHA and AEI cages
        1.  OSDA nitrogens are replaced with carbons to maintain charge neutrality
    3.  An AGA is used to sample the configurational space the OSDA can adopt within a FW cage
        1.  20 parents are randomly displace within a cage
        2.  The structures are minimized using the PBE-D3 functional
            1.  Resulting energies are used to score the candidates
        3.  Parents used within the AGA are selected based on a Boltzmann distribution
        4.  Those parents undergo a mutation which translates and rotates them in the cage.
        5.  This process is repeated until 10 children have been generated
        6.  The children are minimized using the PBE-D3 functional and steps 3-6 are repeated until a total of 50 structures have been generated
    4.  These 50 candidates are a representation of the global configurations an OSDA can adopt with a particular cage\\begin{figure} \\begin{center} \\includegraphics\[scale=.5,trim={0cm 5cm 0cm 0cm},clip\]{./Figures/DFT\_GA\_to\_Ori.pdf} \\caption{Schematic representation of the DFT/AGA proceedure. Candidates are minimized are generated in sequencial step and minimized with the PBE-D3 functional. We select the tertiary carbon (previously the notrogen) of an OSDA and look at the orientation and translation within a framwork with respect to a vector which describes the length of the cage. The lowest energy point corresponds to the most favorable configuration the OSDA can sit within the framework and is denoted as $\\text{IE}^{\\text{DFT}}\_{\\text{L}}$}. \\label{fig:DFT\_GA\_to\_Ori} \\end{center} \\end{figure}
2.  Xuyao will be doing the CMD calculations in siliceous zeolites with CN OSDAs.
    
    1.  CHA and AEI unit cell are full siliceous and obtained from IZA using IZA lattice constant. Nitrogen in OSDAs are replaced with C.
    2.  For each OSDA candidates, one OSDA is inserted in AEI and CHA with random location and orientation.
    3.  Dreiding force field is used to describe OSDA/FW interaction and OSDA self potential.
    4.  MD at 5000K is used to sample the global configurational space of OSDA in FW.
        1.  FW is set to be rigid. Only OSDA is sampled by MD.
        2.  1000 ps equilibartion run and 1000 ps production run with 0.2 fs time step is performed for each MD sampling.
    5.  From the high temperature MD trajectory, each image are sorted base on their spatial orientations into 8 bins. In each bin, the lowest potential energy image is selected as the representative of this orientation.
    6.  These 8 low energy configuration represent the global configurations of Each representative is re-sampled with MD at 343K with same time step and simulation length as above to explore the local configuration.\\begin{figure} \\begin{center} \\includegraphics\[scale=.5\]{./Figures/CMD-OSDA-FW-Workflow.pdf} \\caption{Workflow of CMD proceedure. Each OSDA/FW combinations is sampled at 5000K with MD to explore global configurations as much as possible. 8 configurations from differnt spacial cosine value with lowest energy are selected as the representive of global configuration and further reasmpled for their local orientations with MD at 343K again. Same plot for camparing IE, orientation and translation are constructed. Each region corresponding to one local configurations of OSDA in FW cages} \\label{fig:CMD-OSDA-FW-Workflow} \\end{center} \\end{figure}

2 Results to Date
-----------------

### 2.1 OSDAs of interest and the FW they crystallize

Using the parameters/models discussed above, we will first compare the lowest energy structure using GA and lowest energy average CMD energy to see if PBE and Dreiding predict similar or differenct affinities for OSDAs to crystallize CHA or AEI. The table below summarizes the OSDAs used in this study and is separated based on which OSDA crystallizes which framework.

\\begin{center} \\begin{tabular}{c|c} \\hline Zeolite & OSDAs \\\\ \\hline CHA & TMADA, DEDMP-3c, DEDMP-3t, TMBCN, PMCH-3c, PMCH-3t \\\\ AEI & DMDMP-2c, DMDMP-3c, DMDMP-3t, DEDMP-2c, DMBCN \\\\ Intergrowth & Tetra \\\\ \\hline \\end{tabular} \\end{center}

The names for these OSDA’s are abbreviations for there full names. We will need to think of a clever way on how to present each one (e.g. Template A,B,C etc.)

### 2.2 Rigid Framework Assumption

Besides evaluating energy differences differently (Dreiding vs. DFT), there is one considerable difference between our two models. The CMD method is restricted to a rigid framework (since Si-O parameters are unknown for Drieding). Therefore it is a reasonable question to ask, “What happens to the DFT results when the framework is rigid and relaxed?” To answer this question, I did two set of DFT calculations. First, I performed my AGA by minimizing the OSDA/FW to a local minimum. I then searched for the lowest energy structure, took the initial structure file (which as the Si-O atoms in the zeolite from IZA) and reoptimized the structures but kept the zeolite fixed. This gives me two structures, one where only the OSDA was relaxed to a minimum and one where both the OSDA and Zeolite are relaxed to a minimum. The results for CHA are shown in the Figure below.

\\begin{figure} \\begin{center} \\includegraphics\[scale=.5,trim={0cm 0cm 0cm 0cm},clip\]{./Figures/Framework-flex.pdf} \\caption{Parity plot comparing the the lowest energy orientation of each OSDA from the GA (flexible framework), compared to a rigid framework. $R^{2}$ value of the data compared to the parity line is 0.99999. }. \\label{fig:Rig\_v\_Flex} \\end{center} \\end{figure}

Figure \\ref{fig:Rig\_v\_Flex} compares the energy of the Rigid framework to the flexible framework. The largest deviation from the parity line is approximately 18 kJ/mol (DMDMP-2c in CHA). and the points lie on the parity line. As such it doesn’t make too much of a difference if the framework is allowed to relax to a minimum. For the remainder of this study the framework is flexible.

### 2.3 Orientation Freedom

We use both the AGA and MD sampling to compare the orientational freedom of an OSDA in a framework. We are comparing orientational space where the OSDA and FW are allowed to be relaxed (DFT/AGA) and ones where only the OSDA is allowed to move(CMD). We have evaluated all of the OSDAs in the table above (with the exception of one of the DMDMP isomers) and we are going to compare two sets of results in this outline.

We have devised a scheme to visualize the orientation an OSDA adopts within the cage. We compute the angle the OSDA makes with the long axis with the cage (using the tertiary carbon and an adjacent carbon or the center of mass with respect to DMBCN which does not have an adjacent carbon), and the displacement of the tertiary carbon along that vertical vector.

\\begin{figure} \\begin{center} \\includegraphics\[scale=.5\]{./Figures/CHA-GA-CMD-TMADA.pdf} \\caption{TMADA in CHA. Left CMD results, Right DFT/AGA results.} \\label{fig:TMADA-CHA} \\end{center} \\end{figure}

The results for fig \\ref{fig:TMADA-CHA} above show that TMADA is fairly rigid in the CHA cage. There are two degenerate orientations of TMADA in CHA in the AGA results, a downward and upward orientation (blue and red points respectively). These are degenerate given the symmetry of the CHA cage. The CMD results only predict one orientation however. The energy barrier to flip to another orientation is greater than 5000 K and thus the CMD sampling method did not sample the other regime. Otherwise, Comparison of the two blue points is fairly similar. The lowest energy structure from DFT is about 30 kJ/mol higher in energy than the average CMD energy. For other OSDA’s in CHA, there is a mixture of results that look like the figure above (where some regime is missed, due to the high barrier to rotate) and others where the CMD and GA results look “identical.”

\\begin{figure} \\begin{center} \\includegraphics\[scale=.5\]{./Figures/AEI-GA-CMD-DMDMP\_2c.pdf} \\caption{DMDMP-2c in CHA. Left CMD results, Right DFT/AGA results.} \\label{fig:DMDMP-2c-AEI} \\end{center} \\end{figure}

The results for fig \\ref{fig:DMDMP-2c-AEI} are for DMDMP-2c in AEI. Both the left and right figures look very similar. The AEI wide frame of the cage is sufficiently large enough for the collection of OSDAs to rotate and change orientations within the cage. Both techniques produce similar orientational flexibility. DMDMP-2c fits fairly loose within the cage, as do the majority of OSDAs for this study. The lowest energy orientation from the DFT results is at about 0.5 and has an energy of -125 kJ/mol, and the CMD results of the same orientation have an energy of approximately 50 kJ/mol higher in energy than the average CMD results for that orientation.

### 2.4 Dreiding vs. DFT

We can compare the overall similarity of the Dreiding and DFT predicted energies for the lowest energy average configuration and lowest energy structure respectively. The Figure bellow plot a parity plot between the two. There is something not quiet right.

Created: 2021-10-27 Wed 16:02

[Validate](http://validator.w3.org/check?uri=referer)
