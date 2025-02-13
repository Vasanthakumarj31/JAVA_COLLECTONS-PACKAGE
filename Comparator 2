//import java.util.Collection;
import java.util.List;
import java.util.ArrayList;
import java.util.Comparator;
import java.util.Collections;

class Student{
    int age;
    String name;
    Student(String name,int age){
        this.age=age;
        this.name=name;
    }
    public String toString(){
        return "name"+name+"age"+age;
    }
}

public class Main {
	public static void main(String[] args) {
		
		Comparator<Student> com=new Comparator<Student>(){
		    public int compare(Student a,Student b){
		  /*      if(a%10 <b%10)
		              return 1;
		        else
		            return 0;*/
		            return Integer.compare(a.age,b.age);
		        }
		        };
		  List<Student> obj=new ArrayList<>();
		  obj.add(new Student("vasan",20));
		  obj.add(new Student("loges",19));
		  obj.add(new Student("vicky",17));
		  obj.add(new Student("tiger",16));
	//	  Collections.sort(obj,com);
		//  System.out.println(obj);
		   for(Student s : obj){
		       System.out.println(s);
		   }
		       
		    }
		}
		            
		        
		        
		              
		
		
	
