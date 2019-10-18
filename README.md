# placefig-matlab-script
Sick of resizing all of your figures in MATLAB when you run your scripts? Yeah, me too. 

Placefig() streamlines this hassle and saves you valuable to do what you do best, writing the stupid code. 
Simply 1) create a sample figure, 2) position it in the size and location you want to output on your screen, 3) run placefig() in the terminal window. Placefig() will output a 'set(gcf) command into the terminal window that you can then 4) copy and 5) paste into your script so that everytime you run your script, your figure pops up sized and ready to go right where you want it. (Generally, pasting the command right after where you create your figure is where I find this works best in my personal workflow.)

Alternatively, if you have a figure saved as a variable on your workspace, you can call that variable into placefig(var) and it will output the set(gcf) commmand to place in your script where you need it. 

Have fun with it, and modify to your hearts desire. Happy MATLABing. 
