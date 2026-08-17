# 🎹 SENSITIVE PIANO CHORD CONSTRUCTOR

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Tone.js](https://img.shields.io/badge/Tone.js-14.7.77-4A90D9.svg)](https://tonejs.github.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Aplicación web interactiva todo-en-uno para aprender **piano**, **armonía** y **teoría musical**. Combina un piano virtual de 88 teclas con detección de acordes en tiempo real, constructor de acordes, sistema de objetivos con feedback visual, efectos musicales sincronizados y un completo catálogo de ejercicios.

![Captura de pantalla](screenshot.png)

---

## 🚀 Características principales

### 🎵 Detección de acordes en tiempo real
- Identifica automáticamente cualquier acorde que toques (piano virtual o MIDI físico).
- Muestra el nombre del acorde, su calidad y las notas que lo componen.
- Visualiza los intervalos (1ª, 3ª, 5ª, 7ª, 9ª, 11ª, 13ª) con colores intuitivos:
  - 🔵 Fundamental (cyan)
  - 🟡 Tercera / Séptima (amarillo)
  - 🟢 Quinta / extensiones (verde)

### 🏗️ Constructor de acordes
- Más de **30 tipos de acordes**: Mayor, Menor, 7, 9, 11, 13, aumentado, disminuido, séptimas, etc.
- Visualiza la estructura completa del acorde con sus intervalos.

### 🎯 Sistema de objetivos y práctica guiada
- Establece cualquier acorde o escala como objetivo.
- Feedback visual en tiempo real:
  - ✅ **Verde** – nota correcta
  - ❌ **Rojo** – nota incorrecta
  - 🔵 **Azul** – nota pendiente
- **Selector de manos**: derecha, izquierda o ambas.
- **Validación inteligente**:
  - **Escalas** → tocar una nota a la vez (secuencial).
  - **Acordes** → tocar todas las notas juntas (simultánea).

### 🎛️ Efectos musicales en tiempo real
- **Trémolo** – repetición rápida en ciclo (velocidad ajustable por BPM).
- **Trino** – alternancia entre notas con intervalo seleccionable.
- **Staccato** – notas cortas y separadas.
- **Glissando** – deslizamiento entre notas.
- **Arpeggio** – notas en sucesión.
- **Apoyatura** – ascendente (♯) o descendente (♭).

### 📚 Catálogo de ejercicios
- Escalas mayores, menores (natural, armónica, melódica)
- Modos griegos (Jónico, Dórico, Frigio, Lidio, Mixolidio, Eólico, Locrio)
- Arpegios (Mayor, Menor, Disminuido, Aumentado, Séptimas)
- Acordes en bloque
- Dinámicas (pp, p, mf, f, ff)
- Figuras rítmicas (Redondas, Blancas, Negras, Corcheas)
- Progresiones (I-IV-V-I, I-vi-IV-V)
- Piezas (Oda a la Alegría de Beethoven)

### 🎹 Piano virtual
- 88 teclas interactivas con ratón y MIDI.
- Retroiluminación en tiempo real.

### 🔌 Soporte MIDI
- Conexión con teclados físicos mediante Web MIDI API.
- Detección automática de notas y acordes.

### 🎙️ Grabación y carga MIDI
- Graba tus interpretaciones en tiempo real.
- Importa archivos MIDI para analizar acordes.

---

## 🛠️ Tecnologías utilizadas

- **HTML5**, **CSS3**, **JavaScript ES6+**
- **Tone.js** – síntesis de audio y efectos
- **Canvas API** – visualización del pentagrama
- **Web MIDI API** – conexión con teclados
- **MidiFile.js** – lectura de archivos MIDI

---

## 🚀 Instalación y uso

### Opción 1: Directo desde el navegador
```bash
git clone https://github.com/tu-usuario/sensitive-piano-chord-constructor.git
cd sensitive-piano-chord-constructor
# Abre index.html en tu navegador
