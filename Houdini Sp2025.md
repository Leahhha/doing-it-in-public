W09
Paul Parneix FX Demo: Destruction/ SC Joints / Fragment

Glue contraints:物体之间的连接

物体坍塌是提前设定好的:prefractured

Fume effect 冒气（或烟、汽）

voronoifracture: ☑️Create interior surfaces (for geometry that has a volume, 制作breakage of a wall, hard objects; it created interior chunks)

Boolean: 减少合并物体

Clip: cut into geometry

# 03-18-2025
HDA - Houdini Digital Assets
in a self contained network
Function: HDA is normally created for repeated operations you wish to perform.  
Allow user to input data from Maya/UE to Houdini engine and Houdini gives visual output

Houdini(HDA: fraction?controlled by slider) -> Unreal(real time simulation in the game scene) 

`Backtick: Means analyze this

# 04-01-2025
Constraints
RBD Constraint:
1. Pin constraint (One box pin to another, like a caterpillar)
2. String constraint

SOP: order matters
DOP: less order required

boundingbox: min and max reaching point

attributewrangle

anchor: used to be renamed, and be able to targeted easily

# Helpful Houdini Code List
if($F%6 == 0, $F, 0): Generate a new one every six frame

getbbox(("op:../PLANK), v@min, v@max);  // v = vector

addpoint(0, set(0, 0, @min[2]));  // @min[2] = 第三位

if(inpointgroup(0,"OUTSIDE", @ptnum) == 1) {
s@name=' ';
}








