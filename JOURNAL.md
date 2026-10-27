---
title: "3lb combat robot"
author: "Dylan"
description: "3lb Vertical spinner combat robot"
created_at: "2026-05-23"
---

# 2026-08-17: Finished the bot!!!!

**Total time spent: 21.0 hours**

Sorry reviewers, I kinda procrastinated making journals for too long. So, I decided to remake the base of the whole robot, which resulted in weight issues and me having to do some major redesigns to my wedge config and how everything is set up. Lets start with the body, I decided that while it looked nice before I felt that it would be more competitive if I made it wider from left to right and thinner from front to back because then i would have to deal with less gyro when i turn and have a higher chance to control the other person. The body on top is the new one compared to the old body on the bottom ![image](https://cdn.hackclub.com/01a01103-ef18-7b76-857b-224d9aed09d0/image.png) I changed how the back was setup for simplicity and to try and save weight. Because I made it wider than I made it thinner, the bot ended up being super overweight, like around 200 grams which is bad. I was able to fix that by pocketing the upright and making it smaller, pocketing the weapon which saved the most weight at 50g, and making all my 3d printed parts have less walls and infill. This helped me get the normal config underweight by only a few grams but I should be able to shave off more weight with 3d printing settings. The biggest issue I have is the wedge config, which I redesigned to save more weight but it is still 100g overweight even though it's better than it used to be. To fix this I am thinking of experimenting with different weapon styles to try to cut my weapon weight in half but that might not end well because it could be weaker. For reference here's how the wedge looked compared to how it looks now, left is old right is new ![image](https://cdn.hackclub.com/01a0113e-d929-7f4a-982d-59e4f0ea6296/image.png) ![image](https://cdn.hackclub.com/01a0113f-6c8a-7d0f-9ac6-29624034717a/image.png)
Thew new wedge is slightly thinner but still should be plenty strong because its made out of sr500 instead of the normal material which is grade 5 titanium. On the weapon stack i changed a decent amount of stuff, I changed the weapon slightly to be lighter by making pockets which will also make it hit harder because it has higher moi ![image](https://cdn.hackclub.com/01a01156-5721-7c9c-ba8b-19172c809cab/image.png) and i also changed the pulleys for the weapon stack so now they run on a almost 2:1 ratio for more torque which makes the tip speed around 220mph and the new pulley runs on a htd5m belt which is super strong. I also changed the top and bottom lid to be more inset into the tpu which will allow it to not be hit as much, i also changed the material to g10 ![image](https://cdn.hackclub.com/01a01174-73b2-714d-9434-14a588c743c6/image.png) ![image](https://cdn.hackclub.com/01a01174-d636-761f-9814-40048d1bad7e/image.png)Another big change i made was the batteries, I changed the battery from a 4s which is big and less efficient to dual 6s batteries which weigh around the same but will give me so much more power. I also changed the escs from running multiple small ones, to running one bigger four in one which will actually weigh less and cost the same. I also had to reorganize my BOM yet again and it looks way better now ![image](https://cdn.hackclub.com/01a0116d-c0a7-7e15-b6ec-1b8d868108d8/image.png) Heres a screenshot of my hackatime since the last journal ![image](https://cdn.hackclub.com/01a01166-d133-72fa-a9a2-986c35059de2/image.png) ![image](https://cdn.hackclub.com/01a01166-e528-76b3-b3e0-eae2a25af642/image.png) Heres how the final render looks ![image](https://cdn.hackclub.com/01a01169-9987-7403-a055-09907c8cc891/image.png) ![image](https://cdn.hackclub.com/01a01173-31ac-7a98-b261-395512e6a4ec/image.png)  

# 2026-06-29: Made a new weapon

**Total time spent: 3.0 hours**

Today I made a new weapon geometry for my bot, the old one I felt was too big and didn't really suit the bot. So I decided to try to build a new weapon that would be lighter and maybe hit harder. I decided to try to make the weapon have a counterweight that could hit hard, and I ended up making a jagged counterweight with teeth. And as another perk, this weapon is wayyy lighter than the last one, so I have more weight for other things. I also realized the horizontal uprights and weapon that I had wouldn't work with the belted system because there's not enough room for the motor to go, so I decided I'm keeping the wedge, but I'm going to make an even lighter weapon for the wedge, but keep the uprights the same, which should make changing configs way easier. This is how my new weapon geo looks ![image](https://cdn.hackclub.com/019f151d-2667-7633-8145-3f7b5c87038a/image.png)

# 2026-05-28: Reworking the BOM

**Total time spent: 1.5 hours**

Today i started reworking my Bom, which is taking way longer than i originally thought it would. Because i had to change so many links ![image](https://cdn.hackclub.com/019e6ce7-fb8d-7baf-a117-ab945df12b05/image.png)

# 2026-05-27: Finshed the weapon stack

**Total time spent: 1.0 hours**

Today I finished the weapon stack. I also figured out how to install Hackatime for fusion so I can more accurately log my time. For the weapon stack, I decided on using thrust washers on the sides and needle roller bearings inside. The sizing of everything ended up being perfect, so now all I have to do before I finish the design is finish the wedge config, like finish moving everything and figure out how everything is going to mount. I started that today, but there's still lots of work to do. Here's how the weapon stack looks sliced in half ![image](https://cdn.hackclub.com/019e67b9-fce2-779b-9d29-82196339bd3a/image.png)

# 2026-05-26: Continued working on the belted system

**Total time spent: 2.0 hours**

Today I continued working on the belt system. First, I had to figure out what type of belt to use, and I decided on using an XL belt. I decided that for the hub, it was going to be made out of TPU, and I want to try to get it to be as solid as possible because if it bends at all, it could hit my motor, which would be all bad. The pulley on the motor will either be made of nylon or TPU; I'm undecided. The pulley also keys onto the motor can, along with getting screwed down with a nut. ![image](https://cdn.hackclub.com/019e6294-4848-79c6-b3e6-b405b6f81566/image.png)
The two pulleys are really close together to the point of almost touching ![image](https://cdn.hackclub.com/019e64a6-f62c-7407-ba8f-0cc055d66420/image.png)

# 2026-05-25: Started a belted weapon system

**Total time spent: 3.0 hours**

Today, I started making a belted weapon system. This robot originally used a hubmotor sold by Repeat Robotics that is simple to use because the weapon just bolts on, and you're done. This works well because of its simplicity. After asking some people I know who have used them before, I decided to switch away from them. The reason I want to switch away is that it will, for one, be much cheaper, and it will also be more reliable if I do it right. Today I just created the motor mount and figured out spacing and what type of belt I'm going to use. For this, I'm going to use a motor the same size as the Repeathub motor, but it's going to have a gear reduction, which will give it more torque. The weapon hub is going to be either 3d printed out of TPU or machined by me out of UHMW. I also decided I may switch my battery to a smaller one, but I am undecided. This is how my setup looks now. The backplate is going to be aluminium, and the standoffs are also aluminium ![image](https://cdn.hackclub.com/019e5ded-a940-78e1-b16c-212d40f37554/image.png) ![image](https://cdn.hackclub.com/019e5ded-d43a-79d5-aab6-a6604990f5e8/image.png)
Here is the battery I was looking at adding ![image](https://cdn.hackclub.com/019e5dee-bd4f-7515-ae76-c6d077015b00/image.png)

# 2026-04-1: Put all the components into the bot

**Total time spent: 0.6 hours**

Over the last few days, I spent some time vibecoding a tool that can make wires in CAD so you can see where things route to and how everything will be placed. Before I did that, though, I had to make all the components: the two drive ESCs, the weapon ESC, the receiver, and the battery. After I got all those in, I used the tool to make the wires so that it looks better, and the wires can be used as a reference for how to actually wire it once I get all the parts. All the electronics, other than the battery, are on the left side of the bot, with the connector going in the middle channel between the right and left sides of the bot. With the wires, the grey wires are phase wires coming from the motors, the red and black wires are positive and negative, respectively, and the white wires are signal wires from the esc's.

Heres a top down view
![image](https://cdn.hackclub.com/019e55eb-ddfb-77d7-94f4-dafd0cb61651/image.png) Here are a few more close-up shots ![image](https://cdn.hackclub.com/019e55eb-fc3b-7358-b3a0-7303b7f2fb4d/image.png)
![image](https://cdn.hackclub.com/019e55ec-0999-79ec-9472-f4207eed764a/image.png)

# 2026-03-7: Finished the BOM And Github

**Total time spent: 1.0 hours**

I finished the BOM and relized im cooked the total price is around $460 so i will either have to cover it myself or hope i can get it approved for tier 1 without having to do anything too extreme. I also added all the files to the Github including the timeline.

Heres the BOM ![image](https://cdn.hackclub.com/019e55eb-2a4f-74bc-973e-e94f3232563c/image.png)

# 2026-03-5: Fixed the CF and made finishing touches

**Total time spent: 2.5 hours**

Today I asked my friend to look over my bot and the biggest thing he said was a issue was the carbon fiber, the issue was that all the screw holes were too close to the edge and it would have just ripped out so he had me fix all of those. The other issue was the UHMW side armor this was a small issue and it was just rounding the armor to be around the wheel instead of a block.
This is how my top lid looks now ![image](https://cdn.hackclub.com/019e55ea-37ff-7dc1-a8f9-295aa24b8490/image.png) And this is how the bottom lid looks ![image](https://cdn.hackclub.com/019e55ea-5acd-715f-adf5-1b85e130b20f/image.png) I also fixed the motor spacer to included the weapon motor wires and the routing of the drive motor wires ![image](https://cdn.hackclub.com/019e55ea-7804-7848-b578-89c9c9107aab/image.png)

# 2026-03-4: Made my horizontal config

**Total time spent: 9.0 hours**

Over the past few days ive been having trouble making a horizontal config. The way horizontal configs work usually is you have a wedge in the front, which replaces the forks, and it is normally made out of 1.6mm titanium, and it deflects the hits from horizontals and makes them bounce off or go flying instead of them digging into your bot. When I made my original wedge, it looked like this ![image](https://cdn.hackclub.com/019e55e9-299e-7e59-b127-7a938d682ec4/image.png) which is super cool because it would protect my uprights and body at the same time butttt it was 130$ out of ti which was way too much. So I made a steel wedge instead, which only costs 35$ for 2 wedges and an extra side piece. ![image](https://cdn.hackclub.com/019e55e9-49fe-7f73-984b-67f893d0cfdd/image.png) Because of how heavy steel is i had to make a bunch of compromises like removing side armor when I have it on and using a smaller weapon and uprights, but I only have to use those when I fight a horizotal otherwise, I get to run it as you saw before. To mount the wedge, I had to make these, which will have screw holes for the wedge to hold onto ![image](https://cdn.hackclub.com/019e55e9-6dfd-73d9-86f0-3ddb2f7eb2b3/image.png) The new version of the uprights and weapon looks like this ![image](https://cdn.hackclub.com/019e55e9-9278-748c-86cd-7ecbbfac2d2a/image.png) The full wedge version of the robot will look like this ![image](https://cdn.hackclub.com/019e55e9-bffe-7ef9-9a84-80c6636638a4/image.png)

# 2026-02-22: Remade the body and got closer to finishing

**Total time spent: 5.0 hours**

Over the past few days, when I worked on this i kept forgetting to journal, I remade the body, made armor, made forks, added screw holes to everything, and remade the wheels. This is how the body looks now ![image](https://cdn.hackclub.com/019e55e7-4da3-7d35-8465-40fdaafa8396/image.png) The white side rails will be made out of UHMW, the same material as my uprights, because it is light and strong. The blue parts are going to be made out of solid TPU. The UHMW parts are mounted from the front, back, top, and bottom, so there is a lot of support. The front parts are mounted to the UHMW, the uprights, and the top and bottom. The back piece is mounted with three holes in the top and bottom and is attached to the UHMW. The uprights are the same but I actually added the mounting holes now. The reason for the changes are because when i showed my friends they pointed out a bunch of issues with it.
here is a front view ![image](https://cdn.hackclub.com/019e55e7-728b-727f-b6e2-07196f61c3bb/image.png) here is a side view ![image](https://cdn.hackclub.com/019e55e7-9213-7168-84b5-2b8730409847/image.png) and here is a top view ![image](https://cdn.hackclub.com/019e55e8-3cbd-7d14-8fba-ff1c7013270b/image.png) I also had to add larger holes to the cf so it could be passthrough holes
The forks on the front are going to be made out of 6.3mm thick ar500 steel991df873dee5/image.png)

# 2026-02-18: Created a good base of the robot

**Total time spent: 6.0 hours**

So far today, I have made the entire base for the robot and finalized what parts I'm going to use. For the weapon motor, I chose the Repeat Robotics 3lb hub motor, and for the drive, I chose the Repeat Robotics Pro 2006 motors. The robot is going to be controlled with a fs-i6 remote, which I already have, and a fs2a drone receiver, which only weighs about 1g, so it's perfect. The Escs im going to use to control the drive motors are 40A AM32 ESCs, which are from Aliexpress, and for the weapon im going to use a 90A ESC from MEPSKING. For the battery, I decided on using a GNB 1100mah 4s lihv which is good because it has a high discharge rate. As for the robot, it took me a few redesigns to choose a shape I like, but I ended up with a rectangle that's wider than it is long, and it's going to be 3d printed out of TPU. ![image](https://cdn.hackclub.com/019e55e0-62cf-77a4-9ac7-cbda74c3cc78/image.png) For the upright they are going to be made out of UHMW, which is slightly pocketed to save on weight. ![image](https://cdn.hackclub.com/019e55e0-9fa3-7073-952b-1bcbbaa6c3a5/image.png) The top lid is going to be made out of 1.5mm tegris, and if that's not strong enough im going to double it up and run two of them if I have weight. The bottom lid is going to be cut by robotsmashingleauge out of 2mm thick carbon fiber because of its stiffness and strength. The wheels are going to be made out of tpu and for grip their going to use Vytaflex. The wheels are going to be belted from the front to the back to have 4wd. This is the current state of the robot ![image](https://cdn.hackclub.com/019e55e0-d5c4-70b7-a683-1f6865c0d914/image.png) ![image](https://cdn.hackclub.com/019e55e0-e4e8-72bd-8dc0-a8745a41028b/image.png) ![image](https://cdn.hackclub.com/019e55e1-0118-7d80-922d-2ced52c5a727/image.png)

# 2026-02-27: Designed the Weapon and chose motor

**Total time spent: 1.0 hours**

so far I designed the asymmetrical weapon with a long tooth and a small, wide counterweight. The diameter of the weapon is about 135mm, which is about as small as you want to make it for it to fit on the hub motor. This took me a bit because I also wanted it to look cool. As for the motor im going to use the Repeat Robotics hub motor, which is good because it's strong and makes the weapon system easier to manage, because instead of having to use belts, it just mounts onto the motor.
This is how the weapon looks ![image](https://cdn.hackclub.com/019e55df-6e87-7775-9d23-193611b44376/image.png)

