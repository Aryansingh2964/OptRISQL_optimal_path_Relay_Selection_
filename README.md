# OptRISQL_optimal_path_Relay_Selection_

In order to transfer data produced by IoT devices at the source, we applied Q-Learning to determine the most energy-efficient route from the source to the gateway. Within the network, we introduced an RTS/CTS-based routing system to prevent data congestion, thereby enhancing the gateway's throughput by eliminating data loss. Our approach minimizes the memory demands of the IoT network, resulting in improved throughput. Although our model experiences some additional data latency, this can be mitigated by enlarging the queue size allocated to each source node.

Results:

1. Enhanced throughput due to a decrease in data loss.
2. The memory demand of the dynamic IoT network has been lessened.
3. The interference of network nodes was minimized by implementing the RTS/CTS protocol.
4. Despite the rise in transmission time, expanding the queue size of the source node might help decrease it to some degree.
