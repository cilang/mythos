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

subgraph cluster_2_d_AuthorityEngine {
            style = filled;
            color = darkgray;
            label = "Authority Engine (/srv/authority)";
            comment = "";

            //
            spark_0_authority_t [label = "Authority.meta(Authority)";comment = "";shape = doublecircle;];
            spark_1_authority_t [label = "Authority.r1(InitAuthority)";comment = "";shape = circle;];
            spark_2_authority_t [label = "Authority.r2(ValidateAuthority)";comment = "";shape = circle;];
            spark_4_authority_t [label = "Authority.r4(NormalizeAuthority)";comment = "";shape = circle;];
            spark_8_authority_t [label = "Authority.r8(ResetAuthority)";comment = "";shape = circle;];
            spark_7_authority_t [label = "Authority.r7(EvolveAuthority)";comment = "";shape = circle;];
            spark_5_authority_t [label = "Authority.r5(RefactorAuthority)";comment = "";shape = circle;];
            spark_3_authority_t [label = "Authority.r3(CodexOfAuthority)";comment = "";shape = doublecircle;];
            spark_6_authority_t [label = "Authority.r6(TBD)";comment = "";shape = doublecircle;];
            spark_9_authority_t [label = "Authority.r9(TBD)";comment = "";shape = doublecircle;];
            spark_a_authority_t [label = "Authority.receive(TBD)";comment = "";shape = triangle;];
            spark_b_authority_t [label = "Authority.send(TBD)";comment = "";shape = invtriangle;];
            spark_c_authority_t [label = "Authority.response(TBD)";comment = "";shape = doublecircle;];
            spark_d_authority_t [label = "Authority.compile(TBD)";comment = "";shape = doublecircle;];
            spark_e_authority_t [label = "Authority.serve(TBD)";comment = "`/srv/authority`";shape = doublecircle;];
            spark_f_authority_t [label = "Authority.exec(LawOfAuthority)";comment = "";shape = doublecircle;];
        }
