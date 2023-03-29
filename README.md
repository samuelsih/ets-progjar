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
    Time taken for tests:   364.697 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    2.74 [#/sec] (mean)
    Time per request:       36469.745 [ms] (mean)
    Time per request:       364.697 [ms] (mean, across all concurrent requests)
    Transfer rate:          0.43 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  358 325.5    502    1531
    Processing:  3073 34285 10232.6  32928   57075
    Waiting:        2 18354 10898.9  17283   52023
    Total:       3584 34643 10282.4  33108   58091

    Percentage of the requests served within a certain time (ms)
    50%  33108
    66%  37643
    75%  44643
    80%  46713
    90%  48626
    95%  52488
    98%  55013
    99%  56548
    100%  58091 (longest request)
</details>

<details>
    <summary>1000 Request, 150 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      150
    Time taken for tests:   360.419 seconds
    Complete requests:      1000
    Failed requests:        1
    (Connect: 0, Receive: 0, Length: 1, Exceptions: 0)
    Write errors:           1
    Total transferred:      158841 bytes
    HTML transferred:       21978 bytes
    Requests per second:    2.77 [#/sec] (mean)
    Time per request:       54062.871 [ms] (mean)
    Time per request:       360.419 [ms] (mean, across all concurrent requests)
    Transfer rate:          0.43 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  353 324.3    502    2044
    Processing:     1 50029 15734.2  47032   79687
    Waiting:        3 27806 16659.9  26471   70464
    Total:          1 50383 15769.3  47303   80711

    Percentage of the requests served within a certain time (ms)
    50%  47303
    66%  58170
    75%  62688
    80%  66826
    90%  73541
    95%  77161
    98%  78168
    99%  79175
    100%  80711 (longest request)
</details>

<details>
    <summary>1000 Request, 200 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      200
    Time taken for tests:   346.334 seconds
    Complete requests:      1000
    Failed requests:        0
    Total transferred:      159000 bytes
    HTML transferred:       22000 bytes
    Requests per second:    2.89 [#/sec] (mean)
    Time per request:       69266.798 [ms] (mean)
    Time per request:       346.334 [ms] (mean, across all concurrent requests)
    Transfer rate:          0.45 [Kbytes/sec] received

    Connection Times (ms)
                min    mean[+/-sd] median   max
    Connect:        0  342 312.1    502    2044
    Processing:  1821 63051 20115.0  58274  100425
    Waiting:        2 35307 22320.4  33049   94829
    Total:       2694 63393 20121.4  58645  100425

    Percentage of the requests served within a certain time (ms)
    50%  58645
    66%  73170
    75%  80838
    80%  82880
    90%  92714
    95%  94738
    98%  97885
    99%  99403
    100%  100425 (longest request)
</details>