---
content_type: page
learning_resource_types: []
ocw_type: CourseSection
title: Calendar
uid: 96f11506-9aa8-5ad7-4f89-a2b9bdffef4b
---

[Scheme software](http://www.gnu.org/software/mit-scheme/) is required to run the .scm files in this section.

This calendar shows the weekly schedule for the course, which usually includes three lecture and group problem solving sessions per week. This calendar provides links to course notes, problem sets, and other relevant resources. These materials are also provided separately in the {{% resource_link bd583dbd-6c80-e65b-19c5-6a507da5b322 "readings" %}}, {{% resource_link 4e8dd40d-dbff-a8ac-64cc-e9ec108d674c "assignments" %}}, and {{% resource_link aaf4057a-bac7-5b9e-89ac-ae095a684679 "tools" %}} sections of this course.

Week 1
------

_Wednesday_ (_First day of class_)

*   Course overview; no notes

Week 2
------

### Readings

*   Notes 1: Proving Arithmetic Equations, pp. 1–6 ({{% resource_link 7b001432-b8a5-30d1-4dbd-eff1211165ec "PDF" %}})

### Assignments

*   Due at the end of Week 2:
    *   Download [Scheme](http://www.gnu.org/software/mit-scheme/)
    *   Download Scheme Continuation Interpreter project (Project 3 from 6.001 Fall '02) and submit solutions to Problems 11, 12 and 13
        *   A description of continuations ({{% resource_link 01677019-20b6-535d-9974-66c55ca5acab "PDF" %}})
        *   Project 3 description ({{% resource_link 19a619a1-daad-086a-4a37-d03cbc20d781 "PDF" %}})
        *   Project 3 code
            *   c-eval.scm ({{% resource_link 53d0a6f4-b476-06cc-5779-734692f1ee11 "SCM" %}})
            *   desugar.scm ({{% resource_link feeec1a0-9b94-ab04-506b-e8098cda4278 "SCM" %}})
            *   meval.scm (Optional) ({{% resource_link 18eccb95-7a94-b4f3-93b4-80a10ca5d4f5 "SCM" %}})

### Monday

*   Diagnostic Questionnaire ({{% resource_link 16bb1a9c-36df-8b04-988a-d40623cea655 "PDF" %}}) and Solutions ({{% resource_link 39c3997d-5720-3488-f499-7041be2aa9b1 "PDF" %}})

### Wednesday

*   Problems on arithmetic equations

### Friday

*   Problems on implementing catch/throw with call-cc

Week 3
------

### Readings

*   Notes 1: Proving Arithmetic Equations, final sections ({{% resource_link 7b001432-b8a5-30d1-4dbd-eff1211165ec "PDF" %}})

### Wednesday

*   Procedure to check a linear proof and convert between linear and tree proofs

### Friday

*   Exercise: Convert a tree proof to a substitution proof ({{% resource_link 766c0826-27b3-888c-7112-3f0a81f9671b "PDF" %}})
*   Scheme code ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/mccamanttreeproof.scm)) for the conversion
*   Arithmetic inequalities
*   Pattern matcher match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm))

Week 4
------

### Readings

*   Pattern matcher match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/match.scm))
*   Pattern-match based procedure proof-match.scm  ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/proofmatch.scm)) for converting a sequence-of-equations proof into a tree proof
*   Notes 2: Substitution into Arithmetic Expressions ({{% resource_link 80772902-b9eb-cdc9-038b-e79d80028188 "PDF" %}})
*   Also, from last week, see Scheme code for converting a tree proof to a substitution proof ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/mccamanttreeproof.scm))

### Monday

*   Structural induction proof of the Substitution Lemma and Soundness of Substitution Proofs (see Notes 2: Substitution into Arithmetic Expressions ({{% resource_link 80772902-b9eb-cdc9-038b-e79d80028188 "PDF" %}}))
*   Intro to pattern matching, with pattern-match based procedure proof-match.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/proofmatch.scm)) for converting a sequence-of-equations proof into a tree proof

### Wednesday

*   Review of Notes 2: Substitution into Arithmetic Expressions ({{% resource_link 80772902-b9eb-cdc9-038b-e79d80028188 "PDF" %}})
*   Problem for Friday: We extend Arithmetic Expressions with another case called an application
*   "Doctor" program using unnested matching eliza.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/eliza.scm))

### Friday

*   Discussion of using match/rewrite rules to put arithmetic expressions (possibly extended with applications and a derivative operator) into canonical form. An example is in deriv-simplify-rules.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/derivsimplifyrules.scm)); this version uses the alphabetized sum-of-monomials canonical form rather than the one-variable-polynomial-with-polynomial-coefficients canonical form of the Notes
*   Intro to Scheme Substitution Model

Week 5
------

### Readings

*   Notes 3: A Scheme Substitution Model, Sections 1–6 (pp. 1–14) ({{% resource_link 02d60bb7-4e90-93dd-658b-55d6bd421f94 "PDF" %}})
*   Skim the scheme programs implementing the {{% resource_link aaf4057a-bac7-5b9e-89ac-ae095a684679 "Scheme Substitution Model" %}}

### Monday

*   Bring your laptop loaded with the {{% resource_link aaf4057a-bac7-5b9e-89ac-ae095a684679 "files" %}} for running the Substitution Model
*   Observe the submodel running on expressions in test-submodel.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/testsubmodel.scm))

### Wednesday

*   Discussion of control contexts in the Substitution Model

### Friday

*   Further example file for Substitution Model evaluation politician.scm ([SCM](/courses/electrical-engineering-and-computer-science/6-844-computability-theory-of-and-with-scheme-spring-2003/tools/politician.scm))

Week 6
------

### Readings

*   Notes 4: Term Models ({{% resource_link 2d8112ce-89db-b4c2-a65b-cdc66f448c74 "PDF" %}})

### Assignments

*   Due on Monday of Week 7: Problems 1–3 in Notes 4: Term Models ({{% resource_link 2d8112ce-89db-b4c2-a65b-cdc66f448c74 "PDF" %}})

### Monday

*   Trivial decision procedure: Two terms are equal in all models iff they are identical
*   Proving it: Introduction to term models

### Wednesday

*   Equational completeness theorem: If an equation follows logical from a set of equations, then the equation is provable using standard rules starting with the set of equations as axioms. Outline of proof using a term model

### Friday

*   Introduction to simple types

Week 7
------

### Monday

*   Environment models for simple types

### Wednesday

*   Combinator formulation of environment models

### Friday

*   Term models for simple types

Week 8
------

### Assignments

*   Due on Monday of Week 10: Problem Set 1 ({{% resource_link 13d6b73e-8698-e6fa-56c8-162f09146853 "PDF" %}})

### Monday

*   Compiling Scheme to register machines with a memory array

### Wednesday

*   Reducing RegM's with a memory array to 2-Counter machines

### Friday

*   Semigroup word problems: Rewrite rules for 2-CM simulation

Week 9
------

### Monday

*   Semigroup word problems: Confluence implies equations capture one-way rewrite rules for 2-CM simulation
*   Diamond Lemma for confluence

Week 10
-------

### Assignments

*   Due at the end of Week 10: Problem 18 from Notes 5: Scheme Computability, Part I ({{% resource_link 60cadbac-50de-8221-1027-b50645a9f28b "PDF" %}})

### Monday

*   Computability on S-expressions

### Wednesday

*   Notes 5: Scheme Computability, Part I ({{% resource_link 60cadbac-50de-8221-1027-b50645a9f28b "PDF" %}})

### Friday

*   Proof that productivity inherits up many-one reducibility (≦{{< sub "m" >}}). Further properties of ≦{{< sub "m" >}}

Week 11
-------

### Wednesday

*   Notes 7: Counter Machines ({{% resource_link b3cd4c14-0068-033a-a77d-3531c35ae049 "PDF" %}})
*   Notes 8: Semigroup Word Problems ({{% resource_link 9c964077-316f-0d4b-3663-3294a1c3c214 "PDF" %}})
*   Notes 9: 1st-order Theory of Concatenation ({{% resource_link e76d7d50-0a96-0f25-df43-efc39ad5e466 "PDF" %}})

### Friday

*   Notes 3: Scheme Substitution Model ({{% resource_link 02d60bb7-4e90-93dd-658b-55d6bd421f94 "PDF" %}})
*   Notes 5: Scheme Computability, Part I ({{% resource_link 60cadbac-50de-8221-1027-b50645a9f28b "PDF" %}})
*   Notes 6: Scheme Computability, Part II ({{% resource_link a783254d-f35a-db71-0c48-318ad5eff59a "PDF" %}})

Week 12
-------

### Assignments

*   Due on Wednesday of Week 13: Final Problem Set, 6 of these 10 problem:
    *   Notes 3: Scheme Substitution Model ({{% resource_link 02d60bb7-4e90-93dd-658b-55d6bd421f94 "PDF" %}}), Problems 2, 13 (which is more appropriately **a** term project ({{% resource_link af6b70be-b43f-8b1b-5079-6a6ffdc38e0e "PDF" %}})), 14
    *   Notes 5: Scheme Computability, Part I ({{% resource_link 60cadbac-50de-8221-1027-b50645a9f28b "PDF" %}}) , Problem 21 – not Problem 22; Problem 22 can be a term project ({{% resource_link af6b70be-b43f-8b1b-5079-6a6ffdc38e0e "PDF" %}})
    *   Notes 6: Scheme Computability, Part II ({{% resource_link a783254d-f35a-db71-0c48-318ad5eff59a "PDF" %}}), Problems 1, 5, 6, 7, 8, 9

### Monday

*   Course projects ({{% resource_link af6b70be-b43f-8b1b-5079-6a6ffdc38e0e "PDF" %}})

### Wednesday

*   Halting Problem for 2-Counter Machines  
    ≤{{< sub "m" >}} Th(∑\*, ·)  
    ≤{{< sub "m" >}} Th({1,2}\*, ·)  
    ≤{{< sub "m" >}} Th(N,+,×, ≦)  
    ≡{{< sub "m" >}} Th(Z,+,-, ×, ≦),

where Th(_M_) denotes the 1st-order formulas valid in model _M_

### Friday

*   Complete proof that \[2-CM Halting Problem ≤{{< sub "m" >}} Th(∑\*, ·)\]
*   Observe that Halts reduces to the set of closed formulas of the form ∃_z_.G where all quantifiers in G range over subwords of _z_

Week 13
-------

### Assignments

*   Due at the beginning of this week: Course project ({{% resource_link af6b70be-b43f-8b1b-5079-6a6ffdc38e0e "PDF" %}}) proposals

### Monday

*   Topic: Diophantine sets over the integers and naturals; closure under intersection. Primes ≠ range(_g_) for any polynomial, _g_

### Wednesday

*   MIN{{< sub "Scheme" >}} ≡{{< sub "T" >}} Halts. Sketch of relative computability: The jump operation

### Friday

*   Diophantine Predicates closed under ∧, ∨, ∃, but not ¬ (negation)
*   A Diophantine polynomial whose nonnegative range is the nonprimes

Week 14
-------

### Assignments

*   Due at the end of this week: Term project ({{% resource_link af6b70be-b43f-8b1b-5079-6a6ffdc38e0e "PDF" %}})

### Monday

*   Excerpt: pp. 174–181 on Undecidability of Exponential Diophantine Polynomials, from Jones, Neil D. "Computability and Complexity: from a Programming Perspective," MIT Press, c. 1997, 466pp.

### Wednesday (Last class)

*   Term project