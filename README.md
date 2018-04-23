# Nested StackView Test
This project programmatically creates and displays 2 nested stackviews (stack1 inside stack2). Both stackViews expand correctly with varying content.
An extension to the UIView is added to help apply constraints to the stackViews in a more simple and intuitive way.

1. I created 2 views, bkView1 and bkView2, and constrain the stackViews to them to display a different background color for each stackView.
2. bkView1 has a background color of green. It contains the stackView, stack1, which contains: label1, label2, and label3. All the labels are vertically stacked.
3. bkView2 has a background color of yellow. It contains label4 and Rect1 (containing stack1, which contains: label1, label2, and label3) and is horizontally stacked.
4. An extension on UIView was created with 2 functions: anchorSize() and anchor().
5. AnchorSize() constrains the view to a height and width.
6. Anchor() constrains the stackViews to the main views and adds optional padding to top, left, right bottom.

