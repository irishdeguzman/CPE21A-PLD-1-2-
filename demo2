#add widgets to create UI application program

from tkinter import *
window = Tk()
window.geometry("400x300+10+20")

window.title("My first Python GUI")
#add label widget

lbl = Label(window, text="My First UI Phyton Program", fg = "red",font =("Verdana, 10"))
lbl.place(x=100,y=70)
#add button widget

btn = Button(window,text = "Submit", bg = "Blue" )
btn.place(x=80, y=115)

#add text field

txtfld = Entry(window,text="This is an entry widget", bd= 5)
txtfld.place(x= 70, y= 90)
def sel():
    selection = "You selected the option" + str(var.get())
    label.config(text = selection)
var = IntVar()
r1 = Radiobutton(window,text="Male", variable= var, value= 1, command= sel)
r1.pack(anchor=W)

r2 = Radiobutton(window,text="Female", variable= var, value= 2, command= sel)
r2.pack(anchor=W)

label = Label(window)
label.pack()
window.mainloop()

