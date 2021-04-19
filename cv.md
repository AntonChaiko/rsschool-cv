## **ANTON CHAIKO**
#### **Links:** 
   * VK:https://vk.com/id592891178
   * Telegram: https://t.me/Chaiko_anton
   * Email: smart.just4fun@gmail.com
### **Goal:** Become an android developer
### **Skills:** Java, HTML,CSS, JavaScript
##  *Code sample:* 
```java
import java.util.Arrays;
import java.util.Comparator;
import java.util.stream.Collectors;
class Meeting {
    
  public static String meeting(String s) {
    return Arrays.stream(s.split(";"))
                 .map(String::toUpperCase)
                 .map(Name::new)
                 .sorted(Comparator.comparing(Name::getLast).thenComparing(Name::getFirst))
                 .map(n -> String.format("(%s, %s)", n.getLast(), n.getFirst()))
                 .collect(Collectors.joining(""));
  }
  
  private static class Name {
    private String first;
    private String last;
    public Name(String name) {
      String[] parts = name.split(":");
      first = parts[0];
      last = parts[1];
    }
    public String getFirst() {
      return first;
    }
    public String getLast() {
      return last;
    }
  }
}
```
## **Experience:** Create DictionaryApp
## **Education:** Brest State Technical University
## **English:** intermediate
