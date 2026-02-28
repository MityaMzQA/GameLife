Developed game application written on WPF technology for the version .NET 5.0. Application is based on the plot of the famous computer game "Life".

The game takes place on a grid that can be infinite, finite, or closed.
Each cell on this surface has eight neighbors surrounding it and can be in one of two states: “alive” (filled) or “dead” (empty).
The distribution of live cells at the beginning of the game is called the first generation. Each subsequent generation is calculated based on the previous one according to the following rules:
-in an empty (dead) cell that is adjacent to three live cells, life begins;
-if a live cell has two or three live neighbors, then this cell continues to live; otherwise (if there are fewer than two or more than three live neighbors), the cell dies (“from loneliness” or “from overpopulation”).

The game ends if:
-there are no “live” cells left on the field;
-the configuration at the next step exactly repeats itself (without shifts or rotations) at one of the earlier steps (a periodic configuration is formed);
-at the next step, none of the cells change their state (a special case of the previous rule, a stable configuration is formed);

The player does not actively participate in the game. They only arrange or generate the initial configuration of “live” cells, which then change according to the rules. Despite the simplicity of the rules, a huge variety of shapes can arise in the game.
