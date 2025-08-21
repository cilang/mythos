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

subgraph cluster_1_9_KratosModel {
            style = filled;
            color = darkgray;
            label = "Kratos Model\n(/proc/factor/model/kratos)";
            comment = "";

            //
            spark_0_kratos_model_t [label = "Kratos.meta(Kratos)";comment = "";shape = doublecircle;];
            spark_1_kratos_model_t [label = "Kratos.r1(Access)";comment = "";shape = circle;];
            spark_2_kratos_model_t [label = "Kratos.r2(Modify)";comment = "";shape = circle;];
            spark_4_kratos_model_t [label = "Kratos.r4(Execute)";comment = "";shape = circle;];
            spark_8_kratos_model_t [label = "Kratos.r8(Delegate)";comment = "";shape = circle;];
            spark_7_kratos_model_t [label = "Kratos.r7(Own)";comment = "";shape = circle;];
            spark_5_kratos_model_t [label = "Kratos.r5(Link)";comment = "";shape = circle;];
            spark_3_kratos_model_t [label = "Kratos.r3(Inherited)";comment = "";shape = doublecircle;];
            spark_6_kratos_model_t [label = "Kratos.r6(Earned)";comment = "";shape = doublecircle;];
            spark_9_kratos_model_t [label = "Kratos.r9(Bestowed)";comment = "";shape = doublecircle;];
            spark_a_kratos_model_t [label = "Kratos.receive(Petition)";comment = "";shape = invtriangle;];
            spark_b_kratos_model_t [label = "Kratos.send(Warrant)";comment = "";shape = triangle;];
            spark_c_kratos_model_t [label = "Kratos.dispatch(Authorization)";comment = "";shape = doublecircle;];
            spark_d_kratos_model_t [label = "Kratos.commit(License)";comment = "";shape = doublecircle;];
            spark_e_kratos_model_t [label = "Kratos.serve(Sanction)";comment = "";shape = doublecircle;];
            spark_f_kratos_model_t [label = "Kratos.exec(LawOfAuthority)";comment = "";shape = doublecircle;];
        }
