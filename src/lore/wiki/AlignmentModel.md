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

subgraph cluster_1_1_AlignmentModel {
            style = filled;
            color = darkgray;
            label = "Alignment Model\n(/proc/factor/model/alignment)";
            comment = "";

            //
            spark_0_alignment_model_t [label = "Alignment.meta(AlignmentModel)";shape = doublecircle;comment = "Raw potential (unformatted).";];
            spark_1_alignment_model_t [label = "Alignment.r1(Causality)";shape = circle;comment = "Planck-time cause/effect links. QFT (S-matrix), Digital Physics";];
            spark_2_alignment_model_t [label = "Alignment.r2(Topology)";shape = circle;comment = "Connectivity (entanglement, wormholes). M-theory (branes), QFT (ER=EPR)";];
            spark_4_alignment_model_t [label = "Alignment.r4(Dimensionality)";shape = circle;comment = "Number of compact/unfolded dimensions. M-theory (Calabi-Yau)";];
            spark_8_alignment_model_t [label = "Alignment.r8(Void)";shape = circle;comment = "Null state (deletion/entropy sink). Information Theory (Landauer) ";];
            spark_7_alignment_model_t [label = "Alignment.r7(Phase)";shape = circle;comment = "Particle/Wave toggle (quantum superposition). QFT (Feynman paths)";];
            spark_5_alignment_model_t [label = "Alignment.r5(Logic)";shape = circle;comment = "Boolean gates (AND/OR/NOT). Digital Physics (Fredkin)";];
            spark_3_alignment_model_t [label = "Alignment.r3(Charge)";shape = circle;comment = "Trinity (+, -, neutral). Fundamental polarity.";];
            spark_6_alignment_model_t [label = "Alignment.r6(Parity)";shape = circle;comment = "Mirroring/negation (e.g., ¬x). Chiral symmetry breaking.";];
            spark_9_alignment_model_t [label = "Alignment.r9(Time)";shape = circle;comment = "Sequential vs. parallel processing. Cyclic flow/termination.";];
            spark_a_alignment_model_t [label = "Alignment.receive(Unity)";shape = triangle;comment = "Cosmic bus (information routing).";];
            spark_b_alignment_model_t [label = "Alignment.send(Diversity)";shape = invtriangle;comment = "Cosmic bus (information routing).";];
            spark_c_alignment_model_t [label = "Alignment.dispatch(Quantization)";shape = doublecircle;comment = "";];
            spark_d_alignment_model_t [label = "Alignment.commit(Superposition)";shape = doublecircle;comment = "";];
            spark_e_alignment_model_t [label = "Alignment.serve(Entanglement)";shape = doublecircle;comment = "";];
            spark_f_alignment_model_t [label = "Alignment.exec(Wavefunction)";shape = doublecircle;comment = "";];
        }
