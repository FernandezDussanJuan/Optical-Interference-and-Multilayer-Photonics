# Optical Interference and Multilayer Photonics Simulation

**Author:** Juan David Fernández Dussán  
**Degree:** Physics (3rd year)  
**Language:** Python

---

## 📖 Project Overview
This project develops a progressive numerical study of optical interference phenomena, starting from basic two-wave interference and culminating in the full **Transfer Matrix Method (TMM)** for arbitrary multilayer dielectric systems.

The objective is to connect analytical wave optics with computational modeling, validating each step through physical consistency checks.

---

## 📂 Project Structure
El repositorio está organizado de la siguiente manera:

* **[01_notebooks](./01_notebooks):** Contiene los desarrollos semanales.
* **[02_figures](./02_figures):** Gráficas generadas por las simulaciones.
* 📝 **[Resultados y Conclusiones](./Final%20Project%20Conclusion.md):** Haz clic aquí para ver el análisis final.

---

## 🔬 Key Physical Concepts Covered
- Monochromatic plane waves
- Phase accumulation
- Fresnel reflection and transmission
- Energy conservation ($R + T = 1$)
- Thin film interference
- Fabry-Pérot resonances
- Distributed Bragg reflectors
- Photonic stop bands
- Transfer Matrix formalism

---

## ⚖️ Numerical Validation
The implementation includes two independent physical validation steps:

1. **Energy conservation verification:** $$R + T = 1$$  
   Numerical deviation is on the order of $10^{-16}$ (machine precision).

2. **Analytical validation of Bragg mirror stop band width:** $$\Delta\lambda = \frac{4\lambda_0}{\pi}\arcsin\left(\frac{n_H - n_L}{n_H + n_L}\right)$$  
   The numerical and analytical results show strong agreement.

---

## 🛠️ Tools Used
- **Python** (NumPy, Matplotlib)
- **Jupyter Notebooks**

---

## 📚 Scientific References
- Hecht, E. - *Optics*
- Born & Wolf - *Principles of Optics*
- Classical thin-film optics formalism

---

## 📝 Conclusiones y Resultados Finales
El análisis detallado de los resultados físicos, la discusión sobre las resonancias de Fabry-Pérot y las conclusiones generales del proyecto se encuentran en el siguiente documento:

👉 **[Haga clic aquí para leer las Conclusiones Finales](./Final%20Project%20Conclusion.md)**