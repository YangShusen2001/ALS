### 相机曲线 
1. CameraOffset     
    对 PivotLocation 进行偏移，得到最终的相机的位置参数 CameraTargetLocation。 
2. PivotLagSpeed    
    Controller 的输入相机不会马上反应，而是会有一个滞后状态，这个滞后速度可以理解成这个东东，不太会表达。  
3. PivotOffset      
    PivotOffset_Z 的用法是用来处理站立和蹲姿时相机的高度。
