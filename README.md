AUTHOR
===
Hongik University student team_1 final project about opensource by B589018 박기정, B589003 권한준

Why we select this project
-------
These days computer techniques is improve really fast and some people tend to overlook about security.
So, we tried to solve this problem by add some functions at lsh shell
We thought about how if who is qualified to access program so that we can prevent from unauthorized users,
then we can protect our source code or data that undergoing in secret.
we can protect data from leak out somewhere.


Options
------------
<ul>
  <li>lsh shell can't be running by 2 processes</li>
  <li>only who have right to access can use shell</li>
  <li>to use shell you have to login</li>
</ul>

method of functions
-------
-> you can set id, pw as you want. and you can give right to user by add ip in list file<br>
![로그인성공](https://user-images.githubusercontent.com/52829400/101628779-a9ceae80-3a63-11eb-98e1-d75281a496eb.gif)<br>

-> only one person can use lsh. if you wanna do approve lsh running by 2 process then edit code <br>
![lsh2개 실행 시 fail](https://user-images.githubusercontent.com/52829400/101629053-16e24400-3a64-11eb-9841-14232e83b1f0.gif)<br>

-> public ip that isn't in list file will be blocked when trying to access<br>
![다른 공인ip로 접속시 차단](https://user-images.githubusercontent.com/52829400/101629082-1f3a7f00-3a64-11eb-8e60-756d4f5bf2bd.gif)

































