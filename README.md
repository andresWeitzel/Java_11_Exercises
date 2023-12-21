# Java_11_Exercises
Exercises with java 11. For example String class,  Files class, Collection interface, Lambdas, Reflection Api, others.

* [Oficial documentation](https://docs.oracle.com/en/java/javase/11/)
* [Recommended Guide](https://www.baeldung.com/java-11-new-features)
* [Online Java Compiler](https://www.jdoodle.com/online-java-compiler)

 <br>

<!------Start Index----->

## Index 📜

<details>
 <summary> See </summary>
 <br>
  
### String Methods
* [Using the isBlank method.](#make-a-simple-request-to-a-host-with-http-)
* [Create a server with http](#create-a-server-with-http-)
   
<br>

</details>

<!------Stop Index----->

<br>

<br>


## Project execution [🔝](#index-)

<details>
  <summary>See</summary>
<br>
  
<br>

</details>


<br>

<br>

## String Methods 

### Using the isBlank method [🔝](#index-)

<br>

#### Check if a string has empty spaces
<details>
  <summary>See solution</summary>
 <br>


* [isBlank method](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/String.html#isBlank())

#### Code
 ```java
public class TestClass {
    public static void main(String args[]) {
        
        /**
         * public boolean isBlank()

Returns true if the string is empty or contains only white space codepoints, otherwise false.

Returns:
    true if the string is empty or contains only white space codepoints, otherwise false
Since:
    11
See Also:
    Character.isWhitespace(int) 
         * 
         */
        
        
     String firstString = "First String to test";

      System.out.println("First String : "+firstString.isBlank());
      
           String secondString = " ";

      System.out.println("Second String : "+secondString.isBlank());
      
                String thirdString = "";

      System.out.println("Third String : "+thirdString.isBlank());

    }
}
 ```

#### Console
 ```java
First String : false
Second String : true
Third String : true

 ```

<br>

</details>



<br>

