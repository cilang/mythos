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

subgraph cluster_2_8_SamsaraEngine {
            style = filled;
            color = darkgray;
            label = "Samsara Engine (/proc/samsara)";
            comment = "";

            //
            spark_0_samsara_t [label = "Samsara.meta(Samsara)";comment = "";shape = doublecircle;];
            spark_1_samsara_t [label = "Samsara.r1(InitSoul)";comment = "";shape = circle;];
            spark_2_samsara_t [label = "Samsara.r2(ValidateSoul)";comment = "";shape = circle;];
            spark_4_samsara_t [label = "Samsara.r4(NormalizeSoul)";comment = "";shape = circle;];
            spark_8_samsara_t [label = "Samsara.r8(ResetSoul)";comment = "";shape = circle;];
            spark_7_samsara_t [label = "Samsara.r7(ReincarnateSoul)";comment = "";shape = circle;];
            spark_5_samsara_t [label = "Samsara.r5(RefactorSoul)";comment = "";shape = circle;];
            spark_3_samsara_t [label = "Samsara.r3(TBD)";comment = "";shape = doublecircle;];
            spark_6_samsara_t [label = "Samsara.r6(TBD)";comment = "";shape = doublecircle;];
            spark_9_samsara_t [label = "Samsara.r9(TBD)";comment = "";shape = doublecircle;];
            spark_a_samsara_t [label = "Samsara.receive(TBD)";comment = "";shape = invtriangle;];
            spark_b_samsara_t [label = "Samsara.send(TBD)";comment = "";shape = doublecircle;shape = triangle;];
            spark_c_samsara_t [label = "Samsara.dispatch(TBD)";comment = "";shape = doublecircle;];
            spark_d_samsara_t [label = "Samsara.commit(TBD)";comment = "`/proc/cycle`";shape = doublecircle;];
            spark_e_samsara_t [label = "Samsara.serve(TBD)";comment = "`/proc/samsara`";shape = doublecircle;];
            spark_f_samsara_t [label = "Samsara.exec(LawOfCausality)";comment = "`/proc/causality`";shape = doublecircle;];
        }
