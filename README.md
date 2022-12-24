# SLR_Parser
It is an efficient bottom-up syntax analysis technique that can be used to parse large classes of context free grammar
SLR Parser :
SLR is simple LR. It is the smallest class of grammar having few number of states. SLR is very easy to construct and is similar to LR parsing. The only difference between SLR parser and LR(0) parser is that in LR(0) parsing table, there’s a chance of ‘shift reduced’ conflict because we are entering ‘reduce’ corresponding to all terminal states. We can solve this problem by entering ‘reduce’ corresponding to FOLLOW of LHS of production in the terminating state. This is called SLR(1) collection of items.
