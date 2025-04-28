# TOP HEADING

You should consider 3 different architecture options in here.

You **don't** need UML in here.

You should also justify your thinking.

Hot tip: use our text book for guidance.

## Component
Component architecture is a single-responsibility design approach that structures software into self-contained components that each handle one distinct part of the program behaviour. Each component is designed to be modular and reusable, encapsulating a specific piece of functionality that interacts with other components through well-defined, optional interfaces.

Within game development, component architecture is used to separate tasks into single-responsibility components that can be swapped in and out of various game objects. For example, a Movement component exclusively handles movement logic, while a Weapon component deals strictly with weapons. These components are loosely related but not dependent on each other, meaning if one component tries to call another that isn’t present, the game should still function correctly.

This design approach has several benefits, including:

- Each class/component is focused and easy to understand.
- Components are easy to modify, extend, or replace.
- Well-designed components can be reused across different projects.
- Problems are easier to isolate and fix because functionality is compartmentalised.
- 
However, there are disadvantages:

- You may end up managing many small scripts, which can become overwhelming.
- More components can sometimes mean more processing at runtime.
- Not all tasks break down cleanly into components—forcing it can lead to code duplication or convoluted logic.


## Inheritance
parent classes
## Interfaces
