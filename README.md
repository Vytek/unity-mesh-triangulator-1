# Unity Mesh Triangulator

Explode into triangles any mesh you want!

![](MeshTriangulator.gif)

### Prerequisites

The given project was made with Unity 2018.2.3f1

### Installing

You can open the Assets folder in a new Unity project or just get the .unitypackage and throw it at any project

## Running the tests

The example project has different objects which use the static MeshTriangulator class. 
If you want to test it with any other objects just try to call the Triangulate() function and give it the object transform 

```
MeshTriangulator.Triangulate(transform)
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
