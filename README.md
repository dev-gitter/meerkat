# Meerkat Lightweight Embedded Web Server

Lightweight Web Server for your application needs.
Turn anything into a web server fast.

- [Documentation](http://cesanta.com/docs.shtml) - configuration options and API reference
- [Examples](https://github.com/cesanta/mongoose/examples) - example programs
for various use cases

Check out Fossa - our [embedded multi-protocol library](https://github.com/cesanta/fossa) with TCP,UDP,HTTP,Websocket,MQTT,DNS support, designed for Internet Of Things!

# Features

- Works on Windows, Mac, UNIX/Linux, iPhone, Android eCos, QNX
and many other platforms
- Digest auth, URL rewrite, file blacklist
- Custom error pages, Virtual hosts, IP-based ACL, HTTP client
- Simple and clean
  [embedding API](meerkat.h). The source code is in single
  [meerkat.c](meerkat.c) file to make embedding easy
- Extremely lightweight, has a core of under 40kB and tiny runtime footprint
- Asynchronous, non-blocking core supporting single- or multi-threaded usage
- Stable, mature and tested, has several man-years invested
  in continuous improvement and refinement

Note: Meerkat does NOT support HTTPS, CGI, SSI, Websocket.

# Licensing

Meerkat is released under commercial and
[GNU GPL v.2](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html) open
source licenses. The GPLv2 open source License does not generally permit
incorporating this software into non-open source programs. 
For those customers who do not wish to comply with the GPLv2 open
source license requirements,
[Cesanta Software](http://cesanta.com) offers a full,
royalty-free commercial license and professional support
without any of the GPL restrictions.
