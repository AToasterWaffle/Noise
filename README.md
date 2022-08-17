# Waffle Noise Library

A noise system for unity

### Value Noise

Returns a random value(between 0 and 1) for each pixel
> Usage: \
> float[,] myNoiseMap = NoiseUtils.GenerateValueNoise(int width, int height, int seed);

### Perlin Noise

Returns a smoothed value(between 0 and 1) for each pixel
> Usage: \
> float[,] myNoiseMap = NoiseUtils.GeneratePerlinNoise(int mapWidth, int mapHeight, int seed, float scale, int octaves,
> float persistance, float lacunarity, Vector2 offset);