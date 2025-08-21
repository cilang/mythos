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

subgraph cluster_2_9_RepositoryEngine {
            style = filled;
            color = darkgray;
            label = "Repository Engine (/sys/repository)";
            comment = "";

            //
            spark_0_repository_t [label = "Repository.meta(Repository)";comment = "";shape = doublecircle;];
            spark_1_repository_t [label = "Repository.r1(Cache)";comment = "";shape = circle;];
            spark_2_repository_t [label = "Repository.r2(Registry)";comment = "";shape = circle;];
            spark_4_repository_t [label = "Repository.r4(Archive)";comment = "";shape = circle;];
            spark_8_repository_t [label = "Repository.r8(Buffer)";comment = "";shape = circle;];
            spark_7_repository_t [label = "Repository.r7(Database)";comment = "";shape = circle;];
            spark_5_repository_t [label = "Repository.r5(Memory)";comment = "";shape = circle;];
            spark_3_repository_t [label = "Repository.r3(Codex)";comment = "";shape = doublecircle;];
            spark_6_repository_t [label = "Repository.r6(Log)";comment = "";shape = doublecircle;];
            spark_9_repository_t [label = "Repository.r9(Template)";comment = "";shape = doublecircle;];
            spark_a_repository_t [label = "Repository.receive(Sub)";comment = "";shape = triangle;];
            spark_b_repository_t [label = "Repository.send(Pub)";comment = "";shape = invtriangle;];
            spark_c_repository_t [label = "Repository.dispatch(Query)";comment = "";shape = doublecircle;];
            spark_d_repository_t [label = "Repository.commit(Transaction)";comment = "";shape = doublecircle;];
            spark_e_repository_t [label = "Repository.serve(Replication)";comment = "";shape = doublecircle;];
            spark_f_repository_t [label = "Repository.exec(LawOfPersistence)";comment = "";shape = doublecircle;];
        }
