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

subgraph cluster_2_4_FixationEngine {
            style = filled;
            color = darkgray;
            label = "Fixation Engine (/dev/fixation)";
            comment = "";

            //
            spark_0_fixation_t [label = "Fixation.meta(Fixation)";comment = "Tha";shape = doublecircle;];
            spark_1_fixation_t [label = "Fixation.r1(Focus)";comment = "";shape = circle;];
            spark_2_fixation_t [label = "Fixation.r2(Constraint)";comment = "";shape = circle;];
            spark_4_fixation_t [label = "Fixation.r4(Attachment)";comment = "";shape = circle;];
            spark_8_fixation_t [label = "Fixation.r8(Stability)";comment = "";shape = circle;];
            spark_7_fixation_t [label = "Fixation.r7(Accumulation)";comment = "";shape = circle;];
            spark_5_fixation_t [label = "Fixation.r5(Inheritance)";comment = "";shape = circle;];
            spark_3_fixation_t [label = "Fixation.r3(CrestOfDesire)";comment = "";shape = circle;];
            spark_6_fixation_t [label = "Fixation.r6(CrestOfTransformation)";comment = "";shape = circle;];
            spark_9_fixation_t [label = "Fixation.r9(CrestOfMatter)";comment = "";shape = circle;];
            spark_a_fixation_t [label = "Fixation.receive(RaimentOfFixation)";comment = "";shape = triangle;];
            spark_b_fixation_t [label = "Fixation.send(ArmamentOfFixation)";comment = "";shape = invtriangle;];
            spark_c_fixation_t [label = "Fixation.dispatch(BodyOfFixation)";comment = "";shape = circle;];
            spark_d_fixation_t [label = "Fixation.commit(SoulOfFixation)";comment = "";shape = circle;];
            spark_e_fixation_t [label = "Fixation.serve(GraceOfFixation)";comment = "";shape = circle;];
            spark_f_fixation_t [label = "Fixation.exec(LawOfFixation)";comment = "";shape = circle;];
        }
