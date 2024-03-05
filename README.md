Pokémon Analytics: Unveiling Insights Through Tableau

Description:
This project, undertaken during my university studies, utilizes Tableau to explore the fascinating world of Pokémon. Through interactive dashboards and engaging stories, I delved into various aspects of these captivating creatures.
This project not only served as a learning experience in data visualization with Tableau, but also allowed me to explore my passion for Pokémon and uncover fascinating insights from a data-driven perspective.

Data Source: The data for this project was obtained from Kaggle: https://www.kaggle.com, a popular platform for data science and machine learning.


![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/8a362ca6-a75c-405f-a731-e1fca9a46dce)
The image shows a graph that displays the type effectiveness of various Pokemon against a Water-type opponent. The x-axis lists different Pokemon types, while the y-axis shows a multiplier value. Higher values on the y-axis indicate greater effectiveness against a Water-type opponent. For example, the graph shows that Electric-type Pokemon have a multiplier of 2 against Water-type Pokemon, while Grass-type Pokemon have a multiplier of 0.5.

![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/ab00abb0-cade-45c8-987b-066d0ff85f98)
The image displays a table that shows various moves a Water-type Pokémon can learn. The table has columns for Category, Name, Effect, PP, Cat. and Namel.

Category: This column specifies the category of the move, which can be either "Physical" or "Special."
Name: This column lists the name of the move.
Effect: This column describes the additional effect the move may have, such as lowering the opponent's Defense or having a high critical hit ratio.
PP: This column shows the Power Points (PP) of the move, which indicates how many times the Pokémon can use the move before needing to recharge.
Cat.: This column likely refers to the "Category" again but is abbreviated.
Namel: This column might be a misspelling of "Name" and seems to repeat the move name.

In one of the stories it will be presented how to find the most effective Pokemon for a battle:
![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/b627cac1-0c05-4de2-91ca-7f53bb641471)
This Tableau visualization shows a story functionality, aiding trainers in strategizing against specific Pokémon types. In this view, the focus is on Dragon-type opponents.
The visualization displays super effective Pokémon against Dragons. It also show additional information such as:

Effectiveness multiplier: A numerical value (e.g., 2.00) indicating how much more damage these Pokémon deal to Dragons compared to neutral effectiveness.
Additional details: This could include Pokémon stats, types, or movesets, helping trainers make informed choices.
By enabling users to explore effective counters, this Tableau function empowers them to build winning strategies against even the most formidable Dragon-type foes.

![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/cc52cc26-dbf8-4733-bb47-98106d95a892)
The visualization highlights Sylveon as super effective against Dragon-type Pokémon, likely due to the Fairy-type's advantage against Dragons. It mentions a multiplier value of 0.5000, which might indicate Sylveon deals double damage to Dragon-type opponents compared to neutral effectiveness.

How do I find a Pokémon for a battle against a Gyarados? We search for Gyarados by name, observe its battle statistics; it is most affected by the Electric type.
![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/479c2972-a4d2-4694-8b17-00c7912561d0)

We search for Gyarados's type, Water, and look at Electric-type Pokémon. There are Electric-type Pokémon with 100% resistance against the Water type: Helioptile and Heliolisk.
![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/b9ed395c-dea6-4026-a02d-54065d4a121e)

It is observed that the two Pokémon have the same statistics, so the choice will be made based on other criteria, such as experience, level, HP value, or the Pokémon's abilities, or the trainer's preferences.
![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/99c577c7-2a87-41af-876b-c5e90af991f6)

In the end, we have the moves that Electric-type Pokémon like Heliolisk and Helioptile can learn, sorted by damage and corresponding Power Points.
![image](https://github.com/AlexandraIftimie/Pokemon/assets/132292637/b1c64ad4-c81b-462f-ac25-74af3bb72329)


This interactive function, part of a larger analysis, allows you to explore various Pokémon and their effectiveness against specific types, empowering you to strategize and build winning teams.

Limitations:

It is important to acknowledge that the data used in this project may not have been entirely comprehensive. While Kaggle: https://www.kaggle.com is a valuable resource for open-source datasets, there is always the possibility of missing information or inconsistencies.

Future Work:

This project opens doors for further exploration. Future iterations could incorporate additional data sources to address potential limitations and delve deeper into specific aspects, such as analyzing move effectiveness or exploring the competitive landscape of the Pokémon world.

Contribution Guidelines:

If you are interested in contributing to this project, feel free to reach out and discuss potential areas for collaboration. This could involve sharing additional data sources, suggesting new visualizations, or even helping to expand the scope of the analysis.
