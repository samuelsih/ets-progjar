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
</details>

<details>
    <summary>1000 Request, 50 Concurrency</summary>

    Server Software:        myserver/1.0
    Server Hostname:        localhost
    Server Port:            8889

    Document Path:          /testing.txt
    Document Length:        22 bytes

    Concurrency Level:      50
    Time taken for tests:   360.835 seconds
    Complete requests:      1000
    Failed requests:        10
    (Connect: 0, Receive: 0, Length: 10, Exceptions: 0)
    Write errors:           10
    Total transferred:      157410 bytes
    HTML transferred:       21780 bytes
    Requests per second:    2.77 [#/sec] (mean)
    Time per request:       18041.729 [ms] (mean)
    Time per request:       360.835 [ms] (mean, across all concurrent requests)
    Transfer rate:          0.43 [Kbytes/sec] received

    Connection Times (ms)
                  min  mean[+/-sd] median   max
    Connect:        0  354 317.6    502    1538
    Processing:     0 17256 5469.4  16639   29640
    Waiting:        9 11012 5997.4  10134   27603
    Total:          0 17610 5563.3  16643   30656

    Percentage of the requests served within a certain time (ms)
    50%  16643
    66%  19695
    75%  22739
    80%  23528
    90%  25541
    95%  27030
    98%  28614
    99%  29125
    100%  30656 (longest request)

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