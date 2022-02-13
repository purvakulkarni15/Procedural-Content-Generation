# Procedural Terrain Generation

#### Perlin Noise:
Generates structured random numbers that follow a smooth gradiet. 

#### Algorithm for terrain generation:
1. Create a 2D grid.
2. For height, layer multiple levels of noise to add detail maintaining the overall shape.
3. Maintain 3 noise maps referred to as octaves each for overall shape, boulders and small rocks.
4. Increase the frequency of each subsequent octave by a factor referrered to as "lacunarity".
5. Decrease the amplitude of each subsequent octave by a factor referrered to as "persistance".
6. Add the 3 noise maps to get final height value.
