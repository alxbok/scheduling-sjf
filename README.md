# scheduling-sjf
Shortest job first scheduling method

Build with

```bash
mvn clean package
```

Run with

```bash
java -jar -Dlogging=on target/scheduling.jar examples/input00.txt
```

Input file is expected to be as follows:

```
3
0 3
1 9
2 6
```

First line denotes the number of tasks/jobs. Remaining lines describe a job, where the first number denotes the arrival time and the second the duration of the job.
