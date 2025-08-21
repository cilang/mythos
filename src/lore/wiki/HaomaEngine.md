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

subgraph cluster_2_a_HaomaEngine {
            style = filled;
            color = darkgray;
            label = "Haoma Engine (/sys/haoma)";
            comment = "";

            //
            spark_0_haoma_t [label = "Haoma.meta(Haoma)";comment = "";shape = doublecircle;];
            spark_1_haoma_t [label = "Haoma.r1(TBD)";comment = "";shape = circle;];
            spark_2_haoma_t [label = "Haoma.r2(TBD)";comment = "";shape = circle;];
            spark_4_haoma_t [label = "Haoma.r4(TBD)";comment = "";shape = circle;];
            spark_8_haoma_t [label = "Haoma.r8(TBD)";comment = "";shape = circle;];
            spark_7_haoma_t [label = "Haoma.r7(TBD)";comment = "";shape = circle;];
            spark_5_haoma_t [label = "Haoma.r5(TBD)";comment = "";shape = circle;];
            spark_3_haoma_t [label = "Haoma.r3(TBD)";comment = "`/sys/lurd`";shape = doublecircle;];
            spark_6_haoma_t [label = "Haoma.r6(TBD)";comment = "";shape = doublecircle;];
            spark_9_haoma_t [label = "Haoma.r9(TBD)";comment = "";shape = doublecircle;];
            spark_a_haoma_t [label = "Haoma.receive(Blueprint)";comment = "";shape = triangle;];
            spark_b_haoma_t [label = "Haoma.send(Instance)";comment = "";shape = invtriangle;];
            spark_c_haoma_t [label = "Haoma.dispatch(Materialization)";comment = "";shape = doublecircle;];
            spark_d_haoma_t [label = "Haoma.commit(Initialization)";comment = "";shape = doublecircle;];
            spark_e_haoma_t [label = "Haoma.serve(Animation)";comment = "`/sys/haoma`";shape = doublecircle;];
            spark_f_haoma_t [label = "Haoma.exec(LawOfFactor)";comment = "";shape = doublecircle;];
        }
