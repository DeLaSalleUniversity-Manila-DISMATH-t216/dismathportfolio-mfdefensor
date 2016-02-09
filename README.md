# Week 1
After the introductions, we had the discussion about propositional logics. The logic was defined.

# Week 2
The logic gates and their corresponding Truth Table values were discussed. The OR, AND, NOR, and XOR

# Week 3
The formal verification is proving arguments. It can be software or hardware. There are six formal verification methods. 3 of them were discussed this week: Direct Proof, Proof by Contraposition, Vacuous and Trivial Proof.
Direct proof is proving conditional statement by assuming the condition (first statement) to be true, and showing that the result (second statement) is also true by using the first statement. Proof by contraposition is proving a conditional statement by contrapositive structure--that is to say, the statements are interchanged--which means, the condition becomes the conclusion, and the conclusion becomes a condition--and each of them are negated, and like direct proof, the first statement (which is then the conclusion turned condition) is assumed true, and the second statement (the condition turned conclusion) should be shown as true using the first statement. The vacuous and trivial proof came from implication. Vacuous proof must show that the condition is false so that the conditional statement must be true. On the other hand, trivial proof shows that the conclusion is true so that the conditional statement must also be true. So far, my favorite of the methods is the direct proof, and I find the vacuous proof quite confusing.

# Week 4
The discussion of formal verification was continued this week. Proving by Contradiction requires making an assumption first, and then abandoning that assumption later. This method uses a single statement. That statement is negated first which is assumed to be true, and then showing that this assumption ends in contradiction. Proof by Equivalence proves a biconditional statement by directly proving it first as a conditional statement and second as an inverse conditional statement.
A new topic has been introduced. Mathematical Induction is substitution with direct proof by first making a basis of subsituting the first value (1) into the proposition, and then applying the inductive steps by proving that substituting k into the proposition gives k+1.

# Week 5
Recursive definition is defining a function in terms of itself. Recursive algorithm is the set of precise instructions for computations, which has a basis step by specifying the value of the function at zero, and a recursive step by giving a rule for finding its value at an integer. Program correcteness was also discussed. A program is said to be correct if the correct answer is obtained if the program terminates, and program should always terminate. It makes use of the Hoare Triple, which has Initial Assertion, which is assumed to be true, Program Segment, which is where the initial assertion is to be substituted, and the Final Assertion, which is shown to be true. There are also rules of inference which states that the program should be split into subprograms. Conditional and if-else statements utilizes Hoare Triple.
