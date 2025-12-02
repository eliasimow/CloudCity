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
