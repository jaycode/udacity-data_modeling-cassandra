# udacity-data_modeling-cassandra
Submission for Udacity's Data Modeling with Cassandra project.

- [Link to rubric](https://review.udacity.com/#!/rubrics/2475/view)
- [Link to project instructions](https://classroom.udacity.com/nanodegrees/nd027/parts/f7dbb125-87a2-4369-bb64-dc5c21bb668a/modules/c0e48224-f2d0-4bf5-ac02-3e1493e530fc/lessons/8616a226-20fc-4408-ae32-eff0265c0f11/concepts/5601623f-c833-49b8-907b-a606e99d00bb)

To review:

1. Make sure to run supported Java version. In the time of writing, Cassandra only supports Java 8. In Ubuntu 18.04, this is the command that I use: `update-alternatives --config java` then pick the option `java-8`.
2. Run Cassandra server locally with this code: `sudo cassandra -f -R`. The `-f` argument will run Cassandra as a foreground process (instead of a Daemon, which is harder to stop), while `-R` is needed when running as root user.
3. Only then the `Project_1B.ipynb` notebook can be run.

