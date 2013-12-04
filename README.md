tptpParser
==========

An xtext based parser for the tptp grammer (http://www.cs.miami.edu/~tptp).  (can be used to generate a java parser, and may lead to an awesome eclipse plugin)

this is built with xtext v2.4.3, and I welcom all patches and pull requests!

If you use this libray, I'd love to hear about it!


The design principles are:
 * the primary goal is the generated java parser, the eclipse plugin (while realy cool is secondary)
 * minimal AST, we will ignore issues that happen in the extended biased problems
 * validate against all sample problems, this should be compititiion ready software
 * keep the eventual java parser and the eventual eclipse plugin (and the target tptp problem set in sync with version numbers)

global TODOs:
 * seperate antlr parser directory (may just be a copy and past procedure)
 * eclipse download site
 * deploy to maven
 * Continous integration setup
 * autoformater
 * tooltip hints
 * compiletime validation of linking and type checking
 * comment meta info tagging
