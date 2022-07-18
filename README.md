<p align="center">
  <img width="70%" height="70%"src="/assets/coaster2.jpg">
</p>

# Roller Coasters: Game versus Reality
Roller coasters are the rides that make millions of people visit theme parks every year and it does not exist a theme park without at least one roller coaster. **The goal is to analyze real existing ride from a technical and spatial-temporal perspective** (how rides they are distributed in the country, how they evolved, …) and then **compare real rides with coasters created in the Planet Coaster game**.

Planet Coaster is a famous computer and console video game developed by Frontier in which the player creates and manages theme parks: from terrain editor and ride building to staff hiring to marketing campaigns. Basically the main goal is make the guests of the park happy, and in order to do so building attractive roller coasters is one of the most important tasks.

When the player builds a new ride, this ride is tested by the artificial intelligence of the game, that simulates real riders, and then a final rating is shown. The rating system consists of three metrics: Excitement, Fear and Nausea, all this metrics must be in a certain interval to classify a ride as "good" in the game.

## Involved Tasks
- **Analyze the real rides** present in the US from a **technical and spatial-temporal perspective** (how they are distributed in the country, how they evolved, …).
- **Analyze the game created rides** and understand what are the **factors that influence the most the rating**: how to build a good ride?
- **Compare the game created rides with real life existing rides** and understand the differences: can game rides exist in reality?

We aim to **answer different questions**, for example:
- What are the factors that determines a good ride?
- How the height and speed of rides changed during the years?
- How the number of inversions changed during the years?
- What are the states with the highest number of rides and why?
- What are the differences between real and game created rides, if there is one?
- Can the game created rides exist in real life or game ride are not realistic? And many other.

## Main Steps of the Projects
1. Data Reading
2. Data Cleaning and Preprocessing
3. Real Rides Data Visualization
4. Game Rides Data Visualization
5. Game VS Reality: Roller Coaster Comparison

## Data Set
For this project we need **three different data sets**: 

1. **one for the rides created in the game** --> game rides visualization.
2. **another for the real life existing rides** --> real rides visualization.
3. **the last one is a merge between the (1) and (2)** --> visualize the differences between game and real rides.

The first data set it's been created by myself, and consists of **multiple game created rides**. It contains all the technical specifications of the rides. A new column will be added and will contain the **coaster class**, that is a flag indicating if the ride is good or not good. The value of this flag is calculated on the three metrics used by Planet Coaster to evaluate a ride: Excitement, Nausea and Fear. 

The majority of the columns **represent technical specification of the ride.** The definition of all the columns it is presented in the following sections.

The other data set cane be found online at the [Montana State University Website](https://math.montana.edu/courses/s216/) and consists of **real world rides present in the US**. This data set in addition to technical specs of the rides also contains information about the year a ride opened in and where the ride is around the country, that is the geographical position. With this information it is possible to **analyze how rides evolved during time**. 

The third data set will be created during the **preprocessing phase**.

