## Backend

Using ASP.NET Web Api, generate code to:
- create a Web API that serves the planet data
- use the following endpoints:
  - GET /planets: returns a list of planets with their names, sizes, and rotation times
  - GET /planets/{id}: returns a specific planet with its name, size, rotation time, and texture URL
  - use the following data model:
    - Planet
      - Id: int
      - Name: string
      - Size: float
      - Distance: float
      - Speed: float
      - RotationSpeed: float
      - TextureUrl: string
  - use the following data:
  ``` JSON
            { Name: "Mercury", Size: 0.383, distance: 5.79, Speed: 0.08, RotationSpeed: 0.01, TextureUrl: "/planets-app/planets-frontend/assets/mercury.jpg" },
            { Name: "Venus", Size: 0.949, distance: 10.82, Speed: 0.03, RotationSpeed: 0.006, TextureUrl: "/planets-app/planets-frontend/assets/venus.jpg" },
            { Name: "Earth", Size: 1, distance: 15, Speed: 0.02, RotationSpeed: 0.008, TextureUrl: "/planets-app/planets-frontend/assets/earth.jpg" },
            { Name: "Mars", Size: 0.532, distance: 22.79, Speed: 0.016, RotationSpeed: 0.012, TextureUrl: "/planets-app/planets-frontend/assets/mars.jpg" },
            { Name: "Jupiter", Size: 11.21, distance: 77.78, Speed: 0.004, RotationSpeed: 0.014, TextureUrl: "/planets-app/planets-frontend/assets/jupiter.jpg" },
            { Name: "Saturn", Size: 9.45, distance: 143.37, Speed: 0.002, RotationSpeed: 0.016, TextureUrl: "/planets-app/planets-frontend/assets/saturn.jpg" },
            { Name: "Uranus", Size: 4.01, distance: 287.1, Speed: 0.0008, RotationSpeed: 0.018, TextureUrl: "/planets-app/planets-frontend/assets/uranus.jpg" },
            { Name: "Neptune", Size: 3.88, distance: 449.5, Speed: 0.0004, RotationSpeed: 0.02, TextureUrl: "/planets-app/planets-frontend/assets/neptune.jpg" }
```