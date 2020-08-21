# Rebuilt-Binary-Treee-only-From-Inorder-Traversal
It's a program written in SML. It can build an unique tree from in-order traversal in O(n) time without checking every possibility. When the it traverse the tree stores some extra information other than a node value. <br/>

A binary tree can be recovered from it’s preorder (or postorder) traversal. Although the same approach can not be used to recover the tree
from inorder traversal. The issue arises due to the difference in type of information that is abstracted by these traversals. Preorder (or postorder) traversal does not hide the parent-child relation viz. a parent node
will always appear before a child node in preorder traversal (after in postorder traversal); although the parity (number of children) of the parent node is lost. However inorder traversal does not have any such guarantee.
For the same reason infix expressions require “cosmetic sugar” such as parentheses, associativity and precedence of operators to enable parsing of expressions unambiguously while prefix (or postfix) expressions need only the
arity of each operator.

# Problem Statement
Considering the discussion above, design and implement an efficient algorithm to recover the binary tree from an
inorder traversal (which contains the minumum “cosmetic sugar”). Your task is to document both the traversal
algorithm that you use and the solution and thought process for the final out come in a single L A TEX-noweb
file. Make sure that you document your final thought processes in the development of your solutions, proofs,
algorithms and code. Since each noweb document can handle only a single programming language, decide
beforehand whether you are going to program in Standard ML or OCaml.

