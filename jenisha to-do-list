import tkinter as t

r=t.Tk()
e=t.Entry(r); e.pack()
l=t.Listbox(r); l.pack()

t.Button(r,text="Add",command=lambda:l.insert(t.END,e.get())).pack()
t.Button(r,text="Delete",command=lambda:l.delete(t.ACTIVE)).pack()

r.mainloop()
