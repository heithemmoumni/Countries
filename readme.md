### Country

Country is the package that helps you to get country name and dialing code by the country .


### Basic Uses

##### Get all countries name and dialing code

```go
countries = _c.all()

console.log(countries)

// example using then

_c.all().then(function(countries) {
	console.log(countries)
}).end(function() {
	console.log('end')
})


```

##### Get a country name and dialing code

```go
countryDetails = _c.get("BD")
```

##### Get multiple countries name and dialing code

```go
countries = _c.getMultipleCountries("BD", "US")
```

##### Get a country name

```go

name := _c.getName("BD")
```

##### Get a country dialing code

```go

dialingCode = _c.getDialingCode("BD")
```

