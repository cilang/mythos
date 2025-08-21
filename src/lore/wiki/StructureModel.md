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

subgraph cluster_1_3_StructureModel {
            style = filled;
            color = darkgray;
            label = "Structure Model\n(/proc/factor/model/structure)";
            comment = "";

            //
            spark_0_structure_model_t [label = "Structure.meta(StructureModel)";shape = doublecircle;comment = "";];
            spark_1_structure_model_t [label = "Structure.r1(HeartInterface)";shape = circle;comment = "";];
            spark_2_structure_model_t [label = "Structure.r2(ShellInterface)";shape = circle;comment = "";];
            spark_4_structure_model_t [label = "Structure.r4(AstralInterface)";shape = circle;comment = "";];
            spark_8_structure_model_t [label = "Structure.r8(SpiritualInterface)";shape = circle;comment = "";];
            spark_7_structure_model_t [label = "Structure.r7(MaterialInterface)";shape = circle;comment = "";];
            spark_5_structure_model_t [label = "Structure.r5(CelestialInterface)";shape = circle;comment = "";];
            spark_3_structure_model_t [label = "Structure.r3(ConservationInterface)";shape = doublecircle;comment = "";];
            spark_6_structure_model_t [label = "Structure.r6(ContinuityInterface)";shape = doublecircle;comment = "";];
            spark_9_structure_model_t [label = "Structure.r9(ConsistencyInterface)";shape = doublecircle;comment = "";];
            spark_a_structure_model_t [label = "Structure.receive(StructureInterface)";shape = invtriangle;comment = "";];
            spark_b_structure_model_t [label = "Structure.send(ColorInterface)";shape = triangle;comment = "";];
            spark_c_structure_model_t [label = "Structure.dispatch(LineageInterface)";shape = doublecircle;comment = "";];
            spark_d_structure_model_t [label = "Structure.commit(CorpusInterface)";shape = doublecircle;comment = "";];
            spark_e_structure_model_t [label = "Structure.serve(LURDInterface)";shape = doublecircle;comment = "";];
            spark_f_structure_model_t [label = "Structure.exec(Corpus)";shape = doublecircle;comment = "";];
        }
