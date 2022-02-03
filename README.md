# assignment2-marla
# Ranya Marla
###### Warangal
> My Favorite place is **Disneyland** and is located in NewYork. It is the first of two theme parks built at the Disneyland Resort in Anaheim, California, opened on July 17, 1955. *It is the only theme park designed and built to completion under the direct supervision of Walt Disney.* It was originally the only attraction on the property; its official name was changed to Disneyland Park to distinguish it from the expanding complex in the 1990s. It was the first Disney theme park.

***

# part-4 directions from airport to warangal

Closest airport from the food court is *Rajiv Gandhi international airport*.<br>
Following are the steps for traveling to my food location

1. You can book a cab or travel on your own vehicle from Warangal to kazipet railway station.
2. Take the first train which is available to travel from kazipet railyway sation to Secunderabad junction.
3. From Secunderabad junction you can book a cab or you can travel in airport buses to reach the Rajiv Gandhi international airport.

## Best food items in Warangal
List of good food items that are recommended to others in Warangal
- Watermelon margarita mocktail
- Chicken soup
- Main course
    - Chicken dum biryani
    - Prawns fry
- Deserts
    - Dark chocolate icecream
    - Kaju bharifi

    [This is aboutme link](https://github.com/RanyaReddy/assignment2-marla/blob/main/AboutMe.md)

***

# Creating the activities table

Below is the table for 4 activities that everyone should try atleast once. It has details regarding the location of the activity and the amount of money needed for the personal equipment.
| Activity | Location | Amount in $|
| --- | --- | ---: |
| Kayaking | California | 25 |
| Cycling Vacation | Europe | 30 |
| Skydiving | Kansas | 15|
| Parasailing | Miami | 10 |

***
# quotes

> “The purpose of our lives is to be happy.”
>> *Dalai lama*

> “Being unique is better than being perfect.”
>> *Charles*

***

# code fencing

# Binomial coefficient

> The binomial coefficients are the positive integers that occur as coefficients in the binomial theorem. Commonly, a binomial coefficient is indexed by a pair of integers n ≥ k ≥ 0 and is written {\displaystyle {\tbinom {n}{k}}.}{\displaystyle {\tbinom {n}{k}}.} It is the coefficient of the xk term in the polynomial expansion of the binomial power (1 + x)n.

[link to source](https://en.wikipedia.org/wiki/Binomial_coefficient)

implementation of Binomial coefficient <https://cp-algorithms.com/combinatorics/binomial-coefficients.html>

```

int C(int n, int k) {
    int res = 1;
    for (int i = n - k + 1; i <= n; ++i)
        res *= i;
    for (int i = 2; i <= k; ++i)
        res /= i;
    return res;
}

```