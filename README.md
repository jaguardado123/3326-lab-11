# Lab Assignment 10

In this lab you will practice working with arrays.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the src/ directory and name your class accordingly and remember to make it **public**. Next, **create your main() method inside your class**.

Now let's begin!

## Arrays

In Java arrays are written a little differently than in C++.

Arrays are used to store multiple values of the same type into a single variable. 

Arrays are declared by placing the [] next to the variable's type.

**Declaring an array in Java:**
```java
int[] myNums;
```

In Java we don't have to allocate memory when declaring an array. We can allocate memory either during the declaration or afterwards.

**Allocating Memory:**
```java
// During Declaration
String[] names = new String[5];

// After Declaration
float[] realNums;
realNums = new float[5];
```

Similarly, you can initialize (assign values) to your array either during the declaration or afterwards by assigning values individually.

**Initializing:**
```java
// During Declaration
String[] cars = {"Toyota", "Ford", "Chevy"};

// After Declaration
String[] colors = new String[3];
colors[0] = "Blue";
colors[1] = "Red";
colors[2] = "Green";
```

## Your program

**Party Inventory**

Assume you are hosting a party and you have asked your guests to `each bring 1 item`. Write a program utilizing arrays to keep inventory of your `guest's names and their item`.

Make sure to `get the number of expected guests` to know how much memory to allocate.

Your output should look like:
```
Welcome to my Party Inventory App!

Expected guests: 3

Enter guest and item: Bob chips

Enter guest and item: Carl dip

Enter guest and item: Jane sodas

Inventory:
1. Bob chips
2. Carl dip
3. Jane sodas

```

## Submit your assignment

To submit your lab assignment click on the source control icon (3 circles with 2 lines) on your leftside navbar. Next, click on the '+' symbol next to "Changes" to stage your changes. Lastly, add a commit message (ex: "First commit") and click "Commit" then "Push" or "Sync Changes". And you're done!
