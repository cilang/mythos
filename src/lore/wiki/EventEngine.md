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

subgraph cluster_2_7_EventEngine {
            style = filled;
            color = darkgray;
            label = "Event Engine (/proc/event)";
            comment = "";

            //
            spark_0_event_t [label = "Event.meta(Event)";comment = "";shape = doublecircle;];
            spark_1_event_t [label = "Event.r1(InitEvent)";comment = "";shape = circle;];
            spark_2_event_t [label = "Event.r2(ValidateEvent)";comment = "";shape = circle;];
            spark_4_event_t [label = "Event.r4(NormalizeEvent)";comment = "";shape = circle;];
            spark_8_event_t [label = "Event.r8(ResetEvent)";comment = "";shape = circle;];
            spark_7_event_t [label = "Event.r7(PotentialEvent)";comment = "";shape = circle;];
            spark_5_event_t [label = "Event.r5(ActualEvent)";comment = "";shape = circle;];
            spark_3_event_t [label = "Event.r3(CrestOfOrigin)";comment = "";shape = doublecircle;];
            spark_6_event_t [label = "Event.r6(CrestOfFlow)";comment = "";shape = doublecircle;];
            spark_9_event_t [label = "Event.r9(CrestOfSignificance)";comment = "";shape = doublecircle;];
            spark_a_event_t [label = "Event.receive(PotentialEvent)";comment = "";shape = triangle;];
            spark_b_event_t [label = "Event.send(ActualEvent)";comment = "";shape = invtriangle;];
            spark_c_event_t [label = "Event.dispatch(Routing)";comment = "";shape = doublecircle;];
            spark_d_event_t [label = "Event.commit(Binding)";comment = "";shape = doublecircle;];
            spark_e_event_t [label = "Event.serve(Reflection)";comment = "`/proc/event`";shape = doublecircle;];
            spark_f_event_t [label = "Event.exec(LawOfProbability)";comment = "`/proc/probability`";shape = doublecircle;];
        }
