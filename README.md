# Array_compaction
//This is a function that takes as input sorted array modifies the array to compact it and remove duplicate


public class Duplicate{
public static ArrayList<integer>rmvDup(Arraylist <integer> comp){
         int count=0, ArrayList<integer> noDup=new ArrayList();
          comp.sort=(null);
          int i= comp.size();
              for (int i=0; i<1; i++){
              If (i!= i-1 && comp.get (i). compareTo (comp.get(i+1))== 0) count++;
              else{
              noDup.add( comp.get(i));
              count = 0
              }
              } return noDup;
              
}
public static void main( string {} args){
ArrayList<integer> sort = new ArrayList<integer> ();
sort.add(2);
sort.add(7);
sort.add(2);
sort.add(9);
sort.add(5);
sort.add(4);
sort.add(7);
sort.add(10);
sort.add(6);
sort.add(8);
sort.add(12);
sort.add(9);
System.out.println(rmvDup (sort));
}

}
