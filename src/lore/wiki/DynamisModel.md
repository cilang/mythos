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

subgraph cluster_1_8_DynamisModel {
            style = filled;
            color = darkgray;
            label = "Dynamis Model\n(/proc/factor/model/dynamis)";
            comment = "This is the Fuel. The model of potential and resources.";

            //
            spark_0_dynamis_model_t [label = "Dynamis.meta(Dynamis)";comment = "The fundamental nature of energetic resources.";shape = doublecircle;];
            spark_1_dynamis_model_t [label = "Dynamis.r1(Mana)";comment = "";shape = circle;];
            spark_2_dynamis_model_t [label = "Dynamis.r2(Stamina)";comment = "";shape = circle;];
            spark_4_dynamis_model_t [label = "Dynamis.r4(Arcane)";comment = "";shape = circle;];
            spark_8_dynamis_model_t [label = "Dynamis.r8(Entropic)";comment = "";shape = circle;];
            spark_7_dynamis_model_t [label = "Dynamis.r7(Spiritual)";comment = "";shape = circle;];
            spark_5_dynamis_model_t [label = "Dynamis.r5(Elemental)";comment = "";shape = circle;];
            spark_3_dynamis_model_t [label = "Dynamis.r3(Reserve)";comment = "";shape = doublecircle;];
            spark_6_dynamis_model_t [label = "Dynamis.r6(Flow)";comment = "";shape = doublecircle;];
            spark_9_dynamis_model_t [label = "Dynamis.r9(Potency)";comment = "";shape = doublecircle;];
            spark_a_dynamis_model_t [label = "Dynamis.receive(Potential)";comment = "";shape = invtriangle;];
            spark_b_dynamis_model_t [label = "Dynamis.send(Current)";comment = "";shape = triangle;];
            spark_c_dynamis_model_t [label = "Dynamis.dispatch(Channel)";comment = "";shape = doublecircle;];
            spark_d_dynamis_model_t [label = "Dynamis.commit(Reservoir)";comment = "";shape = doublecircle;];
            spark_e_dynamis_model_t [label = "Dynamis.serve(Conduit)";comment = "";shape = doublecircle;];
            spark_f_dynamis_model_t [label = "Dynamis.exec(LawOfConservation)";comment = "";shape = doublecircle;];
        }
