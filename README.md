# DressMatch #
## Final Project Algorithms Code Description ##

This program is a platform which allows the users to input the clothes in their wardrobe allowing them to see all their clothes in a neat and organised format. This would be as easy as taking a picture of your clothes and submitting it to the app with some filters such as the brand, size, color, etc.

Main functions of the platform:
  - The program aims to provide fashion insight to its users.
  - Allows users to input the clothing item the own to provide a more personalized service. 


## Instalations and Libraries used: ##
  1. Requires Python Programming Language- It will work with all versions between 3.6 and 3.8.
  2. Requires to import the Random Library, if it is has already imported you can avoid this step.
  The random library is downloaded using the following command:
  _import random as rn_
  

## Usage: ##
Once the user accesses our platform he will be presented with two options: 
  1. Insert new clothes into the platform
  2. Create an outfit with previously inserted items

The user will have to choose between both options, and based on their choice they will have to answer some questions in order to allow the program to provide the optimal outfit according to his/her needs.

### Creating the wardrobe ###
If the user chooses the first option, he will be asked to input the charactercteristics of the piece of clothing he wishes to insert into the program. 
  1. Bottom
  2. Top
  3. Shoes
  4. All in one (dresses, rompers, etc)

For the Bottoms, Tops, and All in ones, they will be asked to specify the type of clothing (t-shirt, sweater, coat, etc.), the brand, the length , the color and for what season it is made. For the Shoes, the user will only be asked the type of shoes (sneakers, flip flops, etc.), the brand, the color and the season.

The user is allowed to insert as many items as he/she desires. Once the user is done inserting the new clothes, the program will automatically take them to the next section, where the program will choose the ideal outfit based on the users preferences.

### Searching for an outfit ###
If the user chooses the second option, he will be taken to the part of the program that creates an outfit combination which best suits his needs. 
The user is fist asked whether he wants the program to choose: 
  - A set _(1 top + 1 bottom + a pair of shoes)_
  - An all in one _(dresses/rompers/etc. + shoes)_

In order to ensure that the outfit conforms with the users needs, he will be required to input some information, such as: 
  - Color
  - Season  

The program will then display a full outfit (whether its a set or an all in one) which matches all the selected characteristics inputted by the user (same color and season).
All the outfits will be randomly assigned meaning that each time the user rreruns the rpogram the outfit will almost certainly be different from the previous one, allowing the user to rerun the program if he doesn't like the first outfit that was selected.


## Additional information: ##
In order to obtain our desired program we have incorporated the following data structures into our code:
  1. Class objects: Tops, bottoms, shoes and All in ones using OOP (Object oriented Programming), along with their corresponding attributes. 
  2. Lists: to save the differente instances incorporated by the users

We have also incorporated the following algorithms:
  1. Insertion
  2. Searching


## Credits: ##
The authors responsible for the development of this project are:

  Ana Encinas Sánchez 
  Calota Gómez Montes
  Carmen Prieto
  Marta Ortiz 
  Maria Goretty Martinez
  Paula Oliver 
