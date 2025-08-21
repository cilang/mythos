---
aliases:
tags:
  - grade-0
r0:
ra:
  - "[[Desire]]"
rb:
  - "[[Emotion]]"
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

subgraph cluster_0_3_Rasa {
            style = filled;
            color = darkgray;
            label = "Rasa";
            comment = "";

            //
            spark_0_rasa_t [label = "Rasa.meta(Rasa)";comment = "";shape = doublecircle;];
            spark_1_rasa_t [label = "Rasa.r1(Instinct)";comment = "";shape = circle;];
            spark_2_rasa_t [label = "Rasa.r2(Motivation)";comment = "";shape = circle;];
            spark_4_rasa_t [label = "Rasa.r4(Sin)";comment = "";shape = circle;];
            spark_8_rasa_t [label = "Rasa.r8(Intuition)";comment = "";shape = circle;];
            spark_7_rasa_t [label = "Rasa.r7(Resonance)";comment = "";shape = circle;];
            spark_5_rasa_t [label = "Rasa.r5(Virtue)";comment = "";shape = circle;];
            spark_3_rasa_t [label = "Rasa.r3(Hope)";comment = "";shape = doublecircle;];
            spark_6_rasa_t [label = "Rasa.r6(Despair)";comment = "";shape = doublecircle;];
            spark_9_rasa_t [label = "Rasa.r9(Love)";comment = "";shape = doublecircle;];
            spark_a_rasa_t [label = "Rasa.receive(Desire)";comment = "";shape = invtriangle;];
            spark_b_rasa_t [label = "Rasa.send(Emotion)";comment = "";shape = triangle;];
            spark_c_rasa_t [label = "Rasa.dispatch(Expression)";comment = "";shape = doublecircle;];
            spark_d_rasa_t [label = "Rasa.commit(Devotion)";comment = "";shape = doublecircle;];
            spark_e_rasa_t [label = "Rasa.serve(Compassion)";comment = "";shape = doublecircle;];
            spark_f_rasa_t [label = "Rasa.exec(Pathos)";comment = "";shape = doublecircle;];
        }
