
Welcome to Group 41 Elevator project’s documentation!
*****************************************************


Indices and tables
******************

*  `Index <genindex.rst>`_

*  `Module Index <py-modindex.rst>`_

*  `Search Page <search.rst>`_


Docs
****

``struct elevator_t``

**int32_t tcp_connect(peer_connection_t peer)**

   Establishes a TCP connection based on a peer_connection_t peer.

   Creates a thread which connects to a peer, and maintains a
   connection which can be accessed through the returned
   channel_socket file descriptor. The connection is terminated when
   the connection is terminated by the peer, or the channel_socket is
   closed.

   :Parameters:
      **peer[in]** – A peer_connection_t structure containing all
      information required to establish a connection.

   :Returns:
      server_socket The file descriptor for message passing between
      threads
