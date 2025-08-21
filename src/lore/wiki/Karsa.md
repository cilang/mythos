---
aliases:
tags:
  - grade-0
r0:
ra:
  - "[[Fixation]]"
rb:
  - "[[Excitation]]"
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

subgraph cluster_0_2_Karsa {
            style = filled;
            color = darkgray;
            label = "Karsa";
            comment = "";

            //
            spark_0_karsa_t [label = "Karsa.meta(Karsa)";comment = "";shape = doublecircle;];
            spark_1_karsa_t [label = "Karsa.r1(Pattern)";comment = "";shape = circle;];
            spark_2_karsa_t [label = "Karsa.r2(Momentum)";comment = "";shape = circle;];
            spark_4_karsa_t [label = "Karsa.r4(Space)";comment = "";shape = circle;];
            spark_8_karsa_t [label = "Karsa.r8(Rhythm)";comment = "";shape = circle;];
            spark_7_karsa_t [label = "Karsa.r7(Inertia)";comment = "";shape = circle;];
            spark_5_karsa_t [label = "Karsa.r5(Time)";comment = "";shape = circle;];
            spark_3_karsa_t [label = "Karsa.r3(Birth)";comment = "";shape = doublecircle;];
            spark_6_karsa_t [label = "Karsa.r6(Death)";comment = "";shape = doublecircle;];
            spark_9_karsa_t [label = "Karsa.r9(Life)";comment = "";shape = doublecircle;];
            spark_a_karsa_t [label = "Karsa.receive(Fixation)";comment = "";shape = invtriangle;];
            spark_b_karsa_t [label = "Karsa.send(Excitation)";comment = "";shape = triangle;];
            spark_c_karsa_t [label = "Karsa.dispatch(Initiation)";comment = "";shape = doublecircle;];
            spark_d_karsa_t [label = "Karsa.commit(Continuation)";comment = "";shape = doublecircle;];
            spark_e_karsa_t [label = "Karsa.serve(Reincarnation)";comment = "";shape = doublecircle;];
            spark_f_karsa_t [label = "Karsa.exec(Cycle)";comment = "";shape = doublecircle;];
        }
