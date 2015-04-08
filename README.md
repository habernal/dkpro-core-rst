# dkpro-core-rst
DKPro Core - Rhetorical Structure Theory (RST) typesystem and wrapper for RST parser

## Prerequisities

- You need a local working copy of RST parser [1]; the copy can be found e.g. here: 
https://github.com/habernal/feng-hirst-rst-parser-acl-2014

## Examples

- There are some examples under src/test

- You only need to point the RSTAnnotator to the src/ folder of the RST parser

## Problems

- Different segmentation (tokenization) and mapping the RST output back to the tokens; sometimes fails due to normalization etc.

[1] Feng, V. W., & Hirst, G. (2014). A Linear-Time Bottom-Up Discourse Parser with Constraints and Post-Editing. In Proceedings of the 52nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) (pp. 511–521). Baltimore, Maryland USA: Association for Computational Linguistics. Retrieved from http://aclweb.org/anthology/P14-1048