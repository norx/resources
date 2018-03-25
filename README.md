# NORX Parallel and Scalable Authenticated Encryption

NORX is a parallel and scalable authenticated encryption algorithm and a third-round candidate in the [CAESAR](http://competitions.cr.yp.to/caesar.html) competition.

NORX was designed by:

- [Jean-Philippe Aumasson](https://aumasson.jp/) ([@veorq](https://twitter.com/veorq))
- [Philipp Jovanovic](https://zerobyte.io/) ([@daeinar](https://twitter.com/daeinar))
- [Samuel Neves](http://eden.dei.uc.pt/~sneves/) ([@sevenps](https://twitter.com/sevenps))

NORX is not patented and freely available for all applications. All content on NORX such as its specification and source code is available under the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/).

# Specifications

The following versions of the NORX specification are available:

- [NORX v3.0](https://github.com/norx/resources/blob/master/specs/norxv30.pdf)
- [NORX v2.0](https://github.com/norx/resources/blob/master/specs/norxv20.pdf)
- [NORX v1.1](https://github.com/norx/resources/blob/master/specs/norxv11.pdf)
- [NORX v1.0](https://github.com/norx/resources/blob/master/specs/norxv10.pdf)

# Implementations

The following NORX reference implementations are available:

- [NORX software](https://github.com/norx/norx) (C)
- [NORX hardware](https://github.com/norx/norx-hw) (VHDL)

Furthermore, there is a number of community implementations in different languages:

- 2017-06-11: [plc](https://github.com/philanc/plc) (Lua); Philippe Leblanc
- 2016-05-23: [norx-cryptol](https://github.com/ttaubert/norx-cryptol) (Cryptol); Tim Taubert ([@ttaubert](https://twitter.com/ttaubert))
- 2016-05-11: [spark_norx](https://github.com/jhumphry/SPARK_NORX) (Ada/Spark); James Humphry
- 2015-06-01: [cifra](https://github.com/ctz/cifra) (C); Joseph Birr-Pixton ([@jpixton](https://twitter.com/jpixton))
- 2015-03-13: [norxavr](https://github.com/leonbotros/norxavr) (C/AVR-Assembly); Leon Botros
- 2015-01-05: [norx-dart](https://github.com/olanoek/norx-dart) (Dart); Olan ÖK ([@olanoek](https://twitter.com/olanoek))
- 2015-01-05: [norx.js](https://github.com/kaepora/norx.js) (JavaScript); Nadim Kobeissi ([@kaepora](https://twitter.com/kaepora))
- 2014-12-04: [norx-py](https://github.com/daeinar/norx-py) (Python2); Philipp Jovanovic ([@daeinar](https://twitter.com/daeinar))
- 2014-07-07: [norx-rust](https://github.com/sneves/norx-rust) (Rust); Samuel Neves ([@sevenps](https://twitter.com/sevenps))
- 2014-05-29: [norx-go](https://github.com/daeinar/norx-go) (Go); Philipp Jovanovic ([@daeinar](https://twitter.com/daeinar))
- 2014-03-27: [norxx](https://code.google.com/p/norxx/) (C++); Sebastian Gesemann ([@EsGeh](https://twitter.com/esgeh))
- 2014-03-19: [norxpy](https://github.com/therealmik/norxpy) (Python/Numpy); Michael Samuel ([@mik235](https://twitter.com/mik235))

# Publications

- Nov 2017: [Under Pressure: Security of Caesar Candidates beyond their Guarantees](https://eprint.iacr.org/2017/1147); Serge Vaudenay, Damian Vizar; IACR ePrint archive report 2017/1147 
- Nov 2017: [Pipeline Oriented Implementation of NORX for ARM Processors](https://sbseg2017.redes.unb.br/wp-content/uploads/2017/04/20171109_ANAIS_SBSEG_2017_FINAL_E-BOOK.pdf#ANAIS_SBSEG_2017.indd%3A.29325%3A1298); Luan Cardoso dos Santos, Julio López; SBSeg 2017 
- May 2017: [Full-State Keyed Duplex With Built-In Multi-User Support](https://eprint.iacr.org/2017/498); Joan Daemen, Bart Mennink, Gilles Van Assche; Asiacrypt 2017 
- Mar 2017: [Cryptanalysis of NORX 2.0](http://tosc.iacr.org/index.php/ToSC/article/view/589); Colin Chaigneau, Thomas Fuhr, Henri Gilbert, Jérémy Jean, Jean-René Reinhard; Fast Software Encryption 2017 
- Jan 2017: [Analysis of the NORX Core Permutation](https://eprint.iacr.org/2017/034); Alex Biryukov, Aleksei Udovenko, Vesselin Velichkov; IACR ePrint archive report 2017/034 
- Dec 2016: [On Linear Properties of G Function in NORX](http://www.jcr.cacrnet.org.cn:8080/mmxb/EN/abstract/abstract179.shtml); Wen Cheng, Jie Guan; Journal of Cryptologic Research 
- Nov 2016: [SAT-based Cryptanalysis of Authenticated Ciphers from the CAESAR Competition](https://eprint.iacr.org/2016/1053); Ashutosh Dhar Dwivedi, Milos Kloucek, Pawel Morawiecki, Ivica Nikolic, Josef Pieprzyk, Sebastian Wojtowicz; IACR ePrint archive report 2016/1053 
- Mar 2016: [Cryptanalysis of Reduced NORX](https://eprint.iacr.org/2016/436); Nasour Bagheri, Tao Huang, Keting Jia, Florian Mendel, Yu Sasaki; Fast Software Encryption 2016
- Mar 2015: [NORX8 and NORX16: Authenticated Encryption for Low-End Systems](https://eprint.iacr.org/2015/1154); Jean-Philippe Aumasson, Philipp Jovanovic, Samuel Neves; TRUDEVICE workshop 2015
- Mar 2015: [Higher Order Differential Analysis of NORX](https://eprint.iacr.org/2015/186); Sourav Das, Subhamoy Maitra, Willi Meier; IACR ePrint archive report 2015/186 
- Dec 2014: [Beyond 2^{c/2} Security in Sponge-Based Authenticated Encryption Modes](https://eprint.iacr.org/2014/373); Philipp Jovanovic, Atul Luykx, Bart Mennink; ASIACRYPT 2014
- Sep 2014: [Analysis of NORX: Investigating Differential and Rotational Properties](https://eprint.iacr.org/2014/317); Jean-Philippe Aumasson, Philipp Jovanovic, Samuel Neves; Latincrypt 2014
- Sep 2014: [NORX: Parallel and Scalable AEAD](http://link.springer.com/chapter/10.1007/978-3-319-11212-1_2); Jean-Philippe Aumasson, Philipp Jovanovic, Samuel Neves; ESORICS 2014

# Misc

Jun 2015: [Benchmarking Modern Authenticated Encryption on 1€ Devices](http://jbp.io/2015/06/01/modern-authenticated-encryption-for-1-euro/) by Joseph Birr-Pixton; NORX among fastest ciphers on small processors. Benchmarked using the [cifra](https://github.com/ctz/cifra) platform.

