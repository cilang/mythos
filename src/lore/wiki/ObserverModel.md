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

subgraph cluster_1_0_ObserverModel {
            style = filled;
            color = darkgray;
            label = "Observer Model\n(/proc/factor/model/observer)";
            comment = "";

            //
            spark_0_observer_model_t [label = "Observer.meta(ObserverModel)";shape = doublecircle;comment = "";];
            spark_1_observer_model_t [label = "Observer.r1(Resource)";shape = circle;comment = "";];
            spark_2_observer_model_t [label = "Observer.r2(Authority)";shape = circle;comment = "";];
            spark_4_observer_model_t [label = "Observer.r4(Relation)";shape = circle;comment = "";];
            spark_8_observer_model_t [label = "Observer.r8(Axiom)";shape = circle;comment = "";];
            spark_7_observer_model_t [label = "Observer.r7(Knowledge)";shape = circle;comment = "";];
            spark_5_observer_model_t [label = "Observer.r5(Lineage)";shape = circle;comment = "";];
            spark_3_observer_model_t [label = "Observer.r3(Assumption)";shape = circle;comment = "";];
            spark_6_observer_model_t [label = "Observer.r6(Suggestion)";shape = circle;comment = "";];
            spark_9_observer_model_t [label = "Observer.r9(Perception)";shape = circle;comment = "";];
            spark_a_observer_model_t [label = "Observer.receive(Sangkan)";shape = triangle;comment = "";];
            spark_b_observer_model_t [label = "Observer.send(Paran)";shape = invtriangle;comment = "";];
            spark_c_observer_model_t [label = "Observer.dispatch(Why|Who)";shape = doublecircle;comment = "";];
            spark_d_observer_model_t [label = "Observer.commit(What|How)";shape = doublecircle;comment = "";];
            spark_e_observer_model_t [label = "Observer.serve(When|Where)";shape = doublecircle;comment = "";];
            spark_f_observer_model_t [label = "Observer.exec(Which|Closure)";shape = doublecircle;comment = "";];
        }
