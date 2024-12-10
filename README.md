import numpy as np
import matplotlib.pyplot as plt

# Data for peaks
x = np.linspace(0, 10, 1000)
peak1 = np.exp(-((x - 3.2) ** 2) / (2 * 0.3 ** 2))  # Peak 1 centered at 3.2 with width ~0.6
peak2 = np.exp(-((x - 4.8) ** 2) / (2 * 0.25 ** 2))  # Peak 2 centered at 4.8 with width ~0.5

# Plotting the peaks
plt.figure(figsize=(10, 6))
plt.plot(x, peak1, label="Peak 1 (tR1=3.2, W1=0.6)", color="blue")
plt.plot(x, peak2, label="Peak 2 (tR2=4.8, W2=0.5)", color="red")
plt.axvline(3.2, color="blue", linestyle="--", alpha=0.5)
plt.axvline(4.8, color="red", linestyle="--", alpha=0.5)

# Annotations
plt.text(3.2, 0.8, "tR1 = 3.2", horizontalalignment='center', color="blue")
plt.text(4.8, 0.8, "tR2 = 4.8", horizontalalignment='center', color="red")

# Labels and legend
plt.title("Chromatographic Peaks and Resolution")
plt.xlabel("Time (min)")
plt.ylabel("Intensity (arbitrary units)")

plt.legend()
plt.grid(alpha=0.3)
plt.show()- 👋 Hi, I’m @m7mdtamer
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
m7mdtamer/m7mdtamer is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
