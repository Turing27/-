# -import turtle as t
t.setup(800,800,20,20)
t.pu()
t.goto(-200,-200)
t.pd()#准备画底盘

t.pencolor('black')
t.pensize(10)
t.seth(180)
t.circle(12,170)
t.circle(2000,15)
t.circle(14,170)#底盘完成

t.up()
t.goto(300,-230)
t.pd()#准备画底层蛋糕

t.pencolor('lightcoral')
t.pensize(10)
t.seth(90)
t.fd(200)

t.circle(12,90)
t.fd(450)
t.circle(12,90)
t.fd(200)#底层蛋糕完成

t.pu()
t.goto(-170,-80)
t.pd()#准备画底层蛋糕的果酱

t.pencolor('darkorange')
t.seth(-70)
for i in range (3):
    t.circle(42,140)
    t.circle(-42,140)#底层蛋糕果酱完成

t.pu()
t.goto(240,-15)
t.pd()#准备画上层蛋糕

t.pencolor('purple')
t.seth(90)
t.fd(150)

t.circle(8,90)
t.fd(310)
t.circle(8,90)
t.fd(150)#上层蛋糕完成

t.pu()
t.goto(-80,100)
t.pd()#准备画上层果酱

t.pencolor('yellowgreen')
t.seth(-70)
for i in range(3):
    t.circle(29,140)
    t.circle(-29,140)#上层蛋糕果酱完成

t.pu()
t.goto(90,140)
t.pd()#准备画蜡烛

t.pencolor('black')
t.pensize(18)
t.seth(90)
t.fd(80)#蜡烛柄完成

t.pu()
t.goto(83,245)
t.pd()#准备画火焰

t.pensize(7)
t.seth(230)
t.pencolor('red')
t.circle(10,210)

t.seth(120)
t.fd(22)

t.seth(240)
t.fd(22)#火焰完成

t.pu()
t.goto(0,280)
t.pd()#准备画火光

t.pensize(8)
t.pencolor('yellow')
t.seth(130)
t.fd(100)

t.pu()
t.goto(90,280)
t.pd()

t.seth(90)
t.fd(100)

t.pu()
t.goto(190,280)
t.pd()

t.seth(50)
t.fd(100)#火光完成

t.pu()
t.goto(-350,350)
t.pd()#准备写字

t.pensize(3)
t.pencolor('black')
t.seth(270)
t.fd(60)

t.fd(-30)
t.seth(0)
t.fd(30)

t.pu()
t.goto(-320,350)
t.pd()

t.seth(270)
t.fd(60)#字母H完成

t.pu()
t.goto(-280,320)
t.pd()

t.seth(140)
t.circle(14,270)

t.pu()
t.goto(-280,328)
t.pd()

t.seth(270)
t.fd(35)#字母A完成

t.pu()
t.goto(-270,328)
t.pd()

t.seth(270)
t.fd(60)

t.fd(-54)
t.seth(40)
t.circle(-14,270)#第一个P完成

t.pu()
t.goto(-240,328)
t.pd()

t.seth(270)
t.fd(60)

t.fd(-54)
t.seth(40)
t.circle(-14,270)#第二个P完成

t.pu()
t.goto(-210,328)
t.pd()

t.seth(-58)
t.fd(35)

t.pu()
t.goto(-173,328)
t.pd()

t.seth(-115)
t.fd(75)#字母Y完成

t.pu()
t.goto(-350,270)
t.pd()

t.seth(270)
t.fd(60)

t.fd(-55)
t.seth(0)
t.fd(8)
t.circle(-13,180)
t.fd(8)
t.seth(0)
t.fd(12)
t.circle(-13,180)
t.fd(12)#字母B完成

t.pu()
t.goto(-310,255)
t.pd()

t.pensize(8)
t.seth(270)
t.fd(1)

t.pu()
t.goto(-310,245)
t.pd()

t.seth(270)
t.pensize(3)
t.fd(30)#字母I完成

t.pu()
t.goto(-290,245)
t.pd()

t.seth(270)
t.fd(30)
t.fd(-25)
t.seth(50)
t.circle(-14,80)#字母R完成

t.pu()
t.goto(-258,245)
t.pd()

t.seth(0)
t.fd(20)

t.pu()
t.goto(-246,270)
t.pd()

t.seth(270)
t.fd(60)#字母T完成

t.pu()
t.goto(-228,270)
t.pd()

t.seth(270)
t.fd(60)

t.fd(-27)
t.seth(50)
t.circle(-18,80)
t.seth(270)
t.fd(30)#字母H完成

t.pu()
t.goto(-170,270)
t.pd()

t.seth(270)
t.fd(60)

t.fd(-27)
t.seth(110)
t.circle(14,290)#字母D完成

t.pu()
t.goto(-140,243)
t.pd()

t.seth(140)
t.circle(15,270)

t.pu()
t.goto(-140,241)
t.pd()

t.seth(270)
t.fd(35)#字母A完成

t.pu()
t.goto(-130,245)
t.pd()

t.seth(-58)
t.fd(35)

t.pu()
t.goto(-96,245)
t.pd()

t.seth(-115)
t.fd(75)#字母Y完成

t.pu()
t.goto(-325,190)
t.pd()

t.seth(135)
t.circle(22,290)

t.pu()
t.goto(-310,157)
t.pd()

t.pensize(8)
t.seth(0)
t.fd(1)#第一个C完成

t.pu()
t.goto(-260,190)
t.pd()

t.pensize(3)
t.seth(135)
t.circle(22,290)

t.pu()
t.goto(-250,157)
t.pd()

t.pensize(8)
t.seth(0)
t.fd(1)#第二个C完成

t.done()






















