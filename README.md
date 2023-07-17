# problem-4
import java.util.HashMap;
import java.util.Map;
public class MultipleCountInDictionary {
public static void main(String[] args) {
Map<String,Integer>dictionary=new HashMap<> ();
dictionary.put("number1",12);
dictionary.put("number2",45);
dictionary.put("number3",7);
dictionary.put("number4",18);
dictionary.put("number5",25);
int[] multiples ={1,2,3,5,5,6,7,8,9};
int totalCount=countMultiplesInDictionary(dictionary,multiples);
System.out.println("Total count of numbers that are multiples:"+totalCount);
}
public static int countMultiplesInDictionary(Map<String,integer>dictionary,int[]multiples) {
int totalCount=0;
for(int number:dictionary.values()) {
for(int multiples:multiples) {
}
}
}
