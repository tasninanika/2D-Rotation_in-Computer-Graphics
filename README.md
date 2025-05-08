# 2D Rotation in Computer Graphics

## 📌 Description

2D Rotation is a fundamental transformation technique in computer graphics used to rotate an object around the origin in the 2D plane. This transformation is achieved by applying a rotation matrix to each point of the object using a specified angle.

The rotation can be:
- **Counterclockwise** if the angle is positive.
- **Clockwise** if the angle is negative.

Rotation preserves the shape and size of the object but changes its orientation. It is especially useful in animations, game development, and modeling transformations.

The new position `(x', y')` of each point `(x, y)` after rotation by an angle θ (in radians) is computed as:

---

## 🧮 Algorithm: 2D Rotation of a Square

**Step 1:** Define the original square by listing its corner points `(x, y)`.

**Step 2:** Choose the angle of rotation in degrees and convert it to radians:  
`angle_rad = radians(angle_deg)`

**Step 3:** For each point in the square:
- `new_x = x * cos(angle_rad) - y * sin(angle_rad)`
- `new_y = x * sin(angle_rad) + y * cos(angle_rad)`  
Store the resulting point in a new list.

**Step 4:** Add the first point again at the end of both original and rotated shapes to close the square for plotting.

**Step 5:** Separate the x and y coordinates of both original and rotated points.

**Step 6:** Use Matplotlib to draw both shapes with different colors and labels.

**Step 7:** Add axis lines, grid, labels, and title to make the visualization clear.

---

## 🖼 Output

The output shows:
- The original square 
- The rotated square 
- The rotation angle clearly labeled in the legend

---

## 🛠 Technologies Used

- Python
- Matplotlib

