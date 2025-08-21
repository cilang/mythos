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

subgraph cluster_2_b_CapabilityEngine {
            style = filled;
            color = darkgray;
            label = "Capability Engine (/sys/capability)";
            comment = "";

            //
            spark_0_capability_t [label = "Capability.meta(Capability)";comment = "";shape = doublecircle;];
            spark_1_capability_t [label = "Capability.r1(ParseCapability)";comment = "";shape = circle;];
            spark_2_capability_t [label = "Capability.r2(ValidateCapability)";comment = "";shape = circle;];
            spark_4_capability_t [label = "Capability.r4(NormalizeCapability)";comment = "";shape = circle;];
            spark_8_capability_t [label = "Capability.r8(ResetCapability)";comment = "";shape = circle;];
            spark_7_capability_t [label = "Capability.r7(EvolveCapability)";comment = "";shape = circle;];
            spark_5_capability_t [label = "Capability.r5(RefactorCapability)";comment = "";shape = circle;];
            spark_3_capability_t [label = "Capability.r3(CodexOfCapability)";comment = "`/sys/codex`";];
            spark_6_capability_t [label = "Capability.r6(TBD)";comment = "";shape = doublecircle;];
            spark_9_capability_t [label = "Capability.r9(TBD)";comment = "";shape = doublecircle;];
            spark_a_capability_t [label = "Capability.receive(TBD)";comment = "";shape = triangle;];
            spark_b_capability_t [label = "Capability.send(TBD)";comment = "";shape = invtriangle;];
            spark_c_capability_t [label = "Capability.response(TBD)";comment = "";shape = doublecircle;];
            spark_d_capability_t [label = "Capability.compile(TBD)";comment = "";shape = doublecircle;];
            spark_e_capability_t [label = "Capability.serve(TBD)";comment = "`/sys/capability`";shape = doublecircle;];
            spark_f_capability_t [label = "Capability.exec(LawOfCapability)";comment = "Law of Capability";shape = doublecircle;];
        }
