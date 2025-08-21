---
aliases:
tags:
  - grade-1
r0:
ra:
rb:
r1:
r2:
r4:
r8:
r7:
r5:
r3:
r6:
r9:
rc:
rd:
re:
rf:
---

subgraph cluster_2_c_DirectiveEngine {
            style = filled;
            color = darkgray;
            label = "Directive Engine (/srv/directive)";
            comment = "";

            //
            spark_0_directive_t [label = "Directive.meta(Directive)";comment = "";shape = doublecircle;];
            spark_1_directive_t [label = "Directive.r1(TBD)";comment = "";shape = circle;];
            spark_2_directive_t [label = "Directive.r2(TBD)";comment = "";shape = circle;];
            spark_4_directive_t [label = "Directive.r4(TBD)";comment = "";shape = circle;];
            spark_8_directive_t [label = "Directive.r8(TBD)";comment = "";shape = circle;];
            spark_7_directive_t [label = "Directive.r7(TBD)";comment = "";shape = circle;];
            spark_5_directive_t [label = "Directive.r5(TBD)";comment = "";shape = circle;];
            spark_3_directive_t [label = "Directive.r3(CodexOfDirective)";comment = "";shape = doublecircle;];
            spark_6_directive_t [label = "Directive.r6(TBD)";comment = "";shape = doublecircle;];
            spark_9_directive_t [label = "Directive.r9(TBD)";comment = "";shape = doublecircle;];
            spark_a_directive_t [label = "Directive.receive(Goal)";comment = "";shape = triangle;];
            spark_b_directive_t [label = "Directive.send(Action)";comment = "";shape = invtriangle;];
            spark_c_directive_t [label = "Directive.dispatch(Strategy)";comment = "";shape = doublecircle;];
            spark_d_directive_t [label = "Directive.commit(Tactic)";comment = "";shape = doublecircle;];
            spark_e_directive_t [label = "Directive.serve(Command)";comment = "`/srv/directive`";shape = doublecircle;];
            spark_f_directive_t [label = "Directive.exec(LawOfDirective)";comment = "";shape = doublecircle;];
        }
