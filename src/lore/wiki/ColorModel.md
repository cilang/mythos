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

subgraph cluster_1_4_ColorModel {
            style = filled;
            color = darkgray;
            label = "Color Model\n(/proc/factor/model/color)";
            comment = "";

            //
            spark_0_color_model_t [label = "Color.meta(ColorModel)";comment = "";shape = doublecircle;];
            spark_1_color_model_t [label = "Color.r1(Red)";comment = "";shape = circle;];
            spark_2_color_model_t [label = "Color.r2(Blue)";comment = "";shape = circle;];
            spark_4_color_model_t [label = "Color.r4(Green)";comment = "";shape = circle;];
            spark_8_color_model_t [label = "Color.r8(Cyan)";comment = "";shape = circle;];
            spark_7_color_model_t [label = "Color.r7(Magenta)";comment = "";shape = circle;];
            spark_5_color_model_t [label = "Color.r5(Yellow)";comment = "";shape = circle;];
            spark_3_color_model_t [label = "Color.r3(Black)";comment = "";shape = doublecircle;];
            spark_6_color_model_t [label = "Color.r6(White)";comment = "";shape = doublecircle;];
            spark_9_color_model_t [label = "Color.r9(Gray)";comment = "";shape = doublecircle;];
            spark_a_color_model_t [label = "Color.receive(Gold)";comment = "";shape = invtriangle;];
            spark_b_color_model_t [label = "Color.send(Silver)";comment = "";shape = triangle;];
            spark_c_color_model_t [label = "Color.dispatch(Obsidian-Black)";comment = "";shape = doublecircle;];
            spark_d_color_model_t [label = "Color.commit(Milky-White)";comment = "";shape = doublecircle;];
            spark_e_color_model_t [label = "Color.serve(Amethyst-Violet)";comment = "";shape = doublecircle;];
            spark_f_color_model_t [label = "Color.exec(Rainbow)";comment = "";shape = doublecircle;];
        }
