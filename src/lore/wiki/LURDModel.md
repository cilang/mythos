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

subgraph cluster_1_6_LURDModel {
            style = filled;
            color = darkgray;
            label = "LURD (Layered Universal Recursion Descriptor) Model\n(/proc/factor/model/lurd)";
            comment = "";

            //
            spark_0_lurd_model_t [label = "LURD.meta(LURDModel)";comment = "";shape = doublecircle;];
            spark_1_lurd_model_t [label = "LURD.r1(BraneDescriptor)";comment = "";shape = circle;];
            spark_2_lurd_model_t [label = "LURD.r2(CosmicDescriptor)";comment = "";shape = circle;];
            spark_4_lurd_model_t [label = "LURD.r4(StellarDescriptor)";comment = "";shape = circle;];
            spark_8_lurd_model_t [label = "LURD.r8(PlanarDescriptor)";comment = "";shape = circle;];
            spark_7_lurd_model_t [label = "LURD.r7(CradleDescriptor)";comment = "";shape = circle;];
            spark_5_lurd_model_t [label = "LURD.r5(MythogenicDescriptor)";comment = "";shape = circle;];
            spark_3_lurd_model_t [label = "LURD.r3(MaterialEssence)";comment = "";shape = doublecircle;];
            spark_6_lurd_model_t [label = "LURD.r6(SpiritualEssence)";comment = "";shape = doublecircle;];
            spark_9_lurd_model_t [label = "LURD.r9(InformationEssence)";comment = "";shape = doublecircle;];
            spark_a_lurd_model_t [label = "LURD.receive(DirectiveDescriptor)";comment = "";shape = invtriangle;];
            spark_b_lurd_model_t [label = "LURD.send(OriginDescriptor)";comment = "";shape = triangle;];
            spark_c_lurd_model_t [label = "LURD.dispatch(InterfaceDescriptor)";comment = "";shape = doublecircle;];
            spark_d_lurd_model_t [label = "LURD.commit(DigitalDescriptor)";comment = "";shape = doublecircle;];
            spark_e_lurd_model_t [label = "LURD.serve(ManifestDescriptor)";comment = "";shape = doublecircle;];
            spark_f_lurd_model_t [label = "LURD.exec(Factor)";comment = "";shape = doublecircle;];
        }
