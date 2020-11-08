# Open GoPro Mount

A modular open source GoPro mount for FPV Drones.

## STL Files

[STL files](./STL) are ready to print GoPro Mounts, all available combinations of camera holders and frames mounts are available in the [STL folder](./STL)
If your specific camera model or frame is not yet supported, please [file a request](https://github.com/theely/Open-GoPro-Mount/issues).

### How to 3D Print

#### Filament

- The main body is designed to be printed with TPU (shore A95 or A98).
- The screen protector is best printed with rigid materials such as PLA, Nylon or hard TPU (shore D58)

#### Slicer Settings

- Infil Density: 30%
- Wall Lines: 4
- Top and Bottom Layers: 4
- Support: Yes

#### Slicer Optimal parts orientation

<img width="400" src="https://user-images.githubusercontent.com/2025999/96481367-bab92b80-123b-11eb-9efe-d3d14730b8a8.png">

<img width="400" src="https://user-images.githubusercontent.com/2025999/96481348-b2f98700-123b-11eb-91b8-be7c9513a711.png">
Note: This part can't be printed without support or the overhang will not print properly.

#### Printed Model Reference

<img width="400" src="https://user-images.githubusercontent.com/2025999/96494169-446df680-1246-11eb-83ca-87b56119bcc6.jpg">

## Design Principle

- Designed to be extremely duravble, ultra light and easy to 3D print.
- Modular approach to allow reusability of the component and easy portability to different quad frame designs.

<img src="https://user-images.githubusercontent.com/2025999/96351786-047c0780-10be-11eb-84a7-6743fbe14ab3.PNG" width="400">

<img src="https://user-images.githubusercontent.com/2025999/96350563-b6173a80-10b6-11eb-8d7b-215e74876cb8.jpg" width="400">

<img src="https://user-images.githubusercontent.com/2025999/96349479-44d48900-10b0-11eb-8346-5a620a46a129.jpg" width="400">

## How to contribute?

The Open-GoPro-Mount is made of 4 components:

- Camera Holder
- Quad Frame Mount
- Lens protection
- Screen protection

### Porting the Open-GoPro-Mount to a new Quad Frame

To port the Open-GoPro-Mount to a new quad frame it's sufficent to design a new Quad Frame Mount.
Either by adapting an existing mount (e.g. Apex Mount (22.5°).step) or by design a new one from scratch.

The angle of the overal mount is defined by the Frame Mount, multiple mount angles can be supported by providing additional Quad Frame Mount featuring a set of angles.

#### Requirements

Each frame mount should include the following joint pice (red part) in order to be compatible with the Camera Holders.

<img src="https://user-images.githubusercontent.com/2025999/96378812-f34efb80-118e-11eb-8896-4a6d0e611ed2.png" width="400">

The joint (red part) has the following dimensions:

<img src="https://user-images.githubusercontent.com/2025999/96380931-14641c00-1190-11eb-9bf0-902115ad2f04.png" width="400">

Its important to respect the distance between the two red pieces:

<img src="https://user-images.githubusercontent.com/2025999/96380984-17f7a300-1190-11eb-8bec-2b530e6b0df1.png" width="400">

### Adapting the Open-GoPro-Mount for a new Camera

To support additional cameras a new Cameras it's sufficent to desing a new Camera Holder.
Either by adapting an existing hodler (e.g. GoPro Hero 5/6/7 Holder.step) or by design a new one from scratch.

#### Requirements

Each camera holder should include the following joint holes in order to be compatible with the Quad Frame Mounts.

<img src="https://user-images.githubusercontent.com/2025999/96549381-b3cc0080-12af-11eb-97fa-e5d5d52479cd.png" width="400">

Distance between the holes are standardised and can not be changes.

<img src="https://user-images.githubusercontent.com/2025999/96549398-b6c6f100-12af-11eb-8299-ac6604b7d02d.png" width="400">

<img src="https://user-images.githubusercontent.com/2025999/96549376-b0d11000-12af-11eb-93ba-03e46be522ce.png" width="400">

The width of the holes does not necesarely be respected as long as there is enought material for the Quad Frame Mounts to join with the Camera Holder.

<img src="https://user-images.githubusercontent.com/2025999/96550661-6e103780-12b1-11eb-8c10-09c576360685.png" width="200"><img src="https://user-images.githubusercontent.com/2025999/96550671-70729180-12b1-11eb-909b-e1cab9a60e39.png" width="200">

## Source File (Designs)

### Fusion360 Project

You can access the source design directly from the shared Fusion360

- [Fusion360 project](https://gmail784198.autodesk360.com/g/projects/20201018344143181/data/dXJuOmFkc2sud2lwcHJvZDpmcy5mb2xkZXI6Y28uZjc2MFRFNlhSaW1rVDFkaDE2NXdIdw)

### Step Files

Or you can import the shared step files and edit them in your favorite CAD program.

##### Cameras

- GoPro Hero 5/6/7
  - GoPro Hero 5/6/7 Holder.step
  - GoPro Hero 5/6/7 Lens Protection.step
  - GoPro Hero 8 Holder.step
  - GoPro Hero 8 Lens Protection.step

##### Frames

- Apex Support (22.5°).step
- DRC Flow Support (30°).step

##### Screen Protection

- GoPro Screen Protection.step
