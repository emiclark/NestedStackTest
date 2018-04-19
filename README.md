# StackViewTest
This project programmatically creates 2 nested stackviews and displays 2 nested stacks (stackView1 inside stack2) with both stacks expanding correctly with varying content.
An extension to the UIView is added to help apply constraints to the stackViews in a more simple and intuitive way.

1. Initially 2 views, 4 labels, and 2 stack views are created.
2. label1, label2, and label3 of varying lengths are added to rect1
3. rec1 is added to stackView1.
4. stack2 is created.
5. label4 is created and added to rect2.
6.rect1 and stackView1 are added to stack2.
7. rect2 is on the left and rect1 is on the right side filling stack2.
8. An extension on UIView was created with 2 functions: anchorSize() and anchor().
9. AnchorSize() constrains the view to a height and width.
10. Anchor() constrains the stackViews to the main views and adds optional padding to top, left, right bottom.

