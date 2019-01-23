# Mandrake App Hadoop Configs
In this repo we store the configurations used for the experiments in our Mandrake paper. In the TeraSort configs, we notably significantly decreased yarn.nm.liveness-monitor.expiry-interval-ms in yarn-site.xml.

Note that both of these configs are set up for the Replica Mover experiments. The experiment categories without the Replica Mover used identical configs, but with dfs.namenode.redundancy.interval.seconds removed in hdfs-site.xml (thereby setting it to the default of 3 seconds).
