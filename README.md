# 2D Ice Shader for Unity

This repository contains a custom 2D Ice Shader for Unity, designed to add a dynamic and visually appealing ice effect to sprites. The shader features adjustable properties like refraction, translucency, and a frozen effect, making it versatile for different icy appearances.

## Features

- **Texture Support**: Applies the shader effect to any 2D sprite.
- **Normal Mapping**: Enhances the visual depth with bump mapping.
- **Refraction**: Simulates the light bending effect through ice.
- **Translucency and Subsurface Scattering**: Mimics the light scattering beneath the surface for a more realistic ice effect.
- **Dynamic Frozen Effect**: Control the intensity of the ice effect dynamically.

## Properties

- `_MainTex`: The main texture of the sprite.
- `_BumpMap`: Normal map for the bump effect.
- `_BumpScale`: Adjusts the scale of the normal map effect.
- `_Refraction`: Controls the refraction intensity.
- `_Translucency`: Adjusts the translucency of the ice.
- `_SubsurfaceColor`: Color of the subsurface scattering effect.
- `_FrozenAmount`: Controls the intensity of the frozen effect.

## Installation

1. Clone or download this repository.
2. Import the shader into your Unity project.
3. Apply the shader to your sprites through the material inspector.

## Usage

1. Create a new material in Unity.
2. Assign this shader to the material.
3. Apply the material to your 2D sprites.
4. Adjust the shader properties in the material inspector to achieve the desired ice effect.

## Contributing

Contributions to improve the shader or add new features are welcome. Please submit pull requests with a description of your changes.
