# MG7
## Devlog
Write your Devlog here. :3
In about a paragraph, explain your TreeOfBirds script. Mention both how an array is used in this script and how vectors are used. Write about a paragraph. 

The TreeOfBirds script is what gives us access to the store all of the Sparrow gameobjects in the _birds array that is tuneable in the inspector in Unity. Using an array makes it easier to loop through a list of objects (in this case it would be the list of sparrow gameobjects) to make sure that they are all satisfying the condition. Vectors are being used to calculate the distance. Vector3.Distance() would be the player's distance to the bird objects. We are able to do this because the player's position and the birds' positions are represented as Vector3 values. We have a SerializeField float variable that we are able to tune in the inspector called interactiondistance which monitors how close the player can get to the bird before the birds pop up out of the trees. But for the birds to actually pop up out of the tree we need that interactiondistance requirement to be met and then SetActive() gets called. 

## Open-Source Assets
- [Forest Nature Pack](https://kaylousberg.itch.io/kaykit-forest) - environment 3D models
- [Quirky Series](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235) - animal 3D models
