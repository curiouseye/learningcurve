# Contract / Schema

- Defines the structure of request and response
- Type of element string, integer , repeating elements, sequence of elements

## Request
```
<GetWeather>
<City Code = "LONDON"/>
<Country Code = "England"/> <!--string-->
<Days>2</Days>  <!--Integer-->
<GetWeather>
```

## Response

```
<WeatherData>
<City Code = "LONDON"/>
<DayData>
<Temparature>19</Temparature>
<Unit> Degrees </Unit>
<Date>9/9/2010</Date>
</DayData>

<DayData>
<Temparature>10</Temparature>
<Unit> Degrees </Unit>
<Date>10/9/2010</Date>
</DayData>
</GetWeather>
```

### Api Testing

![API Testing](https://github.com/curiouseye/learningcurve/raw/master/API%20Testing.png)


### Old Workflow

- Understand the contract
- Wait for developer to complete and deploy. Usually takes 3 weeks
- Testers start writing assertions and testing

### New Workflow

- Understand the contract
- Developers starts work
- Team prepares a virtual mock server that mimics the response.
- Testers start writing assertions and testing day 2
- Developer completes work
- Tester completes final work
- Effective feedback is possible


