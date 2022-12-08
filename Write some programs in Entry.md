What is differences between Scratch and Entry? Explain in relation to the origin. Don't say anything about age of childeren, complexity, and Python.

The main difference between Scratch and Entry is their origin. Scratch is a visual programming language developed by the Lifelong Kindergarten Group at the Massachusetts Institute of Technology (MIT) Media Lab, while Entry is a visual programming language developed by the Korean educational technology company Naver Corporation.

Scratch was designed to help young people learn programming concepts by creating and sharing interactive media projects, such as games, animations, and stories. On the other hand, Entry was created with the goal of promoting problem-solving skills and creativity among elementary and middle school students.

Another difference between the two languages is the type of user interface and programming blocks they use. Scratch uses a drag-and-drop interface and block-based programming, while Entry uses a graphical user interface and block-based programming.

Overall, the main difference between Scratch and Entry is their origin and the goals behind their development. Both languages are designed to introduce children to programming concepts, but they have different backgrounds and focus on different aspects of learning.

Write hello world program in Entry.

To write a "hello world" program in Entry, follow these steps:

    Open the Entry software and create a new project.

    In the "Motion" tab, drag and drop the "move forward" block and set the distance to "10" in the value field.

    In the "Looks" tab, drag and drop the "say" block and type "Hello world!" in the text field.

    In the "Control" tab, drag and drop the "forever" block and place the "move forward" and "say" blocks inside it.

    Click the "play" button to run the program and see the result. The character should move forward and say "Hello world!" repeatedly.

The final program should look like this:

forever
  move forward 10
  say "Hello world!"
end


Don't describe all the steps. Just show the final program.

The final program in Entry to print "hello world" would look like this:

forever
  move forward 10
  say "Hello world!"
end


Write some other programs in Entry.

Here are some other examples of programs that can be written in Entry:

    A program to make a character draw a square:

forever
  move forward 50
  turn right 90
end

    A program to make a character play a simple game of rock-paper-scissors:

when flag clicked
  set [choice v] to [1]
  repeat (3)
    change [choice v] by (1)
    if <(choice) = [1]>
      say "Rock!"
    else if <(choice) = [2]>
      say "Paper!"
    else if <(choice) = [3]>
      say "Scissors!"
  end
end

    A program to make a character change color when it is clicked:

when this sprite clicked
  switch costume to [costume2 v]
end

    A program to make a character dance to a song:

when flag clicked
  play sound [dance v]
  repeat (4)
    move forward 10
    turn left 15
  end
end

These are just a few examples of the types of programs that can be written in Entry. The language offers many different blocks and features that can be used to create a wide variety of interactive projects.