# The SIMON and SPECK Families of Block Ciphers

SIMON and SPECK are families of lightweight block ciphers, each of
which comes in a variety of widths and key sizes. The aim of SIMON and
SPECK is to fill the need for secure, flexible, and analyzable
lightweight block ciphers that perform well on a wide range of current
and future platforms.

This repository hosts general information about the algorithms with
pointers to more detailed information available in other repositories
or papers.

## Presentations and Papers

* [The SIMON and SPECK Families of Lightweight Block
Ciphers](https://eprint.iacr.org/2013/404.pdf)
  * Original paper from June 2013 including algorithm descriptions and
    test vectors
* [The SIMON and SPECK Block Ciphers on AVR 8-bit
  Microcontrollers](https://eprint.iacr.org/2014/947.pdf)
  * Presented at LightSec in September 2014
  * [Springer
    proceedings](https://link.springer.com/chapter/10.1007%2F978-3-319-16363-5_1)
* [The SIMON and SPECK Lightweight Block Ciphers](http://dx.doi.org/10.1145/2744769.2747946)
  * Presented at the Design Automation Conference in June 2015
  * [IEEE Xplore](http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7167361)
* SIMON and SPECK: Ciphers for Contrained Platforms
  * Presented at the
    [RAIN RFID](http://rainrfid.org) [June 24, 2015 Open
    Meeting](http://rainrfid.org/resources/rain-meetings/portland-or-2015-06-24/).
  * [Slides](http://www.rainrfid.org/wp-content/uploads/2015/07/Wingers-RAINRFID.pdf)
* [SIMON and SPECK: Block Ciphers for the Internet of
Things](https://eprint.iacr.org/2015/585.pdf)
  * Presented at the
    [NIST Lightweight Cryptography Workshop](
    http://www.nist.gov/itl/csd/ct/lwc_workshop2015.cfm) in July 2015.
  * [Slides](http://csrc.nist.gov/groups/ST/lwc-workshop2015/presentations/session1-shors.pdf)
    and
    [Paper](http://csrc.nist.gov/groups/ST/lwc-workshop2015/papers/session1-shors-paper.pdf)
    at NIST.

## Implementations

The [original SIMON and SPECK
paper](https://eprint.iacr.org/2013/404.pdf) is the best source for
algorithm descriptions and test vectors.

### Higher-end Software

The
[simon-speck-supercop](https://github.com/iadgov/simon-speck-supercop)
repository includes X86 and ARM implementations using the SSE4.2, AVX2, and
NEON instruction sets for high performance. While the implementations
are structured for the
[SUPERCOP benchmarking toolkit](https://bench.cr.yp.to/supercop.html),
they should be adaptable to other systems.

### Microcontrollers

The University of Luxembourg [Fair Evaluation of Lightweight
Cryptographic Systems (FELICS)
project](https://www.cryptolux.org/index.php/FELICS) includes our
contributions of a range of small and fast implementations of SIMON and
SPECK for the 8-bit AVR, 16-bit MSP430, and 32-bit Cortex-M
microcontrollers.

### ASICs and FPGAs

We have unreleased implementations of SIMON and SPECK for ASICs and
FPGAs that have been documented in our papers. The team is glad to
answer questions about ASIC and FPGA implementation of the algorithms.

## Contact Us

SIMON and SPECK are products of the
[National Security Agency](https://www.nsa.gov/)'s
[Research Directorate](https://www.nsa.gov/what-we-do/research/),
produced as part of our
[Information Assurance research
mission](https://www.nsa.gov/what-we-do/research/ia-research/).
Contact one of the following members of the SIMON and SPECK team with
any questions:

Name                  | Email
----------------------|------------------------------------
Ray Beaulieu          | rayb@ccrwest.org
Doug Shors            | djshors@tycho.ncsc.mil
Jason Smith           | jksmit3@tycho.ncsc.mil
Stefan Treatman-Clark | sgtreat@tycho.ncsc.mil
Bryan Weeks           | beweeks@tycho.ncsc.mil
Louis Wingers         | lrwinge@tycho.ncsc.mil

## Intellectual Property

SIMON and SPECK are free from any intellectual property restrictions.

This Work was prepared by a United States Government employee and, therefore, is excluded from copyright by Section 105 of the Copyright Act of 1976.

Copyright and Related Rights in the Work worldwide are waived through the [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) [Universal license](https://creativecommons.org/publicdomain/zero/1.0/legalcode).

## Disclaimer
See [DISCLAIMER](./DISCLAIMER.md).
