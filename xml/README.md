# xml benchmark

Parses a protein database in a semi-stream manner where it parses a subtree for a single protein to a DOM using the Java API for XML Processing (JAXP).

Download Database
```
chmod +x download.sh
bash download.sh
```

Compile code
```
chmod +x compile.sh
bash compile.sh
```

Run benchmark with default options
```
chmod +x run.sh
bash run.sh
```

Run benchmark with different options
```
Usage: java -Xms5000m -Xmx5000m Main [options] [path/to/dataset]
  -r  NROUNDS  number of rounds of benchmark
  -t  NTHREADS number of threads
```
