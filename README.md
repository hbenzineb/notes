# notes
Some notes for me
# Configrations Spark
- `--num-executors` = `In this approach, we'll assign one executor per core`
                    = `total-cores-in-cluster`
                    = `num-cores-per-node * total-nodes-in-cluster` 
                    = 16 x 10 = 160
- `--executor-cores`  = 1 (one executor per core)
- `--executor-memory` = `amount of memory per executor`
                      = `mem-per-node/num-executors-per-node`
                      = 64GB/16 = 4GB
