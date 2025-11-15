## 🔍 What Is Cosine in Trigonometry?

We all know what cosine is in trigonometry. If you don't remember, here's a quick refresher:

**Cosine = Adjacent / Hypotenuse**

---

## 🌊 What Is the Cosine Transform?

We represent frequency in the form of a wave — it oscillates from 0 to 1, back to -1, and repeats.

But in terms of the cosine transform, the wave oscillates from 1 to -1 and is **symmetric around the y-axis**.

---

## 🧠 Why Is Symmetry Around the Y-Axis Helpful?

- It **smoothes out the signal at the edges**.
- JPEG images are represented as pixels. If we consider boundaries/edges, that would be:
  - Top-left
  - Top-right
  - Bottom-left
  - Bottom-right
- Once we use the cosine transform, these images appear smoother and don’t show spikes in brightness.
- This is also why we don’t use sine waves — they’re not symmetric.

---

## ➕ Cosine Transform = Sum of Cosine Waves

The cosine transform represents a signal as the **sum of cosine waves** with different frequencies and amplitudes.

---

## ⏱️ Time Domain vs 📊 Frequency Domain

- **Time domain** shows the signal as a wave.
- **Frequency domain** shows it as **bars or spikes**.

In the time domain, you see how loud the sound is at each moment.  
In the frequency domain, you see which notes are present and how strong they are.

---

## ❓ Why Do We Need the Cosine Transform?

- Signals often contain **noise**, especially in higher frequencies.
- **Noise is mostly present in high frequencies**.
- We **retain low frequencies** and **reduce high frequencies**.
- High frequencies store fine details that are often **not visible to the human eye** and can be removed.

---

## 🧩 What Problem Does This Solve?

- We don’t store all the information — we **compress the signal**.
- This leads to **smaller file sizes** with minimal quality loss.

---

## 📦 Real-World Applications

- **JPEG compression**
- **MP3 compression**
- **Video compression**
- **Signal extraction from images/audio**
