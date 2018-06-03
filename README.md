# Awesome Language Engineering [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![alan_behind](https://user-images.githubusercontent.com/4667129/31479957-bc003858-aecf-11e7-91ae-f8a1faab66da.jpg)](https://github.com/NLKNguyen/awesome-language-engineering)
> A curated list of useful resources for computer language engineering and theory

Whether you want to create a text-processor, a parser, a language application, a DSL (Domain Specific Language), or a full-fledged programming language with compiler and tooling, this page serves as a directory map to point you to the right direction.

Better yet, help others finding their way by contributing to this page with the resources that you think useful.

## Contents

- [Tools](#tools)
- [Books](#books)
- [Articles](#articles)


# Tools

Just like other domains, knowing the available tools that are tried-and-true will save you a lot of time and efforts. Furthermore, you will also learn the emerging techniques that are adopted in different tools which make the skills more transferable.

### [ANTLR](http://www.antlr.org/) (ANother Tool for Language Recognition) 
A powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build and walk parse trees.

Describe language lexical and grammar specification in a declarative file format `.g4` (Lex/Yacc format alike), and the generator can create a parser for the following target languages: Java, C#, Python, JavaScript, Go, C++, Swift ([see update](https://github.com/antlr/antlr4/blob/master/doc/targets.md))

*Learning materials*:

* Book: [The Definitive ANTLR 4 Reference](https://amzn.to/2srUkns): Build your own languages with ANTLR v4

    <a href="https://www.amazon.com/Definitive-ANTLR-4-Reference/dp/1934356999/ref=as_li_ss_il?ie=UTF8&qid=1527979678&sr=8-1&keywords=The+Definitive+ANTLR+4+Reference&linkCode=li3&tag=mynn11481-20&linkId=faa51b40044cf23c6dc907495556b43f" target="_blank"><img src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1934356999&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" width="200px"></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1934356999" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

* Doc: [Supported Documentation](https://github.com/antlr/antlr4/blob/master/doc/index.md) for the above books

* Web: [ANTLR Mega Tuotrial](https://tomassetti.me/antlr-mega-tutorial/): A comprehensive tutorial that explains all you need to know to understand language design fundamentals and use ANTLR effectively. There is PDF version. All free.

* Video: [Terence Parr - ANTLR4](https://vimeo.com/59285751): Dr. Terence Parr introduces the latest (and last) revision of his parser generator, ANTLR



### [MPS](https://www.jetbrains.com/mps/) (Meta Programming System)

With JetBrains MPS, you can define custom editors for any new language and make using these DSLs simpler. Even domain experts, who are not familiar with traditional programming, can easily work in MPS with domain-specific languages designed around their domain-specific terminology.

*Learning materials*:

* Book: [The MPS Language Workbench Volume I](https://amzn.to/2JmX8fr):  a simple introduction to the JetBrains MPS language workbench and a complete reference manual

    <a href="https://www.amazon.com/MPS-Language-Workbench-Programming-System/dp/153053335X/ref=as_li_ss_il?ie=UTF8&qid=1505363569&sr=8-1&keywords=jetbrains+MPS&linkCode=li3&tag=mynn11481-20&linkId=728463da56cd2c9871036f31e2e65908" target="_blank"><img src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=153053335X&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=153053335X" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
    
* Book: [The MPS Language Workbench Volume II](https://amzn.to/2JbNM2F): how to customize the MPS platform to better integrate it with the needs of your languages

    <a href="https://www.amazon.com/MPS-Language-Workbench-II-Programming/dp/1532805373/ref=as_li_ss_il?ie=UTF8&qid=1505363569&sr=8-2&keywords=jetbrains+MPS&linkCode=li3&tag=mynn11481-20&linkId=59bc0aae249a79c5a3f5e0dd58a2e5c1" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1532805373&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1532805373" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

### [Xtext](https://eclipse.org/Xtext/)

Xtext is a framework by Eclipse for development of programming languages and domain-specific languages. With Xtext you define your language using a powerful grammar language. As a result you get a full infrastructure, including parser, linker, typechecker, compiler as well as editing support for Eclipse, IntelliJ IDEA and your favorite web browser.

*Learning materials*:

* Book: [Implementing Domain-Specific Languages with Xtext and Xtend](https://amzn.to/2JlatEW): learn how to implement a DSL with Xtext and Xtend using easy-to-understand examples and best practices

    <a href="https://www.amazon.com/Implementing-Domain-Specific-Languages-Xtext-Xtend-ebook/dp/B01CSLI6HM/ref=as_li_ss_il?ie=UTF8&qid=1505686814&sr=8-1&keywords=xtext&linkCode=li3&tag=mynn11481-20&linkId=9d12bf285266213ea26f6fa068ff4b08" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=B01CSLI6HM&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=B01CSLI6HM" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />


### [Sirius](https://eclipse.org/Xtext/)

Sirius is an Eclipse project which allows you to easily create your own graphical modeling workbench by leveraging the Eclipse Modeling technologies, including EMF and GMF.

*Learning materials*:

* Web: [Official Guide](http://www.eclipse.org/sirius/getstarted.html): provides an introduction to Sirius and a series of tutorials to get started building your own graphical modeling tool



### [Flex](https://github.com/westes/flex) and [Bison](https://www.gnu.org/software/bison/)

Flex and Bison are aging unix utilities that help you write very fast parsers for almost arbitrary file formats. Lex and Yacc are the original tools; Flex and Bison are their almost completely compatible newer versions.

*Learning materials*:

* Web: [Flex & Bison Tutorial](http://aquamentus.com/flex_bison.html): this webpage is supposed to be a tutorial for complete novices needing to use Flex and Bison for some real project.

* Book: [Flex & Bison](https://amzn.to/2LQrOnw): explains how to use flex and bison to solve your problems quickly. This is the update from the original Lex & Yacc book described below.

    <a href="https://www.amazon.com/flex-bison-Text-Processing-Tools/dp/0596155972/ref=as_li_ss_il?ie=UTF8&qid=1505766504&sr=8-1&keywords=flex+and+bison&linkCode=li3&tag=mynn11481-20&linkId=242d418d7209a3cf975792c778a7e176" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0596155972&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=0596155972" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

* Book: [Lex & Yacc](https://amzn.to/2ssI5qE): shows you how to use two Unix utilities, lex and yacc, in program development. These tools help programmers build compilers and interpreters, but they also have a wider range of applications.

    <a href="https://www.amazon.com/lex-yacc-Doug-Brown/dp/1565920007/ref=as_li_ss_il?ie=UTF8&qid=1505766519&sr=8-1&keywords=lex+and+yacc&linkCode=li3&tag=mynn11481-20&linkId=a3038a1a661bbea9395d539c22c14df7" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1565920007&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1565920007" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

### [Kaitai Struct](http://kaitai.io/#quick-start) 

A parser generator for reading binary data. This is a declarative language for specifying data structure of binary data in order to generate parser (in multiple target languages) that handles reading binary file formats, network stream packet formats, etc. It comes with a compiler, an IDE, a visualizer, and library of format specs.

Describe binary structure specification in a declarative file format `.ksy` (YAML alike), and the generator can create a parser for the following target languages: C++/STL, C#, Java, JavaScript, Perl, PHP, Python, Ruby ([see update](http://kaitai.io/))

### [Sed](https://www.gnu.org/software/sed/) and [Awk](https://www.gnu.org/software/gawk/)

Sed and Awk are two text processing programs that are mainstays of the UNIX programmer's toolbox. 

- Sed is a stream editor (non-interactive) to do common text editing jobs like search/extract/replace/insert.
- Awk is a whole programming language ideal for handling data extraction, reporting, and data-reformatting jobs.

Both are command-line interface programs that can be used independently or together nicely for many text processing purposes. They are great for recognizing and extracting information from text input. For simple language recognition tasks, perhaps they are the best tools for the job with the least effort due to their simplicity and targeted use cases. Sed and Awk are part of most, if not all, Linux/Unix/macOS distributions. They are available to download for Windows as well.

*Learning materials*:

* Doc:
    * [Sed official manual](https://www.gnu.org/software/sed/manual/)
    * [Awk official manual](https://www.gnu.org/software/gawk/manual/)
* Web:
    * [Sed tutorial](http://www.grymoire.com/Unix/Sed.html)
    * [Awk tutorial](http://www.grymoire.com/Unix/Awk.html)
    * [Handy Sed one-liners](http://www.pement.org/sed/sed1line.txt)    
    * [Handy Awk one-liners](http://pement.org/awk/awk1line.txt)
    * [Awk by Example](https://www.ibm.com/developerworks/library/l-awk1/)
* Course:
    * [Lynda.com Sed Essential Training](https://www.lynda.com/SED-tutorials/SED-Essential-Training/359472-2.html)
    * [Lynda.com Awk Essential Training](https://www.lynda.com/Linux-tutorials/AWK-Essential-Training/162719-2.html)
    
* Book:

    * [Sed & Awk](https://amzn.to/2JoLWPb)
        
        <a href="https://www.amazon.com/sed-awk-Dale-Dougherty/dp/1565922255/ref=as_li_ss_il?ie=UTF8&qid=1508814582&sr=8-2&keywords=sed&linkCode=li3&tag=mynn11481-20&linkId=2ef4692b88007297cb76113e8828f0b4" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1565922255&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1565922255" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
        
    * [The AWK Programming Language](https://amzn.to/2J59Qjv)

        <a href="https://www.amazon.com/AWK-Programming-Language-Alfred-Aho/dp/020107981X/ref=as_li_ss_il?s=books&ie=UTF8&qid=1527984736&sr=1-1&keywords=awk+programming+language&dpID=41WxQ-gPjWL&preST=_SY291_BO1,204,203,200_QL40_&dpSrc=srch&linkCode=li3&tag=mynn11481-20&linkId=91d1fed07f2bfe973ce3be90d84ff206" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=020107981X&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=020107981X" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

    * [Effective awk Programming](https://amzn.to/2kKFjcg)

        <a href="https://www.amazon.com/Effective-awk-Programming-Universal-Processing/dp/1491904615/ref=as_li_ss_il?s=books&ie=UTF8&qid=1527984931&sr=1-1&keywords=effective+awk+programming+language&linkCode=li3&tag=mynn11481-20&linkId=2110bc834ad5c67b30857d3597a3f8fe" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1491904615&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1491904615" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />
        
# Fundamentals

# Books

### **[DSL Engineering](https://amzn.to/2HfyF6z)**

*Designing, Implementing and Using Domain-Specific Languages*

<a href="https://www.amazon.com/DSL-Engineering-Designing-Implementing-Domain-Specific/dp/1481218581/ref=as_li_ss_il?ie=UTF8&qid=1505967419&sr=8-3&keywords=domain+specific+languages&linkCode=li3&tag=mynn11481-20&linkId=5eeaee127a3c85ae1922734c300464a2" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=1481218581&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=1481218581" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

The definitive resource on domain-specific languages: based on years of real-world experience, relying on modern language workbenches and full of examples. Domain-Specific Languages are programming languages specialized for a particular application domain.


### **[Language Implementation Patterns](https://amzn.to/2xCBS0z)**

*Create Your Own Domain-Specific and General Programming Languages*

<a href="https://www.amazon.com/Language-Implementation-Patterns-Domain-Specific-Programming/dp/193435645X/ref=as_li_ss_il?s=books&ie=UTF8&qid=1527985098&sr=1-1&keywords=Language+Implementation+Patterns&dpID=51QDoAv%252BFgL&preST=_SX218_BO1,204,203,200_QL40_&dpSrc=srch&linkCode=li3&tag=mynn11481-20&linkId=74fe9628b485dfa8ab1e36bd67e33e09" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=193435645X&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=193435645X" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

Written by the author of ANTLR, and it is also the tool used in the book, but the general concepts apply regardless of what you use.

### **[Compilers: Principles, Techniques, and Tools](https://amzn.to/2J8cipq)** 

<a href="https://www.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811//ref=as_li_ss_il?ie=UTF8&linkCode=li3&tag=mynn11481-20&linkId=9793c66f2ad6b1f2e740b235c955ac8d" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=0321486811&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=0321486811" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

A classic compiler book that is known to professors, students, and developers worldwide as the "Dragon Book"

### **[Writing An Interpreter In Go](https://amzn.to/2JcBvLt)** 

<a href="https://www.amazon.com/dp/300055808X//ref=as_li_ss_il?coliid=I3HPPYJ76KKH81&colid=28DF35XRZA3V&psc=0&ref_=lv_ov_lig_dp_it&linkCode=li3&tag=mynn11481-20&linkId=4a752f54ba3aeebe83b7e9fb27e8263c" target="_blank"><img border="0" src="https://ws-na.amazon-adsystem.com/widgets/q?_encoding=UTF8&ASIN=300055808X&Format=_SL250_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1&tag=mynn11481-20" ></a><img src="https://ir-na.amazon-adsystem.com/e/ir?t=mynn11481-20&l=li3&o=1&a=300055808X" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />

Learning how to use a C-like language such as Go to create a complete programming language by applying fundamental concepts of lexer, parser, AST (Abstract Syntax Tree), Pratt technique, and recursive descent parser. This also shows you how to implement a REPL (interactive language shell).

# Articles

**General:**

* [Five Questions About Language Design](http://www.paulgraham.com/langdes.html)
* [Designing the next programming language? Understand how people learn!](http://www.theenterprisearchitect.eu/blog/2013/02/14/designing-the-next-programming-language-understand-how-people-learn/)
* [So you want to write your own language?](http://www.drdobbs.com/architecture-and-design/so-you-want-to-write-your-own-language/240165488)
* [Generations of programming languages](http://www.byte-notes.com/generation-programming-languages)
* [Turing Completeness](https://en.wikipedia.org/wiki/Turing_completeness)


**Paradigms:**

* [Programming Paradigms for Dummies: What Every Programmer Should Know](https://www.info.ucl.ac.be/~pvr/VanRoyChapter.pdf)
* [Paradigms of programming languages](http://cs.lmu.edu/~ray/notes/paradigms/)


**Type Systems**

* [Type Systems](http://lucacardelli.name/Papers/TypeSystems.pdf)
* [Static vs. Dynamic Type Checking](https://thesocietea.org/2015/11/programming-concepts-static-vs-dynamic-type-checking/)



# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nikyle Nguyen](https://github.com/NLKNguyen/) has waived all copyright and related or neighboring rights to this work.
