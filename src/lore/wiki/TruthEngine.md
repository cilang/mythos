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

subgraph cluster_2_0_TruthEngine {
            style = filled;
            color = darkgray;
            label = "Truth Engine (/dev/truth)";
            comment = "";

            //
            spark_0_truth_t [label = "Truth.meta(Truth)";comment = "Asha";shape = doublecircle;];
            spark_1_truth_t [label = "Truth.r1(Verification)";comment = "";shape = circle;];
            spark_2_truth_t [label = "Truth.r2(Evidence)";comment = "";shape = circle;];
            spark_4_truth_t [label = "Truth.r4(Definition)";comment = "";shape = circle;];
            spark_8_truth_t [label = "Truth.r8(Consistency)";comment = "";shape = circle;];
            spark_7_truth_t [label = "Truth.r7(Recognition)";comment = "";shape = circle;];
            spark_5_truth_t [label = "Truth.r5(Authenticity)";comment = "";shape = circle;];
            spark_3_truth_t [label = "Truth.r3(CrestOfObjectivity)";comment = "";shape = circle;];
            spark_6_truth_t [label = "Truth.r6(CrestOfBoundary)";comment = "";shape = circle;];
            spark_9_truth_t [label = "Truth.r9(CrestOfClarity)";comment = "";shape = circle;];
            spark_a_truth_t [label = "Truth.receive(RaimentOfTruth)";comment = "";shape = triangle;];
            spark_b_truth_t [label = "Truth.send(ArmamentOfTruth)";comment = "";shape = invtriangle;];
            spark_c_truth_t [label = "Truth.dispatch(BodyOfTruth)";comment = "";shape = circle;];
            spark_d_truth_t [label = "Truth.commit(SoulOfTruth)";comment = "";shape = circle;];
            spark_e_truth_t [label = "Truth.serve(GraceOf)";comment = "";shape = circle;];
            spark_f_truth_t [label = "Truth.exec(LawOfTruth)";comment = "";shape = circle;];
        }
