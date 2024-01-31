       DIFFERENTIATE BETWEEN HTTP/1,1 VS HTTP/2

HTTP/1.1:
1.Introduction :
 The first usable version of HTTP was created in 1997.It relies on a straightforward request-response mechanism,where each element is requested and delivered individually and it has limitation

2.Multiplexing:
limited to one request/response at a time per connection,causing delays

3.Prioritization:
Lack native support for prioritizing request,potentially affecting the order in which resources are loaded.

4:Connection Handling:
 Uses multiple connections for paralleslism,leading to slower page loads due to connection overhead.

5.Header Compression:
   Headers are not compressed,resulting in increased latency and bandwidth usage.


HTTP/2:   

1.Introduction :
  A  new version of HTTP called HTTP/2 was created.HTTP/2 solves several problems that the creators of http/1.1 did not anticipate.It is much faster and more efficient than HTTP/1.1.It was derived from the earlier experimental SPDY protocol.

2.Multiplexing:
  Supports concurrent requests and response over a single connection,enhancing speed.

3.Prioritization:
  Introduces stream prioritization, allowing servers to prioritize critical resources,improving page rendering.

4:Connection Handling:
  Utilizes a single,multiplexed connection,reducing latency and improving efficiency.

5.Header Compression:
  Implements header compression,reducing the amount of data transmitted and improving performance.     