# sms_system
it takes two parameter name and contact number and send the respected message to respected  person.
from tkinter import *
from tkinter.ttk import Combobox
Window=Tk()
v1=IntVar()
r1=Radiobutton(Window,text="male",variable=v1,value=1)
r2=Radiobutton(Window,text="Female",variable=v1,value=2)
r1.place(x=20,y=100)
r2.place(x=70,y=100)
var=StringVar()
var.set("One")
data=("One","Two","Three","Four")
cb=Combobox(Window,values=data,textvar=var)
cb.place(x=20,y=120)

ch1=IntVar()
ch2=IntVar()
ch=Checkbutton(Window,text="Cricket",variable=ch1)
ch11=Checkbutton(Window,text="Football",variable=ch2)
ch.place(x=20,y=80)
ch11.place(x=70,y=80)
lb=Label(Window,text="Enter your name")
lb.place(x=3,y=60)
entry1=Entry(Window,text="Enter name")
entry1.place(x=80,y=60)
Window.mainloop()
