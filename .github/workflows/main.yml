import numpy as np
import matplotlib.pyplot as plt

# Tạo hàm vẽ hình trái tim
def draw_heart():
    t = np.linspace(0, 2 * np.pi, 1000)
    x = 16 * np.sin(t)**3
    y = 13 * np.cos(t) - 5 * np.cos(2*t) - 2 * np.cos(3*t) - np.cos(4*t)

    plt.figure(figsize=(6, 6))
    plt.plot(x, y, color='red')
    plt.fill(x, y, color='red', alpha=0.5)
    plt.axis('off')  # Tắt các trục
    plt.title("Hình Trái Tim")
    plt.show()

# Vẽ hình trái tim
draw_heart()
