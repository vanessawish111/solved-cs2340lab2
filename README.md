Download Link: https://assignmentchef.com/product/solved-cs2340lab2
<br>
5/5 - (3 votes)

a <a href="http://vb.net/" target="_blank" rel="nofollow noopener">VB.NET</a> program, named CS2340Lab2



The program has one form with 6 textboxes, 7 labels and 3 buttons.

The Form

1.  The title is “Lab2” followed by your name.

2.  The size of the form is (500, 450), the FormBorderStyle is FixedSingle and has no ControlBox.

3.  The WindowState is Normal and the StartPosition is CenterScreen.

The Top Label

4.  The AutoSize property is True.

5.  The text of the label is “PayRoll Program.” The font size is 14, font name is Times New

Roman, and font style is underlined.

6.  It is above other controls and horizontally centered.

The Six Pairs of Textboxes and Labels

7.  Below the top label, there are three textboxes on the left and three textboxes on the right.

All textboxes have the default size, and there a label above each textbox.

8.  The three textboxes on the left are displayed top-down, aligned on the left with the same distance between them. The same applies to the three textboxes on the right, and each one on the right is aligned on the top with one textbox on the left.

9.  Each label is aligned on the left with the textbox below it. The texts of the labels are

“ID,” “Hours,” “Rate,” “Gross Pay,” “Deduction,” and “Net Pay.”

10. All the labels have the default font with the TextAlign being MiddleLeft .

11. The entire group of controls are centered both horizontally and vertically.

12. The three textboxes on the left are used to get input values.

a.  TextAlign is Left.

b.  ID must have at least one non-space character. c.  Hours must be non-negative number.

d.  Rate must be a positive number.

13. The three textboxes on the right are used to display output values.

a.  TextAlign is Right.

b.  All values must be in Currency format. c.  All are ReadOnly.

d.  BackColor is Window, same as those input textboxes.

The Buttons14. The texts of the buttons are “COMPUTE,” “RESET,” and “EXIT.” The underlinedcharacters are the access keys.

15. The three buttons are horizontally centered with the same distance between them.16. Button COMPUTE is the AcceptButton and button EXIT is the CancelButton of the form.

The Click Events of the buttons

17. The program will check the input values when button COMPUTE is clicked.

The values will be checked top-down, and when one invalid value is found, the following will not be checked.A message box will be displayed when one input value is found invalid, and the focus will go to the corresponding textbox.For an empty ID, the message is

Enter the ID please!For an invalid hours, the message must be on two lines as follows:

Invalid Hours!

Hours must be non-negative!

For an invalid rate, the message must be on two lines as follows:

Invalid Rate!

Rate must be positive!

18. If all input values are valid, the program will compute the Gross Pay, Deduction, and Net Pay.

19. The Gross Pay is the product of Hours and Rate. But any hours above 40 are overtime hours and are paid one time and half of the regular Rate.

20. The Deduction is 33% of the Gross Pay, and the Net Pay is the difference of the Gross Pay and the Deduction.

21. Remember that all output values must be displayed in the currency format.

22. The program will clear all textboxes and move the focus to the texbox for ID when button RESET is clicked.

23. The program will terminate when button EXIT is clicked. Tab Order

24. Textbox ID will have the focus when the program starts.

25. When the Tab key is pressed, the focus will go to textbox Hours, Rate, button

COMPUTE, RESET, EXIT , and then back to textbox ID.

26. The output textboxes on the right will not receive focus when the Tab key is pressed. (TabStop  False)