# Flight-Tracking-System

An Airport has a runway for planes landing and take-off. When the runway is busy, planes wishing to take-off or land must wait. Landing planes get priority, and if the runway is available, it can be used.

A Java class, Airport.java has been implemented for this simulation, using two appropriate lists, one for the planes waiting to take-off and one for those waiting to land. For instance, the sooner a plane comes for landing, the sooner it will land. Also, the record of all the planes that have already landed or taken-off are stored in one single list, to print out the activity log whenever asked, such that the sooner a plane landed, the later it shows in the printout.

Commands:

"t flight-number (for taking off the plane with the flight number flight-number), l flight-number (for landing the plane with the flight number flight-number), n (for conducting the next possible landing or taking off operation), p (for printing the status of the two queues), g (for printing the list of the planes already taken-off or landed), q (to quit the program)"

Methods Used:

"The Airport, addTakeOff, addLanding, handleNextAction, waitingPlanes, log"

A Tester Class, AirportTester.java is also attached with the rest of the files in order to implement the Airport.java class.
