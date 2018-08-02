## A JAVA implementation of the CoAP - Java使用netty封装CoAP通信

This implementation of the Constrained Application Protocol bases on the asynchronous and event-driven network
application framework [Netty](http://netty.io) (thats where the 'n' in nCoAP comes from). The nCoAP framework
currently covers

* the raw protocol ([RFC 7252](https://tools.ietf.org/html/rfc7252)),
* the observation of CoAP resources ([RFC 7641](https://tools.ietf.org/html/rfc7641)),
* the blockwise transfer ([draft 19](https://tools.ietf.org/html/draft-ietf-core-block-19)),
* the identification of endpoints with changing IPs
([draft 01](https://tools.ietf.org/html/draft-kleine-core-coap-endpoint-id-01)) , and
* the CoRE Link Format ([RFC 6690](https://tools.ietf.org/html/rfc6690)).

but without DTLS (i.e. support for the coaps scheme). 

provide simple CoAP applications for both, client and server. There intention is to highlight, how easy it is to
write such applications using ncoap. 

实例中有client、server可进行测试调用