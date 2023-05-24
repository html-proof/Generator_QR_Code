import qrcode

import os

image_path =r"C:\Users\DELL\PycharmProjects\pythonProject2\images" //path of images to be save
os.mkdir(image_path)
word =input("input the website :")
img =qrcode.make(word)
img.save(os.path.join(image_path,f"{word}.png"))
print("done")
