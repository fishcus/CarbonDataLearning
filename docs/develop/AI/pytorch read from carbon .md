/usr/local/bin/python3.6 /Users/xubo/Desktop/xubo/git/historm/examples/mnist/pytorch_example_carbon.py --dataset-url file:///tmp/mnistcarbon
2019-03-20 14:50:53 WARN  NativeCodeLoader:62 - Unable to load native-hadoop library for your platform... using builtin-java classes where applicable
2019-03-20 14:50:53 INFO  CarbonProperties:715 - Property file path: /Users/xubo/Desktop/xubo/git/historm/examples/mnist/../../../conf/carbon.properties
2019-03-20 14:50:53 INFO  CarbonProperties:908 - ------Using Carbon.properties --------
2019-03-20 14:50:53 INFO  CarbonProperties:909 - {}
2019-03-20 14:50:53 INFO  CarbonProperties:701 - Considered file format is: V3
2019-03-20 14:50:53 INFO  CarbonProperties:595 - Blocklet Size Configured value is "64
2019-03-20 14:50:53 WARN  CarbonProperties:473 - The enable unsafe sort value "null" is invalid. Using the default value "true
2019-03-20 14:50:53 WARN  CarbonProperties:485 - The enable off heap sort value "null" is invalid. Using the default value "true
2019-03-20 14:50:53 WARN  CarbonProperties:446 - The custom block distribution value "null" is invalid. Using the default value "false
2019-03-20 14:50:53 WARN  CarbonProperties:433 - The enable vector reader value "null" is invalid. Using the default value "true
2019-03-20 14:50:53 WARN  CarbonProperties:461 - The carbon task distribution value "null" is invalid. Using the default value "block
2019-03-20 14:50:53 WARN  CarbonProperties:564 - The enable auto handoff value "null" is invalid. Using the default value "true
2019-03-20 14:50:53 WARN  CarbonProperties:1306 - The specified value for property 512is invalid.
2019-03-20 14:50:53 WARN  CarbonProperties:1317 - The specified value for property carbon.sort.storage.inmemory.size.inmbis invalid. Taking the default value.512
2019-03-20 14:50:53 INFO  CarbonProperties:1544 - Considered value for min max byte limit for string is: 200
2019-03-20 14:50:53 INFO  CarbonProperties:1568 - Using default value for carbon.detail.batch.size 100
2019-03-20 14:50:53 INFO  CacheProvider:169 - Executor LRU cache size not configured. Initializing with driver LRU cache size.
2019-03-20 14:50:53 INFO  CarbonLRUCache:76 - LRU cache size not configured. Therefore default behavior will be considered and no LRU based eviction of columns will be done
2019-03-20 14:50:53 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:50:53 INFO  SegmentPropertiesAndSchemaHolder:119 - Constructing new SegmentProperties for table: null_null. Current size of segment properties holder list is: 1
2019-03-20 14:50:53 WARN  UnsafeMemoryManager:80 - It is not recommended to set offheap working memory size less than 512MB, so setting default value to 512
2019-03-20 14:50:53 INFO  UnsafeMemoryManager:106 - Offheap Working Memory manager is created with size 536870912 with OFFHEAP
2019-03-20 14:50:53 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:50:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:50:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:50:54 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:50:54 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:50:54 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:50:54 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
Could not load 'org-xerial-snappy.properties' from classpath: java.lang.NullPointerException
2019-03-20 14:50:54 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task f9cc6704-d441-4a22-97a9-74ee6e96f3cf is 0. Current running tasks are 
Train Epoch: 1 [0]	Loss: 2.285782
Train Epoch: 1 [640]	Loss: 2.337632
Train Epoch: 1 [1280]	Loss: 2.333856
Train Epoch: 1 [1920]	Loss: 2.260382
Train Epoch: 1 [2560]	Loss: 2.217748
Train Epoch: 1 [3200]	Loss: 2.188217
Train Epoch: 1 [3840]	Loss: 2.183000
Train Epoch: 1 [4480]	Loss: 2.108146
Train Epoch: 1 [5120]	Loss: 2.071620
Train Epoch: 1 [5760]	Loss: 2.063108
Train Epoch: 1 [6400]	Loss: 1.829151
Train Epoch: 1 [7040]	Loss: 1.984795
Train Epoch: 1 [7680]	Loss: 1.899874
Train Epoch: 1 [8320]	Loss: 1.758754
Train Epoch: 1 [8960]	Loss: 1.430577
Train Epoch: 1 [9600]	Loss: 1.516592
Train Epoch: 1 [10240]	Loss: 1.490098
Train Epoch: 1 [10880]	Loss: 1.218670
Train Epoch: 1 [11520]	Loss: 1.390218
Train Epoch: 1 [12160]	Loss: 1.291149
Train Epoch: 1 [12800]	Loss: 1.220356
Train Epoch: 1 [13440]	Loss: 0.940153
Train Epoch: 1 [14080]	Loss: 1.104682
Train Epoch: 1 [14720]	Loss: 1.461526
Train Epoch: 1 [15360]	Loss: 0.977735
Train Epoch: 1 [16000]	Loss: 1.264806
Train Epoch: 1 [16640]	Loss: 0.976631
Train Epoch: 1 [17280]	Loss: 0.752029
Train Epoch: 1 [17920]	Loss: 0.623432
Train Epoch: 1 [18560]	Loss: 0.856591
Train Epoch: 1 [19200]	Loss: 0.704677
Train Epoch: 1 [19840]	Loss: 0.710518
Train Epoch: 1 [20480]	Loss: 0.618581
Train Epoch: 1 [21120]	Loss: 0.714359
Train Epoch: 1 [21760]	Loss: 0.453344
Train Epoch: 1 [22400]	Loss: 0.717983
Train Epoch: 1 [23040]	Loss: 0.757566
Train Epoch: 1 [23680]	Loss: 1.339123
Train Epoch: 1 [24320]	Loss: 0.537104
Train Epoch: 1 [24960]	Loss: 0.812371
Train Epoch: 1 [25600]	Loss: 0.636014
Train Epoch: 1 [26240]	Loss: 0.551098
Train Epoch: 1 [26880]	Loss: 0.985334
Train Epoch: 1 [27520]	Loss: 0.576406
Train Epoch: 1 [28160]	Loss: 0.630549
Train Epoch: 1 [28800]	Loss: 0.644189
Train Epoch: 1 [29440]	Loss: 0.684245
Train Epoch: 1 [30080]	Loss: 0.816633
Train Epoch: 1 [30720]	Loss: 0.650315
Train Epoch: 1 [31360]	Loss: 0.854016
Train Epoch: 1 [32000]	Loss: 0.762712
Train Epoch: 1 [32640]	Loss: 0.621915
Train Epoch: 1 [33280]	Loss: 0.501230
Train Epoch: 1 [33920]	Loss: 0.419197
Train Epoch: 1 [34560]	Loss: 0.531512
Train Epoch: 1 [35200]	Loss: 0.627516
Train Epoch: 1 [35840]	Loss: 0.539651
Train Epoch: 1 [36480]	Loss: 0.660502
Train Epoch: 1 [37120]	Loss: 0.561924
Train Epoch: 1 [37760]	Loss: 0.573489
Train Epoch: 1 [38400]	Loss: 0.493495
Train Epoch: 1 [39040]	Loss: 0.266270
Train Epoch: 1 [39680]	Loss: 0.511906
Train Epoch: 1 [40320]	Loss: 0.484316
Train Epoch: 1 [40960]	Loss: 0.583771
Train Epoch: 1 [41600]	Loss: 0.627826
Train Epoch: 1 [42240]	Loss: 0.478195
Train Epoch: 1 [42880]	Loss: 0.629916
Train Epoch: 1 [43520]	Loss: 0.462198
Train Epoch: 1 [44160]	Loss: 0.501586
Train Epoch: 1 [44800]	Loss: 0.584187
Train Epoch: 1 [45440]	Loss: 0.837299
Train Epoch: 1 [46080]	Loss: 0.558246
Train Epoch: 1 [46720]	Loss: 0.366500
Train Epoch: 1 [47360]	Loss: 0.519636
Train Epoch: 1 [48000]	Loss: 0.463642
Train Epoch: 1 [48640]	Loss: 0.428661
Train Epoch: 1 [49280]	Loss: 0.258727
Train Epoch: 1 [49920]	Loss: 0.517323
Train Epoch: 1 [50560]	Loss: 0.543509
Train Epoch: 1 [51200]	Loss: 0.507358
Train Epoch: 1 [51840]	Loss: 0.359976
Train Epoch: 1 [52480]	Loss: 0.402240
Train Epoch: 1 [53120]	Loss: 0.502452
Train Epoch: 1 [53760]	Loss: 0.343815
Train Epoch: 1 [54400]	Loss: 0.391273
Train Epoch: 1 [55040]	Loss: 0.395168
Train Epoch: 1 [55680]	Loss: 0.318477
Train Epoch: 1 [56320]	Loss: 0.581236
Train Epoch: 1 [56960]	Loss: 0.388356
Train Epoch: 1 [57600]	Loss: 0.477020
Train Epoch: 1 [58240]	Loss: 0.253826
Train Epoch: 1 [58880]	Loss: 0.259579
Train Epoch: 1 [59520]	Loss: 0.215142
2019-03-20 14:51:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:51:54 INFO  SegmentPropertiesAndSchemaHolder:119 - Constructing new SegmentProperties for table: null_null. Current size of segment properties holder list is: 2
2019-03-20 14:51:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:51:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:51:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:51:54 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:51:54 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:51:54 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:51:54 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:51:54 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 8984fae8-7008-4b4b-8a40-5c2022eefc1a is 0. Current running tasks are 

Test set: Average loss: 0.2071, Accuracy: 9360/10000 (94%)

2019-03-20 14:52:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:52:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:52:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:52:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:52:00 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:52:00 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:52:00 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:52:00 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:52:00 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 588cdaf7-3cb7-440d-9ee0-1712a91aa106 is 0. Current running tasks are 
Train Epoch: 2 [0]	Loss: 0.367007
Train Epoch: 2 [640]	Loss: 0.432181
Train Epoch: 2 [1280]	Loss: 0.516762
Train Epoch: 2 [1920]	Loss: 0.358722
Train Epoch: 2 [2560]	Loss: 0.328926
Train Epoch: 2 [3200]	Loss: 0.459095
Train Epoch: 2 [3840]	Loss: 0.356688
Train Epoch: 2 [4480]	Loss: 0.421650
Train Epoch: 2 [5120]	Loss: 0.568110
Train Epoch: 2 [5760]	Loss: 0.653166
Train Epoch: 2 [6400]	Loss: 0.333973
Train Epoch: 2 [7040]	Loss: 0.258421
Train Epoch: 2 [7680]	Loss: 0.364918
Train Epoch: 2 [8320]	Loss: 0.416871
Train Epoch: 2 [8960]	Loss: 0.329008
Train Epoch: 2 [9600]	Loss: 0.535322
Train Epoch: 2 [10240]	Loss: 0.616199
Train Epoch: 2 [10880]	Loss: 0.288175
Train Epoch: 2 [11520]	Loss: 0.836662
Train Epoch: 2 [12160]	Loss: 0.411719
Train Epoch: 2 [12800]	Loss: 0.303899
Train Epoch: 2 [13440]	Loss: 0.378207
Train Epoch: 2 [14080]	Loss: 0.417326
Train Epoch: 2 [14720]	Loss: 0.661157
Train Epoch: 2 [15360]	Loss: 0.461623
Train Epoch: 2 [16000]	Loss: 0.615861
Train Epoch: 2 [16640]	Loss: 0.504750
Train Epoch: 2 [17280]	Loss: 0.212996
Train Epoch: 2 [17920]	Loss: 0.188105
Train Epoch: 2 [18560]	Loss: 0.558179
Train Epoch: 2 [19200]	Loss: 0.410543
Train Epoch: 2 [19840]	Loss: 0.196490
Train Epoch: 2 [20480]	Loss: 0.218065
Train Epoch: 2 [21120]	Loss: 0.313573
Train Epoch: 2 [21760]	Loss: 0.212964
Train Epoch: 2 [22400]	Loss: 0.380071
Train Epoch: 2 [23040]	Loss: 0.319232
Train Epoch: 2 [23680]	Loss: 0.455140
Train Epoch: 2 [24320]	Loss: 0.218306
Train Epoch: 2 [24960]	Loss: 0.293270
Train Epoch: 2 [25600]	Loss: 0.476152
Train Epoch: 2 [26240]	Loss: 0.309941
Train Epoch: 2 [26880]	Loss: 0.486455
Train Epoch: 2 [27520]	Loss: 0.318613
Train Epoch: 2 [28160]	Loss: 0.324029
Train Epoch: 2 [28800]	Loss: 0.304571
Train Epoch: 2 [29440]	Loss: 0.483699
Train Epoch: 2 [30080]	Loss: 0.470499
Train Epoch: 2 [30720]	Loss: 0.440620
Train Epoch: 2 [31360]	Loss: 0.669291
Train Epoch: 2 [32000]	Loss: 0.383710
Train Epoch: 2 [32640]	Loss: 0.346964
Train Epoch: 2 [33280]	Loss: 0.305476
Train Epoch: 2 [33920]	Loss: 0.243168
Train Epoch: 2 [34560]	Loss: 0.380213
Train Epoch: 2 [35200]	Loss: 0.392316
Train Epoch: 2 [35840]	Loss: 0.418344
Train Epoch: 2 [36480]	Loss: 0.203124
Train Epoch: 2 [37120]	Loss: 0.306917
Train Epoch: 2 [37760]	Loss: 0.316601
Train Epoch: 2 [38400]	Loss: 0.489781
Train Epoch: 2 [39040]	Loss: 0.199472
Train Epoch: 2 [39680]	Loss: 0.323343
Train Epoch: 2 [40320]	Loss: 0.373648
Train Epoch: 2 [40960]	Loss: 0.294339
Train Epoch: 2 [41600]	Loss: 0.361074
Train Epoch: 2 [42240]	Loss: 0.387314
Train Epoch: 2 [42880]	Loss: 0.597544
Train Epoch: 2 [43520]	Loss: 0.301102
Train Epoch: 2 [44160]	Loss: 0.305913
Train Epoch: 2 [44800]	Loss: 0.398140
Train Epoch: 2 [45440]	Loss: 0.555469
Train Epoch: 2 [46080]	Loss: 0.479042
Train Epoch: 2 [46720]	Loss: 0.486001
Train Epoch: 2 [47360]	Loss: 0.459709
Train Epoch: 2 [48000]	Loss: 0.265368
Train Epoch: 2 [48640]	Loss: 0.192428
Train Epoch: 2 [49280]	Loss: 0.182621
Train Epoch: 2 [49920]	Loss: 0.350025
Train Epoch: 2 [50560]	Loss: 0.437208
Train Epoch: 2 [51200]	Loss: 0.492215
Train Epoch: 2 [51840]	Loss: 0.347642
Train Epoch: 2 [52480]	Loss: 0.172868
Train Epoch: 2 [53120]	Loss: 0.374734
Train Epoch: 2 [53760]	Loss: 0.183523
Train Epoch: 2 [54400]	Loss: 0.184523
Train Epoch: 2 [55040]	Loss: 0.309864
Train Epoch: 2 [55680]	Loss: 0.350634
Train Epoch: 2 [56320]	Loss: 0.335555
Train Epoch: 2 [56960]	Loss: 0.254995
Train Epoch: 2 [57600]	Loss: 0.396028
Train Epoch: 2 [58240]	Loss: 0.219932
Train Epoch: 2 [58880]	Loss: 0.095480
Train Epoch: 2 [59520]	Loss: 0.236780
2019-03-20 14:52:59 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:52:59 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:52:59 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:52:59 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:52:59 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:52:59 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:52:59 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:52:59 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:52:59 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task a1c99468-78bc-4946-a672-5e71cbf7f752 is 0. Current running tasks are 

Test set: Average loss: 0.1283, Accuracy: 9612/10000 (96%)

2019-03-20 14:53:05 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:53:05 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:53:05 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:53:05 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:53:05 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:53:05 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:53:05 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:53:05 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:53:05 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task a66273ba-3845-4db5-b100-0e1630d95c90 is 0. Current running tasks are 
Train Epoch: 3 [0]	Loss: 0.350555
Train Epoch: 3 [640]	Loss: 0.117425
Train Epoch: 3 [1280]	Loss: 0.306276
Train Epoch: 3 [1920]	Loss: 0.300997
Train Epoch: 3 [2560]	Loss: 0.232824
Train Epoch: 3 [3200]	Loss: 0.177426
Train Epoch: 3 [3840]	Loss: 0.264823
Train Epoch: 3 [4480]	Loss: 0.211199
Train Epoch: 3 [5120]	Loss: 0.454979
Train Epoch: 3 [5760]	Loss: 0.376617
Train Epoch: 3 [6400]	Loss: 0.243124
Train Epoch: 3 [7040]	Loss: 0.289412
Train Epoch: 3 [7680]	Loss: 0.211558
Train Epoch: 3 [8320]	Loss: 0.260737
Train Epoch: 3 [8960]	Loss: 0.181089
Train Epoch: 3 [9600]	Loss: 0.378199
Train Epoch: 3 [10240]	Loss: 0.732148
Train Epoch: 3 [10880]	Loss: 0.319451
Train Epoch: 3 [11520]	Loss: 0.351135
Train Epoch: 3 [12160]	Loss: 0.285644
Train Epoch: 3 [12800]	Loss: 0.259823
Train Epoch: 3 [13440]	Loss: 0.197887
Train Epoch: 3 [14080]	Loss: 0.357724
Train Epoch: 3 [14720]	Loss: 0.425680
Train Epoch: 3 [15360]	Loss: 0.315605
Train Epoch: 3 [16000]	Loss: 0.528516
Train Epoch: 3 [16640]	Loss: 0.369489
Train Epoch: 3 [17280]	Loss: 0.155466
Train Epoch: 3 [17920]	Loss: 0.246183
Train Epoch: 3 [18560]	Loss: 0.157316
Train Epoch: 3 [19200]	Loss: 0.431465
Train Epoch: 3 [19840]	Loss: 0.164292
Train Epoch: 3 [20480]	Loss: 0.235194
Train Epoch: 3 [21120]	Loss: 0.262023
Train Epoch: 3 [21760]	Loss: 0.226817
Train Epoch: 3 [22400]	Loss: 0.203712
Train Epoch: 3 [23040]	Loss: 0.266434
Train Epoch: 3 [23680]	Loss: 0.487281
Train Epoch: 3 [24320]	Loss: 0.201996
Train Epoch: 3 [24960]	Loss: 0.331722
Train Epoch: 3 [25600]	Loss: 0.230213
Train Epoch: 3 [26240]	Loss: 0.232757
Train Epoch: 3 [26880]	Loss: 0.401630
Train Epoch: 3 [27520]	Loss: 0.430758
Train Epoch: 3 [28160]	Loss: 0.367647
Train Epoch: 3 [28800]	Loss: 0.264625
Train Epoch: 3 [29440]	Loss: 0.269611
Train Epoch: 3 [30080]	Loss: 0.395009
Train Epoch: 3 [30720]	Loss: 0.392870
Train Epoch: 3 [31360]	Loss: 0.353648
Train Epoch: 3 [32000]	Loss: 0.325959
Train Epoch: 3 [32640]	Loss: 0.154797
Train Epoch: 3 [33280]	Loss: 0.130730
Train Epoch: 3 [33920]	Loss: 0.219464
Train Epoch: 3 [34560]	Loss: 0.217244
Train Epoch: 3 [35200]	Loss: 0.384878
Train Epoch: 3 [35840]	Loss: 0.448447
Train Epoch: 3 [36480]	Loss: 0.308817
Train Epoch: 3 [37120]	Loss: 0.252364
Train Epoch: 3 [37760]	Loss: 0.365259
Train Epoch: 3 [38400]	Loss: 0.316132
Train Epoch: 3 [39040]	Loss: 0.077221
Train Epoch: 3 [39680]	Loss: 0.320068
Train Epoch: 3 [40320]	Loss: 0.250686
Train Epoch: 3 [40960]	Loss: 0.525312
Train Epoch: 3 [41600]	Loss: 0.274168
Train Epoch: 3 [42240]	Loss: 0.227666
Train Epoch: 3 [42880]	Loss: 0.360813
Train Epoch: 3 [43520]	Loss: 0.343204
Train Epoch: 3 [44160]	Loss: 0.285835
Train Epoch: 3 [44800]	Loss: 0.423706
Train Epoch: 3 [45440]	Loss: 0.410366
Train Epoch: 3 [46080]	Loss: 0.312415
Train Epoch: 3 [46720]	Loss: 0.392820
Train Epoch: 3 [47360]	Loss: 0.218742
Train Epoch: 3 [48000]	Loss: 0.154548
Train Epoch: 3 [48640]	Loss: 0.098035
Train Epoch: 3 [49280]	Loss: 0.129384
Train Epoch: 3 [49920]	Loss: 0.186289
Train Epoch: 3 [50560]	Loss: 0.342948
Train Epoch: 3 [51200]	Loss: 0.243596
Train Epoch: 3 [51840]	Loss: 0.223811
Train Epoch: 3 [52480]	Loss: 0.152599
Train Epoch: 3 [53120]	Loss: 0.384197
Train Epoch: 3 [53760]	Loss: 0.153865
Train Epoch: 3 [54400]	Loss: 0.172264
Train Epoch: 3 [55040]	Loss: 0.123473
Train Epoch: 3 [55680]	Loss: 0.308916
Train Epoch: 3 [56320]	Loss: 0.393515
Train Epoch: 3 [56960]	Loss: 0.175626
Train Epoch: 3 [57600]	Loss: 0.337233
Train Epoch: 3 [58240]	Loss: 0.142384
Train Epoch: 3 [58880]	Loss: 0.080305
Train Epoch: 3 [59520]	Loss: 0.082884
2019-03-20 14:53:57 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:53:57 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:53:57 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:53:57 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:53:57 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:53:57 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:53:57 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:53:57 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:53:57 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 6dc79b5c-63e6-4f72-91df-f02104b0959a is 0. Current running tasks are 

Test set: Average loss: 0.1019, Accuracy: 9685/10000 (97%)

2019-03-20 14:54:03 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:54:03 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:54:03 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:54:03 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:54:03 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:54:03 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:54:03 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:54:03 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:54:03 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 5d37d0ed-18f0-4e4d-aa86-01343797c2c4 is 0. Current running tasks are 
Train Epoch: 4 [0]	Loss: 0.133426
Train Epoch: 4 [640]	Loss: 0.118391
Train Epoch: 4 [1280]	Loss: 0.191146
Train Epoch: 4 [1920]	Loss: 0.296228
Train Epoch: 4 [2560]	Loss: 0.147819
Train Epoch: 4 [3200]	Loss: 0.265481
Train Epoch: 4 [3840]	Loss: 0.252090
Train Epoch: 4 [4480]	Loss: 0.372485
Train Epoch: 4 [5120]	Loss: 0.456237
Train Epoch: 4 [5760]	Loss: 0.450172
Train Epoch: 4 [6400]	Loss: 0.249236
Train Epoch: 4 [7040]	Loss: 0.175827
Train Epoch: 4 [7680]	Loss: 0.235061
Train Epoch: 4 [8320]	Loss: 0.289850
Train Epoch: 4 [8960]	Loss: 0.223034
Train Epoch: 4 [9600]	Loss: 0.341033
Train Epoch: 4 [10240]	Loss: 0.530448
Train Epoch: 4 [10880]	Loss: 0.284233
Train Epoch: 4 [11520]	Loss: 0.460967
Train Epoch: 4 [12160]	Loss: 0.195560
Train Epoch: 4 [12800]	Loss: 0.189293
Train Epoch: 4 [13440]	Loss: 0.272721
Train Epoch: 4 [14080]	Loss: 0.178528
Train Epoch: 4 [14720]	Loss: 0.471891
Train Epoch: 4 [15360]	Loss: 0.282806
Train Epoch: 4 [16000]	Loss: 0.474944
Train Epoch: 4 [16640]	Loss: 0.272013
Train Epoch: 4 [17280]	Loss: 0.219168
Train Epoch: 4 [17920]	Loss: 0.270154
Train Epoch: 4 [18560]	Loss: 0.233247
Train Epoch: 4 [19200]	Loss: 0.377780
Train Epoch: 4 [19840]	Loss: 0.273059
Train Epoch: 4 [20480]	Loss: 0.129608
Train Epoch: 4 [21120]	Loss: 0.196545
Train Epoch: 4 [21760]	Loss: 0.077037
Train Epoch: 4 [22400]	Loss: 0.249871
Train Epoch: 4 [23040]	Loss: 0.299491
Train Epoch: 4 [23680]	Loss: 0.406926
Train Epoch: 4 [24320]	Loss: 0.130408
Train Epoch: 4 [24960]	Loss: 0.180158
Train Epoch: 4 [25600]	Loss: 0.225101
Train Epoch: 4 [26240]	Loss: 0.198154
Train Epoch: 4 [26880]	Loss: 0.320152
Train Epoch: 4 [27520]	Loss: 0.150102
Train Epoch: 4 [28160]	Loss: 0.156629
Train Epoch: 4 [28800]	Loss: 0.236901
Train Epoch: 4 [29440]	Loss: 0.184212
Train Epoch: 4 [30080]	Loss: 0.319365
Train Epoch: 4 [30720]	Loss: 0.262566
Train Epoch: 4 [31360]	Loss: 0.378446
Train Epoch: 4 [32000]	Loss: 0.310984
Train Epoch: 4 [32640]	Loss: 0.138727
Train Epoch: 4 [33280]	Loss: 0.181318
Train Epoch: 4 [33920]	Loss: 0.148251
Train Epoch: 4 [34560]	Loss: 0.148098
Train Epoch: 4 [35200]	Loss: 0.431532
Train Epoch: 4 [35840]	Loss: 0.198928
Train Epoch: 4 [36480]	Loss: 0.158312
Train Epoch: 4 [37120]	Loss: 0.299332
Train Epoch: 4 [37760]	Loss: 0.265984
Train Epoch: 4 [38400]	Loss: 0.291737
Train Epoch: 4 [39040]	Loss: 0.123652
Train Epoch: 4 [39680]	Loss: 0.245321
Train Epoch: 4 [40320]	Loss: 0.124493
Train Epoch: 4 [40960]	Loss: 0.227828
Train Epoch: 4 [41600]	Loss: 0.249229
Train Epoch: 4 [42240]	Loss: 0.170462
Train Epoch: 4 [42880]	Loss: 0.339044
Train Epoch: 4 [43520]	Loss: 0.461033
Train Epoch: 4 [44160]	Loss: 0.166669
Train Epoch: 4 [44800]	Loss: 0.314357
Train Epoch: 4 [45440]	Loss: 0.243238
Train Epoch: 4 [46080]	Loss: 0.285255
Train Epoch: 4 [46720]	Loss: 0.325884
Train Epoch: 4 [47360]	Loss: 0.289123
Train Epoch: 4 [48000]	Loss: 0.166662
Train Epoch: 4 [48640]	Loss: 0.099103
Train Epoch: 4 [49280]	Loss: 0.162687
Train Epoch: 4 [49920]	Loss: 0.264765
Train Epoch: 4 [50560]	Loss: 0.259200
Train Epoch: 4 [51200]	Loss: 0.299291
Train Epoch: 4 [51840]	Loss: 0.147179
Train Epoch: 4 [52480]	Loss: 0.148046
Train Epoch: 4 [53120]	Loss: 0.183692
Train Epoch: 4 [53760]	Loss: 0.203080
Train Epoch: 4 [54400]	Loss: 0.148796
Train Epoch: 4 [55040]	Loss: 0.249341
Train Epoch: 4 [55680]	Loss: 0.227968
Train Epoch: 4 [56320]	Loss: 0.281970
Train Epoch: 4 [56960]	Loss: 0.154411
Train Epoch: 4 [57600]	Loss: 0.370441
Train Epoch: 4 [58240]	Loss: 0.149356
Train Epoch: 4 [58880]	Loss: 0.212778
Train Epoch: 4 [59520]	Loss: 0.121375
2019-03-20 14:54:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:54:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:54:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:54:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:54:54 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:54:54 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:54:54 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:54:54 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:54:55 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task f97401e8-769f-4d4a-ae19-33e89b1b2dd3 is 0. Current running tasks are 

Test set: Average loss: 0.0837, Accuracy: 9732/10000 (97%)

2019-03-20 14:55:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:55:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:55:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:55:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:55:00 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:55:00 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:55:00 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:55:00 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:55:01 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task beeb6303-f5c1-4999-8e9d-1ad6173a2e6e is 0. Current running tasks are 
Train Epoch: 5 [0]	Loss: 0.133022
Train Epoch: 5 [640]	Loss: 0.179920
Train Epoch: 5 [1280]	Loss: 0.266334
Train Epoch: 5 [1920]	Loss: 0.343186
Train Epoch: 5 [2560]	Loss: 0.113988
Train Epoch: 5 [3200]	Loss: 0.098909
Train Epoch: 5 [3840]	Loss: 0.106457
Train Epoch: 5 [4480]	Loss: 0.124581
Train Epoch: 5 [5120]	Loss: 0.258228
Train Epoch: 5 [5760]	Loss: 0.185223
Train Epoch: 5 [6400]	Loss: 0.192984
Train Epoch: 5 [7040]	Loss: 0.193926
Train Epoch: 5 [7680]	Loss: 0.231152
Train Epoch: 5 [8320]	Loss: 0.191185
Train Epoch: 5 [8960]	Loss: 0.156300
Train Epoch: 5 [9600]	Loss: 0.404363
Train Epoch: 5 [10240]	Loss: 0.497838
Train Epoch: 5 [10880]	Loss: 0.212423
Train Epoch: 5 [11520]	Loss: 0.398825
Train Epoch: 5 [12160]	Loss: 0.373783
Train Epoch: 5 [12800]	Loss: 0.224425
Train Epoch: 5 [13440]	Loss: 0.192071
Train Epoch: 5 [14080]	Loss: 0.137069
Train Epoch: 5 [14720]	Loss: 0.326920
Train Epoch: 5 [15360]	Loss: 0.366430
Train Epoch: 5 [16000]	Loss: 0.314790
Train Epoch: 5 [16640]	Loss: 0.369718
Train Epoch: 5 [17280]	Loss: 0.212666
Train Epoch: 5 [17920]	Loss: 0.075569
Train Epoch: 5 [18560]	Loss: 0.178044
Train Epoch: 5 [19200]	Loss: 0.169460
Train Epoch: 5 [19840]	Loss: 0.273811
Train Epoch: 5 [20480]	Loss: 0.113115
Train Epoch: 5 [21120]	Loss: 0.154628
Train Epoch: 5 [21760]	Loss: 0.068625
Train Epoch: 5 [22400]	Loss: 0.241559
Train Epoch: 5 [23040]	Loss: 0.297394
Train Epoch: 5 [23680]	Loss: 0.232573
Train Epoch: 5 [24320]	Loss: 0.134908
Train Epoch: 5 [24960]	Loss: 0.131814
Train Epoch: 5 [25600]	Loss: 0.196076
Train Epoch: 5 [26240]	Loss: 0.288513
Train Epoch: 5 [26880]	Loss: 0.282197
Train Epoch: 5 [27520]	Loss: 0.213639
Train Epoch: 5 [28160]	Loss: 0.297652
Train Epoch: 5 [28800]	Loss: 0.322903
Train Epoch: 5 [29440]	Loss: 0.295710
Train Epoch: 5 [30080]	Loss: 0.250481
Train Epoch: 5 [30720]	Loss: 0.248221
Train Epoch: 5 [31360]	Loss: 0.303998
Train Epoch: 5 [32000]	Loss: 0.209867
Train Epoch: 5 [32640]	Loss: 0.271166
Train Epoch: 5 [33280]	Loss: 0.093661
Train Epoch: 5 [33920]	Loss: 0.117853
Train Epoch: 5 [34560]	Loss: 0.115405
Train Epoch: 5 [35200]	Loss: 0.344062
Train Epoch: 5 [35840]	Loss: 0.228585
Train Epoch: 5 [36480]	Loss: 0.233853
Train Epoch: 5 [37120]	Loss: 0.257682
Train Epoch: 5 [37760]	Loss: 0.320490
Train Epoch: 5 [38400]	Loss: 0.134957
Train Epoch: 5 [39040]	Loss: 0.043440
Train Epoch: 5 [39680]	Loss: 0.227480
Train Epoch: 5 [40320]	Loss: 0.151166
Train Epoch: 5 [40960]	Loss: 0.141209
Train Epoch: 5 [41600]	Loss: 0.372392
Train Epoch: 5 [42240]	Loss: 0.140270
Train Epoch: 5 [42880]	Loss: 0.364506
Train Epoch: 5 [43520]	Loss: 0.267885
Train Epoch: 5 [44160]	Loss: 0.155338
Train Epoch: 5 [44800]	Loss: 0.288144
Train Epoch: 5 [45440]	Loss: 0.328292
Train Epoch: 5 [46080]	Loss: 0.282959
Train Epoch: 5 [46720]	Loss: 0.406517
Train Epoch: 5 [47360]	Loss: 0.187695
Train Epoch: 5 [48000]	Loss: 0.098301
Train Epoch: 5 [48640]	Loss: 0.116394
Train Epoch: 5 [49280]	Loss: 0.076960
Train Epoch: 5 [49920]	Loss: 0.155052
Train Epoch: 5 [50560]	Loss: 0.206654
Train Epoch: 5 [51200]	Loss: 0.370844
Train Epoch: 5 [51840]	Loss: 0.097386
Train Epoch: 5 [52480]	Loss: 0.130981
Train Epoch: 5 [53120]	Loss: 0.259443
Train Epoch: 5 [53760]	Loss: 0.149990
Train Epoch: 5 [54400]	Loss: 0.119980
Train Epoch: 5 [55040]	Loss: 0.203729
Train Epoch: 5 [55680]	Loss: 0.234442
Train Epoch: 5 [56320]	Loss: 0.202660
Train Epoch: 5 [56960]	Loss: 0.258859
Train Epoch: 5 [57600]	Loss: 0.390048
Train Epoch: 5 [58240]	Loss: 0.173944
Train Epoch: 5 [58880]	Loss: 0.148547
Train Epoch: 5 [59520]	Loss: 0.061496
2019-03-20 14:55:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:55:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:55:54 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:55:54 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:55:54 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:55:54 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:55:54 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:55:54 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:55:54 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 167e701a-96ce-4304-a19d-5b865683615a is 0. Current running tasks are 

Test set: Average loss: 0.0744, Accuracy: 9759/10000 (98%)

2019-03-20 14:56:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:56:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:56:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:56:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:56:00 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:56:00 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:56:00 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:56:00 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:56:01 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 862f595e-6796-409a-8537-b172ab0f0897 is 0. Current running tasks are 
Train Epoch: 6 [0]	Loss: 0.219443
Train Epoch: 6 [640]	Loss: 0.162626
Train Epoch: 6 [1280]	Loss: 0.189814
Train Epoch: 6 [1920]	Loss: 0.245815
Train Epoch: 6 [2560]	Loss: 0.104524
Train Epoch: 6 [3200]	Loss: 0.155156
Train Epoch: 6 [3840]	Loss: 0.193051
Train Epoch: 6 [4480]	Loss: 0.189202
Train Epoch: 6 [5120]	Loss: 0.176248
Train Epoch: 6 [5760]	Loss: 0.150705
Train Epoch: 6 [6400]	Loss: 0.177552
Train Epoch: 6 [7040]	Loss: 0.212865
Train Epoch: 6 [7680]	Loss: 0.306086
Train Epoch: 6 [8320]	Loss: 0.121795
Train Epoch: 6 [8960]	Loss: 0.110298
Train Epoch: 6 [9600]	Loss: 0.278949
Train Epoch: 6 [10240]	Loss: 0.346339
Train Epoch: 6 [10880]	Loss: 0.130604
Train Epoch: 6 [11520]	Loss: 0.282518
Train Epoch: 6 [12160]	Loss: 0.189636
Train Epoch: 6 [12800]	Loss: 0.210286
Train Epoch: 6 [13440]	Loss: 0.143920
Train Epoch: 6 [14080]	Loss: 0.185768
Train Epoch: 6 [14720]	Loss: 0.357559
Train Epoch: 6 [15360]	Loss: 0.219228
Train Epoch: 6 [16000]	Loss: 0.365144
Train Epoch: 6 [16640]	Loss: 0.286296
Train Epoch: 6 [17280]	Loss: 0.148133
Train Epoch: 6 [17920]	Loss: 0.164677
Train Epoch: 6 [18560]	Loss: 0.105183
Train Epoch: 6 [19200]	Loss: 0.393613
Train Epoch: 6 [19840]	Loss: 0.314566
Train Epoch: 6 [20480]	Loss: 0.051319
Train Epoch: 6 [21120]	Loss: 0.190173
Train Epoch: 6 [21760]	Loss: 0.130387
Train Epoch: 6 [22400]	Loss: 0.129569
Train Epoch: 6 [23040]	Loss: 0.329427
Train Epoch: 6 [23680]	Loss: 0.268516
Train Epoch: 6 [24320]	Loss: 0.064806
Train Epoch: 6 [24960]	Loss: 0.119560
Train Epoch: 6 [25600]	Loss: 0.175755
Train Epoch: 6 [26240]	Loss: 0.177872
Train Epoch: 6 [26880]	Loss: 0.214771
Train Epoch: 6 [27520]	Loss: 0.330112
Train Epoch: 6 [28160]	Loss: 0.320819
Train Epoch: 6 [28800]	Loss: 0.155155
Train Epoch: 6 [29440]	Loss: 0.214926
Train Epoch: 6 [30080]	Loss: 0.441102
Train Epoch: 6 [30720]	Loss: 0.161992
Train Epoch: 6 [31360]	Loss: 0.221331
Train Epoch: 6 [32000]	Loss: 0.191845
Train Epoch: 6 [32640]	Loss: 0.179320
Train Epoch: 6 [33280]	Loss: 0.255594
Train Epoch: 6 [33920]	Loss: 0.098467
Train Epoch: 6 [34560]	Loss: 0.072606
Train Epoch: 6 [35200]	Loss: 0.267735
Train Epoch: 6 [35840]	Loss: 0.143921
Train Epoch: 6 [36480]	Loss: 0.129160
Train Epoch: 6 [37120]	Loss: 0.126650
Train Epoch: 6 [37760]	Loss: 0.160551
Train Epoch: 6 [38400]	Loss: 0.119256
Train Epoch: 6 [39040]	Loss: 0.061482
Train Epoch: 6 [39680]	Loss: 0.160220
Train Epoch: 6 [40320]	Loss: 0.128222
Train Epoch: 6 [40960]	Loss: 0.302786
Train Epoch: 6 [41600]	Loss: 0.348609
Train Epoch: 6 [42240]	Loss: 0.132669
Train Epoch: 6 [42880]	Loss: 0.293090
Train Epoch: 6 [43520]	Loss: 0.310226
Train Epoch: 6 [44160]	Loss: 0.159202
Train Epoch: 6 [44800]	Loss: 0.233421
Train Epoch: 6 [45440]	Loss: 0.393068
Train Epoch: 6 [46080]	Loss: 0.303591
Train Epoch: 6 [46720]	Loss: 0.312914
Train Epoch: 6 [47360]	Loss: 0.304528
Train Epoch: 6 [48000]	Loss: 0.150398
Train Epoch: 6 [48640]	Loss: 0.095629
Train Epoch: 6 [49280]	Loss: 0.087483
Train Epoch: 6 [49920]	Loss: 0.161874
Train Epoch: 6 [50560]	Loss: 0.291905
Train Epoch: 6 [51200]	Loss: 0.255473
Train Epoch: 6 [51840]	Loss: 0.139762
Train Epoch: 6 [52480]	Loss: 0.090808
Train Epoch: 6 [53120]	Loss: 0.206185
Train Epoch: 6 [53760]	Loss: 0.247653
Train Epoch: 6 [54400]	Loss: 0.101262
Train Epoch: 6 [55040]	Loss: 0.150002
Train Epoch: 6 [55680]	Loss: 0.344544
Train Epoch: 6 [56320]	Loss: 0.110879
Train Epoch: 6 [56960]	Loss: 0.186846
Train Epoch: 6 [57600]	Loss: 0.255287
Train Epoch: 6 [58240]	Loss: 0.075215
Train Epoch: 6 [58880]	Loss: 0.082469
Train Epoch: 6 [59520]	Loss: 0.130096
2019-03-20 14:56:53 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:56:53 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:56:53 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:56:53 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:56:53 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:56:53 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:56:53 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:56:53 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:56:53 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task ccad43e2-21e6-4011-a5f1-752fe7d6c367 is 0. Current running tasks are 

Test set: Average loss: 0.0677, Accuracy: 9794/10000 (98%)

2019-03-20 14:57:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:00 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:00 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:00 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:57:00 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:57:00 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:57:00 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:57:00 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task f82e856e-a4c9-46b2-bf28-4fbe9feb6851 is 0. Current running tasks are 
Train Epoch: 7 [0]	Loss: 0.155772
Train Epoch: 7 [640]	Loss: 0.087497
Train Epoch: 7 [1280]	Loss: 0.251437
Train Epoch: 7 [1920]	Loss: 0.213632
Train Epoch: 7 [2560]	Loss: 0.115700
Train Epoch: 7 [3200]	Loss: 0.229382
Train Epoch: 7 [3840]	Loss: 0.131795
Train Epoch: 7 [4480]	Loss: 0.229748
Train Epoch: 7 [5120]	Loss: 0.311208
Train Epoch: 7 [5760]	Loss: 0.213538
Train Epoch: 7 [6400]	Loss: 0.305787
Train Epoch: 7 [7040]	Loss: 0.171872
Train Epoch: 7 [7680]	Loss: 0.163688
Train Epoch: 7 [8320]	Loss: 0.138992
Train Epoch: 7 [8960]	Loss: 0.159411
Train Epoch: 7 [9600]	Loss: 0.181904
Train Epoch: 7 [10240]	Loss: 0.493205
Train Epoch: 7 [10880]	Loss: 0.130823
Train Epoch: 7 [11520]	Loss: 0.223935
Train Epoch: 7 [12160]	Loss: 0.184462
Train Epoch: 7 [12800]	Loss: 0.072725
Train Epoch: 7 [13440]	Loss: 0.096975
Train Epoch: 7 [14080]	Loss: 0.147654
Train Epoch: 7 [14720]	Loss: 0.303259
Train Epoch: 7 [15360]	Loss: 0.303932
Train Epoch: 7 [16000]	Loss: 0.320905
Train Epoch: 7 [16640]	Loss: 0.352445
Train Epoch: 7 [17280]	Loss: 0.189542
Train Epoch: 7 [17920]	Loss: 0.175035
Train Epoch: 7 [18560]	Loss: 0.152754
Train Epoch: 7 [19200]	Loss: 0.196915
Train Epoch: 7 [19840]	Loss: 0.127665
Train Epoch: 7 [20480]	Loss: 0.054456
Train Epoch: 7 [21120]	Loss: 0.143223
Train Epoch: 7 [21760]	Loss: 0.104953
Train Epoch: 7 [22400]	Loss: 0.186320
Train Epoch: 7 [23040]	Loss: 0.236021
Train Epoch: 7 [23680]	Loss: 0.314053
Train Epoch: 7 [24320]	Loss: 0.094015
Train Epoch: 7 [24960]	Loss: 0.118901
Train Epoch: 7 [25600]	Loss: 0.128155
Train Epoch: 7 [26240]	Loss: 0.164362
Train Epoch: 7 [26880]	Loss: 0.219551
Train Epoch: 7 [27520]	Loss: 0.151401
Train Epoch: 7 [28160]	Loss: 0.236813
Train Epoch: 7 [28800]	Loss: 0.215936
Train Epoch: 7 [29440]	Loss: 0.200132
Train Epoch: 7 [30080]	Loss: 0.168023
Train Epoch: 7 [30720]	Loss: 0.131028
Train Epoch: 7 [31360]	Loss: 0.280241
Train Epoch: 7 [32000]	Loss: 0.184831
Train Epoch: 7 [32640]	Loss: 0.110894
Train Epoch: 7 [33280]	Loss: 0.224672
Train Epoch: 7 [33920]	Loss: 0.060892
Train Epoch: 7 [34560]	Loss: 0.094208
Train Epoch: 7 [35200]	Loss: 0.226489
Train Epoch: 7 [35840]	Loss: 0.375783
Train Epoch: 7 [36480]	Loss: 0.217420
Train Epoch: 7 [37120]	Loss: 0.188162
Train Epoch: 7 [37760]	Loss: 0.096024
Train Epoch: 7 [38400]	Loss: 0.155238
Train Epoch: 7 [39040]	Loss: 0.043930
Train Epoch: 7 [39680]	Loss: 0.201528
Train Epoch: 7 [40320]	Loss: 0.091109
Train Epoch: 7 [40960]	Loss: 0.139657
Train Epoch: 7 [41600]	Loss: 0.107503
Train Epoch: 7 [42240]	Loss: 0.214840
Train Epoch: 7 [42880]	Loss: 0.136737
Train Epoch: 7 [43520]	Loss: 0.215805
Train Epoch: 7 [44160]	Loss: 0.183524
Train Epoch: 7 [44800]	Loss: 0.168786
Train Epoch: 7 [45440]	Loss: 0.406933
Train Epoch: 7 [46080]	Loss: 0.284426
Train Epoch: 7 [46720]	Loss: 0.241633
Train Epoch: 7 [47360]	Loss: 0.211997
Train Epoch: 7 [48000]	Loss: 0.156682
Train Epoch: 7 [48640]	Loss: 0.220073
Train Epoch: 7 [49280]	Loss: 0.101531
Train Epoch: 7 [49920]	Loss: 0.171502
Train Epoch: 7 [50560]	Loss: 0.318973
Train Epoch: 7 [51200]	Loss: 0.218229
Train Epoch: 7 [51840]	Loss: 0.132420
Train Epoch: 7 [52480]	Loss: 0.044463
Train Epoch: 7 [53120]	Loss: 0.145007
Train Epoch: 7 [53760]	Loss: 0.127096
Train Epoch: 7 [54400]	Loss: 0.129830
Train Epoch: 7 [55040]	Loss: 0.133351
Train Epoch: 7 [55680]	Loss: 0.217803
Train Epoch: 7 [56320]	Loss: 0.183657
Train Epoch: 7 [56960]	Loss: 0.150541
Train Epoch: 7 [57600]	Loss: 0.268375
Train Epoch: 7 [58240]	Loss: 0.124597
Train Epoch: 7 [58880]	Loss: 0.028662
Train Epoch: 7 [59520]	Loss: 0.093442
2019-03-20 14:57:52 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:52 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:52 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:52 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:52 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:57:52 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:57:52 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:57:52 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:57:52 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 27de2c72-68dd-4010-b9e6-3d6c67771983 is 0. Current running tasks are 

Test set: Average loss: 0.0598, Accuracy: 9818/10000 (98%)

2019-03-20 14:57:58 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:58 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:58 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:57:58 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:57:58 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:57:58 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:57:58 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:57:58 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:57:58 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 1df2df0f-f6be-431e-bd7a-acee074b9fd4 is 0. Current running tasks are 
Train Epoch: 8 [0]	Loss: 0.165838
Train Epoch: 8 [640]	Loss: 0.110791
Train Epoch: 8 [1280]	Loss: 0.210825
Train Epoch: 8 [1920]	Loss: 0.163282
Train Epoch: 8 [2560]	Loss: 0.173866
Train Epoch: 8 [3200]	Loss: 0.146679
Train Epoch: 8 [3840]	Loss: 0.109272
Train Epoch: 8 [4480]	Loss: 0.249333
Train Epoch: 8 [5120]	Loss: 0.226237
Train Epoch: 8 [5760]	Loss: 0.276430
Train Epoch: 8 [6400]	Loss: 0.310856
Train Epoch: 8 [7040]	Loss: 0.125033
Train Epoch: 8 [7680]	Loss: 0.087205
Train Epoch: 8 [8320]	Loss: 0.207336
Train Epoch: 8 [8960]	Loss: 0.178555
Train Epoch: 8 [9600]	Loss: 0.241254
Train Epoch: 8 [10240]	Loss: 0.395371
Train Epoch: 8 [10880]	Loss: 0.155893
Train Epoch: 8 [11520]	Loss: 0.223370
Train Epoch: 8 [12160]	Loss: 0.176467
Train Epoch: 8 [12800]	Loss: 0.197149
Train Epoch: 8 [13440]	Loss: 0.207378
Train Epoch: 8 [14080]	Loss: 0.176353
Train Epoch: 8 [14720]	Loss: 0.218597
Train Epoch: 8 [15360]	Loss: 0.276840
Train Epoch: 8 [16000]	Loss: 0.370336
Train Epoch: 8 [16640]	Loss: 0.330776
Train Epoch: 8 [17280]	Loss: 0.062488
Train Epoch: 8 [17920]	Loss: 0.100223
Train Epoch: 8 [18560]	Loss: 0.126668
Train Epoch: 8 [19200]	Loss: 0.209926
Train Epoch: 8 [19840]	Loss: 0.124070
Train Epoch: 8 [20480]	Loss: 0.162006
Train Epoch: 8 [21120]	Loss: 0.197650
Train Epoch: 8 [21760]	Loss: 0.138141
Train Epoch: 8 [22400]	Loss: 0.094706
Train Epoch: 8 [23040]	Loss: 0.337466
Train Epoch: 8 [23680]	Loss: 0.219723
Train Epoch: 8 [24320]	Loss: 0.104830
Train Epoch: 8 [24960]	Loss: 0.159212
Train Epoch: 8 [25600]	Loss: 0.181168
Train Epoch: 8 [26240]	Loss: 0.154889
Train Epoch: 8 [26880]	Loss: 0.258730
Train Epoch: 8 [27520]	Loss: 0.147021
Train Epoch: 8 [28160]	Loss: 0.288530
Train Epoch: 8 [28800]	Loss: 0.148682
Train Epoch: 8 [29440]	Loss: 0.058572
Train Epoch: 8 [30080]	Loss: 0.225266
Train Epoch: 8 [30720]	Loss: 0.122578
Train Epoch: 8 [31360]	Loss: 0.246804
Train Epoch: 8 [32000]	Loss: 0.276243
Train Epoch: 8 [32640]	Loss: 0.108334
Train Epoch: 8 [33280]	Loss: 0.213710
Train Epoch: 8 [33920]	Loss: 0.172510
Train Epoch: 8 [34560]	Loss: 0.083054
Train Epoch: 8 [35200]	Loss: 0.303114
Train Epoch: 8 [35840]	Loss: 0.334981
Train Epoch: 8 [36480]	Loss: 0.141909
Train Epoch: 8 [37120]	Loss: 0.165625
Train Epoch: 8 [37760]	Loss: 0.296360
Train Epoch: 8 [38400]	Loss: 0.144463
Train Epoch: 8 [39040]	Loss: 0.032683
Train Epoch: 8 [39680]	Loss: 0.197244
Train Epoch: 8 [40320]	Loss: 0.091684
Train Epoch: 8 [40960]	Loss: 0.318707
Train Epoch: 8 [41600]	Loss: 0.155329
Train Epoch: 8 [42240]	Loss: 0.193886
Train Epoch: 8 [42880]	Loss: 0.181515
Train Epoch: 8 [43520]	Loss: 0.196627
Train Epoch: 8 [44160]	Loss: 0.113538
Train Epoch: 8 [44800]	Loss: 0.235946
Train Epoch: 8 [45440]	Loss: 0.257220
Train Epoch: 8 [46080]	Loss: 0.239904
Train Epoch: 8 [46720]	Loss: 0.244768
Train Epoch: 8 [47360]	Loss: 0.224074
Train Epoch: 8 [48000]	Loss: 0.167662
Train Epoch: 8 [48640]	Loss: 0.150174
Train Epoch: 8 [49280]	Loss: 0.163935
Train Epoch: 8 [49920]	Loss: 0.114764
Train Epoch: 8 [50560]	Loss: 0.159651
Train Epoch: 8 [51200]	Loss: 0.372867
Train Epoch: 8 [51840]	Loss: 0.114531
Train Epoch: 8 [52480]	Loss: 0.092066
Train Epoch: 8 [53120]	Loss: 0.153045
Train Epoch: 8 [53760]	Loss: 0.071268
Train Epoch: 8 [54400]	Loss: 0.068548
Train Epoch: 8 [55040]	Loss: 0.111004
Train Epoch: 8 [55680]	Loss: 0.203602
Train Epoch: 8 [56320]	Loss: 0.135373
Train Epoch: 8 [56960]	Loss: 0.182411
Train Epoch: 8 [57600]	Loss: 0.189879
Train Epoch: 8 [58240]	Loss: 0.072110
Train Epoch: 8 [58880]	Loss: 0.016181
Train Epoch: 8 [59520]	Loss: 0.044500
2019-03-20 14:58:49 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:58:49 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:58:49 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:58:49 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:58:49 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:58:49 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:58:49 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:58:49 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:58:49 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 8236896b-ce32-4217-b3f0-42640bdc19e1 is 0. Current running tasks are 

Test set: Average loss: 0.0600, Accuracy: 9815/10000 (98%)

2019-03-20 14:58:55 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:58:55 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:58:55 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:58:55 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:58:55 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:58:55 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:58:55 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:58:55 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:58:56 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 26b102d1-830e-482f-95b1-86951ba7ea82 is 0. Current running tasks are 
Train Epoch: 9 [0]	Loss: 0.131657
Train Epoch: 9 [640]	Loss: 0.059061
Train Epoch: 9 [1280]	Loss: 0.282538
Train Epoch: 9 [1920]	Loss: 0.117102
Train Epoch: 9 [2560]	Loss: 0.140965
Train Epoch: 9 [3200]	Loss: 0.131497
Train Epoch: 9 [3840]	Loss: 0.057273
Train Epoch: 9 [4480]	Loss: 0.184212
Train Epoch: 9 [5120]	Loss: 0.264503
Train Epoch: 9 [5760]	Loss: 0.163100
Train Epoch: 9 [6400]	Loss: 0.254767
Train Epoch: 9 [7040]	Loss: 0.211086
Train Epoch: 9 [7680]	Loss: 0.113581
Train Epoch: 9 [8320]	Loss: 0.129519
Train Epoch: 9 [8960]	Loss: 0.194726
Train Epoch: 9 [9600]	Loss: 0.269754
Train Epoch: 9 [10240]	Loss: 0.345229
Train Epoch: 9 [10880]	Loss: 0.109983
Train Epoch: 9 [11520]	Loss: 0.231946
Train Epoch: 9 [12160]	Loss: 0.274068
Train Epoch: 9 [12800]	Loss: 0.245801
Train Epoch: 9 [13440]	Loss: 0.162373
Train Epoch: 9 [14080]	Loss: 0.245791
Train Epoch: 9 [14720]	Loss: 0.231902
Train Epoch: 9 [15360]	Loss: 0.263097
Train Epoch: 9 [16000]	Loss: 0.239213
Train Epoch: 9 [16640]	Loss: 0.343002
Train Epoch: 9 [17280]	Loss: 0.060418
Train Epoch: 9 [17920]	Loss: 0.116341
Train Epoch: 9 [18560]	Loss: 0.093712
Train Epoch: 9 [19200]	Loss: 0.343085
Train Epoch: 9 [19840]	Loss: 0.187094
Train Epoch: 9 [20480]	Loss: 0.126354
Train Epoch: 9 [21120]	Loss: 0.211115
Train Epoch: 9 [21760]	Loss: 0.079328
Train Epoch: 9 [22400]	Loss: 0.131795
Train Epoch: 9 [23040]	Loss: 0.268449
Train Epoch: 9 [23680]	Loss: 0.174875
Train Epoch: 9 [24320]	Loss: 0.035407
Train Epoch: 9 [24960]	Loss: 0.192064
Train Epoch: 9 [25600]	Loss: 0.030683
Train Epoch: 9 [26240]	Loss: 0.331260
Train Epoch: 9 [26880]	Loss: 0.276717
Train Epoch: 9 [27520]	Loss: 0.129356
Train Epoch: 9 [28160]	Loss: 0.125225
Train Epoch: 9 [28800]	Loss: 0.198220
Train Epoch: 9 [29440]	Loss: 0.142949
Train Epoch: 9 [30080]	Loss: 0.288696
Train Epoch: 9 [30720]	Loss: 0.204790
Train Epoch: 9 [31360]	Loss: 0.162738
Train Epoch: 9 [32000]	Loss: 0.133145
Train Epoch: 9 [32640]	Loss: 0.080335
Train Epoch: 9 [33280]	Loss: 0.076079
Train Epoch: 9 [33920]	Loss: 0.082205
Train Epoch: 9 [34560]	Loss: 0.154868
Train Epoch: 9 [35200]	Loss: 0.402400
Train Epoch: 9 [35840]	Loss: 0.320517
Train Epoch: 9 [36480]	Loss: 0.108865
Train Epoch: 9 [37120]	Loss: 0.233512
Train Epoch: 9 [37760]	Loss: 0.171635
Train Epoch: 9 [38400]	Loss: 0.132088
Train Epoch: 9 [39040]	Loss: 0.044784
Train Epoch: 9 [39680]	Loss: 0.135655
Train Epoch: 9 [40320]	Loss: 0.097692
Train Epoch: 9 [40960]	Loss: 0.299618
Train Epoch: 9 [41600]	Loss: 0.149204
Train Epoch: 9 [42240]	Loss: 0.171862
Train Epoch: 9 [42880]	Loss: 0.268623
Train Epoch: 9 [43520]	Loss: 0.242356
Train Epoch: 9 [44160]	Loss: 0.164874
Train Epoch: 9 [44800]	Loss: 0.122416
Train Epoch: 9 [45440]	Loss: 0.250456
Train Epoch: 9 [46080]	Loss: 0.146218
Train Epoch: 9 [46720]	Loss: 0.177949
Train Epoch: 9 [47360]	Loss: 0.264691
Train Epoch: 9 [48000]	Loss: 0.125752
Train Epoch: 9 [48640]	Loss: 0.120864
Train Epoch: 9 [49280]	Loss: 0.069218
Train Epoch: 9 [49920]	Loss: 0.264876
Train Epoch: 9 [50560]	Loss: 0.228902
Train Epoch: 9 [51200]	Loss: 0.257688
Train Epoch: 9 [51840]	Loss: 0.056373
Train Epoch: 9 [52480]	Loss: 0.050665
Train Epoch: 9 [53120]	Loss: 0.126954
Train Epoch: 9 [53760]	Loss: 0.187967
Train Epoch: 9 [54400]	Loss: 0.099100
Train Epoch: 9 [55040]	Loss: 0.133680
Train Epoch: 9 [55680]	Loss: 0.151748
Train Epoch: 9 [56320]	Loss: 0.065836
Train Epoch: 9 [56960]	Loss: 0.124708
Train Epoch: 9 [57600]	Loss: 0.190154
Train Epoch: 9 [58240]	Loss: 0.136770
Train Epoch: 9 [58880]	Loss: 0.072374
Train Epoch: 9 [59520]	Loss: 0.062970
2019-03-20 14:59:47 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:59:47 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:59:47 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:59:47 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:59:47 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:59:47 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:59:47 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:59:47 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:59:47 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task a9dd3c8f-a284-4e25-af05-50df267e5d47 is 0. Current running tasks are 

Test set: Average loss: 0.0546, Accuracy: 9828/10000 (98%)

2019-03-20 14:59:53 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:59:53 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:59:53 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 14:59:53 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 14:59:53 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 14:59:53 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 14:59:53 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 14:59:53 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 14:59:53 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task 7cf2e847-5e27-4057-9b7d-04ca623e5625 is 0. Current running tasks are 
Train Epoch: 10 [0]	Loss: 0.157934
Train Epoch: 10 [640]	Loss: 0.024991
Train Epoch: 10 [1280]	Loss: 0.139293
Train Epoch: 10 [1920]	Loss: 0.217213
Train Epoch: 10 [2560]	Loss: 0.094404
Train Epoch: 10 [3200]	Loss: 0.145280
Train Epoch: 10 [3840]	Loss: 0.073621
Train Epoch: 10 [4480]	Loss: 0.145945
Train Epoch: 10 [5120]	Loss: 0.140010
Train Epoch: 10 [5760]	Loss: 0.158769
Train Epoch: 10 [6400]	Loss: 0.240596
Train Epoch: 10 [7040]	Loss: 0.126470
Train Epoch: 10 [7680]	Loss: 0.201828
Train Epoch: 10 [8320]	Loss: 0.129035
Train Epoch: 10 [8960]	Loss: 0.169470
Train Epoch: 10 [9600]	Loss: 0.249120
Train Epoch: 10 [10240]	Loss: 0.286503
Train Epoch: 10 [10880]	Loss: 0.138080
Train Epoch: 10 [11520]	Loss: 0.364770
Train Epoch: 10 [12160]	Loss: 0.175269
Train Epoch: 10 [12800]	Loss: 0.089608
Train Epoch: 10 [13440]	Loss: 0.183963
Train Epoch: 10 [14080]	Loss: 0.068392
Train Epoch: 10 [14720]	Loss: 0.289272
Train Epoch: 10 [15360]	Loss: 0.188141
Train Epoch: 10 [16000]	Loss: 0.209769
Train Epoch: 10 [16640]	Loss: 0.364886
Train Epoch: 10 [17280]	Loss: 0.067130
Train Epoch: 10 [17920]	Loss: 0.118737
Train Epoch: 10 [18560]	Loss: 0.120383
Train Epoch: 10 [19200]	Loss: 0.103540
Train Epoch: 10 [19840]	Loss: 0.247157
Train Epoch: 10 [20480]	Loss: 0.055414
Train Epoch: 10 [21120]	Loss: 0.245621
Train Epoch: 10 [21760]	Loss: 0.166192
Train Epoch: 10 [22400]	Loss: 0.153272
Train Epoch: 10 [23040]	Loss: 0.208131
Train Epoch: 10 [23680]	Loss: 0.245485
Train Epoch: 10 [24320]	Loss: 0.042757
Train Epoch: 10 [24960]	Loss: 0.133654
Train Epoch: 10 [25600]	Loss: 0.136447
Train Epoch: 10 [26240]	Loss: 0.154257
Train Epoch: 10 [26880]	Loss: 0.078691
Train Epoch: 10 [27520]	Loss: 0.235755
Train Epoch: 10 [28160]	Loss: 0.130210
Train Epoch: 10 [28800]	Loss: 0.229463
Train Epoch: 10 [29440]	Loss: 0.060868
Train Epoch: 10 [30080]	Loss: 0.224706
Train Epoch: 10 [30720]	Loss: 0.115355
Train Epoch: 10 [31360]	Loss: 0.182676
Train Epoch: 10 [32000]	Loss: 0.121437
Train Epoch: 10 [32640]	Loss: 0.087172
Train Epoch: 10 [33280]	Loss: 0.105006
Train Epoch: 10 [33920]	Loss: 0.063366
Train Epoch: 10 [34560]	Loss: 0.077966
Train Epoch: 10 [35200]	Loss: 0.242928
Train Epoch: 10 [35840]	Loss: 0.176073
Train Epoch: 10 [36480]	Loss: 0.097494
Train Epoch: 10 [37120]	Loss: 0.216588
Train Epoch: 10 [37760]	Loss: 0.254439
Train Epoch: 10 [38400]	Loss: 0.196087
Train Epoch: 10 [39040]	Loss: 0.083074
Train Epoch: 10 [39680]	Loss: 0.143313
Train Epoch: 10 [40320]	Loss: 0.069078
Train Epoch: 10 [40960]	Loss: 0.194661
Train Epoch: 10 [41600]	Loss: 0.089956
Train Epoch: 10 [42240]	Loss: 0.145244
Train Epoch: 10 [42880]	Loss: 0.105328
Train Epoch: 10 [43520]	Loss: 0.230065
Train Epoch: 10 [44160]	Loss: 0.100717
Train Epoch: 10 [44800]	Loss: 0.245473
Train Epoch: 10 [45440]	Loss: 0.260901
Train Epoch: 10 [46080]	Loss: 0.301113
Train Epoch: 10 [46720]	Loss: 0.201933
Train Epoch: 10 [47360]	Loss: 0.195668
Train Epoch: 10 [48000]	Loss: 0.122407
Train Epoch: 10 [48640]	Loss: 0.066318
Train Epoch: 10 [49280]	Loss: 0.162691
Train Epoch: 10 [49920]	Loss: 0.198229
Train Epoch: 10 [50560]	Loss: 0.069079
Train Epoch: 10 [51200]	Loss: 0.504960
Train Epoch: 10 [51840]	Loss: 0.156962
Train Epoch: 10 [52480]	Loss: 0.097819
Train Epoch: 10 [53120]	Loss: 0.128436
Train Epoch: 10 [53760]	Loss: 0.121727
Train Epoch: 10 [54400]	Loss: 0.093868
Train Epoch: 10 [55040]	Loss: 0.193212
Train Epoch: 10 [55680]	Loss: 0.255295
Train Epoch: 10 [56320]	Loss: 0.132586
Train Epoch: 10 [56960]	Loss: 0.197574
Train Epoch: 10 [57600]	Loss: 0.280921
Train Epoch: 10 [58240]	Loss: 0.072130
Train Epoch: 10 [58880]	Loss: 0.027580
Train Epoch: 10 [59520]	Loss: 0.036734
2019-03-20 15:00:44 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 15:00:44 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 15:00:44 INFO  CarbonInputFormat:494 - Started block pruning ...
2019-03-20 15:00:44 INFO  CarbonInputFormat:550 - Finished block pruning ...
2019-03-20 15:00:44 INFO  QueryModelBuilder:94 - Projection Columns: [image, digit, idx]
2019-03-20 15:00:44 INFO  AbstractQueryExecutor:122 - Query will be executed on table: null
2019-03-20 15:00:44 INFO  ResultCollectorFactory:68 - Vector based dictionary collector is used to scan and collect the data
2019-03-20 15:00:44 INFO  DictionaryBasedVectorResultCollector:71 - Direct pagewise vector fill collector is used to scan and collect the data
2019-03-20 15:00:44 INFO  UnsafeMemoryManager:176 - Total offheap working memory used after task cb2a4296-321b-4c44-b521-0bfaa5a0794e is 0. Current running tasks are 

Test set: Average loss: 0.0508, Accuracy: 9843/10000 (98%)


Process finished with exit code 0
