# Programming Graphics and Animation

![Test](img/rpsls_animation.gif)

In this stage of the project, we will program the animation of both hands. When we press the space key, the two hands will start displaying various random positions (rock, paper, scissors, lizard, Spock). Finally, one fixed hand position will remain. In other words, in this version of the game, the machine plays against itself, showing two random moves, one for player A and another for player B.

# The Checklist

1. Create the game project in Scratch on its **web version**: [scratch.mit.edu](https://scratch.mit.edu).
2. First, choose a background for the game and insert text in the bottom right corner with the names of the programming team members (pair).
3. Search the internet for 5 images of hands representing the different options for playing Rock, Paper, Scissors, Lizard, Spock. The images should have appropriate quality and resolution.
4. Each of the 5 images should be in a separate PNG file with the following names: rock.png, paper.png, scissors.png, lizard.png, and spock.png. Modify the images if necessary to have a transparent background. You can remove the background using Scratch tools or other tools like GIMP or websites such as [www.remove.bg/es](https://www.remove.bg/es).
5. Create 3 sprites in Scratch: one for the game referee (a person) and two for each hand (player A and B).
6. Use the 5 prepared images to define 5 costumes for each hand in Scratch.
7. Program the necessary code in the referee and each hand so that, when the space key is pressed, the animation starts simultaneously in each hand and ends with a random option.
8. Test that everything works correctly.
9. Download the Scratch project file (.sb3) and rename it according to the last names and names of the members 9. 1 and 2 of the team: LastName1FirstName1_LastName2FirstName2.sb3 (for example: PérezJuan_LópezAna.sb3)
10. Attach submit the .sb3 file here.

## 1. Scratch

![Scratch](img/scratch_web.png)

Scratch is a visual programming language and an online community developed by the MIT Media Lab. It is designed to be user-friendly, especially for beginners, allowing them to create interactive stories, games, and animations without the need for traditional coding. Scratch uses a drag-and-drop interface where users snap together blocks of code, making it accessible to people of all ages.

You can use Scratch online. The platform is web-based, and you can access it through your web browser. This means you don't need to download or install any software to start programming in Scratch. The online version allows users to create, share, and remix projects, fostering a collaborative and creative learning environment. You can find the Scratch platform at the official website: [scratch.mit.edu/](https://scratch.mit.edu/).

# 2. The Background

![Scratch](img/rpsls_bg.png)

First, choose a background for the game and insert text in the bottom right corner with the names of the

In Scratch, a backdrop is the background or scenery that serves as the visual environment for your project. It provides context to the sprites and actions happening in your project. Backdrops can be static images or even dynamic scenes that change over time.

To add a new backdrop in Scratch:

1. **Open Your Project:**
   - Go to the Scratch website (https://scratch.mit.edu/) and log in if you aren't already.
   - Open the project to which you want to add a new backdrop.

2. **Choose or Upload a Backdrop:**
   - In the stage area (the large white space where your sprites and backdrops are displayed), find the "Choose a backdrop from library" option. It's usually located in the bottom-left corner.
   - Click on it to open the backdrop library. Here, you can choose from a variety of pre-made backdrops.
   - If you want to use your own image as a backdrop, click on the "Upload Backdrop" button, which allows you to upload an image from your computer.

3. **Select and Add the Backdrop:**
   - If you're choosing from the library, click on the backdrop you want to use, and it will be added to your project.
   - If you're uploading your own image, select the image from your computer, and it will be added as a new backdrop.


Adding backdrops allows you to create more engaging and visually appealing projects in Scratch, enhancing the overall experience for your users.

# 3. Five images

![Google](img/rpsls_google.png)

Search the internet for 5 images of hands representing the different options for playing Rock, Paper, Scissors, Lizard, Spock. The images should have appropriate quality and resolution.

Each of the 5 images should be in a separate PNG file with the following names:

    rock.png
    paper.png
    scissors.png
    lizard.png
    spock.png

If the objects Rock, Paper, Scissors, Lizard, and Spock appear together in a single image, you can make 5 cuts of the image using GIMP or another image editor.

## 4. Edit the pictures

Modify the images if necessary to have a transparent background. You can remove the background using Scratch tools or other tools like GIMP or websites such as [www.remove.bg/es](https://www.remove.bg/es).

<iframe width="560" height="315" src="https://www.youtube.com/embed/2bayy0ZoPqM?si=oQ4uhBakdWHni6T7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br/>

## 5. The Sprites

![Three spries](img/rpsls_3sprites.png)

Create 3 sprites in Scratch: one for the game referee (a person) and two for each hand (player A and B).

In Scratch, a sprite is a graphic object or character that can be programmed to perform various actions. Sprites are the interactive elements in a Scratch project, and they can be customized and controlled using Scratch's visual programming language.

Each sprite has its own set of scripts (programming instructions) that dictate its behavior. Users can create or choose sprites from Scratch's library, which includes a variety of characters, animals, objects, and more. Sprites can be moved, rotated, and resized, and they can respond to different events or user inputs, such as keyboard presses or mouse clicks.

In the context of a game like Rock Paper Scissors Lizard Spock, sprites represent the hands making different gestures, and their movements and positions.

## 6. Five costumes: rock, paper, scissors, lizard, and Spock

Use the 5 prepared images to define 5 costumes for each hand in Scratch.

![Hand costumes](img/rpsls_costumes.png)

## 7. The animation code

Program the necessary code in the referee and each hand so that, when the space key is pressed, the animation starts simultaneously in each hand and ends with a random option.

<!-- ![Hand animation](img/rpsls_animation.png)-->

### Exercise

Use the blocksin the image to program the animation.

![Hand animation puzzle](img/rpsls_animation_puzzle.png)

This is the algorithm that you have to program:

    when space key pressed
        say(Rock, Paper, Scissors, Lizard, Spock!)
        MoveHand

    define MoveHand
        repeat(10)
            playerA_move = pick_random(1,5)
            costume = playerA_move
            wait 0.1 seconds
        SayMove

## 8. Test it!

![Test](img/rpsls_animation.gif)

Test that everything works correctly. The animation of the hands should start when the **space key** is pressed.

## 9. Download the Scratch project file (.sb3)

![Save to your computer](img/scratch_save.png)

Download the Scratch project file (.sb3) and rename it according to the last names and names of the members 1 and 2 of the team:

    LastName1FirstName1_LastName2FirstName2.sb3
    
For example:
    
    PérezJuan_LópezAna.sb3

## 10. Turn in your project

Attach and submit the .sb3 file. [This is how](https://support.microsoft.com/en-au/topic/turn-in-an-assignment-in-microsoft-teams-e25f383a-b747-4a0b-b6d5-a2845a52092b).


