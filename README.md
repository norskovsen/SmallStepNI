# Mechanization of a noninterference proof for a toy imperative language with small-step semantics in Coq.

Author: Aslan Askarov

The main NI theorem is in **NI.v**.

#### Notes
* The proof relies on Coq 8.4lp6_1 (does not work on 8.5!) 
* The proof scripts use CPDT tactics. They are assumed to be placed in lib/cpdt/; they are not included in the repository.
* The proof uses SF libraries; these and other small libraries are included for convenience in lib/.
* Comments and suggestions on how to improve these scripts are welcome.

#### ChangeLog

* 2016-07-10: update to the latest version of Cpdt tactics

* 2015-04-04: initial version of the proof.
