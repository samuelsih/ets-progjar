# Hasil Benchmark

## Multithread (unsecure)

- 1000 Request, 10 Concurrency
    ```
    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      10
    Time taken for tests:   375.207 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    2.67 [#/sec] (mean)
    Time per request:       3752.075 [ms] (mean)
    Time per request:       375.207 [ms] (mean, across all concurrent requests)
    Transfer rate:          0.41 [Kbytes/sec] received

    Connection Times (ms)
                min  mean[+/-sd] median   max
    Connect:        0  263 294.4      1    1527
    Processing:  1504 3442 1423.6   3040   10781
    Waiting:       23 3022 1611.5   2550   10476
    Total:       1595 3706 1412.3   3088   10781

    Percentage of the requests served within a certain time (ms)
    50%   3088
    66%   4059
    75%   4583
    80%   4952
    90%   5634
    95%   6409
    98%   7454
    99%   8444
    100%  10781 (longest request)
    ```