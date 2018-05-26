# GDDMarkdownTemplate
Game Design Document Markdown Template

This is meant to be used in GitHub wiki.
This template is based on the template by [Artjom Kurapov](https://kurapov.ee/rus/lab/game_development/#f191).

Please feel free to create pull requests with any additions you think should be made to this template.

# Game Design Doc Table of Contents
1. [Copyright Information](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/1.-Copyright-Information)
2. [Version History](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/2.-Version-History)
3. [Game Overview](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview)

    1. [Game Concept](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#game-concept)
    2. [Feature Set](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#feature-set)
    3. [Genre](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#genre)
    4. [Target Audience](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#target-audience)
    5. [Game Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#game-flow)
    6. [Look and Feel](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#look-and-feel)
    7. [Project Scope](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#project-scope)
        1. [Number of locations](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-locations)
        2. [Number of levels](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-levels)
        3. [Number of NPC’s](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-npcs)
        5. [Number of weapons](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/3.-Game-Overview#number-of-weapons)

4. [Gameplay and Mechanics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics)

    1. [Gameplay](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#gameplay)
        1. [Game Progression](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#game-progression)
        2. [Mission/Challenge Structure](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#missionchallenge-structure)
        3. [Puzzle Structure](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#puzzle-structure)
        4. [Objectives](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#objectives)
        5. [Play Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#play-flow)
    2. [Mechanics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#mechanics)
        1. [Physics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#physics)
        2. [Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#movement)
            1. [General Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#general-movement)
            2. [Other Movement](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#other-movement)
        3. [Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#objects)
            1. [Picking Up Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#picking-up-objects)
            2. [Moving Objects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#moving-objects)
        4. [Actions](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#actions)
            1. [Switches and Buttons](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#switches-and-buttons)
            2. [Picking Up, Carrying and Dropping](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#picking-up-carrying-and-dropping)
            3. [Talking](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#talking)
            4. [Reading](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#reading)
        5. [Combat](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#combat)
        6. [Economy](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#economy)
    3. [Screen Flow](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-flow)
        1. [Screen Flow Chart](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-flow-chart)
        2. [Screen Descriptions](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#screen-descriptions)
            1. [Main Menu Screen](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#main-menu-screen)
            2. [Options Screen](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#options-screen)
    4. [Game Options](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#game-options)
    5. [Replaying and Saving](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#replaying-and-saving)
    6. [Cheats and Easter Eggs](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/4.-Gameplay-and-Mechanics#cheats-and-easter-eggs)

5. [Story, Setting and Character](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character)
    1. [Story and Narrative](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#story-and-narrative)
        1. [Back Story](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#back-story)
        2. [Plot Elements](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#plot-elements)
        3. [Game Progression](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#game-progression)
        4. [License Considerations](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#license-considerations)
        5. [Cut Scenes](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#license-considerations)
            1. [Cut Scene #1](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#cut-scene-1)
                1. [Actors](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#actors)
                2. [Descriptions](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#descriptions)
                3. [Storyboard](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#storyboard)
                4. [Script](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#script)
    2. [Game World](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#game-world)
        1. [General look and feel of world](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#general-look-and-feel-of-world)
        2. [Area #1](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#area-1)
            1. [General Description](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#general-description)
            2. [Physical Characteristics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#physical-characteristics)
            3. [Levels that use area](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#levels-that-use-area)
            4. [Connections to other areas](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#connections-to-other-areas)
    3. [Characters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#characters)
        1. [Character #1](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#character-1)
            1. [Back Story](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#back-story-1)
            2. [Personality](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#personality)
            3. [Look](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#personality)
                1. [Physical Characteristics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#physical-characteristics-1)
                2. [Animations](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#animations)
            4. [Special Abilities](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#special-abilities)
            5. [Relevance to Game Story](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#relevance-to-game-story)
            6. [Relationship to Other Characters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#relationship-to-other-characters)
            7. [Statistics](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/5.-Story,-Setting-and-Character#statistics)

6. [Levels](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels)
    1. [Level #1](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#level-1)
        1. [Synopsis](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#synopsis)
        2. [Introductory Material](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#introductory-material)
        3. [Objectives](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#objectives)
        4. [Physical Description](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#physical-description)
        5. [Map](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#map)
        6. [Critical Path](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#critical-path)
        7. [Encounters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#encounters)
        8. [Level Walkthrough](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#level-walkthrough)
        9. [Closing Material](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/6.-Levels#closing-material)

7. [Interface](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface)
    1. [Visual System](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#visual-system)
        1. [HUD](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#hud)
        2. [Menus](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#menus)
        3. [Rendering System](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#rendering-system)
        4. [Camera](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#camera)
        5. [Lighting Models](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#lighting-models)
    2. [Control System](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#control-system)
    3. [Audio](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#audio)
    4. [Music](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#music)
    5. [Sound Effects](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#sound-effects)
    6. [Help System](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/7.-Interface#help-system)

8. [Artificial Intelligence](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence)
    1. [Opponent AI](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#opponent-ai)
    2. [Enemy AI](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#enemy-ai)
    3. [Non-combat Characters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#non-combat-characters)
    4. [Friendly Characters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#friendly-characters)
    5. [Support AI](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#support-ai)
        1. [Player and Collision Detection](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#player-and-collision-detection)
        2. [Pathfinding](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/8.-Artificial-Intelligence#pathfinding)

9. [Technical](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical)
    1. [Target Hardware](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#target-hardware)
    2. [Development Hardware and Software](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#development-hardware-and-software)
    3. [Development Procedures and Standards](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#development-procedures-and-standards)
    4. [Game Engine](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#game-engine)
    5. [Network](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#network)
    6. [Scripting Language](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/9.-Technical#scripting-language)

10. [Game Art](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art)
    1. [Concept Art](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#concept-art)
    2. [Style Guides](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#style-guides)
    3. [Characters](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#characters)
    4. [Environments](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#environments)
    5. [Equipment](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#equipment)
    6. [Cut scenes](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#cut-scenes)
    7. [Miscellaneous](https://github.com/TheLazyHatGuy/GDDMarkdownTemplate/wiki/10.-Game-Art#miscellaneous)

Secondary Software	12
    Editor	12
    Installer	12
    Update software	12

Management	12
    Detailed Schedule	12
    Budget	12
    Risk Analysis	12
    Localization Plan	12
    Test Plan	12

Appendices	12
    Asset List	12
        Art	12

        Sound	12

        Music	13

        Voice	13
