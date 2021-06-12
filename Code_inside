from tkinter import *

root = Tk()
root.title("+-*/")
root.configure(background="powder blue")

x = Entry(root, width=50, borderwidth=24, bg="white", fg="black")
x.grid(row=0, column=0, columnspan=5, padx=10, pady=30)
x.insert(0,"Click to start calculate!")

def CLICK(num):
    x.delete(0, END)
    f = x.get()
    x.delete(0, END)
    x.insert(0, str(f) + str(num))
    
def CLEAR():
    x.delete(0,END)

def ADD():
    global f_number, cal
    f_number = int(x.get())
    cal = "add"
    x.delete(0,END)
def SUB():
    global f_number, cal
    f_number = int(x.get())
    cal = "sub"
    x.delete(0,END)    
def DIV():
    global f_number, cal
    f_number = int(x.get())
    cal = "div"
    x.delete(0,END)    
def MUL():
    global f_number, cal
    f_number = int(x.get())
    cal = "mul"
    x.delete(0,END)

def EQU():
    sec_num = int(x.get())
    x.delete(0,END)
    if cal == "add":
        x.insert(0, f_number + sec_num)
    if cal == "sub":
        x.insert(0, f_number - sec_num)
    if cal == "mul":
        x.insert(0, f_number * sec_num)
    if cal == "div":
        x.insert(0, f_number / sec_num)

But1 = Button(root, text="1", padx=50, pady=17, command=lambda: CLICK(1), fg="black", bg="#1EDC00")
But2 = Button(root, text="2", padx=50, pady=17, command=lambda: CLICK(2), fg="black", bg="#1EDC00")
But3 = Button(root, text="3", padx=51, pady=17, command=lambda: CLICK(3), fg="black", bg="#1EDC00")
But4 = Button(root, text="4", padx=50, pady=17, command=lambda: CLICK(4), fg="black", bg="#1EDC00")
But5 = Button(root, text="5", padx=50, pady=17, command=lambda: CLICK(5), fg="black", bg="#1EDC00")
But6 = Button(root, text="6", padx=51, pady=17, command=lambda: CLICK(6), fg="black", bg="#1EDC00")
But7 = Button(root, text="7", padx=50, pady=17, command=lambda: CLICK(7), fg="black", bg="#1EDC00")
But8 = Button(root, text="8", padx=50, pady=17, command=lambda: CLICK(8), fg="black", bg="#1EDC00")
But9 = Button(root, text="9", padx=51, pady=17, command=lambda: CLICK(9), fg="black", bg="#1EDC00")
But0 = Button(root, text="0", padx=50, pady=17, command=lambda: CLICK(0), fg="black", bg="#1EDC00")

But_add = Button(root, text="+", padx=49, pady=17, command=ADD, fg="white", bg="blue")
But_sub = Button(root, text="-", padx=51, pady=17, command=SUB, fg="white", bg="blue")
But_mul = Button(root, text="*", padx=51, pady=17, command=MUL, fg="white", bg="blue")
But_div = Button(root, text="/", padx=51, pady=17, command=DIV, fg="white", bg="blue")
But_equal = Button(root, text="=", padx=110, pady=17, command=EQU, fg="white", bg="green")
But_claer = Button(root, text="CLEAR", padx=97, pady=17, command=CLEAR, fg="white", bg="#FF3C28")

But1.grid(row=3, column=1, pady=2)
But2.grid(row=3, column=2, pady=2)
But3.grid(row=3, column=3, pady=2)
But4.grid(row=2, column=1, pady=2)
But5.grid(row=2, column=2, pady=2)
But6.grid(row=2, column=3, pady=2)
But7.grid(row=1, column=1, pady=2)
But8.grid(row=1, column=2, pady=2)
But9.grid(row=1, column=3, pady=2)
But0.grid(row=4, column=1, pady=2)

But_add.grid(row=5, column=1, pady=2)
But_sub.grid(row=6, column=1, pady=2)
But_mul.grid(row=6, column=2, pady=2)
But_div.grid(row=6, column=3, pady=2)
But_equal.grid(row=5, column=2, columnspan=2)
But_claer.grid(row=4, column=2, columnspan=2)

root.mainloop()
