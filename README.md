# Ex1
In the GroupAdmin class (which implements the sender interface) , there is an option to update all group members with every update that happens to UndoableStringBuilder.
The possible changes UndoableStringBuilder can have are:
An append function that adds a string to the end of the current string.
A Insert functionthat adds a String to a specific place in the Current String.
A delete function that deletes all characters between two indexes.
and an undo function that undoes the last change we made in the UndoableStringBuilder.
Every change we will update all the members who are registered to the GroupAdmin ,using the notifyObservers function which simply goes through all the members and updates their UndoableStringBuilder.
In GroupAdmin there is an option to add and remove members.
The ConcreteMember class (which implements the Member interface) represents a member of the GroupAdmin list.
To this class has the update function that updates its UndoableStringBuilder to match the update of the UndoableStringBuilder of the GroupAdmin to which it belongs.
The design pattern we wrote according to is Observer.
The GroupAdmin class is the observerable that sends the updates and the ConcreteMember is the observer for which the updates are made.
