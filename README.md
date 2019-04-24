# Mandrake App Hadoop Configs
In this repo we store the configurations used for the experiments in our paper 'Mandrake: Implementing Durabilty for Edge Clouds'. It contains all files in the etc folder of our Hadoop setup, however the most notable files are core-site.xml, hdfs-site.xml, mapred-site.xml, yarn-site.sml, and hadoop-env.sh.

Note that this setup is for the Replica Mover experiments. The experiment categories without the Replica Mover used identical configs, but with the 'dfs.namenode.redundancy.interval.seconds' removed from hdfs-site.xml.
