# PokemonInformation
A site that feature a pokemon information


The project has 3 pages. 
index.html has:
Search Pokémon by ID, name, type, or ability. Users can:
-View basic info
-Add to favorites
-View more info

pokemonFavorites.html – Shows all saved Pokémon:
Sort by name/ID
Remove or download favorites
View detailed info

pokemonDetails.html – Displays detailed stats and data about a selected Pokémon.

Where we struggled:
At the start we passed json values by their actual values (name(string), id(int)) and 
after wanting to expand our project and create more information page we saw 
that we needed to pass the whole pokemon object so we had to rewrite the funcionality.
It took us some time to figure out how to work with the pokemon json file in the API.


We managed to solve the first problem by not using onClick (as we usually do in the class) on the buttons,
 but insted we used EventListner and called a function to achieve our goal.
 We figure out how to work with the pokeAPI by reading the docstring on the site. 
