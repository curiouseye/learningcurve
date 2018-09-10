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


