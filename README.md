# Software_Engineering-Apache_Whisker-Daniel_Legacinski-Dmytro_Nesvitailo
# ⚖️ Apache Whisker Legal Demo V2 — Localhost Click-Fix

A simple **localhost web demo** that shows how license compliance documentation can be generated and reviewed for a small software distribution.

The project demonstrates the idea of using structured license metadata, similar to **Apache Whisker**, to create legal documentation such as:

- `LICENSE`
- `NOTICE`
- generation log
- license matrix
- project analysis

This version is prepared as a stable **V2 localhost edition**, where every button works through normal page links, so the interface is easier to use and more reliable during presentation.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Main Goal](#-main-goal)
- [What Is Apache Whisker?](#-what-is-apache-whisker)
- [Main Features](#-main-features)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [How to Use the Application](#-how-to-use-the-application)
- [Generated Files](#-generated-files)
- [License Matrix](#-license-matrix)
- [Risk Example](#-risk-example)
- [How the Server Works](#-how-the-server-works)
- [Educational Value](#-educational-value)
- [Known Limitations](#-known-limitations)
- [Author](#-author)

---

## 🚀 Project Overview

**Apache Whisker Legal Demo V2** is an educational project created to explain how license documentation can be generated for a software project.

The project contains a small demo application inside the `distribution` folder.  
This demo application includes:

- own project files,
- third-party MIT component,
- third-party Apache-2.0 component,
- GPL-like risk example that is **not included** in the final distribution.

The system runs locally in the browser and allows the user to view project files, generate legal documentation and inspect license-related information.

---

## 🎯 Main Goal

The main goal of this project is to show how a software team can organize information about licenses and third-party components.

The project answers questions such as:

- What files are included in the application?
- Which files are created by the project author?
- Which files come from third-party sources?
- What licenses are used?
- What obligations are connected with these licenses?
- Which files should be included in the final distribution?
- Which files are only risk examples and should not be distributed?

---

## ⚖️ What Is Apache Whisker?

**Apache Whisker** is a tool from the Apache Creadur project.  
It helps developers manage license metadata and generate legal documentation for software distributions.

Apache Whisker does **not** choose a license automatically.  
It also does **not** replace legal advice.

Its purpose is to help structure information about:

- project licenses,
- third-party licenses,
- copyright notices,
- organizations,
- included resources,
- generated `LICENSE` and `NOTICE` files.

In this project, the V2 localhost version demonstrates the same idea in a simpler and more visual way.

---

## ✨ Main Features

### 🌐 Localhost Web Interface

The project starts a local web server on:

```text
http://localhost:8080
