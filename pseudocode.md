# Making a Bowl of Cereal

1. User needs to choose choice of cereal, choice of milk, and size of Bowl:
* Choice of Cereal: trix, cherrios, appleJacks
* Choice of Milk: skim, onePercent, twoPercent
* Size of Bowl: smallBowl, largeBowl

2. Gather materials:
* Getting the Milk will require opening the fridge.
* Getting the cereal will require opening the cerealCabinet.
* Getting the bowl will require opening the bowlCabinet.
* Getting the spoon will require opening the utensilDrawer.

3. User adds Cereal to the bowl:
* 2 cups of cereal are required.

4. User adds Milk to the bowl:
* 1 cup of milk is required.

5. User enjoys. 

<hr>

# INIT: Variables 
* Milk, Cereal, Bowl, Spoon

<hr>

**FUNCTION** getUtensil(choice)
* user selects spoon 
<br>

**ENDFUNCTION**

<br>


**FUNCTION** chooseCereal(choice)
* user selects choice of cereal 
<br>

**ENDFUNCTION**

<br>

**FUNCTION** chooseMilk(choice)
* user selects choice of milk
<br>

**ENDFUNCTION**

<br>

**FUNCTION** bowlSize(size)
* user selects size of bowl
<br>

**ENDFUNCTION**

<br>

**FUNCTION** openDoor(chooseDoor)
* user opens appropriate door to gather supplies
<br>

**ENDFUNCTION**

<br>

**FUNCTION** closeDoor(chooseDoor)
* user closes door that was opened
<br>

**ENDFUNCTION**

<br>

**FUNCTION** addCerealToBowl
* **IF** cereal < 2 cups
* add more cereal to bowl until cereal is 2 cups
* **ELSE** continue 
* **ENDIF**
<br>

**ENDFUNCTION**

<br>

**FUNCTION** addMilkToBowl
* **IF** milk < 1 cup
* add more milk to bowl until milk is 1 cup
* **ELSE** continue
* **ENDIF**
<br>

**ENDFUNCTION**

<br>

**FUNCTION** enjoy
* user eats cereal
<br>

**ENDFUNCTION**

<hr>

## START

openDoor('cerealCabinet'); <br>
chooseCereal('appleJacks'); <br>
closeDoor('cerealCabinet'); <br>
<br>
openDoor('fridge'); <br>
chooseMilk('onePercent'); <br>
closeDoor('fridge') <br>
<br>
openDoor('bowlCabinet'); <br>
bowlSize('smallBowl'); <br>
closeDoor('bowlCabinet') <br>
<br>
openDoor('utensilDrawer'); <br>
getUtensil('spoon'); <br>
closeDoor('bowlCabinet') <br>
<br>
addCerealToBowl(); <br>
addMilkToBowl(); <br>
enjoy(); <br>

## End

<hr>



    




