Mohamed_GEO712-Repository
================
2023-10-05

<style>
body {
text-align: justify}
</style>

# Session_04-Activity

# Research Interest

------------------------------------------------------------------------

My research interest lies in the transportation area. Transportation
engineering has seen a significant advance in the past decade as
transportation is not just limited to highway design but it has to take
into consideration the surrounding developments and how the traffic will
be impacted by it. Solving the global congestion crises is a research
opportunity that is addressed by many researchers whether in a direct or
indirect ways. In transportation there are two topics that interest me
the most which are Public Transportation and Drones. Enhancing public
transportation by optimizing the timing and locations of the
transportation system or by using electric buses will lower congestion,
environmental impact, and can help with the energy crises that the world
is having. As an emerging technology drones have a lot of uses that can
solve a lot of problems. Transportation wise drones can be used in
parcel delivery, which can reduce carbon emissions significantly and can
reduce the time needed for the delivery. Using Drones in parcel delivery
can also create problems, mainly related to public perception as many
people will consider it as a privacy breach to have drones hovering over
houses.

# Favorites

------------------------------------------------------------------------

## Favorite Music

1.  Lessa Bahinlha
2.  Runaway aurora
3.  Aaron smith dancin
4.  cairokee ghammad einak
5.  mahmoud el esseily dom dom

## Favorite Equation

### Bernoulli’s Equation

$$
P_1 + \frac{1}{2} \rho v^2_1 + \rho g h_1 = P_2 + \frac{1}{2} \rho v^2_1 + \rho g h_2
$$

## Favorite Artists

| Name              | Achievements                     |
|-------------------|----------------------------------|
| Denzel Washington | 2 Oscars & 3 Golden Globe Awards |
| Tom Hanks         | 2 Oscars & 5 Golden Globe Awards |
| Robert De Niro    | 2 Oscars & 2 Golden Globe Awards |
| Robert Downey Jr  | 3 Golden Globe Awards            |
| Leonardo dicaprio | 1 Oscar & 3 Golden Globe Awards  |

# Chunk of Code

------------------------------------------------------------------------

``` r
# Program to check if the input number is odd or even.
# A number is even if division by 2 give a remainder of 0.
# If remainder is 1, it is odd.

num = as.integer(readline(prompt="Enter a number: "))
```

    ## Enter a number:

``` r
if(is.na(num)) {
  print("Number is : NA")
}else if(num == 0) {
  print("Zero")
}else if((num %% 2) == 0) {
     print(paste(num,"is Even"))
 } else {
     print(paste(num,"is Odd"))
 }
```

    ## [1] "Number is : NA"

# Folder Structure

The main research project folder have the following sub_folders:

1.  Raw Data: will have the data as collected.
2.  Processed Data: will contain the cleaned and analysed data.
3.  Code: will have a detailed description of the process used to
    analyse the data and the software used in the process for
    reproducability purposes.
4.  Resources: will have the source of the data and papers used in the
    literature review.
