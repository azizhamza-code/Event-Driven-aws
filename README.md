# Event-Driven-aws
lab storage-first pattern

The storage-first pattern is a way of reducing latency in an application by moving storage closer to the API layer. In this pattern, the API layer accepts the request and immediately writes the data to storage. It then responds back to the user quickly, while the compute layer processes the data asynchronously. This allows the user to continue without waiting for the compute layer to finish processing the data. This is especially useful during scaling events when the backend may be overwhelmed with requests.
