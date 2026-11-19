# Page 1. Introduction

Mathematics is an important subject that helps us understand different shapes, patterns and measurements in our surroundings. One of its major branches, calculus, provides methods for calculating areas of geometrical figures, especially those bounded by curves and straight lines.

A circle is a common geometrical shape, while an oblique line is a straight line inclined to the coordinate axes. When an oblique line intersects a circle at two distinct points, it divides the circular region into two parts known as circular segments. The area of these regions can be determined using mathematical methods.

The main aim of this project is to study the area bounded by a circle and an oblique line using definite integration. It includes the equations of both curves, their points of intersection, the derivation of the required formula, graphical representations and numerical examples to understand the concept clearly.

---

# Page 2. Basic Concept of a Circle

A circle is defined as the set of all points in a plane that are at a fixed distance from a fixed point. The fixed point is called the centre of the circle, while the constant distance is known as its radius. Every point on the circumference is equally distant from the centre.

A circle is a closed geometrical figure and its shape is completely determined by its radius. The diameter is the longest chord of a circle and passes through its centre. It is always twice the length of the radius.

The standard equation of a circle whose centre is at the origin and whose radius is r is:

x² + y² = r²

This equation represents all the points lying on the circumference of the circle and will be used throughout this project.

---

# Page 3. Standard Equation of a Circle

Consider a circle with its centre at the origin O(0,0) and radius r. Let P(x,y) be any point on its circumference. Since every point on the circumference is at a fixed distance from the centre, the distance OP must be equal to r.

Using the distance formula, we get:

OP = √[(x − 0)² + (y − 0)²]

Since OP = r,

√(x² + y²) = r

Squaring both sides gives:

**x² + y² = r²**

This is the standard equation of a circle with centre at the origin. It establishes the relationship between the coordinates of every point on the circumference and the radius of the circle.

**DIAGRAM:** Draw a circle with centre O(0,0). Mark a point P(x,y) on the circumference and join OP. Label the radius r, x-axis and y-axis.

---

# Page 4. General Equation of a Circle

The equation of a circle is not limited to a centre at the origin. When the centre is located at a general point (h,k) and the radius is r, its equation becomes:

(x − h)² + (y − k)² = r²

On expanding this equation, we obtain the general form:

x² + y² + 2gx + 2fy + c = 0

Comparing the two forms, the coordinates of the centre are (-g,-f), while the radius is given by:

r = √(g² + f² − c)

The equation represents a real circle when g² + f² − c is positive. In this project, we mainly consider circles centred at the origin because they make the calculations and graphical representations simpler.

---

# Page 5. Straight Lines

A straight line is a geometrical figure that extends infinitely in both directions. It is one of the basic elements of coordinate geometry and can be represented algebraically using a linear equation. Every point lying on the line satisfies its equation.

The inclination of a straight line is measured with respect to the positive direction of the x-axis. The slope of a line represents its steepness and is calculated by dividing the change in the y-coordinate by the change in the x-coordinate.

For two points (x₁,y₁) and (x₂,y₂), the slope is:

m = (y₂ − y₁)/(x₂ − x₁)

The value of the slope helps us understand the direction and inclination of a straight line on the coordinate plane.

---

# Page 6. Oblique Lines

An oblique line is a straight line that is inclined to the coordinate axes. Unlike horizontal and vertical lines, it has a finite and non-zero slope. Such lines are commonly represented using the slope-intercept form of a linear equation.

The general slope-intercept form is:

y = mx + c

Here, m represents the slope of the line and c represents its y-intercept. The slope determines the inclination, while the y-intercept indicates the point where the line crosses the y-axis.

An oblique line intersecting a circle forms a chord and divides the circular region into two segments. This relationship is the main geometrical idea studied in this project.

**DIAGRAM:** Draw coordinate axes showing three separate lines: one horizontal, one vertical and one oblique. Label each line clearly.

---

# Page 7. Bounded Regions

When a straight line intersects a circle at two distinct points, it forms a chord inside the circle. The chord and the corresponding arc enclose a region known as a circular segment. Such a region is bounded by both a curved and a straight boundary.

A circle divided by a chord forms two segments. The smaller region is called the minor segment, while the larger region is called the major segment. Both regions together make up the complete circular area.

The area of these segments can be calculated using definite integration. The required limits are determined by the points where the straight line intersects the circle, making the calculation dependent on the equations of both curves.

**DIAGRAM:** Draw a circle intersected by an oblique line. Shade the smaller region and label the minor segment, major segment, chord and arc.

---

# Page 8. Points of Intersection

The points of intersection are the points that lie on both the circle and the straight line. To determine these points, the equations of the two curves must be solved simultaneously. Their coordinates help us identify the exact limits required for integration.

Consider a circle with equation:

x² + y² = r²

And an oblique line:

y = mx + c

Substituting the equation of the line into the equation of the circle gives:

x² + (mx + c)² = r²

This equation can be simplified into a quadratic equation in x. Its roots provide the x-coordinates of the intersection points, while the corresponding y-coordinates are obtained from the equation of the line.

---

# Page 9. Nature of Intersection

A straight line can intersect a circle in different ways depending on its position relative to the centre. The perpendicular distance between the centre and the line determines the nature of this intersection.

When the distance is less than the radius, the line intersects the circle at two distinct points and is called a secant. When the distance equals the radius, the line touches the circle at exactly one point and is called a tangent.

If the perpendicular distance is greater than the radius, the line does not intersect the circle. Therefore, for calculating the area of a circular segment, the perpendicular distance must be less than the radius.

**DIAGRAM:** Draw three separate circles illustrating a secant, tangent and non-intersecting line. Label all three cases.

---

# Page 10. Chord of a Circle

A chord is a straight line segment joining any two points on the circumference of a circle. The diameter is a special chord that passes through the centre and has the greatest possible length among all chords.

When an oblique line intersects a circle, the portion of the line inside the circle forms a chord. This chord divides the circle into a minor segment and a major segment, depending on the length of the corresponding arcs.

An important property of a circle states that the perpendicular drawn from its centre to a chord bisects the chord. This property is useful in finding the chord length and calculating the area of the enclosed segment.

**DIAGRAM:** Draw a circle with chord AB. Mark the centre O and perpendicular OM from O to AB. Label OA = r, OM = d and AM = MB.

---

# Page 11. Perpendicular Distance

The perpendicular distance between the centre of a circle and an oblique line is an important quantity in calculating the enclosed area. It represents the shortest distance from the centre to the straight line and is measured along a perpendicular.

Consider a circle centred at O(0,0) and an oblique line represented by:

y = mx + c

Rearranging the equation gives:

mx − y + c = 0

Using the formula for the distance of a point from a straight line, the perpendicular distance from the origin is:

d = |m(0) − 0 + c|/√(m² + 1)

Therefore, the required distance is:

**d = |c|/√(1 + m²)**

This formula will be used in the numerical examples later in the project.

---

# Page 12. Length of the Chord

The perpendicular drawn from the centre of a circle to a chord divides the chord into two equal parts. This property allows us to calculate the length of the chord using the Pythagoras theorem.

Let r be the radius of the circle and d be the perpendicular distance from its centre to the chord. If L represents the total length of the chord, then the right-angled triangle formed gives:

(L/2)² + d² = r²

Rearranging the equation:

(L/2)² = r² − d²

Taking the square root and multiplying both sides by 2 gives:

**L = 2√(r² − d²)**

This formula is valid when d is less than r, which means that the line intersects the circle at two distinct points.

---

# Page 13. Definite Integration

Integration is an important branch of calculus that is used to calculate quantities such as areas, volumes and accumulated changes. It is particularly useful when dealing with curved boundaries, where ordinary geometrical formulas may not be sufficient.

A definite integral represents the accumulated value of a function between two fixed limits. It is written in the following form:

∫ₐᵇ f(x) dx

Here, a represents the lower limit and b represents the upper limit of integration. The function f(x) describes the mathematical relationship being considered over the given interval.

In geometrical applications, definite integration helps determine the exact area enclosed by curves. It is therefore an essential mathematical tool for studying the area bounded by a circle and an oblique line.

---

# Page 14. Area Under a Curve

The area under a curve can be calculated using definite integration. Consider a continuous function y = f(x) lying above the x-axis between x = a and x = b. The area enclosed by the curve, the x-axis and the two vertical boundaries is represented by an integral.

The required area is expressed as:

A = ∫ₐᵇ f(x) dx

When two curves are involved, the area between them is calculated by subtracting the lower function from the upper function. This gives the general expression:

A = ∫ₐᵇ [f(x) − g(x)] dx

This principle is directly applicable to the present topic because the required region is enclosed by a circular arc and an oblique straight line.

**GRAPH:** Draw a smooth curve above the x-axis between x = a and x = b. Shade the enclosed area and label the limits.

---

# Page 15. Circle and Integration

The equation of a circle centred at the origin is:

x² + y² = r²

To express the circle in terms of y, we rearrange the equation:

y² = r² − x²

Taking square roots gives:

y = ±√(r² − x²)

The positive value represents the upper semicircle, while the negative value represents the lower semicircle. These two expressions describe the complete circumference of the circle.

Using these equations, the area of different portions of a circle can be calculated through definite integration. This provides the foundation for finding the area bounded by the circle and an oblique line.

**GRAPH:** Draw the circle x² + y² = r² on coordinate axes. Label the upper semicircle and lower semicircle.

---

# Page 16. Area of a Semicircle

The equation of the upper semicircle is:

y = √(r² − x²)

To calculate its area, we integrate the function between the limits −r and r. Therefore, the area is expressed as:

A = ∫₋ᵣʳ √(r² − x²) dx

Since the upper semicircle is symmetrical about the y-axis, the integral can also be written as:

A = 2∫₀ʳ √(r² − x²) dx

Evaluating the standard integral gives:

A = 2 × (πr²/4)

Therefore, the area of a semicircle is:

**A = πr²/2**

This result also confirms that the area of a complete circle is πr².

---

# Page 17. Rotation of Axes

When a circle is intersected by an oblique line, direct integration can become complicated because the line is inclined to the coordinate axes. To simplify the calculation, we can introduce a new coordinate system by rotating the original axes.

Let u represent the coordinate along the direction of the oblique line and v represent the perpendicular coordinate. The new axes remain perpendicular to each other, but their orientation is changed to match the position of the line.

Since rotation of axes does not change distances, angles or areas, the equation of the circle remains:

u² + v² = r²

In this new coordinate system, the oblique line becomes a horizontal line represented by v = d, where d is its perpendicular distance from the centre.

**DIAGRAM:** Draw the original circle with an inclined chord. Beside it, draw the rotated coordinate system showing the same circle with a horizontal chord.

---

# Page 18. Circular Segment

In the rotated coordinate system, the equation of the circle is:

u² + v² = r²

Solving for v gives:

v = ±√(r² − u²)

The upper boundary of the circle is represented by the positive value, while the straight-line boundary is represented by v = d. The region between these two boundaries forms the minor circular segment.

At the points of intersection, the values of v are equal. Therefore:

d = √(r² − u²)

Squaring and rearranging gives:

u² = r² − d²

Hence, the limits of integration are:

**u = ±√(r² − d²)**

**GRAPH:** Draw a circle with a horizontal chord v = d. Shade the minor segment and label the radius, centre, perpendicular distance and intersection points.

---

# Page 19. Setting Up the Integral

The area of the minor segment is the difference between the area under the upper circular boundary and the area under the horizontal chord. The upper boundary is represented by √(r² − u²), while the lower boundary is d.

The limits of integration are obtained from the intersection points of the circle and the chord. Therefore, the required area can be expressed as:

A = ∫₋ₐᵃ [√(r² − u²) − d] du

Here:

a = √(r² − d²)

This integral represents the exact area enclosed by the minor arc and the chord. It forms the main mathematical expression used to derive the formula for the required region.

---

# Page 20. Evaluation of the Integral

Starting with the integral obtained on the previous page:

A = ∫₋ₐᵃ [√(r² − u²) − d] du

Since the expression is symmetrical about the v-axis, we can write:

A = 2∫₀ᵃ √(r² − u²) du − 2ad

Using the standard integration formula:

∫√(r² − u²) du

= (u/2)√(r² − u²) + (r²/2) sin⁻¹(u/r)

Substituting the limits 0 and a, and using √(r² − a²) = d, we obtain:

A = ad + r² sin⁻¹(a/r) − 2ad

Therefore:

**A = r² sin⁻¹(a/r) − ad**

---

# Page 21. Final Area Formula

From the previous result, we have:

A = r² sin⁻¹(a/r) − ad

We also know that:

a = √(r² − d²)

Substituting this value gives:

A = r² sin⁻¹[√(r² − d²)/r] − d√(r² − d²)

Using the trigonometric identity:

sin⁻¹[√(r² − d²)/r] = cos⁻¹(d/r)

The final expression becomes:

**A = r² cos⁻¹(d/r) − d√(r² − d²)**

This is the required formula for the area of the minor circular segment, where r is the radius and d is the perpendicular distance from the centre to the oblique line.

---

# Page 22. Area of the Major Segment

A straight line intersecting a circle divides it into two circular segments. The smaller part is called the minor segment, while the remaining larger part is called the major segment.

The area of the complete circle is given by:

A(circle) = πr²

Since the minor and major segments together form the entire circle, the area of the major segment can be obtained by subtracting the minor segment from the total circular area.

Therefore:

A(major) = πr² − A(minor)

Substituting the derived formula gives:

**A(major) = πr² − [r² cos⁻¹(d/r) − d√(r² − d²)]**

Thus, the areas of both segments can be determined using the same mathematical approach.

---

# Page 23. Example 1: Given Information

Consider a circle whose equation is:

x² + y² = 25

An oblique line intersects this circle and is represented by:

y = x + 2

We need to calculate the area of the minor circular segment formed by the circle and the straight line. Comparing the circle equation with x² + y² = r², we obtain the radius as:

r² = 25

Therefore:

r = 5

The equation of the line gives its slope m = 1 and y-intercept c = 2. We will first calculate the perpendicular distance from the centre of the circle to the given line.

---

# Page 24. Example 1: Calculation

The perpendicular distance from the origin to the line y = x + 2 is:

d = |c|/√(1 + m²)

Substituting m = 1 and c = 2:

d = 2/√(1 + 1)

**d = √2**

Using the formula for the minor segment:

A = r² cos⁻¹(d/r) − d√(r² − d²)

Substituting r = 5 and d = √2:

A = 25 cos⁻¹(√2/5) − √2√(25 − 2)

A = 25 cos⁻¹(√2/5) − √46

Therefore:

**A ≈ 25.32 square units**

Hence, the area of the minor circular segment is approximately 25.32 square units.

---

# Page 25. Example 2: Given Information

Consider another circle represented by the equation:

x² + y² = 100

An oblique line intersects the circle and is given by:

y = 2x + 6

The objective is to calculate the area of the minor segment enclosed by these two curves. Comparing the circle equation with its standard form, we obtain:

r² = 100

Therefore:

r = 10

From the equation of the straight line, its slope is m = 2 and its y-intercept is c = 6. Using these values, we can determine the perpendicular distance from the centre to the given line.

---

# Page 26. Example 2: Calculation

The perpendicular distance is calculated using:

d = |c|/√(1 + m²)

Substituting m = 2 and c = 6:

d = 6/√(1 + 4)

**d = 6/√5**

Using the formula for the minor circular segment:

A = r² cos⁻¹(d/r) − d√(r² − d²)

Substituting the values:

A = 100 cos⁻¹(3/(5√5)) − (6/√5)√(100 − 36/5)

Simplifying:

A = 100 cos⁻¹(3/(5√5)) − 24√29/5

Therefore:

**A ≈ 104.07 square units**

Hence, the minor segment has an area of approximately 104.07 square units.

---

# Page 27. Graph of Example 1

The graphical representation of the first solved example helps us understand the position of the circle and the oblique line on the coordinate plane. The circle is represented by x² + y² = 25, while the straight line is represented by y = x + 2.

The centre of the circle is O(0,0) and its radius is 5 units. The straight line intersects the circle at two distinct points, forming a chord. The perpendicular distance between the centre and the line is √2 units.

The smaller region enclosed by the chord and the corresponding circular arc represents the minor segment. Its calculated area is approximately 25.32 square units, as obtained in the first solved example.

**GRAPH — FULL PAGE:**

Draw the graph of:

x² + y² = 25

y = x + 2

Label:
- Centre O(0,0)
- Radius r = 5
- Oblique line y = x + 2
- Two intersection points
- Chord
- Perpendicular distance d = √2
- Shaded minor segment

---

# Page 28. Applications

The calculation of areas bounded by curves and straight lines has several applications in mathematics and other fields. Definite integration provides an accurate method of finding areas that cannot always be calculated using ordinary geometrical formulas.

In engineering and architecture, such calculations are useful when studying curved structures, circular designs and enclosed regions. They help in estimating the areas of different sections and understanding their geometrical properties.

This concept is also important in the study of calculus because it combines coordinate geometry, algebra, trigonometry and integration. It demonstrates how different mathematical concepts can work together to solve practical and theoretical problems.

---

# Page 29. Conclusion

Through this project, the concept of finding the area bounded by a circle and an oblique line has been studied in detail. The equations of circles and straight lines were used to understand their intersection and the formation of circular segments.

The perpendicular distance from the centre to the oblique line was used to simplify the geometrical problem. By applying definite integration, the formula for calculating the area of the minor circular segment was successfully derived. The area of the major segment was also obtained using the total area of the circle.

The solved examples and graphical representations helped demonstrate the practical use of the derived formula. Overall, this project shows how calculus can be applied to geometrical problems and highlights the importance of definite integration in mathematics.

---

# Page 30. Bibliography

1. ISC Mathematics Textbook for Class XII.
2. NCERT Mathematics, Class XII, Part II, Chapter: Applications of Integrals.
3. CISCE Official Mathematics Syllabus for Class XII.
4. Class notes and reference material provided by the Mathematics teacher.
5. Reference material on coordinate geometry, circles and definite integration.
