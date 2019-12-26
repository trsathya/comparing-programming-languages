### Functions with parameter names
<table>
<tr>
<th>Dart</th>
<th>Swift</th>
<th>golang</th>
<th>Objective-C</th>
<th>Java</th>
</tr>


<tr>
<td>
Parameters are named and not required, by default
</td>
<td>
Parameters are named and required, by default
</td>
<td>

</td>
<td>

</td>
<td>
</td>
</tr>


<tr>
<td>

  ```dart
  String greet1(String person) {
    return 'Hello, ' + person + '!';
  }
  main() {
    print(greet1('Sathya'));
  }
  // prints 'Hello, Sathya!'
  ```

</td>
<td>

  ```swift
  func greet1(person: String) -> String {
      return "Hello, " + person + "!"
  }
  print(greet1(person: "Sathya"))
  // prints 'Hello, Sathya!'
  
  ```

</td>
<td>

  ```golang
  ```
</td>
<td>

  ```objc
  ```
</td>
<td>

  ```java
  ```
</td>
</tr>

<tr>
<td colspan=5>### Functions parameters with default values</td>
</tr>


<tr>
<td>

</td>
<td>
Parameters with default value becomes optional
</td>
<td>

</td>
<td>

</td>
<td>
</td>
</tr>


<tr>
<td>

  ```dart
  ```  
</td>
<td>


  ```swift
  func greet2(person: String = "Sathya") -> String {
      return "Hello, " + person + "!"
  }
  print(greet2())
  // prints 'Hello, Sathya!'
  ```

</td>
<td>

  ```golang
  ```
</td>
<td>

  ```objc
  ```
</td>
<td>

  ```java
  ```
</td>
</tr>


<tr>
<td colspan=5>unnamed parameters in functions</td>
</tr>



<tr>
<td>

  ```dart
  ```  
</td>
<td>

Unnamed parameters
  ```swift
  func greet3(_ person: String = "Sathya") -> String {
    return "Hello, " + person + "!"
  }
  print(greet3("kumar"))
  // prints 'Hello, kumar!'
  ```

</td>
<td>

  ```golang
  ```
</td>
<td>

  ```objc
  ```
</td>
<td>

  ```java
  ```
</td>
</tr>










<tr>
<td>

  ```dart
  ```  
</td>
<td>

  ```swift
  ```

</td>
<td>

  ```golang
  ```
</td>
<td>

  ```objc
  ```
</td>
<td>

  ```java
  ```
</td>
</tr>
</table>
