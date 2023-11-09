# Reliable Transmission

Reliable Transmission is a service that ensures data is delivered from the source to the destination without any errors. This includes mechanisms that provide accurate, on-time delivery of all packets while managing packet loss, duplication, or out-of-order delivery. In server-side game development, protocols like TCP (Transmission Control Protocol) are often used to accomplish reliable transmission. Reliable transmission is particularly necessary for critical data where all transmitted information must arrive at the destination correctly and in the right order. TCP accomplishes this by establishing a connection before data transfer begins and using sequence numbers to track delivery and reassemble pieces in the correct order. TCP also sends acknowledgements back to the source confirming packet delivery, and implements re-transmission of lost or corrupted data. Despite its overhead and slower speed compared to other methods, such as the User Datagram Protocol (UDP), reliable transmission is vital when data integrity is a priority over speed.