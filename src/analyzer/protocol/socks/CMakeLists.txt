zeek_add_plugin(
    Zeek SOCKS
    SOURCES SOCKS.cc Plugin.cc
    BIFS events.bif
    PAC socks.pac socks-protocol.pac socks-analyzer.pac)
