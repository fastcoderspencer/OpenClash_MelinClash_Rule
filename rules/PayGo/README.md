# Ultra Mobile PayGo & T-Mobile
* 加了一个 Ultra Mobile PayGo的分流规则自用，因为Wifi Calling 总是出不来，然后自己选择美国节点就OK了，瞬间秒出来
* 同样适用于 T-Mobile

* 我自己抓包看 在打开WIFI启用WIFI-Calling时，只看到的只有这个链接请求
  `ss.epdg.epc.geo.mnc260.mcc310.pub.3gppnetwork.org:4500 udp`
* 故意添加了
  `DOMAIN-SUFFIX,mnc260.mcc310.pub.3gppnetwork.org`
