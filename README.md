This repository contains a COBOL program with an infinite loop caused by an unconditional GOTO statement in the termination section.  The bug and its solution are demonstrated with code examples in separate files.  The original code has a flaw where the termination section will never end, while the solution removes the unnecessary GO TO statement, ensuring correct program flow.