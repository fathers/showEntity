showEntity
A client-server system to allow several reservation agencies to make seat reservation for various shows.

The implementation has to be done using only session beans on the server side.

The server should provide 3 methods :
the first one allows to make a reservation. It takes as parameters: the agency name, the client name, the number of seats to be reserved. It returns a unique reservation identifier as a result. This method fails if the number of available seats is lower than the number requested.

   The first one allows to make a reservation. It takes as parameters: the agency name, the client name, the number of seats to be reserved. It returns a unique reservation identifier as a result. This method fails if the number of available seats is lower than the number requested.
   The second method allows to cancel a reservation using its identifier.
   The last method allows to get informations such as the show room name, the room capacity, the number of available seats and the show name.
