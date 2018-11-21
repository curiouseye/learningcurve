# NUnit Step 1

 1. Create a class library project 
 2. Add  `NUNIT`  nuget package to the  project

```
using NUnit.Framework;

namespace ClassLibrary1 {
  [TestFixture]
  public class SearchTests {
    [Test]
    public void SearchByName() {
      var actual = 10;
      var expected = 10;
      Assert.That( actual , Is.EqualTo( expected ) );
    }
  }
 }    
```
