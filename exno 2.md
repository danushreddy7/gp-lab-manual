# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date: 12/3/25
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1. Create a new project in Unreal Engine and choose a template that suits your needs.
2. Add anewactor to the level and call it "Coin".
3. Create a new blueprint based on the Coin actor byselecting it in the Content Browser and
choosing "Create Blueprint".
4. Openthe Coin blueprint and add a static meshcomponent to represent the coin. You can
import a 3D model or use one of the default shapes provided by Unreal Engine.
5. Add acollision component to the Coin blueprint so that the player can interact with it.
Choose a simple collision shape like a sphere or a box.
6. Add acollision component to the Coin blueprint so that the player can interact with it.
Choose a simple collision shape like a sphere or a box.
7. Create a new blueprint based on the player character byselecting it in the Content
Browser and choosing "Create Blueprint".
8. Openthe player blueprint and add a collision component to represent the player's
interaction with the coins.
9. Add anevent to the player blueprint that gets triggered when the player collides with a
10. coin. Use a collision event and check if the collided actor is a coin.
11. If the collided actor is a coin, check if it has already been collected. If not, set its
IsCollected variable to true and add its value to a score variable in the player blueprint.
12. Remove the coin fromthe level bycalling its Destroy function.
13. Add several instances of the Coin actor to the level and adjust their positions so that they
are spread out and not too close to each other.

## Output:
![image](https://github.com/user-attachments/assets/f45ac9ae-9731-4e9b-845f-77f830992a73)
![image](https://github.com/user-attachments/assets/e1456301-493b-444f-8bbb-5fd18ed2819a)
![image](https://github.com/user-attachments/assets/27512ce9-9f7c-4ada-939b-ff5208958b77)
![image](https://github.com/user-attachments/assets/aefd2345-fd3a-42b5-b70f-7be4c90a3d60)
![image](https://github.com/user-attachments/assets/2728f648-f624-4ca1-8960-55cd5ae3bf61)
## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
