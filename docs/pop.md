# AWS Points of Presence

- AWS provides global network of Points of Presence locations.

- It consists of edge locations and regional edge caches.

- Amazon CloudFront is a content delivery network (CDN) used to distribute content to end users to reduce latency. Amazon Route 53 is a Domain Name System (DNS) service. Requests going to either one of these services will be routed to the nearest edge location automatically in order to lower latency.

- Regional edge caches are used by default with Amazon CloudFront. They are used when you have content that is not accessed frequently enough to remain in an edge location.

- Regional edge caches absorb this content and provide an alternative to fetching the content from the origin server.

- Regional edge caches sit between your origin webserver and the global edge locations that serve traffic directly to your viewers.

- Regional Edge Caches have larger cache-width than any individual edge location, so your objects remain in cache longer at these locations.
