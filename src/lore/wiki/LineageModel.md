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

subgraph cluster_1_5_LineageModel {
            style = filled;
            color = darkgray;
            label = "Lineage Model\n(/proc/factor/model/lineage)";
            comment = "";

            //
            spark_0_lineage_model_t [label = "Lineage.meta(LineageModel)";comment = "";shape = doublecircle;];
            spark_1_lineage_model_t [label = "Lineage.r1(InsectLineage)";comment = "People of Truth";shape = circle;];
            spark_2_lineage_model_t [label = "Lineage.r2(NawangLineage)";comment = "People of Convergence";shape = circle;];
            spark_4_lineage_model_t [label = "Lineage.r4(ChimeraLineage)";comment = "People of Fixation";shape = circle;];
            spark_8_lineage_model_t [label = "Lineage.r8(WormLineage)";comment = "People of Wisdom";shape = circle;];
            spark_7_lineage_model_t [label = "Lineage.r7(PawangLineage)";comment = "People of Divergence";shape = circle;];
            spark_5_lineage_model_t [label = "Lineage.r5(SerpentineLineage)";comment = "People of Excitation";shape = circle;];
            spark_3_lineage_model_t [label = "Lineage.r3(ArachnidLineage)";comment = "People of Asha";shape = doublecircle;];
            spark_6_lineage_model_t [label = "Lineage.r6(AvesixLineage)";comment = "People of Vikara";shape = doublecircle;];
            spark_9_lineage_model_t [label = "Lineage.r9(DraconisLineage)";comment = "People of Karsa";shape = doublecircle;];
            spark_a_lineage_model_t [label = "Lineage.receive(MineralLineage)";comment = "People of Essence";shape = invtriangle;];
            spark_b_lineage_model_t [label = "Lineage.send(PlantLineage)";comment = "People of Presence";shape = triangle;];
            spark_c_lineage_model_t [label = "Lineage.dispatch(VulpineLineage)";comment = "People of Desire";shape = doublecircle;];
            spark_d_lineage_model_t [label = "Lineage.commit(FelixaLineage)";comment = "People of Rasa";shape = doublecircle;];
            spark_e_lineage_model_t [label = "Lineage.serve(CanineLineage)";comment = "People of Emotion";shape = doublecircle;];
            spark_f_lineage_model_t [label = "Lineage.exec(WorldTreeLineage)";comment = "People of Emergence";shape = doublecircle;];
        }
