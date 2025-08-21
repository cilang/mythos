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

subgraph cluster_1_7_PraxisModel {
            style = filled;
            color = darkgray;
            label = "Praxis Model\n(/proc/factor/model/praxis)";
            comment = "This is the How. The model of practical application, technique, and skill.";

            //
            spark_0_praxis_model_t [label = "Praxis.meta(Praxis)";comment = "The fundamental nature of applied power.";shape = doublecircle;];
            spark_1_praxis_model_t [label = "Praxis.r1(Invocation)";comment = "Calling upon an Engine's function.";shape = circle;];
            spark_2_praxis_model_t [label = "Praxis.r2(Transmutation)";comment = "Changing the state of Matter/Energy.";shape = circle;];
            spark_4_praxis_model_t [label = "Praxis.r4(Conjuration)";comment = "Creating something from nothing.";shape = circle;];
            spark_8_praxis_model_t [label = "Praxis.r8(Abjuration)";comment = "Warding, protection, creating boundary.";shape = circle;];
            spark_7_praxis_model_t [label = "Praxis.r7(Divination)";comment = "Querying the system for information.";shape = circle;];
            spark_5_praxis_model_t [label = "Praxis.r5(Enchantment)";comment = "Embedding a function into an object.";shape = circle;];
            spark_3_praxis_model_t [label = "Praxis.r3(Intuition)";comment = "Non-logical grasp of Praxis.";shape = doublecircle;];
            spark_6_praxis_model_t [label = "Praxis.r6(Theory)";comment = "The intellectual framework behind Praxis.";shape = doublecircle;];
            spark_9_praxis_model_t [label = "Praxis.r9(Mastery)";comment = "The synthesis of Intuition and Theory.";shape = doublecircle;];
            spark_a_praxis_model_t [label = "Praxis.receive(Intent)";comment = "";shape = invtriangle;];
            spark_b_praxis_model_t [label = "Praxis.send(Effect)";comment = "";shape = triangle;];
            spark_c_praxis_model_t [label = "Praxis.dispatch(Method)";comment = "";shape = doublecircle;];
            spark_d_praxis_model_t [label = "Praxis.commit(Rote)";comment = "";shape = doublecircle;];
            spark_e_praxis_model_t [label = "Praxis.serve(Ritual)";comment = "";shape = doublecircle;];
            spark_f_praxis_model_t [label = "Praxis.exec(LawOfPraxis)";comment = "";shape = doublecircle;];
        }
