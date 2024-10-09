import tkinter as tk
from time import strftime

# Create the root window
root = tk.Tk()
root.title("Digital Clock")

# Define the function to update time
def time():
    string = strftime('%H:%M:%S %p')  # Format the time
    label.config(text=string)  # Update the label with the time string
    label.after(1000, time)  # Call the time function every 1 second (1000 ms)

# Customize the label for displaying the time
label = tk.Label(root, font=('calibri', 40, 'bold'), background='black', foreground='cyan')
label.pack(anchor='center')

# Start the clock
time()

# Keep the window running
root.mainloop()
