<table>
<tr>
<th>Swift</th>
<th>Objective-C</th>
<th>golang</th>
</tr>

<tr>

<td>
  
```swift
print("Hello, world!")
// Prints "Hello, world!"
```

</td>

<td>
  
```objective-c
NSLog(@"Hello world!");
// Prints "Hello, world!"
```

</td>

<td>
  
  ```golang
  fmt.Println("Hello world!")
  // Prints "Hello, world!"
  ```

</td>


</tr>


<tr>
<td>

  ```csharp
  const int x = 3;
  const string y = "foo";
  readonly Object obj = getObject();
  ```
</td>
<td>

  ```nemerle
  def x : int = 3;
  def y : string = "foo";
  def obj : Object = getObject();
  ```
</td>
<td>
  Variables defined with <code>def</code> cannot be changed once defined. This is similar to <code>readonly</code> or <code>const</code> in C# or <code>final</code> in Java. Most variables in Nemerle aren't explicitly typed like this.
</td>
</tr>
</table>
