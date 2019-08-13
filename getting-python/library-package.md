---
layout: default
---

# ไลบรารี่และแพคเกจ

---

<br>

### **แนะนำไลบรารี่**

ไลบรารี่ (library) เปรียบเสมือนโปรแกรมสำเร็จรูปที่เก็บฟังก์ชันการทำงานที่เฉพาะทาง ประโยชน์ของไลบรารี่สำเร็จรูปที่มากับโปรแกรมก็คือผู้ใช้งานไม่จำเป็นที่จะต้องสร้างไลบรารี่ขึ้นมาใหม่เองทั้งหมด แต่สามารถนำไลบรารี่ที่ได้มีการพัฒนาไว้อยู่แล้วมาใช้งานได้เลย เช่น ฟังก์ชัน print และ for

ไลบรารี่ส่วนใหญ่ของไพธอนทั้งที่ถูกพัฒนาโดยผู้พัฒนาหลักและผู้ใช้งานทั่วไปจะถูกสร้างและอัพโหลดขึ้นไปเก็บไว้ในเซอร์เวอร์ของ [Python Package Index (PyPI)][pypi-server] หรือไม่ก็เซอร์เวอร์ของ [Anaconda Cloud][ana-cloud]

- ไลบรารี่ที่ไม่ได้ถูกติดตั้งมากับตัวไพธอนสามารถติดตั้งได้เองโดยใช้คำสั่งต่อไปนี้
  - `pip` สำหรับคนที่ใช้ไพธอนของ Python.org 
  - `conda` สำหรับคนที่ใช้ไพธอนของ Anaconda

[pypi-server]: https://pypi.org/
[ana-cloud]: https://anaconda.org/anaconda-server

ตัวอย่างการติดตั้ง

ถ้าใช้ pip ให้ใช้คำสั่งต่อไปนี้

```sh
pip install ชื่อของไลบรารี่
```

หรือถ้าใช้ conda ก็ใช้คำสั่งต่อไปนี้

```sh
conda install ชื่อของไลบรารี่
```

<br>

---

<br>

**ด้านล่างคือไลบรารี่ยอดนิยมที่ผู้เขียนไพธอนทั่วไปใช้แยกไปตามประเภทของการใช้งาน**

### **การจัดการข้อมูล (Data Manipulation)**

- [Pandas](https://pandas.pydata.org/)

### **คณิตศาสตร์และสถิติ (Mathematics and Statistics)**

- [NumPy](https://numpy.org/) 
- [SciPy](https://www.scipy.org/) 
- [Statsmodels](https://www.statsmodels.org/stable/index.html)
- [SymPy](https://www.sympy.org/)

### **การสร้างโมเดลแบบการเรียนรู้ของเครื่องจักร (Machine Learning)** 

- [Scikit-Learn ](https://scikit-learn.org/)
- [TensorFlow](https://www.tensorflow.org/) 
- [Keras](https://keras.io/) 
- [PyTorch](https://pytorch.org/)

### **การประมวลผลภาษาทางธรรมชาติ (Natural Language Processing)**

- [NLTK](https://www.nltk.org/) 
- [Gensim](https://radimrehurek.com/gensim/) 
- [PyThaiNLP](https://pythainlp.github.io/)

### **การแสดงผลข้อมูล (Data Visualization)**

- [Matplotlib](https://matplotlib.org/) 
- [Seaborn](https://seaborn.pydata.org/) 
- [ggplot](http://ggplot.yhathq.com/)
- [Bokeh](https://bokeh.pydata.org/en/latest/)
