# Ex1
In the grupAdmin class we wrote (which implements the sender interface), there is an option to update all members of the group with every update that happens to undoStringBilder.
The possible changes that undoStringBilder can have are:
  Insert a String to a specific place in the Current String.
We did this by calling the function we already wrote in the undoStringBilder class from assignment 0.
to append new String to the end of the current String.
Delete all the chars between two indexes.
Undo the last change in the String Builder.
Every change we will update all those registered to groupAdmin using the notifyObservers function which simply goes through all the members and updates their srtingBilder.
In groupAdmin there is an option to add and remove members.
The concrettt class (which implements the Member interface) represents a member in the groupAdmin list and has the update function that updates the member's undoStri to be in accordance with the undo of the groupAghkl to which it belongs.
The design template we wrote according to is observe.
The groupAdmin class is the observable that sends the updates and the ConcreteMember is the observer for which the updates are made.

