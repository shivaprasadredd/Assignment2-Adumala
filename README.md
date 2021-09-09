# Assignment2-Adumala

## shiva prasad Reddy Adumala
#### My favourite place is my state capital city Hyderabad <br>
 Hyderabad is a widely famous city present in the Telangana region. It is situated at an altitude of 541 meters above on the decan plateau. It is also one of the most highly **populated**cities. Besides, it is mainly **recognized** for its rich background, cuisine, multilingual culture, etc. It was initially established near the Musi river banks, which is now referred to as the old historic city.

---

##  Journey from maryville to Hyderabad.
1. Firstly, book flight ticket from kansas to Hyderabad, Now arrange a ride from maryville to kansas city International Airport.
    1. get your boarding passes and drop your luggage for checkin.
2. Once you board the flight start sleeping for minimum 24 hours and yoy will reach hyderabad.
    1 wakeup at layover and refresh, board again.
3. from hyderabad find a cab and go to the home.

* Items that should be brought for maximum enjoyment.
    * Indian currency.
    * No need to bring anything we have everything for enjoyment
    [commentator](aboutme.md)

    ---

 ## Table creation.

 Food/drinks that I would recommend someone try.

| Food/Drinks | Location     | Price($) |
| ------------| ---------    | -------- |
| Burger      | Mc Donalds   | 3$       |
| Milk Shake  | Hungry Jacks | 2$       |
| Fries       | Kfc          | 2$       |


## Quotes
> Be yourself; everyone else is already taken.-*Oscar Wilde*
> “Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.-*Albert Einstein*

---

## Code fencing
>In geometry, a simple polygon /ˈpɒlɪɡɒn/ is a polygon that does not intersect itself and has no holes.<https://en.wikipedia.org/wiki/Simple_polygon>

```
double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}
```

<https://cp-algorithms.com/geometry/area-of-simple-polygon.html>