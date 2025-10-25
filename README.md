# MythOS: An Objectives Relational Cosmos

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

- Requirement: `3n+1` or `19ⁿ`
- Distribution: [f(n), f(n)+1, f(n)] where f(n) = (19ⁿ - 1)/3
- Default: `n = 120` = 361 steps total with Distribution: [-1,0,+1] = [120, 121, 120] steps

### Cilang Topology

**Invariant Structure:**

- 16 Cilang vertices: `{0,1,2,3,4,5,6,7,8,9,a,b,c,d,e,f}`
- 35 Usepong edges with 3 morphism types: `{IN, OUT, REC}`
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

    cilang_0_t [label = "{{Name}}.meta({{meta}})";comment = "Abstract: {{descriptions}}";shape = doublecircle;color = darkgray;];
    cilang_1_t [label = "{{Name}}.r1({{title}})";comment = "Initiation: {{descriptions}}";color = darkgreen;];
    cilang_2_t [label = "{{Name}}.r2({{title}})";comment = "Response: {{descriptions}}";color = darkgreen;];
    cilang_4_t [label = "{{Name}}.r4({{title}})";comment = "Integration: {{descriptions}}";color = darkgreen;];
    cilang_8_t [label = "{{Name}}.r8({{title}})";comment = "Reflection: {{descriptions}}";color = darkgreen;];
    cilang_7_t [label = "{{Name}}.r7({{title}})";comment = "Consolidation: {{descriptions}}";color = darkgreen;];
    cilang_5_t [label = "{{Name}}.r5({{title}})";comment = "Propagation: {{descriptions}}";color = darkgreen;];
    cilang_3_t [label = "{{Name}}.r3({{title}})";comment = "Thesis: {{descriptions}}";color = darkblue;];
    cilang_6_t [label = "{{Name}}.r6({{title}})";comment = "Antithesis: {{descriptions}}";color = darkblue;];
    cilang_9_t [label = "{{Name}}.r9({{title}})";comment = "Synthesis: {{descriptions}}";color = darkblue;];
    cilang_a_t [label = "{{Name}}.receive({{title}})";comment = "Potential: {{descriptions}}";shape = invtriangle;color = darkred;];
    cilang_b_t [label = "{{Name}}.send({{title}})";comment = "Manifest: {{descriptions}}";shape = triangle;color = darkred;];
    cilang_c_t [label = "{{Name}}.dispatch({{title}})";comment = "Why-Who: {{descriptions}}";shape = doublecircle;color = darkred;];
    cilang_d_t [label = "{{Name}}.commit({{title}})";comment = "What-How: {{descriptions}}";shape = doublecircle;color = darkgreen;];
    cilang_e_t [label = "{{Name}}.serve({{title}})";comment = "When-Where: {{descriptions}}";shape = doublecircle;color = darkblue;];
    cilang_f_t [label = "{{Name}}.exec({{title}})";comment = "Which-Closure: {{descriptions}}";shape = doublecircle;color = lightgray;];

    cilang_a_t -> cilang_0_t [label = "IN"; comment = "{{descriptions}}"; color = darkred; constraint = false;];
    cilang_0_t -> cilang_b_t [label = "OUT"; comment = "{{descriptions}}"; color = darkred;];
    cilang_0_t -> cilang_3_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    cilang_0_t -> cilang_6_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    cilang_0_t -> cilang_9_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    cilang_0_t -> cilang_1_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_0_t -> cilang_2_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_0_t -> cilang_4_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_0_t -> cilang_8_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_0_t -> cilang_7_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_0_t -> cilang_5_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];

    cilang_a_t -> cilang_c_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    cilang_b_t -> cilang_c_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    cilang_1_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_2_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_4_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_8_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_7_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_5_t -> cilang_d_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_3_t -> cilang_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    cilang_6_t -> cilang_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
    cilang_9_t -> cilang_e_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];

    cilang_1_t -> cilang_2_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_2_t -> cilang_4_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_4_t -> cilang_8_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_8_t -> cilang_7_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_7_t -> cilang_5_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_5_t -> cilang_1_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both; style = dashed; constraint = false;];
    cilang_3_t -> cilang_6_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    cilang_6_t -> cilang_9_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    cilang_9_t -> cilang_3_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both; style = dashed; constraint = false;];
    cilang_a_t -> cilang_b_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both; style = dashed; constraint = false;];

    cilang_c_t -> cilang_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkred; dir = both;];
    cilang_d_t -> cilang_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkgreen; dir = both;];
    cilang_e_t -> cilang_f_t [label = "REC"; comment = "{{descriptions}}"; color = darkblue; dir = both;];
}
```

![Image](src/specs/sparklet/sparklet.svg)

---

### The Brunnian Link and Borromean Rings

The **Brunnian Link** and **Borromean Rings** is used in dependency management of a Factor.

- cilang_d_t (commit) is dependent on the results of cilang_[1,2,4,8,7,5]_t (6-Link Brunnian Dependency)
- cilang_e_t (serve) is dependent on the results of cilang_[3,6,9]_t (Borromean Dependency)
- cilang_0_t (meta) is dependent on the results of cilang_[1-9,a,b]_t (11-Link Brunnian Dependency)
- cilang_c_t (dispatch) is dependent on the results of cilang_[a,b]_t (2-Link Brunnian Dependency or Vesica Pisces Dependency)
- cilang_f_t (exec) is dependent on the results of cilang_[c,d,e]_t (Borromean Dependency).

I often used this [Prompt Header](src/specs/prompt-header.md) when talking with AI.

## License

<a href="https://opensource.org/licenses/MIT">
  <img align="right" height="96" alt="MIT License" src="meta/shared/mit-license.png" />
</a>

The MythOS are licensed under the **MIT License**.

The full text of the license can be accessed via [this link](https://opensource.org/licenses/MIT) and is also included in the [license](LICENCE) file of this software package.
