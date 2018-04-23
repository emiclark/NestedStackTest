# StackViewTest
This project programmatically creates and displays 2 nested stackviews (stack1 inside stack2). Both stackViews expand correctly with varying content.
An extension to the UIView is added to help apply constraints to the stackViews in a more simple and intuitive way.

1. I created 2 views and constrain the stackViews to them to display a different background color for each stackView.
2. Rect1 has a background color of green. It contains the stackView, stack1, which contains: label1, label2, and label3 which are vertically stacked.
3. Rect2 has a background color of yellow. It contains label4 and Rect1 (containing stack1, which contains: label1, label2, and label3) and is horizontally stacked.
4. An extension on UIView was created with 2 functions: anchorSize() and anchor().
5. AnchorSize() constrains the view to a height and width.
6. Anchor() constrains the stackViews to the main views and adds optional padding to top, left, right bottom.

