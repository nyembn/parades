It is a demonstration of thread synchronization in Java. It follows a story as the following.
Students from two different schools will participate in a Halloween Parade.
The students from one school wear blue costumes, and the other students wear
orange costumes. Students arrive at the meeting place (simulated by
sleep( random )) in front of the stadium and group in formations of two orange
and one blue costume. Once a group is formed (students of the same group will
wait on the same notification object), it will start parading around the stadium
(sleep( random )) . Only students in groups may march in the parade. The very
last group can start marching even it is incomplete. After each circle around the
stadium, students separate from their groups and take a snack break (simulated
by sleep( random )).
Parades: 6 Parades in interval of 1 hour.
Students will terminate after the last parade ends or if they already managed to
participate in three parades.
