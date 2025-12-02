### Design Doc
#### Introduction
We’re excited by the idea of procedurally generating assets that can amplify the visual impact of our GPU final project, real time cloud generation. Because a big focus of that final project is collisions, we’d like to make assets here that can highlight that functionality. We think that floating cloud rocks and foliage, and procedurally animated fauna flying between those assets and the GPU clouds, would look incredible!

#### Goal
We aim to create high-quality floating island assets with procedurally animated birds that react to them. These assets, along with supporting elements like a skybox, will be assembled into a cohesive demo scene. By juxtaposing the islands and the birds, we hope to convey a strong sense of scale and enhance the visual impact of our scene. 

#### Inspiration/reference:
- Avatar
  - https://www.youtube.com/watch?v=YfK6CNTAG7o
- RIVEN architecture
  - https://www.youtube.com/watch?v=JumtB_YY2I4

#### Specification:
- Houdini Floating Terrain Generation
  - Rock architecture
  - Vines
  - Foliage, Trees
- Basic Architecture
  - Homes
  - Bridges
- Birds
  - Extra Credit: Custom Bird Generation
  - Procedural Animation:
    - Flocking
    - Obstacle Avoidance
    - Triangle Leader Following

#### Techniques:
- [Ivy Tool](https://www.sidefx.com/tutorials/project-titan-ivy-tool/) 
- [Vines Generation](https://www.youtube.com/watch?v=3u6UNNJQ_cM)
- [Procedural Rock Generation](https://www.sidefx.com/tutorials/proc-rocks-using-vops/)
- [Bird Flight Modeling](https://grail.cs.washington.edu/projects/flight/wu2003realistic.pdf)
- Boids, Leader Following, Obstacle Avoidance

#### Design:
<img width="405" height="416" alt="image" src="https://github.com/user-attachments/assets/a7aa48b4-8126-4e35-9e97-08cc9878c9d3" />

#### Timeline:
- Week 1
  - Floating islands base and procedural ivies 
  - Basic Birds Modeling
- Week 2 
  - Vines between floating islands 
  - Bird Flying Animations
- Week 3 
  - Riven style architecture on islands
  - Bird Behavioral Animations
- Week 4
  - Polish architecture and add more foliage 
  - Birds in engine with terrain

## Milestone 1



https://github.com/user-attachments/assets/ba4b1430-0102-4c41-aac1-231499145be9

Progress:

Programmed some flocking behavior into houdini, using several POP forces!
Next step there will be to tie bird animation to the particle state and to add obstacle avoidance.


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f416693e-6145-4759-a5c8-610ae4503def" />

Progress: 

Created base for procedural floating islands. The next step would be adding vegeatation, structures, etc. to enrich the island's visuals. 

## Milestone 2: Implementation part 2 (due 11/24)

<img width="1168" height="641" alt="image" src="https://github.com/user-attachments/assets/8034e447-f2d1-4057-9f5b-a954f721239d" />
Ruined Brick Generation


https://github.com/user-attachments/assets/4376d492-bd75-4e5d-bad1-ffc780beb52b

WIP bridge creation

## Final Version Overview

For our procedural final project, we have constructed a highly dynamic set of art assets for use in constructing a decayed cloud city. The scene is composed of four pieces, each of which is configurable and parameterized. The pieces are as follows:

- Floating Islands. These are the centerpiece of the scene, and can be made to fit any arbitrary size the artist desires. Procedural moss grows along the islands' rocky underbellies. Simulated grass and weeds flow in the wind as the render progresses.

- Molded Rope Bridges. These can be set to join any two arbitrary points in space, connecting islands across any distance and height. Decay level can be set, which dictates the bridge's number of remaining planks and the sag of the parabola.

- Decayed Walls. Artist's can use the Houdini pen tool to draw out a section of the wall that has crumbled over the decades; bricks will be broken and half and sheared off by this border. Remaining bricks are still decayed by a noise boolean union effect.

- Boids. A flock of seagulls flies back and forth between islands. They are motivated by a set of force principles: to chase the center of the pack, to avoid collision with each other, and to avoid collision with the islands. The seagull model is sourced from https://www.turbosquid.com/Search/Artists/msurguy

## Post Mortem

Overall, we really enjoyed working on this project! We reacted quickly to changing conditions to readjust scope, and that avoided some potential pitfalls that could have led to a less complete final project. The choice to complete the overall experience in Houdini first was the correct one, as we simply didn't have the time to port it over to GPU for our final experience. 

