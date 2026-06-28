tags:: [[recipe]], [[beans]], [[Mexican cuisine]], [[pinto bean]], [[braise]], [[dutch oven]]

- ## Ingredients
- ### Bean Soak
- 1 cup [[dried pinto bean]]
- Plenty of [[water]]
- 1 tbsp [[kosher salt]]
- ½ tsp [[baking soda]]
- ### Beans
- 1 [[pig foot]]
- [[chicken broth]], enough to just cover the beans
- 1 medium [[onion]], diced
- 3–4 cloves [[garlic]], minced
- 1 [[bay leaf]]
- 1 tbsp [[tomato paste]]
- 1 tsp [[Mexican oregano]]
- 1 tsp [[ground cumin]]
- ½–1 tsp [[black pepper]]
- [[salt]], to taste
- A little [[cooking oil]] (for sautéing)
- ## Method
- 1. **Soak the beans.** Cover the beans with plenty of water and add the kosher salt and baking soda. Soak overnight, then drain and rinse.
  
  2. **Build the pot.** Place the soaked beans in a Dutch oven. Pour in enough chicken broth to just cover the beans. Add the pig foot and bay leaf. Bring to a gentle simmer.
  
  3. **Sweat the aromatics.** Heat a small amount of cooking oil in a skillet over medium heat. Cook the onion until translucent. Add the garlic and cook for 30–60 seconds. Transfer both to the Dutch oven.
  
  4. **Simmer.** Cook gently for 2–3 hours, or until the beans are tender and the pig foot is very soft. Add more broth or hot water if needed to keep the beans barely covered.
  
  5. **Finish.** Stir in the tomato paste, Mexican oregano, ground cumin, and black pepper. Simmer for another 15–20 minutes. Taste and adjust the salt if necessary.
  
  6. **Serve.** Remove the pig foot. Pull off the tender meat and gelatinous skin, chop them, and stir them back into the beans if desired. Discard the bones and any tough connective tissue.
- ## PlantUML Diagram
- ```plantuml
  @startuml
  title Porky Pinto Beans (Dutch Oven)
  skinparam titleFontSize 30
  skinparam titleFontName Arial
  skinparam titleFontColor Black
  skinparam titleFontStyle bold
  
  participant "Bowl" as Bowl
  participant "Dutch Oven" as Pot
  participant "Skillet" as Pan
  
  == Soak ==
  
  note right of Bowl
  Ingredients:
  • 1 cup dried pinto bean
  • water
  • 1 tbsp kosher salt
  • ½ tsp baking soda
  end note
  
  Bowl -> Bowl : Soak beans
  note right of Bowl : Overnight
  
  Bowl -> Bowl : Drain and rinse
  
  == Build the Pot ==
  
  note right of Pot
  Ingredients:
  • soaked pinto bean
  • chicken broth
  • pig foot
  • bay leaf
  end note
  
  Pot -> Pot : Combine ingredients
  Pot -> Pot : Bring to simmer
  
  == Aromatics ==
  
  note right of Pan
  Ingredients:
  • onion
  • garlic
  • cooking oil
  end note
  
  Pan -> Pan : Sweat onion
  note right of Pan : Until translucent
  
  Pan -> Pan : Cook garlic
  note right of Pan : 30–60 sec
  
  Pan -> Pot : Add aromatics
  
  == Simmer ==
  
  note right of Pot
  Ingredients:
  • beans
  • pig foot
  • broth
  end note
  
  Pot -> Pot : Simmer gently
  note right of Pot : 2–3 hours
  
  == Finish ==
  
  note right of Pot
  Ingredients:
  • tomato paste
  • Mexican oregano
  • ground cumin
  • black pepper
  • salt
  end note
  
  Pot -> Pot : Stir in seasonings
  Pot -> Pot : Simmer
  note right of Pot : 15–20 min
  
  == Serve ==
  
  Pot -> Pot : Remove pig foot
  Pot -> Pot : Chop meat and skin
  Pot -> Pot : Stir back into beans
  
  @enduml
  ```