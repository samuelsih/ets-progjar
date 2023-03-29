# Hasil Benchmark

## Multithread (unsecure)

<details>
    <summary>1000 Request, 10 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      10
    Time taken for tests:   130.945 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.64 [#/sec] (mean)
    Time per request:       1309.448 [ms] (mean)
    Time per request:       130.945 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.19 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0    0   0.4      0       3
    Processing:     3 1279 815.4   1159    4860
    Waiting:        1 1227 788.9   1126    4823
    Total:          3 1279 815.3   1159    4860

    Percentage of the requests served within a certain time (ms)
    50%   1159
    66%   1483
    75%   1743
    80%   1924
    90%   2422
    95%   2758
    98%   3237
    99%   3703
    100%   4860 (longest request)
</details>

<details>
    <summary>1000 Request, 50 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      50
    Time taken for tests:   123.578 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    8.09 [#/sec] (mean)
    Time per request:       6178.891 [ms] (mean)
    Time per request:       123.578 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.26 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0    0   0.4      0       2
    Processing:     8 5756 3378.3   5259   14339
    Waiting:        2 5707 3355.2   5230   14141
    Total:          8 5756 3378.4   5259   14339

    Percentage of the requests served within a certain time (ms)
    50%   5259
    66%   6985
    75%   8347
    80%   8911
    90%  10818
    95%  11606
    98%  12604
    99%  12911
    100%  14339 (longest request)


</details>

<details>
    <summary>1000 Request, 100 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      100
    Time taken for tests:   130.179 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    7.68 [#/sec] (mean)
    Time per request:       13017.905 [ms] (mean)
    Time per request:       130.179 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.19 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0    0   0.4      0       2
    Processing:    18 11602 6892.7  10565   24401
    Waiting:        1 11548 6862.9  10496   24401
    Total:         18 11602 6892.7  10566   24401

    Percentage of the requests served within a certain time (ms)
    50%  10566
    66%  14733
    75%  18170
    80%  19389
    90%  21546
    95%  22539
    98%  23296
    99%  23753
    100%  24401 (longest request)
</details>

<details>
    <summary>1000 Request, 150 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      150
    Time taken for tests:   123.979 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    8.07 [#/sec] (mean)
    Time per request:       18596.790 [ms] (mean)
    Time per request:       123.979 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.25 [Kbytes/sec] received

    Connection Times (ms)
                min  mean[+/-sd] median   max
    Connect:        0    0   0.4      0       2
    Processing:    24 15653 9595.6  14263   36187
    Waiting:        1 15603 9570.2  14187   36053
    Total:         24 15653 9595.6  14263   36189

    Percentage of the requests served within a certain time (ms)
    50%  14263
    66%  20819
    75%  23286
    80%  23884
    90%  29542
    95%  33134
    98%  34088
    99%  34632
    100%  36189 (longest request)
</details>

<details>
    <summary>1000 Request, 200 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      200
    Time taken for tests:   124.776 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    8.01 [#/sec] (mean)
    Time per request:       24955.160 [ms] (mean)
    Time per request:       124.776 [ms] (mean, across all concurrent requests)
    Transfer rate:          1.24 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0    0   0.4      0       2
    Processing:    35 20154 13101.5  19388   42670
    Waiting:        1 20106 13077.5  19296   42474
    Total:         35 20154 13101.6  19388   42670

    Percentage of the requests served within a certain time (ms)
    50%  19388
    66%  28990
    75%  32755
    80%  34554
    90%  37589
    95%  39050
    98%  40403
    99%  40969
    100%  42670 (longest request)
</details>