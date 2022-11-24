import java.util.Arrays;

public class Passengers {
    String PassengerList[];
    int capacity;

    void PassengerCapacity (){
        PassengerList = new String[capacity];
    }
    void AddPassenger(int id, String PassengerName){

        PassengerList[id] = PassengerName;
        System.out.println("The passenger is added successfully.");
    }

    void viewTotalPassengers(){

        System.out.println("Passenger list " +  Arrays.toString(PassengerList));
    }

    void RemovePassenger (int id){

        PassengerList [id] = null;
        System.out.println("The Passenger is removed successfully.");
    }
    void updatePassenger (int id, String PassengerName) {
        PassengerList[id] = PassengerName;
        System.out.println("The Passenger is updated successfully.");
    }
    int Totalpassenger (){
        return PassengerList.length;
    }
}
