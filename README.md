# node-amf 

Fork of [AMF module](https://github.com/timwhitlock/node-amf) for NodeJS by [Tim Whitlock](http://twitter.com/timwhitlock)

I forked this in order to experiment with improving the library performance,
but unfortunately I wasn't able to get better than a 2x speedup for
deserialization, so I ended up writing my own native module [node_amf_cc](https://www.npmjs.org/package/node_amf_cc) which gets 10-20x better performance.
node_amf_cc is the only module I plan to maintain going forward, but feel free to play with the deserialization speedup here.

