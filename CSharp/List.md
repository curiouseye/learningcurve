# C# List

#### Creating a list of strings

```
var countries = new List<string>();
```

#### Creating and initialising a list of strings

```
var countries = new List<string>{
"India",
"China",
"Cuba"
};
```

#### Finding a item in a list

```
var cCountries = countries.Where( country => country.StartsWith("C") ).ToList();
```

#### Find a item in list of class objects

```
   public class Person {
      public string Name { get; set; }
      public int Age { get; set; }
    }
```
```
var people = new List<Person> {
        new Person { Name = "Siva" , Age = 50 },
        new Person { Name = "King" , Age = 25 },
        new Person { Name = "Kevin" , Age = 6 },
        new Person { Name = "Victor" , Age = 8 },
      };
var minors = people.Where( p => p.Age < 18 ).ToList();

var personStartingWithK = people
.Where( p => p.Name.StartsWith( "K" ) || p.Age >18 )
.ToList();
```
