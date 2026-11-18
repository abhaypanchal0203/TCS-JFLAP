# Theory of Computer Science: Self-Learning with JFLAP

- **Name:** Abhay Sudhir Panchal
- **Roll No.:** 43
- **Class / Branch / Sem:** D12B / CMPN / Semester V
- **Subject:** Theory of Computer Science (26CMPC51)

This repository contains 30 JFLAP (`.jff`) examples covering finite automata, transducers, regular expressions, regular and context-free grammars, LL/LR/CYK parsing, pushdown automata, Turing machines, and Chomsky Normal Form transformations.

## Setup & Usage

1. Ensure Java (JDK/JRE 8+) is installed on your machine.
2. Download JFLAP 7.1 from https://www.jflap.org/modules/.
3. Launch JFLAP and open any `.jff` file via **File → Open**.

## List of JFLAP Files

| # | Topic | File | Description |
|---|-------|------|-------------|
| 1 | Deterministic Finite Automata | `43_AbhayPanchal_deterministic_finite_automata_18-11-26.jff` | DFA over {a,b} accepting strings that end in "ba" |
| 2 | Nondeterministic Finite Automata | `43_AbhayPanchal_nondeterministic_finite_automata_18-11-26.jff` | NFA over {0,1} accepting strings containing the substring "101" |
| 3 | NFA to DFA Conversion | `43_AbhayPanchal_nfa_to_dfa_conversion_18-11-26.jff` | NFA over {a,b} accepting strings ending in either "aa" or "bb" |
| 4 | DFA Minimization | `43_AbhayPanchal_dfa_minimization_18-11-26.jff` | 4-state DFA over {0,1} for odd-length strings that minimizes to 2 states |
| 5 | DFA to Regular Grammar Conversion | `43_AbhayPanchal_dfa_to_regular_grammar_18-11-26.jff` | DFA accepting strings over {0,1} with an even number of 1's |
| 6 | DFA to Regular Expression Conversion | `43_AbhayPanchal_dfa_to_regular_expression_18-11-26.jff` | DFA accepting strings over {a,b} starting and ending with "a" (length >= 2) |
| 7 | Combining Automata | `43_AbhayPanchal_combining_automata_18-11-26.jff` | DFA for strings over {0,1} containing "01", for union or concatenation |
| 8 | Regular Expression | `43_AbhayPanchal_regular_expression_18-11-26.jff` | Regular expression a(a+b)*b |
| 9 | Regular Expression to DFA Conversion | `43_AbhayPanchal_regex_to_dfa_18-11-26.jff` | Regular expression (01+1)*0 for conversion to DFA |
| 10 | Regular Expression Identities | `43_AbhayPanchal_regular_expression_identities_18-11-26.jff` | Regular expression (0+1)*1(0+1)* for checking regular identities |
| 11 | Regular Grammar | `43_AbhayPanchal_regular_grammar_18-11-26.jff` | Right-linear regular grammar generating 0*10 |
| 12 | Regular Grammar to DFA Conversion | `43_AbhayPanchal_regular_grammar_to_dfa_18-11-26.jff` | Right-linear grammar generating (ab)*a to convert into a DFA |
| 13 | DFA Relationship to Grep | `43_AbhayPanchal_dfa_grep_bab_18-11-26.jff` | DFA for (a+b)*bab demonstrating grep substring pattern matching |
| 14 | Mealy Machine | `43_AbhayPanchal_mealy_2s_complement_18-11-26.jff` | Mealy machine that computes 2's complement (LSB to MSB) |
| 15 | Moore Machine | `43_AbhayPanchal_moore_detect_bb_18-11-26.jff` | Moore machine over {a,b} that outputs 1 right after "bb" is seen |
| 16 | Context-free Grammar | `43_AbhayPanchal_context_free_grammar_18-11-26.jff` | CFG S -> aaSb | lambda generating a^(2n) b^n |
| 17 | Pushdown Automata | `43_AbhayPanchal_pushdown_automaton_18-11-26.jff` | NPDA accepting a^n b^(2n) (n >= 1) by final state |
| 18 | NPDA to CFG Conversion | `43_AbhayPanchal_npda_to_cfg_conversion_18-11-26.jff` | NPDA for odd palindromes w c w^R formatted for direct CFG conversion |
| 19 | CFG to NPDA Conversion | `43_AbhayPanchal_cfg_to_npda_conversion_18-11-26.jff` | CFG generating a^n b^m c^m d^n to convert into an NPDA |
| 20 | Context-free Grammar with Single Symbols | `43_AbhayPanchal_cfg_single_symbols_18-11-26.jff` | CFG with single-symbol right-hand sides (S -> X | Y, X -> a, Y -> b) |
| 21 | Context-free Grammar with Multiple Symbols | `43_AbhayPanchal_cfg_multiple_symbols_18-11-26.jff` | CFG with multi-symbol right-hand sides (S -> xABy) |
| 22 | CFG in Error using User Control Parse | `43_AbhayPanchal_cfg_error_parse_18-11-26.jff` | CFG S -> bSb | ab for stepping through dead-ends in User Control Parse |
| 23 | LL Parsing | `43_AbhayPanchal_ll_parsing_18-11-26.jff` | LL(1) grammar for comma-separated lists S -> aA, A -> cA | lambda |
| 24 | LR Parsing | `43_AbhayPanchal_lr_parsing_18-11-26.jff` | LR(1) grammar S -> S+A | A, A -> b for bottom-up shift-reduce parsing |
| 25 | CYK Parsing | `43_AbhayPanchal_cyk_parsing_18-11-26.jff` | Grammar in Chomsky Normal Form generating a+ b+ for CYK parsing |
| 26 | One-Tape Turing Machine | `43_AbhayPanchal_one_tape_turing_machine_18-11-26.jff` | One-tape TM over {a,b} that replaces every a with x and every b with y |
| 27 | Multi-Tape Turing Machine | `43_AbhayPanchal_multi_tape_turing_machine_18-11-26.jff` | Two-tape TM that recognizes 0^n 1^n (n >= 1) using the second tape |
| 28 | Turing Machine Building Blocks | `43_AbhayPanchal_turing_building_block_18-11-26.jff` | TM building block subroutine that scans right to find the first 1 |
| 29 | Unrestricted Grammar | `43_AbhayPanchal_unrestricted_grammar_18-11-26.jff` | Type-0 unrestricted grammar that generates 0^n 1^n 2^n (n >= 1) |
| 30 | CFG to Chomsky Normal Form Transformation | `43_AbhayPanchal_cfg_to_cnf_transformation_18-11-26.jff` | CFG (S -> ABA, A -> aA | lambda, B -> bB | lambda) for CNF transformation |
