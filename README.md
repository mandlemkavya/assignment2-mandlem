# assignment2-mandlem
# KAVYA #
#### Inorbit
Being vegan subway is the best place to find lot of healthy hygiene veg burgers/sandwiches/pizza for affordable price , one of the favorite item is veg burger which is liked by most of the people.
***Inorbit Mall is a subsidiary of K. Raheja Corporation which runs shopping malls in various parts of India***. The first Inorbit Mall opened in 2004, in Malad, Mumbai. This is the fourth oldest shopping mall in Mumbai, from Infiniti Mall of Andheri, R-Mall of Mulund, and Crossroads of South Mumbai.


## Directions to Inorbit

Rajiv Gandhi International Airport is closest airport 
1. Get on Nehru Outer Ring Rd in Gandiguda from Airport Approach Road  
2. Head east on Airport Approach Road toward Cargo Rotary  
3. At Cargo Rotary, take the 3rd exit and stay on Airport Approach Road  
4. Use the left lane to keep left at the fork and continue toward NH 44  
5. Continue on Nehru Outer Ring Rd to Madhava Reddy Colony  
6. Use the left 3 lanes to take exit 19 toward Nanakramguda/Financial District  
7. Follow Gachibowli Rd/Old Mumbai Hwy and Hitech City Main Rd to Inorbit Mall Rd in Madhapur  
8. At Gachibowli Cir, take the 3rd exit onto Gachibowli Rd/Old Mumbai Hwy   
9. At the roundabout, take the 3rd exit onto Inorbit Mall Rd   

## LIST of Delicious Food 

            -- Aloo patty
            -- Italian B.M.T
            -- Corn&Peas
            -- Egg And Cheese wrap
            -- Paneer Tikka
            -- Veg premium sandwich
            -- subway club sandwich
            -- Mexican wrap


About Me Link  

https://github.com/mandlemkavya/assignment2-mandlem/blob/main/AboutMe.md


## Sports
Table shows the sports activity cost effectiveness data which was held on different location in the year-2021. Data shows detailed cost analysis volley ball event held on location cost is higher than badminton sports event, cricket is one of the best game in the world also numerous amount of player resulted in high cost consumption for security, accomdation, food, other extra sources

| SPORTS/ACTIVITY | LOCATION | AMOUNT |
| ------------- | ------------- | ------------- |
| VOLLEYBALL  | AMERICA  | $4500  |
| BADMINTON  | AUSTRALIA  | $3200  |
| BASKETBALL  | CHINA  | $5500  |
| CRICKET  | INDIA  | $6000  |



## Quotes
> The journey of a thousand miles begins with one step
*- Lao Tzu*

> Strive not to be a success, but rather to be of value
*- Albert Einstein*



## ALGORITHM

Algorithms are used as specifications for performing calculations, data processing, automated reasoning, automated decision-making and other tasks. In contrast, a heuristic is an approach to problem solving that may not be fully specified or may not guarantee correct or optimal results, especially in problem domains where there is no well-defined correct or optimal result

Algorithm Details: <https://en.wikipedia.org/wiki/Algorithm> 
 
```ruby
  int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}
```

Competitive Programming Algorithm: <https://cp-algorithms.com/geometry/oriented-triangle-area.html> 
 
