# Modeling and Preventing Virus Spread Using Agent Based Modeling and Computer Simulations

## Aashni Manroa

Welcome to this project! My paper is linked above, and so is my code. 

This is a personal project that I have been working on since sophomore year of college. Using the IDE and coding language Netlogo, I was able to create a geospatial computer simulation of COVID-19 spread. In my model, people are randomly initialized and move along roads in Washington, D.C.. There are a specific number of people who are already sick, based on COVID data for the region. There are also a specific number of people who are masked and vaccinated, also based on data from the region. 

The virus can be transmitted only if the transmitter and receiver are unmasked, and the receiver is not vaccinated. People can either die or survive the virus once they have it. Death is more likely as the age of the persons increases, with random number generation controlling death. I experimented with different methods to reduce the spread and deaths (having the people wear masks and/or get vaccinated). These variables were dynamic, changing based on the community around each person. For example, if the majority of a person's neighbors were wearing a mask, the person would put one one, and vice versa - if the majority of neighbors were unmasked, the person would take it off. This is similar for vaccines, but if a person gets vaccinated, they cannot become unvaccinated. 

This current model is a more recent version, but a previous version from winter 2021 showed surprising similarity to the current COVID trends (second waves, etc). 

This project was very successful, as I concluded that implementing either masks or vaccines had about the same effect, but combining them had the best chance at reducing the deaths and spread rate caused by the virus. 

I presented this project at the ACM Capital Region Celebration of Women in Computing as a student presenter, as well as in the poster competition at the Richard Tapia Celebration of Diversity in Computing.
