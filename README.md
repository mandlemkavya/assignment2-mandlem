# assignment2-mandlem
# KAVYA #
#### Inorbit
Being vegan subway is the best place to find lot of healthy hygiene veg burgers/sandwiches/pizza for affordable price , one of the favorite item is veg burger which is liked by most of the people.
***Inorbit Mall is a subsidiary of K. Raheja Corporation which runs shopping malls in various parts of India***. The first Inorbit Mall opened in 2004, in Malad, Mumbai. This is the fourth oldest shopping mall in Mumbai, from Infiniti Mall of Andheri, R-Mall of Mulund, and Crossroads of South Mumbai.

<section>

<h1> ORDERED LIST </h1>
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
<h1> UNORDERED LIST </h1> 

            -- Aloo patty
            -- Italian B.M.T
            -- Corn&Peas
            -- Egg And Cheese wrap
            -- Paneer Tikka
            -- Veg premium sandwich
            -- subway club sandwich
            -- Mexican wrap


</section>


<li> About Me Link </li> 



https://github.com/mandlemkavya/assignment2-mandlem/blob/main/AboutMe.md

<section>

<h2> Sports </h2>
<p>  Table shows the sports activity cost effectiveness data which was held on different location in the year-2021. Data shows detailed cost analysis volley ball event held on location cost is higher than badminton sports event, cricket is one of the best game in the world also numerous amount of player resulted in high cost consumption for security, accomdation, food, other extra sources </p>

| SPORTS/ACTIVITY | LOCATION | AMOUNT |
| ------------- | ------------- | ------------- |
| VOLLEYBALL  | AMERICA  | $4500  |
| BADMINTON  | AUSTRALIA  | $3200  |
| BASKETBALL  | CHINA  | $5500  |
| CRICKET  | INDIA  | $6000  |

</section>

<section>
<h2> Quotes </h2>
<blockquote> <q>  The journey of a thousand miles begins with one step </q>
<i> - Lao Tzu </i>
</br>
<q> Strive not to be a success, but rather to be of value </q>
<i> - Albert Einstein </i>
</blockquote>
</section>

<section>
  <h1>ALGORITHM </h1>
<hr>
<blockquote>
  Competitive Programming Algorithm <https://cp-algorithms.com/geometry/oriented-triangle-area.html> 
  </blockquote>
 
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
 
</section>