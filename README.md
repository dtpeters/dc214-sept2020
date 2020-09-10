# dc214-sept2020



BAP project page
https://github.com/BinaryAnalysisPlatform/bap

Tutorial
https://github.com/BinaryAnalysisPlatform/bap-tutorial


Don't use the toolkit just yet (Sept 9 2020) unless you want to struggle, still has some bugs
https://github.com/BinaryAnalysisPlatform/bap-tutorial



Bap predecessor,BitBlaze:
http://bitblaze.cs.berkeley.edu/



BAP Plugin with paper, code:
https://github.com/BinaryAnalysisPlatform/bap-plugins/tree/master/saluki

Doc Pages:

BIL:
https://binaryanalysisplatform.github.io/bap/api/master/bap/Bap/Std/Bil/index.html
BIL semantics outline:
https://github.com/BinaryAnalysisPlatform/bil/releases/download/v0.1/bil.pdf

Main Page:
https://binaryanalysisplatform.github.io/bap/api/master/index.html

Std Library:
https://binaryanalysisplatform.github.io/bap/api/master/bap/Bap/Std/index.html


Primus Lisp, the micro-execution framework:
https://binaryanalysisplatform.github.io/bap/api/master/bap-primus/Bap_primus/Std/index.html

Disassembly:
https://binaryanalysisplatform.github.io/bap/api/master/bap/Bap/Std/Disasm/index.html









Core Theory, the new datalog-like API for BAP

https://binaryanalysisplatform.github.io/bap/api/master/bap-core-theory/Bap_core_theory/index.html

Repos with code that uses Core Theory, the new datalog based API:
https://gist.github.com/ivg/bbd1ba6d9362e778e723a467a3f8c8b0

https://github.com/BinaryAnalysisPlatform/bap/blob/master/plugins/bil/bil_semantics.ml

https://github.com/BinaryAnalysisPlatform/bap/blob/master/plugins/bil/bil_float.ml
https://github.com/BinaryAnalysisPlatform/bap/blob/master/plugins/bil/bil_lifter.ml



Datalog Based Program Analysis projects

Souffle
https://souffle-lang.github.io/

Doop
https://bitbucket.org/yanniss/doop/src/master/
https://plast-lab.github.io/doop-pldi15-tutorial/


Holmes
https://github.com/maurer/holmes
https://kilthub.cmu.edu/articles/Holmes_Binary_Analysis_Integration_Through_Datalog/7571519

https://docs.rs/holmes/0.1.0/holmes/










Really interesting and informative article on Binary Analysis in Asia
https://cacm.acm.org/magazines/2020/4/243645-asias-surging-interest-in-binary-analysis/fulltext





Disassembler Stuff:

XED from Intel itself:
https://intelxed.github.io/


Capstone:
http://www.capstone-engine.org/

An old capstone bug failing to decode an instruction:
https://github.com/aquynh/capstone/issues/1129


Failed opcode from BAP:
https://www.felixcloutier.com/x86/cvtss2sd

An article on how many instructions there are the x86 ISA and why its a complicated question:
https://stefanheule.com/blog/how-many-x86-64-instructions-are-there-anyway/

A patch adding support in the linux kernel for a new instruction 
https://patchwork.kernel.org/patch/10610307/




Intermediate Languages:
RREIL
https://bitbucket.org/mihaila/bindead/wiki/Introduction%20to%20RREIL

BIL






On soundness:
https://cacm.acm.org/blogs/blog-cacm/236068-soundness-and-completeness-with-precision/fulltext
https://blog.sigplan.org/2019/08/07/what-does-it-mean-for-a-program-analysis-to-be-sound/





CFG stuff

A paper on a program that uses BAP and angr, and goes into the differences between the construction of CFGs why one is preferable over another
https://arxiv.org/pdf/1807.05843 

On forced Execution for constructing CFGs

http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.221.5538


CFG analysis in Angr
https://docs.angr.io/built-in-analyses/cfg



An interesting paper comparing the relative usability of BAP and Angr
http://tyconmismatch.com/papers/nfm2019_bap_angr.pdf

--
+-
