# Jenkins Git Integration (Java)

### Steps:

1. Create java program in local machine. (ex. source.java)
  ```java
     public class source{
        public static void main(String args[]){
            System.out.println("Sample java program to test Jenkins git integration");
        }
     }
  ```
  
2. Create git repository and push `source.java` code.

3. Login to Jenkins, create Freestyle project and provide git repository url (created in previous step).
