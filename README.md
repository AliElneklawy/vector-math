# vector-math
To use the Vector Module in your Python scripts, follow these steps:

**Import the required vector classes from the module**:

from vectors import Vect2D, Vect3D, Vect4D

# Create vector objects:

**Create a 2D vector**

vec2d = Vect2D((2, 3))

**Create a 3D vector**

vec3d = Vect3D((1, 4, 6))

**Create a 4D vector**

vec4d = Vect4D((3, 5, 7, 2))

# Perform vector operations using the methods provided by the vector classes:
**Addition**

result = vec2d + vec2d

**Subtraction**

result = vec3d - vec3d

**Scalar multiplication**

result = vec4d * 2

**Dot product**

result = vec2d.dot(vec2d)

**Cross product (only applicable for 3D vectors)**

result = vec3d.cross(vec3d)

**Angle calculation (in radians)**

result = vec4d.angle(vec4d)

**Access the magnitude of a vector**

magnitude = vec2d.mag

# Print the vector representation
print(vec3d)  # Output: (1, 4, 6)
