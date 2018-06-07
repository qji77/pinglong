# pinglong

pinglong is the useful ping for long run pings.

It's written in python3 and uses the standard ping or ping6 command, but gives you a nicer output, especially when you run ping for long.

It's currenly tested only on Linux.

## example outpout

```
$ pinglong testhost.example.com
PING testhost.example.com (11.22.33.44)
17:31: ..............................   0.0%      28.896      28.952      29.138
17:32: .............................x   3.3%      28.905      28.934      29.018
17:33: .............x...............x   6.7%      28.888      28.925      29.014
17:34: .....x........................   3.3%      28.891      28.936      28.996
17:35: .....xx.....x..........x......  13.3%      28.878      28.954      29.176
17:36: .....x........................   3.3%      28.901      28.944      29.044
17:37: ..............................   0.0%      28.911      28.953      29.054
17:38: ..............................   0.0%      28.904      28.962      29.013
17:39: ..............................   0.0%      28.897      28.967      29.208
17:40: ..............................   0.0%      28.878      28.942      29.027
17:41: ..............................   0.0%      28.897      28.946      29.227
17:42: ..............................   0.0%      28.896      28.972      29.33
17:43: ..............................   0.0%      28.91       28.958      29.026
17:44: ..............................   0.0%      28.906      28.962      29.014
17:45: ..............................   0.0%      28.896      28.977      29.315
17:46: ..............................   0.0%      28.89       28.949      29.118
17:47: ..............................   0.0%      28.892      28.946      29.015
17:48: ..............................   0.0%      28.886      28.925      29.016
17:49: ..............................   0.0%      28.895      28.968      29.21
17:50: ..............................   0.0%      28.898      28.944      29.011
17:51: ..............................   0.0%      28.908      28.963      29.447
17:52: ..............................   0.0%      28.898      28.948      29.075
17:53: ............................xx   6.7%      28.902      29.008      29.86
17:54: ..............................   0.0%      28.907      28.957      29.045
17:55: ..............................   0.0%      28.904      28.958      29.051
17:56: ..............................   0.0%      28.898      28.979      29.486
17:57: ..............................   0.0%      28.904      28.984      29.711
17:58: ..............................   0.0%      28.894      28.944      29.002
17:59: ..............................   0.0%      28.905      28.971      29.616
Time         x=lost   .=OK            loss(%)    min [ms]    avg [ms]    max [ms]
18:00: ..............................   0.0%      28.899      28.945      29.095
18:01: ..............................   0.0%      28.905      28.950      29.034
18:02: ..............................   0.0%      28.896      28.931      28.971
18:03: ..............................   0.0%      28.896      28.953      29.038
18:04: ..............................   0.0%      28.908      28.968      29.13
18:05: ..............................   0.0%      28.858      28.973      29.801
18:06: ..............................   0.0%      28.895      28.946      29.029
18:07: ..............................   0.0%      28.9        28.947      29.011
18:08: ..............................   0.0%      28.917      28.977      29.41
18:09: ..............................   0.0%      28.886      28.942      29.054
18:10: ..............................   0.0%      28.897      28.949      29.027
18:11: ..............................   0.0%      28.893      28.950      29.06
18:12: ..xxxxxxxxxxxxxxxxxxxxxxxxxxxx  93.3%      28.91       28.917      28.924
18:13: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxx  100.0%
18:14: ..xxx.........................  10.0%      28.889      28.946      29.018
18:15: ..............................   0.0%      28.881      28.956      29.057
18:16: ........................^C       0.0%      28.908      28.954      29.012

Total: 1374 packets transmitted, 1302 received, 5% packet loss
       RTT: min/avg/max = 28.858/28.955/29.86 ms
       Downtime: sum =~ 141.4 sec
```
