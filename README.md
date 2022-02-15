# Finding-force-on-charge-2-due-to-charge-1.
This a code I did in my second semester in college, where I completed my physics assignment without calculating stuff for every single problems.
this is a code i wrote with python in jupytor notebook.
you have to manually edit the e, q1, q2, r1, r2, scale.
As the name implies its a code to help you find the force on a charge due to another charge.
q1 is the first charge,and q2 is the second one. we are calculating force on q1 due to q2. r1 and r2 are the vector positions of the 2 charges respectively.
e is the scale of the charge. typically problems come in micro coulomb format. so you can just put '1e-6' or '0.000001' as the value of e and proceed do give the raw value on q1 and q2. for example if q1 is 10 micro coulomb you can simply change the value of e to 1e-6 and dirctly input q1 as 10*e.
similarly, scale is the input of the scale of the vector units. if the vector you input is in micro units, simply change the value of scale to 1e-6 so that the code can convert your vector vaues to meter automatically.
run the code
you will get a vector output of r12 in the form of a list which is x, y, z respectivly and the x, y and z component of the forces. 
you can modify the code in your own way. 
let me know if there are any mistakes or any improvement i can make.
thanks.
