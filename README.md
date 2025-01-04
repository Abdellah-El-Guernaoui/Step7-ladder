# Step7-ladder
First to simulate the program many softwares are essential : S7-PLCSIM & Factory IO

I worked on programming a PLC for a box sorting mechanism using ladder logic in Step 7, simulated in Factory I/O. The system sorts boxes based on three criteria: color, depth, and width.
First, I created a machine with vision sensors to sort objects/boxes by color, pushing each object to its designated path. Next, I programmed a second machine with two sensors to measure box height -if the height meets the criteria, the box is passed along, if not the box is pushed to the next machine. Finally, the third machine checks width, pushing boxes that exceed the limit to their respective location. 
The result is a fully automated sorting process that organizes boxes precisely to their intended destinations.
