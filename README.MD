# Mini grep
This is a mini version of the grep CLI application which comes with many unix based systems. The program will take two arguments a file path and a string to look for inside the file and the program will return each line that mathces the second argument. 

This project is based on "The Rust Programming Language" book mini grep project but I added lifetimes on mine. Adding lifetimes will increase the efficiency of the program. Rather than cloning the strings into the `Config` struct attributes we're going to pass in the reference of the arguments. This will avoid all the exahustive process of cloning a string. We are improving memory as well as speed efficiency with this little change.
