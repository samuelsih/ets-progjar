# Hasil Benchmark

## Multithread (unsecure)

<details>
    <summary>1000 Request, 10 Concurrency</summary>

    Concurrency Level:      10
    Time taken for tests:   142.091 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.04 [#/sec] (mean)
    Time per request:       1420.910 [ms] (mean)
    Time per request:       142.091 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.09 [Kbytes/sec] received

    Connection Times (ms)
                min  mean[+/-sd] median   max
    Connect:        0   30 119.0      0     526
    Processing:   276 1353 716.3   1137    3724
    Waiting:        2 1263 723.4   1079    3703
    Total:        276 1383 704.7   1156    3724

    Percentage of the requests served within a certain time (ms)
    50%   1156
    66%   1540
    75%   1850
    80%   2058
    90%   2414
    95%   2731
    98%   3136
    99%   3440
    100%   3724 (longest request)
</details>

<details>
    <summary>1000 Request, 50 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      50
    Time taken for tests:   137.166 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.29 [#/sec] (mean)
    Time per request:       6858.285 [ms] (mean)
    Time per request:       137.166 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.13 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  132 230.1      0    1025
    Processing:  1543 6416 2508.1   5133   12763
    Waiting:        1 4842 2574.8   4111   12232
    Total:       2057 6548 2552.6   5591   13263

    Percentage of the requests served within a certain time (ms)
    50%   5591
    66%   7635
    75%   8651
    80%   8701
    90%  10728
    95%  11739
    98%  12256
    99%  12750
    100%  13263 (longest request)

</details>

<details>
    <summary>1000 Request, 100 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      100
    Time taken for tests:   133.409 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.50 [#/sec] (mean)
    Time per request:       13340.862 [ms] (mean)
    Time per request:       133.409 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.16 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  128 227.8      0    2034
    Processing:  1541 12292 4502.9  10711   21022
    Waiting:        2 7043 4320.7   6152   19984
    Total:       1858 12419 4533.3  10711   21022

    Percentage of the requests served within a certain time (ms)
    50%  10711
    66%  13760
    75%  16382
    80%  17930
    90%  19966
    95%  20008
    98%  20508
    99%  21004
    100%  21022 (longest request)
</details>

<details>
    <summary>1000 Request, 150 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      150
    Time taken for tests:   130.724 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.65 [#/sec] (mean)
    Time per request:       19608.636 [ms] (mean)
    Time per request:       130.724 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.19 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  126 223.2      0    1029
    Processing:  1361 17898 6376.3  15821   29127
    Waiting:        1 10090 6392.8   9163   28109
    Total:       1362 18023 6396.1  15846   29625

    Percentage of the requests served within a certain time (ms)
    50%  15846
    66%  20841
    75%  22974
    80%  25533
    90%  28072
    95%  28580
    98%  29087
    99%  29124
    100%  29625 (longest request)
</details>

<details>
    <summary>1000 Request, 200 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      200
    Time taken for tests:   137.814 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.26 [#/sec] (mean)
    Time per request:       27562.893 [ms] (mean)
    Time per request:       137.814 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.13 [Kbytes/sec] received

    Connection Times (ms)
                min  mean[+/-sd] median   max
    Connect:        0  133 224.7      0    1015
    Processing:  2077 24837 8547.0  24583   41417
    Waiting:        1 13571 8494.8  12275   37340
    Total:       2189 24969 8556.0  25092   41417

    Percentage of the requests served within a certain time (ms)
    50%  25092
    66%  29114
    75%  31093
    80%  33608
    90%  37302
    95%  38827
    98%  40385
    99%  40903
    100%  41417 (longest request)
</details>