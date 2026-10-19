# Códigos para Práctico — Prof. Amina Helmi (LAPIS 2026)

Repositorio de materiales y códigos para el práctico de la Profesora Amina Helmi (*Placing the Milky Way in its Cosmological Context*) en la escuela de astrofísica **XII LAPIS 2026**.

## Instrucciones del Práctico y Descripción Completa

- **Documento del proyecto (en el repositorio)**: [`Lapis2026.pdf`](./Lapis2026.pdf)
- **Diapositivas del proyecto (en el repositorio)**: [`project-slides.pdf`](./project-slides.pdf)
- **Descripción completa del proyecto (Google Drive)**: [Ver documento de instrucciones](https://drive.google.com/file/d/1VS7VQuLhsBE84s6EhljcN_0PydGDXkS0/view?usp=sharing)
- **Proyecto**: *Identification and characterization of merger debris through clustering using Gaia data*.

## Datos y Catálogos

- Los datos se descargarán desde el **Gaia Archive** o **Gaia DataLab**.
- **Importante**: Por favor crea una cuenta con anticipación antes del inicio de la escuela para poder acceder a los datos durante el práctico.

## Software y Estructura

- `IOM_clustering/` — Submódulo con el fork de [SofieLovdal/IOM_clustering](https://github.com/SofieLovdal/IOM_clustering) en [`LAPIS-2026/IOM_clustering`](https://github.com/LAPIS-2026/IOM_clustering).

## Lecturas Previas Sugeridas

- [Wempe et al. (2025)](https://ui.adsabs.harvard.edu/abs/2025A%26A...701A.178W/abstract)
- [Dodd et al. (2023)](https://ui.adsabs.harvard.edu/abs/2023A%26A...670L...2D/abstract)

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/aminahelmi.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
