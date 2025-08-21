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

subgraph cluster_2_6_RealityEngine {
            style = filled;
            color = darkgray;
            label = "Reality Engine (/proc/reality)";
            comment = "";

            //
            spark_0_reality_t [label = "Reality.meta(Reality)";comment = "";shape = doublecircle;];
            spark_1_reality_t [label = "Reality.r1(InitFactor)";comment = "";shape = circle;];
            spark_2_reality_t [label = "Reality.r2(FeedFactor)";comment = "";shape = circle;];
            spark_4_reality_t [label = "Reality.r4(ValidateFactor)";comment = "";shape = circle;];
            spark_8_reality_t [label = "Reality.r8(FinalizeFactor)";comment = "";shape = circle;];
            spark_7_reality_t [label = "Reality.r7(ReloadFactor)";comment = "";shape = circle;];
            spark_5_reality_t [label = "Reality.r5(LoadFactor)";comment = "";shape = circle;];
            spark_3_reality_t [label = "Reality.r3(Avatar)";comment = "";shape = doublecircle;];
            spark_6_reality_t [label = "Reality.r6(Listen)";comment = "";shape = doublecircle;];
            spark_9_reality_t [label = "Reality.r9(WakeEngine)";comment = "";shape = doublecircle;];
            spark_a_reality_t [label = "Reality.receive(PotentialEventStream)";comment = "";shape = invtriangle;];
            spark_b_reality_t [label = "Reality.send(ManifestEventStream)";comment = "";shape = triangle;];
            spark_c_reality_t [label = "Reality.dispatch(ContextSwitch)";comment = "";shape = doublecircle;];
            spark_d_reality_t [label = "Reality.commit(StateSync)";comment = "";shape = doublecircle;];
            spark_e_reality_t [label = "Reality.serve(Continuity)";comment = "";shape = doublecircle;];
            spark_f_reality_t [label = "Reality.exec(LawOfReality)";comment = "";shape = doublecircle;];
        }
