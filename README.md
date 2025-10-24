# MythOS: A Cilang Cosmology

> **Where hard sci-fi meets high fantasy through computational topology**

<a href="https://github.com/cilang/mythos/issues">
  <img src="https://img.shields.io/github/issues/cilang/mythos">
</a>
<a href="https://github.com/cilang/mythos/network">
  <img src="https://img.shields.io/github/forks/cilang/mythos">
</a>
<a href="https://github.com/cilang/mythos/stargazers">
  <img src="https://img.shields.io/github/stars/cilang/mythos">
</a>
<a href="https://github.com/cilang/mythos/blob/main/license">
  <img src="https://img.shields.io/github/license/cilang/mythos">
</a>
<br>
<br>

## 🎯 What is MythOS?

**MythOS** is a **Fictional Cosmology** that use **Cilang Topology** and **Cilang Space** as its **First Principle**.

### Cilang Space

**Mathematical Definition:**

S = {(x,y,z,w) ∈ ℝ⁴ | x² + y² + z² + w² = 1}

w ∈ [w₀, w₁, w₂, ..., w₁₅]

**Probability Quantization:**

- Requirement: `2n+1`
- Distribution: Balanced Ternary `n-1-n` across [-1, 0, +1]
- Default: `n = 180` = 361 steps total with Distribution: [-1,0,+1] = [180, 1, 180] steps

### Cilang Topology

**Invariant Structure:**

- 16 Spark vertices: `{0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f}`
- 35 Arc edges with 3 morphism types: `{IN, OUT, REC}`
- Fixed relational patterns

**Template:**

```dot
strict digraph Cilang {
    style = filled;
    color = lightgray;
    node [shape = circle; style = filled; color = lightgreen;];
    edge [color = darkgray;];
    label = "{{Name}}";
    comment = "{{descriptions}}";

    spark_0_t [label = "{{Name}}.meta({{meta}})";comment = "Abstract: {{descriptions}}";shape = doublecircle;color = darkgray;];
    spark_1_t [label = "{{Name}}.r1({{title}})";comment = "Initiation: {{descriptions}}";color = darkgreen;];
    spark_2_t [label = "{{Name}}.r2({{title}})";comment = "Response: {{descriptions}}";color = darkgreen;];
    spark_4_t [label = "{{Name}}.r4({{title}})";comment = "Integration: {{descriptions}}";color = darkgreen;];
    spark_8_t [label = "{{Name}}.r8({{title}})";comment = "Reflection: {{descriptions}}";color = darkgreen;];
    spark_7_t [label = "{{Name}}.r7({{title}})";comment = "Consolidation: {{descriptions}}";color = darkgreen;];
    spark_5_t [label = "{{Name}}.r5({{title}})";comment = "Propagation: {{descriptions}}";color = darkgreen;];
    spark_3_t [label = "{{Name}}.r3({{title}})";comment = "Thesis: {{descriptions}}";color = darkblue;];
    spark_6_t [label = "{{Name}}.r6({{title}})";comment = "Antithesis: {{descriptions}}";color = darkblue;];
    spark_9_t [label = "{{Name}}.r9({{title}})";comment = "Synthesis: {{descriptions}}";color = darkblue;];
    spark_a_t [label = "{{Name}}.receive({{title}})";comment = "Potential: {{descriptions}}";shape = invtriangle;color = darkred;];
    spark_b_t [label = "{{Name}}.send({{title}})";comment = "Manifest: {{descriptions}}";shape = triangle;color = darkred;];
    spark_c_t [label = "{{Name}}.dispatch({{title}})";comment = "Why-Who: {{descriptions}}";shape = doublecircle;color = darkred;];
    spark_d_t [label = "{{Name}}.commit({{title}})";comment = "What-How: {{descriptions}}";shape = doublecircle;color = darkgreen;];
    spark_e_t [label = "{{Name}}.serve({{title}})";comment = "When-Where: {{descriptions}}";shape = doublecircle;color = darkblue;];
    spark_f_t [label = "{{Name}}.exec({{title}})";comment = "Which-Closure: {{descriptions}}";shape = doublecircle;color = lightgray;];

    spark_a_t -> spark_0_t [label = "IN"; comment = "{{descriptions}}"; color = darkred; constraint = false;];
    spark_0_t -> spark_b_t [label = "OUT"; comment = "{{descriptions}}"; color = darkred;];
    spark_0_t -> spark_3_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    spark_0_t -> spark_6_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    spark_0_t -> spark_9_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    spark_0_t -> spark_1_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_0_t -> spark_2_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_0_t -> spark_4_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_0_t -> spark_8_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_0_t -> spark_7_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_0_t -> spark_5_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];

    spark_a_t -> spark_c_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    spark_b_t -> spark_c_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    spark_1_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_2_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_4_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_8_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_7_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_5_t -> spark_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_3_t -> spark_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    spark_6_t -> spark_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    spark_9_t -> spark_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];

    spark_1_t -> spark_2_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_2_t -> spark_4_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_4_t -> spark_8_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_8_t -> spark_7_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_7_t -> spark_5_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_5_t -> spark_1_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    spark_3_t -> spark_6_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    spark_6_t -> spark_9_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    spark_9_t -> spark_3_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    spark_a_t -> spark_b_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both; style = dashed; constraint = false;];

    spark_c_t -> spark_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    spark_d_t -> spark_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    spark_e_t -> spark_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
}
```

![Image](src/specs/sparklet/sparklet.svg)

---

### The Brunnian Link and Borromean Rings

The **Brunnian Link** and **Borromean Rings** is important to optimize things from Knot Theory things.

Oh! Almost forgot, The **Cilang Topology** is just one amongst hypothetically who-knows-how-many _Invariant Topology_ that inhabits **Cilang Space**.

Explore it through Brunnian Link and you might found various things that are interesting.

Because in Cilang Topology;

- the spark_d_t (commit) is dependent on the results of spark_[1,2,4,8,7,5]_t (6-Link Brunnian Logic)
- spark_e_t (serve) is dependent on the results of spark_[3,6,9]_t (Borromean Logic)
- the spark_0_t (meta) is dependent on the results of spark_[1-9,a,b]_t (11-Link Brunnian Logic)
- spark_c_t (dispatch) is dependent on the results of spark_[a,b]_t (2-Link Brunnian Logic or Vesica Pisces Logic)
- then spark_f_t (Closure) is dependent on the results of spark_[c,d,e]_t (Borromean Logic).

The **Cilang Framework** uses **Brunnian Link** dependencies to ensure Dynamic Formal Verification (DFV) across all processes. Critical synthesis points are governed by the **Borromean Link** (the 6^3_2 Brunnian), while the origin point requires the dual-source integrity defined by the **Vesica Pisces**.

I often used this [Prompt Header](https://github.com/cilang/mythos/blob/master/src%2Fspecs%2Fsparklet%2Fmythos_prompt.txt) when talking with AI.

## Prior Art Declaration

This specification documents prior art for:

- Cilang Topology (16-vertex, 35-edge computational graph)
- Cilang Space (3-sphere constrained manifold with 16-fold w-multiplex)
- Balanced ternary quantization with 361 probability multitudes

## License

<a href="https://opensource.org/licenses/MIT">
  <img align="right" height="96" alt="MIT License" src="meta/shared/mit-license.png" />
</a>

The MythOS are licensed under the **MIT License**.

The full text of the license can be accessed via [this link](https://opensource.org/licenses/MIT) and is also included in the [license](LICENCE) file of this software package.
