cd - > torna al percorso precedente alla tua ultima mossa
cd .. > sali di livello
pwd > mostra il percorso corrente
ls > lista delle cartelle e dei file nella direcory
ls -A > lista delle cartelle e dei file nascosti nella direcory
mkdir > crea una cartella nella directory
rm > cancella un file o una cartella nella directory
mv > sposta un file o una cartella in un’altra directory
cp > copia un file o una cartella in un’altra directory

Livello 1: go to the top of the main tower of the castle
cd Castle
cd Main_tower
cd First_floor
cd Second_floor
cd Top_of_the_tower

Livello 2: go to the castle Cellar
cd ..
cd ..
cd ..
cd ..
cd Cellar

Livello 3: Go back to the starting location and then go to the throne room using only two commands
cd -
cd Castle/Main_building/Throne_room

Livello 4: Build a "Hut" in the forest, and then build a "Chest" in the hut
cd -
cd Firest
mkdir Hut
cd Hut
mkdir Chest

Livello 5: Go back to the cellar and get rid of all the spiders. Leave the bats  alone: they appear on the castle's coat of arms and are said to confer luck.
cd -
cd Castle/Cellar
rm spider_1
rm spider_2
rm spider_3

Livello 6: Collect all the coins that you can find in the garden in front of the castle, and put them in your chest in your hut in the forest.
cd -
cd Garden
mv coin_1 ../Forest/Hut/Chest
mv coin_2 ../Forest/Hut/Chest
mv coin_3 ../Forest/Hut/Chest

Livello 7: Collect all the coins hidden in the garden in front of the castle, and put them in your chest (in your hut in the forest).
ls -A
mv .21530_coin_3 ../Forest/Hut/Chest
mv .5095_coin_2 ../Forest/Hut/Chest
mv .60966_coin_1 ../Forest/Hut/Chest

Livello 8: Get rid of all the spiders that are crawling in the cellar. Again, do not do not disturb the bats.
cd -
cd Castle/Cellar
rm *_spider_*

Livello 9: The spiders are getting clever: they found a way to hide. Get rid of all the spiders that are hiding in the cellar without disturbing the bats.
rm .*_spider_*

Livello 10: You have taken a fancy to the four standards in the great hall of the castle. As stealing them would not go unnoticed, put a copy (same name, same content) of each in your chest.
cd -
cd Castle/Great_hall
cp *_? ~/Forest/Hut/Chest/
