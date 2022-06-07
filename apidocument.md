// Page 1  I require Four different urls on 1st page
> List of city
> (Get) http://localhost:9100/location
> live :https://febapidu.herokuapp.com/location
> list of restaurant

> (Get) http://localhost:9100/restaurants
> live:https://febapidu.herokuapp.com/restaurants

> Restaurant on the basis of city 
> (Get) :http://localhost:9100/location?lalchowk
> live :https://febapidu.herokuapp.com/location?delhi

> List of QuickSearch
> (Get) http://localhost:9100/mealType
> live: https://febapidu.herokuapp.com/mealtype

// Page 2
> List of restaurants on the basis of meal
> (Get)  http://localhost:9100/restaurants?mealId=5 http://localhost:9100/restaurants?mealId=5&stateId=2
> live https://febapidu.herokuapp.com/restaurants?mealId=5

> Filter on basis of cuisine
> (Get) http://localhost:9100/filter/1?cuisineId=5
> live :https://febapidu.herokuapp.com/filter/1?cuisineId=5

> Filter on basis of cost
> (Get)  http://localhost:9100/filter/1?lcost=700&hcost=1200
> live :https://febapidu.herokuapp.com/filter/1?lcost=700&hcost=1200

> Sort on basis of cost
> (Get) http://localhost:9100/filter/1?lcost=500&hcost=1200&sort=-1
> live::https://febapidu.herokuapp.com/filter/1?lcost=500&hcost=1200&sort=-1

// Page3
> Details of the restaurant
> (Get) http://localhost:9100/details/5
> live :
> Menu of the Restaurant
> (Get)http://localhost:9100/menu/7

// Page4
> Menu details (selected items added in cart)
> (Post) 
> Place order
> (Post) 



