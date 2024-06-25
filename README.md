# Burner Modeling

modeling of the fluid dynamics of a turbulent burner (without reactions) in OpenFoam.

Features:

- $v_{gas} = 20 m/s$
- EGR (exhaust gas recirculation)
  - $v_{gasEGR} = -5m/s$
- dual stage burning
  - $v_{gas2stage} = 10 m/s$
- $D_{equivalent} = 11 cm$
- custom burner for steam reforming
- 7 Mln mesh, run on 16 cores.
- RANS simulation, turbulence model: K-omega_SST

## Results

- mesh clip (cropped)

  - 1
    ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_mesh.png)
  - 2
    ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_mesh2.png)

- velocity field
  ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_glyph.png)

- stream tracing
  ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_stream_tracing.png)

### blender renderings

- BACK
  ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_BACK.png)
- FRONT
  ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_FRONT.png)
- SIDE
  ![alt text](https://github.com/sommaa/burner_modeling/blob/main/images_BURNER/BURNER_SIDE.png)
