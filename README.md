# CS5830 Project 7

## Emberly's chosen dataset and notes

https://catalog.data.gov/dataset/austin-animal-center-outcomes?from_hint=eyJxIjoiaGVhbHRoIiwic29ydCI6InBvcHVsYXJpdHkiLCJyZXN1bHRzIjoiNDAifQ%3D%3D

* I chose to define adopted animals as any outcome that included the word adopted
* I chose to remove reclaimed animals from the dataset, because I felt like they didn't really matter to the investigation of what factors make a pet
more likely to be adopted.
* I guessed that the main factors for if an animal got adopted would be:
    * Days in Shelter (quant)
    * Date of Birth in relation to Outcome Date (show how old they were when they had an outcome) (quant)
    * Type (qual)
    * Primary Breed (qual)
* I dropped NaN values from each of these columns, but I noticed that when I dropped animals that didn't have a birth date,
the adopted animal column barely changed, but the not adopted animal column lost 2000ish animals.
* I thought this was really intersting, so I made a new binary column for if they have a birthday.

## Sulove's chosen dataset and notes