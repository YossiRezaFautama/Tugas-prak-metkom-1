# buat isi laporan tugas, foto dkk
from PIL import Image
import matplotlib.pyplot as plt

# path file foto di laptop
img = Image.open("C:/Users/Yossi/Pictures/Screenshots/Screenshot 2025-09-19 100800.png")  # ganti dengan lokasi file

# tampilkan
plt.imshow(img)
plt.axis("off")
plt.show()